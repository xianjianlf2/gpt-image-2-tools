# GPT-Image-2 Tools

> A free, privacy-first, multi-provider **AI image playground** — text-to-image, image-to-image, and inpainting in one box. Your API key stays in your browser and never leaves your device.
>
> 免费、隐私优先、多端点兼容的 **AI 图像创作工具** —— 一个输入框搞定文生图 / 图生图 / 局部重绘。密钥只存浏览器，永不离开本机。

### 👉 Live demo / 在线体验：**https://image.markxian.cn**

[![demo](https://image.markxian.cn/showcase/peaks.jpg)](https://image.markxian.cn)

---

## ✨ Features

- **One multimodal input** — type to generate; drag / paste / drop an image to edit; brush a mask to inpaint.
- **Works with any OpenAI-compatible endpoint** — `gpt-image`, `flux`, `dall-e`, and most proxy gateways. Bring your own key (BYOK).
- **Streaming + concurrent** — watch images render; get all N at once even on endpoints that return one per call.
- **Iterate** — lightbox, before/after compare, reroll one, "continue from this", download all.
- **✨ AI prompt enhance** — rewrite a rough idea into a polished prompt (optional text endpoint).
- **History** — grouped by day, filter by type/time, search, restore a whole group. Stored locally (IndexedDB).
- **Searchable model picker** — pulls the live `/models` list, image-filtered, with a connection test.
- **i18n** — 中文 / English, instant switch.
- **100% client-side** — no backend, no key relay. Self-hostable static files.

## 🔒 Privacy

Your endpoint, key, model, history and settings live only in your browser (`localStorage` / IndexedDB). The app talks to **your** endpoint directly — there is no server in the middle that sees your key, prompts, or images.

## 🚀 Self-host

This repo is the **built static app** — just serve the files:

```bash
# any static server works
npx serve .
# or drop the folder on Cloudflare Pages / Netlify / Vercel / GitHub Pages / nginx
```

Then open it, click **Settings**, and fill in your endpoint + key + model.

## 🐛 Found a bug? Want a feature?

Please open an **[Issue](../../issues)** — bug reports and ideas are very welcome. ⭐ Star the repo if it's useful!

## License

[MIT](LICENSE)
