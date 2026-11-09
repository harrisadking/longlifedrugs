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

- Keep the Long Life storefront as a single index-route experience with semantic CSS design tokens, so its reference-matched styling stays consistent and easy to adjust.
- Keep PDF drug classification names and examples in a shared data module consumed by shop browsing, so the taxonomy remains testable and distinct from confirmed inventory.
- Keep Firebase browser configuration separate from code and enforce staff-only Firestore and Storage writes in Firebase rules, because client-side route guards alone are not security.
