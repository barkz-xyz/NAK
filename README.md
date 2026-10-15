# NAK — Interactive 3D Oracle

A browser-based creative prototype that combines a stylized 3D conch, custom rendering, animated interactions, audio, and a Web3-inspired interface.

## Highlights

- Three.js WebGPU rendering with Three.js Shading Language (TSL).
- Blender/GLB scene assets, camera controls, and animated interaction states.
- Custom depth-of-field and outline treatments.
- Oracle prompt flow with simulated wallet connection and transaction approval.
- Token-data visuals with API fallback paths.

**Prototype scope:** the wallet and transaction approval flow in the current public source is simulated. It is an interaction demo; it does not submit an on-chain payment.

## Run locally

```bash
npm install
npm run dev
```

Use a browser that supports the rendering features used by the project. For a production bundle and local preview:

```bash
npm run build
npm run preview
```

## Explore the source

- [src/main.js](src/main.js) — scene setup, rendering, interactions, and data visuals
- [src/CustomDepthOfFieldNode.js](src/CustomDepthOfFieldNode.js) — custom rendering node
- [src/style.css](src/style.css) — interface and visual styling
- [public](public) — scene and media assets

Built by [Alejandro Mendoza / bobo labs](https://github.com/bobo-labs).
