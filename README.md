# Virtual Smoke

A browser-based AR interaction that tracks your hand and face to render a virtual cigarette and procedural smoke in real time.

## Live Demo

No installation needed - try it directly in your browser:
[https://virtualsmoke.netlify.app/](https://virtualsmoke.netlify.app/)

Allow camera access when prompted. Works best in Chrome or Edge on desktop.

## Run Locally

Requirements: Node.js 22.13+, npm, a webcam, and Chrome or Edge.

```
git clone https://github.com/KwonTaeJunDS/Virtual_Smoke.git
cd Virtual_Smoke
npm install
npm run dev
```

Open http://localhost:3000 and allow camera access.

## Interaction

1. Pinch the cigarette with your thumb and index finger, or hold it between your index and middle fingers.
2. Move the cigarette close to your mouth. You can keep holding it or release it onto your lips.
3. Purse your lips to inhale. The cigarette burns and becomes shorter.
4. Open your mouth to exhale smoke. If you wait three seconds, the smoke comes out through your nose.
5. Continue inhaling until the cigarette burns down and falls.

Press `D` to show tracking and performance information.

## Built With

- TypeScript for the interaction logic
- React and CSS for the interface
- MediaPipe for hand and face tracking
- Three.js, WebGL, and GLSL for the cigarette and smoke rendering

Camera frames are processed locally in the browser and are not uploaded or stored.

## Changes from Original

This is a fork of [KwonTaeJunDS/Virtual_Smoke](https://github.com/KwonTaeJunDS/Virtual_Smoke) with the following changes:

- Deployed to [Netlify](https://netlify.com) so the project is publicly accessible online without needing a local server
- Updated configuration to support static hosting

## Credits

Original project by [KwonTaeJunDS](https://github.com/KwonTaeJunDS).

## License

[MIT](LICENSE)
