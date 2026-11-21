# pxxl-xray-node

Personal xray node wrapper for a Pxxl free project.

Deploy on Pxxl from this GitHub repo (Free plan, GitHub-repo deploy only, no card):
- Language: Node (detected from `package.json`)
- Build command: `npm install`
- Start command: `npm start`
- Environment variables:
  - `UUID` — a VLESS UUID (generate one, never commit it)
  - `WSPATH` — WebSocket path, e.g. `/vless`
  - `PORT` — provided by Pxxl automatically

Pxxl terminates TLS at the edge (`https://<name>.pxxlspace.cv`), xray listens plain WebSocket inside.

No credentials are stored in this repository.
