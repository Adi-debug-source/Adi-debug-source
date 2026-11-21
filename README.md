<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/portrait-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/portrait-light.svg">
  <img src="assets/portrait-light.svg" width="280" alt="Portrait of Aditya Kumar drawn in code symbols, brackets, slashes and hash marks set in a monospace grid">
</picture>

### Aditya Kumar

I studied Computer Science and Artificial Intelligence at Aberystwyth University. I design, test and release small tools for macOS and the command line. The two below are public, MIT licensed, and install with Homebrew.

#### Tools

- **[Tokenmeter](https://github.com/Adi-debug-source/tokenmeter)** (Python, with a Swift menu bar app). Shows what AI coding usage would have cost at API rates, read from the local logs of Claude Code, Codex, Gemini CLI and other coding agents. Its Claude Code totals match that tool's own cost figures to ten decimal places. Standard-library Python with nothing to install, and tested in CI on macOS and Linux.
- **[Bytemeter](https://github.com/Adi-debug-source/bytemeter)** (Swift). A native macOS menu bar app that counts the data a Mac sends and receives, broken down by interface and by app, with a dashboard and a CSV export. It has no dependencies and makes no network requests of its own. The counting engine lives in its own target, so an iOS version can reuse it.

In development, not public yet: Immaculate, a native macOS cleaner and system monitor in SwiftUI.

#### How I build

I decide what each tool does, write part of the code by hand and direct AI coding agents for the rest, and I check every change through tests and real use.

Privately, I run a multi-agent assistant I designed for my own work: a coordinator that routes each request to 14 specialist agents, each fenced to its own remit. It runs on rules I wrote and Python guard hooks kept under test, and stays on my own machine.

#### Stack

In the tools above: Python, Swift and SwiftUI. Also: Java, TypeScript, JavaScript, HTML and CSS, C++ and MySQL.

---

I am looking for a graduate or junior role in software or AI engineering in the UK, and happy to relocate. I am also open to freelance projects. Each repository has a changelog and a test suite, the quickest way to see how I work.

Contact: analog.universe@proton.me
