<div align="center">

<img src="logo.png" alt="PageToVid" width="96" height="96">

# PageToVid

**Turn any website into a narrated, captioned video — from the web app, the API, your AI assistant or your editor.**

[![Website](https://img.shields.io/badge/pagetovid.com-6366f1?style=flat-square&logo=googlechrome&logoColor=white)](https://pagetovid.com)
[![Docs](https://img.shields.io/badge/docs-pagetovid.github.io-0b0b0f?style=flat-square&logo=readthedocs&logoColor=white)](https://pagetovid.github.io/docs/)
[![MCP](https://img.shields.io/badge/MCP-pagetovid.com%2Fmcp-0b0b0f?style=flat-square)](https://pagetovid.github.io/docs/mcp/)
[![Chrome Web Store](https://img.shields.io/chrome-web-store/v/oaiajdabfjpklohkinnacldlojbnjemd?style=flat-square&logo=googlechrome&logoColor=white&label=Chrome)](https://chromewebstore.google.com/detail/pagetovid-%E2%80%94-capture/oaiajdabfjpklohkinnacldlojbnjemd)
[![VS Code Marketplace](https://img.shields.io/visual-studio-marketplace/v/pagetovid.pagetovid-capture?style=flat-square&logo=visualstudiocode&logoColor=white&label=VS%20Code)](https://marketplace.visualstudio.com/items?itemName=pagetovid.pagetovid-capture)
[![Follow on X](https://img.shields.io/badge/follow-%40PageToVid-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/PageToVid)

[Website](https://pagetovid.com) · [Documentation](https://pagetovid.github.io/docs/) · [Examples](https://pagetovid.github.io/docs/examples) · [MCP server](https://pagetovid.github.io/docs/mcp/) · [API](https://pagetovid.github.io/docs/api) · [Extensions](https://pagetovid.github.io/docs/extensions)

</div>

PageToVid reads a page, writes the script, films the site in a real browser, records the voice-over
and renders an MP4 with captions — or builds a film from a storyboard you write. One link in, one
film out — in 13 languages, in 16:9, 9:16, 1:1 or 4:5.

## Use it where you already work

| | How | |
|---|---|---|
| 🌐 **Web app** | Paste a link at [pagetovid.com](https://pagetovid.com) — free to start | [Getting started](https://pagetovid.github.io/docs/getting-started) |
| 🤖 **Claude, ChatGPT, Cursor, Codex, Gemini CLI** | Add `https://pagetovid.com/mcp` as a connector, then ask for a video in plain words | [MCP server](https://pagetovid.github.io/docs/mcp/) |
| 🧩 **Chrome** | [PageToVid — Capture](https://chromewebstore.google.com/detail/pagetovid-%E2%80%94-capture/oaiajdabfjpklohkinnacldlojbnjemd): screencasts, full-page shots, brand kits, filming behind a login | [Extensions](https://pagetovid.github.io/docs/extensions#chrome) |
| 🧑‍💻 **VS Code, Cursor, Windsurf** | [PageToVid Studio](https://marketplace.visualstudio.com/items?itemName=pagetovid.pagetovid-capture): Claude Code plans the flows worth filming from your code | [Extensions](https://pagetovid.github.io/docs/extensions#vs-code) |
| ⚙️ **REST API** | Automations, bulk generation, a video per product page | [API](https://pagetovid.github.io/docs/api) |

```bash
# Claude Code: the server, or the plugin with its slash commands
claude mcp add --transport http pagetovid https://pagetovid.com/mcp
/plugin marketplace add PageToVid/claude-plugins
```

## Examples

Every film below was made with PageToVid from a single link, on our own sites. Click a poster to watch it.

<table>
<tr>
<td width="50%" valign="top"><a href="https://pagetovid.com/watch/pagetovid-in-60-seconds-cmvpm7axc001gs60151w3o8qr"><img src="https://pagetovid.com/v/cmvpm7axc001gs60151w3o8qr.jpg" alt="PageToVid in 60 seconds" width="100%"></a><br><b>PageToVid in 60 seconds</b><br><sub>An animated explainer written as scenes, no page needed · also in <a href="https://pagetovid.com/watch/pagetovid-en-60-secondes-cmvpnmgoq001hs6019ofo61zx">French</a>, <a href="https://pagetovid.com/watch/pagetovid-en-60-segundos-cmvpnmt7x0024s601u0la1qyu">Spanish</a>, <a href="https://pagetovid.com/watch/pagetovid-in-60-sekunden-cmvpnn7fb002rs601x5r02et8">German</a></sub></td>
<td width="50%" valign="top"><a href="https://pagetovid.com/watch/plan-your-dream-wedding-cmvn4vhnu0009s6013fv3pk9l"><img src="https://pagetovid.com/v/cmvn4vhnu0009s6013fv3pk9l.jpg" alt="Plan your dream wedding — nyna.ai" width="100%"></a><br><b>Plan your dream wedding</b><br><sub>nyna.ai, filmed in a real browser · 16:9 explainer</sub></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://pagetovid.com/watch/show-me-your-site-i-ll-tell-you-what-s-wrong-cmvn4vgys0004s601ouveqmxe"><img src="https://pagetovid.com/v/cmvn4vgys0004s601ouveqmxe.jpg" alt="Show me your site — drurls.com" width="100%"></a><br><b>Show me your site. I'll tell you what's wrong.</b><br><sub>drurls.com · a product explainer from the home page</sub></td>
<td width="50%" valign="top"><a href="https://pagetovid.com/watch/use-nyna-from-your-ai-assistant-cmvilj35p006vs601mrj6w0b3"><img src="https://pagetovid.com/v/cmvilj35p006vs601mrj6w0b3.jpg" alt="Use Nyna from your AI assistant" width="100%"></a><br><b>Use Nyna from your AI assistant</b><br><sub>nyna.ai · a demo of one page, filmed step by step</sub></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://pagetovid.com/watch/pagetovid-capture-for-chrome-film-the-app-behind-your-login-cmvi0zdw4001zs601fdhouzdn"><img src="https://pagetovid.com/v/cmvi0zdw4001zs601fdhouzdn.jpg" alt="PageToVid Capture for Chrome" width="100%"></a><br><b>Film the app behind your login</b><br><sub>The Chrome extension, explained in an animated film</sub></td>
<td width="50%" valign="top"><a href="https://pagetovid.com/watch/expert-terrassement-vrd-aix-en-provence-paca-cmvnaqbbx0004s601he0fn7wk"><img src="https://pagetovid.com/v/cmvnaqbbx0004s601he0fn7wk.jpg" alt="Expert Terrassement & VRD — vertical ad" width="40%"></a><br><b>Expert Terrassement & VRD</b><br><sub>stp-terrassement.com · a 9:16 ad in French, the mobile site filmed</sub></td>
</tr>
</table>

More in the [examples gallery](https://pagetovid.github.io/docs/examples).

## Tips for a better film

- **The words are the length.** A scene lasts as long as the narration over it — write fewer words for a shorter film, about 149 a minute.
- **Film the shape you will post.** 9:16 films the mobile layout, 16:9, 1:1 and 4:5 the desktop one.
- **Preview for free.** `create_video` with `draft: true` costs nothing; edit the storyboard, then render once.
- **Give it the brief.** One sentence on who it is for and what they should do next beats a long prompt.
- **App behind a login?** Send your signed-in session from the [Chrome extension](https://pagetovid.github.io/docs/extensions#chrome) instead of filming the sign-in page.

All of them in [Tips & tricks](https://pagetovid.github.io/docs/tips).

## Repositories

| Repository | |
|---|---|
| 📘 [**docs**](https://github.com/PageToVid/docs) | The public documentation — guides, the full MCP tool reference, examples, tips. Issues for every product live here. |
| 🧩 [**claude-plugins**](https://github.com/PageToVid/claude-plugins) | The Claude Code plugin marketplace: the MCP server plus `/pagetovid:video`, `/pagetovid:animate`, `/pagetovid:edit` and more. |
| 🏠 [**.github**](https://github.com/PageToVid/.github) | This profile and the community health files. |

## Follow along

[X](https://x.com/PageToVid) · [LinkedIn](https://www.linkedin.com/company/pagetovid/) · [YouTube](https://www.youtube.com/@Pagetovid) · [Instagram](https://www.instagram.com/pagetovid_com/) · [Pinterest](https://www.pinterest.com/Pagetovid/) · [Facebook](https://www.facebook.com/pagetovid)

## Getting help

Bugs and ideas: [open an issue](https://github.com/PageToVid/docs/issues/new/choose) ·
Security: our [security policy](https://github.com/PageToVid/.github/blob/main/SECURITY.md) ·
Anything else: hello@pagetovid.com
