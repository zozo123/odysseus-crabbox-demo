# Odysseus × crabbox × islo.dev

Project page for a June 2026 demo: run [Odysseus](https://github.com/odysseus-dev/odysseus),
a self-hosted AI workspace by odysseus-dev, on a throwaway [islo.dev](https://islo.dev)
microVM in one command via [openclaw/crabbox](https://github.com/openclaw/crabbox).
No local install; nothing left behind.

By [Yossi Eliaz](https://yossieliaz.netlify.app/). Demo, June 2026.
islo.dev is built by my employer, Incredibuild.

**Project page:** https://zozo123.github.io/odysseus-crabbox-demo/

```bash
git clone https://github.com/zozo123/odysseus.git && cd odysseus
export ISLO_API_KEY=$(cat islo.key)      # islo api-key create …

./crabbox.sh serve   # boot Odysseus → public URL you can click
./crabbox.sh test    # warm a box, sync the checkout, run the suite, tear down
./crabbox.sh shell   # interactive shell on the box
```

- **Code (fork + `crabbox.sh`):** https://github.com/zozo123/odysseus ·
  [PR #1](https://github.com/zozo123/odysseus/pull/1)
- **Upstream:** [PR #2076](https://github.com/odysseus-dev/odysseus/pull/2076)
  (closed, not merged) · [issue #2150](https://github.com/odysseus-dev/odysseus/issues/2150)
- **crabbox** (ephemeral runner, by openclaw): https://github.com/openclaw/crabbox
- **islo.dev** (sandbox service): https://islo.dev

This repo is the static project page only; there is no hosted instance. It's
published from `main` / root (GitHub Pages, legacy build) with a `.nojekyll`
marker. All numbers on the page are from real runs on islo.dev sandboxes in
June 2026.
