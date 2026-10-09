## Hi there 👋

**Devops | Full stack dev | Gamedev | Founder**

**TL;DR:** Linux nerd → DevOps wrangler → indie gamedev. 🐧 → ☁️ → 🎮

### 🗺️ The Quest Log

- **2025 – now · 🎮 Founder, [Land of Enchantment Games](https://enchant.games)**
  My personal indie game studio, based in New Mexico.
- **Also cooking 🍳: my side projects**
  - **[merecatholicity.com](https://merecatholicity.com)** ([Git](https://github.com/merecatholicity/merecatholicity.com)): my eclectic ecumenical project. It includes a self-published book, *Mere Catholicity* (public domain, typeset in LaTeX for PDF, paperback and Logos), a library of the Fathers, councils and classics re-typeset from public-domain sources, and **merecat** 🐈, an AI research librarian that answers from the library with citations. I built it serverless: a PureScript, lit-js and Tailwind front end over a custom headless API backend on Cloudflare Workers, with D1 (SQLite), R2 (S3-compatible storage) and Durable Objects for real-time chat. A GitHub Actions CI/CD system ships both the application and its Terraform infrastructure, with approval gates before production, staged rollouts and nightly tests against production. For the community side I borrowed the best bits of the old internet: 4chan-style auth, Snapchat-style DMs, Signal-style end-to-end encryption, and Facebook-style profiles and walls.
  - **[stasislinux.org](https://stasislinux.org)** ([Git](https://codeberg.org/sta_sis/stasis)): my own Linux distro, the natural follow-through of my years as a package maintainer on KISS Linux with Dylan Araps.
  - **[backseat-driver](https://github.com/a-schaefers/backseat-driver)**: my tutor for keeping AI-era programmers' fundamentals sharp.
  - **[.emacs.d](https://github.com/a-schaefers/.emacs.d)**: my Emacs config. It starts in about 0.2s, with everything deferred through use-package. It prefers built-ins (eglot, flymake), runs on vertico/corfu/tree-sitter, and binds the same SLIME-style keys in every language.

- **2020 – 2025 · ☁️ DevOps @ Upgrade, Inc. · Immaculata Studios, LLC · Skvare, LLC**
  Herded Kubernetes, Terraform (5k+ lines of homegrown modules), AWS, CI/CD pipelines, monitoring, and a Postfix server that sent a million emails a month without landing in spam. Rode the industry's evolution from LAMP-stack monoliths to IaC-driven cloud microservices, right up to the arrival of AI automation, which is when I turned to solo gamedev.

- **2017 – 2020 · 🐧 Open Source Hermit**
  Spent 10+ hours a day learning Linux from the kernel up. Maintained packages for KISS Linux, wrote docs for Funtoo, and built [Themelios](https://github.com/a-schaefers/themelios) (a NixOS ZFS-on-root installer) and [Spartan Emacs](https://github.com/a-schaefers/spartan-emacs). Got commits merged upstream ([e.g. libcap](https://bugzilla.kernel.org/show_bug.cgi?id=206741)).
  Also went viral on Hacker News by booting my Linux distro with Emacs as init ([systemE](https://news.ycombinator.com/item?id=28439275)).

### 🎧 Off the clock

Professional music recording, aspiring DJ, and I play guitar. 🎸 Big fan of electronic music, house and techno. I love traveling in Europe, especially Greece. 🇬🇷 Born and raised in the Pacific Northwest, and an avid fly fisherman. 🎣

### 🤖 The slop shelf

My secondary GitHub, [@el-sloppo](https://github.com/el-sloppo), is where I push my favorite AI slop projects. Most of them live under [Emacs-OS](https://github.com/emacs-os):

- **[embr.el](https://github.com/emacs-os/embr.el)**: a web browser inside Emacs. Emacs is the display server and headless Chromium is the renderer, streamed over CDP screencast. It has EXWM-style key passthrough, optional Vimium-style modal navigation, and a native C rendering path built on the Emacs canvas patch. It doubles as a proof of concept for getting that patch mainlined.
- **[jellyfin-emms-mpv.el](https://github.com/emacs-os/jellyfin-emms-mpv.el)**: browse and play your Jellyfin library from Emacs. Music goes through EMMS and video through mpv, with poster galleries, and playback position syncs back so "Continue Watching" stays accurate.
- **[elcava](https://github.com/emacs-os/elcava)**: a cava clone in pure Emacs Lisp. It captures system audio from PipeWire, runs the FFT in Elisp, and draws a live Unicode spectrum in a buffer.
- **[el-init](https://github.com/emacs-os/el-init)**: Emacs as PID 1, for real this time. It's a systemd-inspired service supervisor written in Emacs Lisp, with a dependency graph, targets, an `M-x elinit` dashboard and an `elinitctl` CLI, plus an optional static-build patchset that turns Emacs into an actual init. It's the spiritual sequel to systemE and the core of Emacs-OS.
