# Odysseus × crabbox × islo.dev

**Live page:** https://zozo123.github.io/odysseus-crabbox-demo/

Run [Odysseus](https://github.com/pewdiepie-archdaemon/odysseus) — a self-hosted
AI workspace — on a throwaway [islo.dev](https://islo.dev) microVM in one command.
No local install; nothing left behind.

```bash
git clone https://github.com/zozo123/odysseus.git && cd odysseus
export ISLO_API_KEY=$(cat islo.key)      # islo api-key create …

./crabbox.sh serve   # boot Odysseus → public URL you can click
./crabbox.sh test    # warm a box, sync the checkout, run the suite, tear down
./crabbox.sh shell   # interactive shell on the box
```

- **Code (fork + `crabbox.sh`):** https://github.com/zozo123/odysseus ·
  [PR #1](https://github.com/zozo123/odysseus/pull/1)
- **crabbox** (ephemeral runner): https://github.com/openclaw/crabbox
- **islo.dev** (sandbox fabric): https://islo.dev

This repo is the static project page only. It's published from `main` / root
(GitHub Pages, legacy build) with a `.nojekyll` marker. All numbers on the page
are from real runs on live islo.dev sandboxes.
