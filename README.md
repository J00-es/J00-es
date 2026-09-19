I build [Refery](https://refery.io), a recruiting partner network for VC-backed startups. Founders get a handpicked shortlist of people who build like founders. The scouts and recruiters who actually know the person keep 70% of the fee.

### Now

- [app.refery.io](https://app.refery.io), the partner desk: searches, candidates, one-tap decisions, agreements signed in the browser, installs as an app on the phone. Private repo, 374 commits since April 2026.
- The matching engine: every open role against every candidate on the bench, nightly, with an evidence trail a person reads before anything is sent.
- Ops in Slack: intake, decisions and follow-ups are reactions on cards, so one channel runs the company.

### How

Next.js 16, React 19, Supabase Postgres with row-level security and pg_cron, Resend, Slack, OpenAI, and an MCP server so a Claude session can run the desk. Every line reviewed, tested where it counts, and shipped by me.

### How it works, in one repo

[J00-es/refery](https://github.com/J00-es/refery): screenshots, architecture and a changelog. The code stays private.

[refery.io](https://refery.io) · [app.refery.io](https://app.refery.io) · hello@refery.io
