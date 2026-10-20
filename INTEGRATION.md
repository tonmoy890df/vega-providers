# Add this provider to Vega

1. Copy `providers/pornhub` into the `providers/` folder of your Vega providers repository.
2. Add `manifest-entry.json` as a new object inside the repository's existing root `manifest.json`. Do not replace the existing manifest.
3. Run `npm install`, then `npm run build`.
4. Commit the generated `dist/` files because Vega loads the built provider modules.
5. Run `npm test -- pornhub` where supported.
