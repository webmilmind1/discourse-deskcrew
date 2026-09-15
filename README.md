<!-- deskcrew-header:start -->
<p align="center">
  <a href="https://deskcrew.io"><img src="https://deskcrew.io/logo.png" alt="DeskCrew" width="96" height="96"></a>
</p>

<h1 align="center">DeskCrew for Discourse</h1>

<p align="center"><b>DeskCrew support-chat widget as a Discourse theme component</b></p>

<p align="center">AI answers, live chat, and ticketing.</p>

<p align="center">
  <a href="https://deskcrew.io"><b>Website</b></a> •
  <a href="https://deskcrew.io/integrations"><b>Integrations</b></a> •
  <a href="https://deskcrew.io/agents"><b>For agents</b></a> •
  <a href="https://deskcrew.io/signup"><b>Sign up</b></a>
</p>

<p align="center">
  <a href="https://github.com/webmilmind1/discourse-deskcrew/stargazers"><img src="https://img.shields.io/github/stars/webmilmind1/discourse-deskcrew?style=flat&logo=github&label=Stars&color=ffd33d" alt="GitHub stars"></a>
  <a href="https://github.com/webmilmind1/discourse-deskcrew"><img src="https://img.shields.io/github/license/webmilmind1/discourse-deskcrew?style=flat&label=License&color=e3a82b" alt="License"></a>
</p>

<p align="center">
  <a href="https://deskcrew.io"><img src="https://img.shields.io/badge/Visit_our_website-6366F1?style=for-the-badge&logoColor=white" alt="Visit our website"></a>
  <a href="https://discord.gg/hdWZgrYDqB"><img src="https://img.shields.io/badge/Join_our_Discord-5865F2?style=for-the-badge&logoColor=white&logo=discord" alt="Join our Discord"></a>
  <a href="https://x.com/getdeskcrew"><img src="https://img.shields.io/badge/Follow_%40getdeskcrew-000000?style=for-the-badge&logoColor=white&logo=x" alt="Follow @getdeskcrew"></a>
  <a href="https://www.instagram.com/getdeskcrew"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logoColor=white&logo=instagram" alt="Instagram"></a>
  <a href="https://mastodon.social/@deskcrew"><img src="https://img.shields.io/badge/Mastodon-6364FF?style=for-the-badge&logoColor=white&logo=mastodon" alt="Mastodon"></a>
  <a href="https://www.youtube.com/channel/UCW7g7TLiUbnK8zWF513ckFA"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logoColor=white&logo=youtube" alt="YouTube"></a>
  <a href="https://www.tiktok.com/@deskcrewhq"><img src="https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logoColor=white&logo=tiktok" alt="TikTok"></a>
</p>

<p align="center"><i>⭐ Help more people find DeskCrew. Star this repo!</i></p>
<!-- deskcrew-header:end -->

[![license](https://img.shields.io/badge/license-MIT-4f46e5)](./LICENSE)

<a href="https://www.producthunt.com/products/deskcrew?utm_source=badge-featured&utm_medium=badge&utm_campaign=badge-deskcrew"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=1197215&theme=dark" alt="DeskCrew on Product Hunt" width="250" height="54" /></a>

[![The DeskCrew AI support widget opening on a Discourse forum and answering a question about adding live chat](https://deskcrew.b-cdn.net/plugins/discourse-demo.gif)](https://deskcrew.b-cdn.net/plugins/discourse-demo.mp4)

<sub>The widget running on a Discourse forum. <a href="https://deskcrew.b-cdn.net/plugins/discourse-demo.mp4">Watch the full quality video</a>.</sub>

A Discourse **theme component** that adds the [DeskCrew](https://deskcrew.io) support-chat widget
to your forum. Visitors get live chat, AI answers from your knowledge base, and a help center,
without touching any code.

## Install

1. In Discourse: **Admin → Customize → Themes → Components → Install**.
2. Choose **From a git repository** and paste this component's repository URL (or **From your
   device** and upload a ZIP of this folder).
3. Add the installed component to your active theme(s):
   **Admin → Customize → Themes → (your theme) → Components → Add**.

## Configure

Open the component's **Settings** and set:

- **widget_key**: your DeskCrew public widget key (starts with `pub_`). Find it in your DeskCrew
  dashboard under **Install**. *The widget stays hidden until this is set.*
- **board** *(optional)*: your DeskCrew board slug.
- **accent_color** *(optional)*: a hex colour for the widget, e.g. `#4f46e5`.
- **position** *(optional)*: `right` (default) or `left`.

That's it. The widget appears on your forum within a minute.

## Content Security Policy

Recent Discourse versions load approved theme scripts automatically. If your forum runs a stricter
CSP and the widget doesn't appear, add `deskcrew.io` to your
**Admin → Settings → `content_security_policy_script_src`** allow-list.

## License

MIT, see [LICENSE](./LICENSE). Questions: hello@deskcrew.io
