# 電脳写真機 (cyberpunkphoto)

Cyberpunk photo and video camera. Opens straight into a full-screen camera with live neon, glitch, scanline and HUD effects; settings sit behind the gear button.

- Web version: https://shunrei2000-ux.github.io/cyberpunkphoto/
- iPhone app: Capacitor wrapper in `ios/`

`index.html` is the whole app. `www/` and `ios/App/App/public/` are copies made by the build.

## Run on an iPhone (Mac + Xcode)

```
git clone https://github.com/shunrei2000-ux/cyberpunkphoto.git
cd cyberpunkphoto
npm install
npm run ios
```

`npm run ios` copies `index.html` into the app and opens Xcode. In Xcode:

1. Select the **App** target, open **Signing & Capabilities**, and choose your Team.
2. Connect the iPhone, pick it as the run destination, and press Run.

After changing `index.html`, run `npm run sync` and press Run again.
