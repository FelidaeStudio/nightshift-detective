# Development

Use pnpm. This is a dependency-free static browser game; deployable assets live in `dist/` and are tracked source files.

- `pnpm dev`: local server on port 4173, or `PORT` when provided.
- `pnpm check`: JavaScript syntax validation.
- `pnpm build`: verify deployable files exist.

Keep README.md as a short English introduction. Keep story spoilers and implementation details out of it.
Keep player progress browser-local unless cross-device persistence is explicitly requested. Preserve the existing Site identity in `.openai/hosting.json`.
After gameplay changes, verify evidence reading, pins, note persistence, incorrect verdict feedback, and successful case completion.
