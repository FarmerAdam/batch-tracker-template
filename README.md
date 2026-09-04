# Batch Tracker

A free, open-source grow-cycle tracker for mushroom/produce growers - rooms,
zones, bays, batches, harvests, costs, and yield forecasting. Single-page
static app (`index.html`), backed by your own free Supabase project. No
shared server, no subscription, no vendor lock-in - you own your data.

## Setup

**No installs, no terminal.** Open [`setup.html`](setup.html) in your
browser and follow the 5 steps - it copies the schema for you, and tests
your Project URL/anon key live before handing you a ready-to-use `config.js`
to download. New to this whole area? Paste [`SETUP-WITH-AI.md`](SETUP-WITH-AI.md)
to Claude or ChatGPT first and it'll walk you through it end to end,
including the GitHub/Supabase dashboard parts `setup.html` can't automate.

Prefer a terminal? `setup.js` does the same schema-push + config-write in
one command (`npm install && npm run setup`) - entirely optional, same end
result either way.

## License

MIT, provided as-is with no warranty - see [`LICENSE`](LICENSE).

This is a self-hosted template: each grower runs their own copy against
their own Supabase project and is solely responsible for their own data,
backups, security configuration, and any costs on their own accounts. The
original author provides no support, uptime guarantee, or liability for any
individual deployment.
