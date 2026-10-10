<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

- Fantasy data (player pool, weekly points, lineups, schedule) is generated deterministically in src/lib/fantasy.ts; only league/team/pick rows live in the database — keeps every member's view identical without storing stats.
- All league writes go through security-definer SQL functions (create_league, make_pick, etc.); tables are select-only for clients — enforces turn order and commissioner rights server-side.
