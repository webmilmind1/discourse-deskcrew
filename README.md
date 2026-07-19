# DeskCrew for Discourse

A Discourse **theme component** that adds the [DeskCrew](https://deskcrew.io) support-chat widget
to your forum. Visitors get live chat, AI answers from your knowledge base, and a help center —
without touching any code.

## Install

1. In Discourse: **Admin → Customize → Themes → Components → Install**.
2. Choose **From a git repository** and paste this component's repository URL (or **From your
   device** and upload a ZIP of this folder).
3. Add the installed component to your active theme(s):
   **Admin → Customize → Themes → (your theme) → Components → Add**.

## Configure

Open the component's **Settings** and set:

- **widget_key** — your DeskCrew public widget key (starts with `pub_`). Find it in your DeskCrew
  dashboard under **Install**. *The widget stays hidden until this is set.*
- **board** *(optional)* — your DeskCrew board slug.
- **accent_color** *(optional)* — a hex colour for the widget, e.g. `#4f46e5`.
- **position** *(optional)* — `right` (default) or `left`.

That's it — the widget appears on your forum within a minute.

## Content Security Policy

Recent Discourse versions load approved theme scripts automatically. If your forum runs a stricter
CSP and the widget doesn't appear, add `deskcrew.io` to your
**Admin → Settings → `content_security_policy_script_src`** allow-list.

## License

MIT — see [LICENSE](./LICENSE). Questions: hello@deskcrew.io
