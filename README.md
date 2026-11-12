# demos

Built demos, served by GitHub Pages at https://demos.liubruce.me/. Each folder is one demo, copied from its own
repository's build; nothing here is edited by hand.

| Folder | Demo | Published from |
|---|---|---|
| [`intra-turn/`](intra-turn/) | Beyond Taking Turns: Feedforward and Leaving Blanks | `xybruceliu/intra-turn` (`cd web && npm run build && npm run publish:pages -- <this repo>`; its DEPLOY.md) |

The demos are static: anything live runs in the visitor's browser, on their own OpenRouter account.
`.nojekyll` keeps GitHub Pages from skipping files whose names start with an underscore; `index.html` sends the root
to the demo.
