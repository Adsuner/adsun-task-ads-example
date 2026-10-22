# Adsun Task block — Telegram Mini App example

Uses the `<adsun-task>` custom element and listens to `reward`, `onBannerNotFound` and `onFastReturn` events.

## Run

```bash
npx serve .
```
Then open it in a browser (debug) or set the URL as your bot's Mini App in @BotFather.

Replace `YOUR_BLOCK_ID` with the block ID from your Adsun publisher panel.

## Debug mode

`debug: true` shows a test ad: no billing, and the Reward URL is **not** called.
Use it outside Telegram too (otherwise you get `NoUserData`). Remove it before going live.

## Links

- Docs: https://adsun.io/documentation
- Mini App monetization: https://adsun.io/telegram-mini-app-monetization

## License

MIT
