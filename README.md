# DEADLOCK source export

This archive contains the complete source for the DEADLOCK digital legacy security website, including the original React/TypeScript app, CSS theme, responsive behavior, icons, local assets, Vite configuration, and all local UI components used by the app.

## Run independently

Requirements: Node.js 20+ and pnpm 9+.

```bash
pnpm install
pnpm dev
```

Open http://localhost:5173.

Other commands:

```bash
pnpm typecheck
pnpm build
pnpm preview
```

The app is self-contained and uses browser localStorage for demo persistence. The interface loads IBM Plex Sans and IBM Plex Mono from the Google Fonts CSS import retained in `src/index.css`; Lucide icons are bundled through the `lucide-react` dependency. No backend, API key, database, or external account connection is required.

## Demo path

Overview → GitHub asset → Legacy Policy → Beneficiary → Legacy Simulation → Verification → Audit Log → Security Center.

All provider-facing behavior is intentionally labeled as Simulation, Action Prepared, Prepared, Queued, or Remains Locked. The app does not detect death, bypass third-party security, unlock external accounts, or authorize releases.
