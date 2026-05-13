# ClickNClaw — Release Timeline

Every version we've shipped, in order.

---

### v0.1.0 — Foundation

The very first scaffold. We lay the groundwork today: an Electron + React shell, the basic chat panel, conversation persistence, and the architectural skeleton for a multi-agent AI workstation. Mostly empty — but the bones are in place.

### v0.2.0 — First Agent Online

ClickNClaw comes to life. We connect our first AI today: Gemini CLI. Streaming responses, markdown rendering, and a real working conversation flow are now live in the app. It actually talks.

### v0.3.0 — Multi-Agent Era

One agent isn't enough. Today we add Claude Code and Codex alongside Gemini. The agent switcher lives in the chat header, and every conversation can choose its own brain. The "AI command center" vision is taking shape.

### v0.4.0 — Tools & Files

Agents stop being just chat partners. We ship tool calling, file read / write / diff operations, a real workspace tree view, and syntax highlighting for 50+ languages. ClickNClaw becomes something you can actually work in.

### v0.5.0 — Workspace Intelligence

The Model Context Protocol (MCP) lands today, opening the door to a universe of plugins. We add the Skills system — composable instruction packs you can attach to any agent — and the first multi-window workspace. Power users finally have room to spread out.

### v0.6.0 — Pre-Beta Lockdown

The architecture is locked down today. We rewrite the theme system from scratch and ship four built-in looks (Classic, Anime Neon, Retro, Ledger), the chrome gets a polish pass end-to-end, and every surface is shaved down to what we want users to see. The public closed-beta is next.

### v0.6.1 — Stability Pass

Boring but necessary. Conversation persistence is now rock-solid, we hunted down memory leaks in long-running sessions, raised file-upload limits, and rewrote every error message to actually be helpful.

### v0.6.2 — Performance

Streaming throughput is up ~40%, heavy markdown lazy-loads, and the app's cold-start is noticeably faster. ClickNClaw stops feeling like an Electron app.

### v0.6.3 — Polish

A full dark-mode contrast audit, accessibility improvements across every modal, and a keyboard-shortcut hub for power users. Last shave before going public.

---

### v0.6.4 — First Public Closed-Beta 🎉

**ClickNClaw is live today.** Token-gated downloads via Solana wallet sign-in at [clicknclaw.com](https://clicknclaw.com), builds for macOS arm64 + Intel, Windows, and Linux AppImage, and the foundation of our auto-update system. Doors are open.

### v0.6.5 — Update Infrastructure

We built our own lightweight update channel. New versions now arrive as a quiet toast in the bottom-right, and the About page has a proper "Check for Updates" flow.

### v0.6.6 — Permission Modes (YOLO)

Three tiers of agent autonomy ship today: **Restricted** (ask for everything), **Confirm-each-action** (the default), and **YOLO** — full automation, no prompts. Per-conversation overrides included, plus an audit log so you can see exactly what your agent did when you weren't watching.

### v0.7.0 — Remote & 3D Game Studio 🚀

Two flagship features in one drop. **Remote (WebUI):** access ClickNClaw from your phone, tablet, or any browser on your network — scan a QR code, log in, real-time sync with your desktop. **3D Game Studio:** type one prompt, get a complete playable Three.js game written straight into your workspace.

### v0.7.1 — Mobile Polish

Now that Remote is real, we make it gorgeous on tablets and phones. Touch-optimized inputs, swipe gestures for sidebar navigation, and layouts that respect the mobile keyboard.

### v0.7.2 — Channels

ClickNClaw gets its first messaging-platform integration today: a full Telegram bot channel, with multi-conversation routing and inline replies. Send a message from Telegram — get a reply from your agent.

### v0.7.3 — Stability

Long-session memory profiling, a brand-new crash-report pipeline, and a deep round of bug fixes from beta-tester feedback. We hear about problems before users have to tell us.

### v0.7.4 — Four New Themes 🎨

Four hand-crafted preset themes ship together today: **Aegean Cobalt** (cool Mediterranean palette), **Aurora Veil** (northern-lights glassmorphic), **Onyx Gold** (art-deco luxury hairline), and **Neon Tokyo** (cyberpunk synthwave). Light + dark variants for every one. Long-session contrast tuned for the eyes.

---

*More to come. Stay tuned at [clicknclaw.com](https://clicknclaw.com).*
