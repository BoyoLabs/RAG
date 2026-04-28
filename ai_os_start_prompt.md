**Prompt:**

I want to build a prototype for an AI-centric operating system called "AI-OS." The goal is to create a system where the primary interface is a conversational AI shell, but with full access to a high-performance graphics layer for gaming, media, and professional development.

**Core Philosophy:**
- The AI is the "Fundamental Layer" and System Orchestrator, not just an app.
- Default interface is a Chat-Centric window (The "Command Center").
- Full UI access is preserved: The AI manages a Tiling Window Manager (TWM) to spawn and organize full-UI applications (Browsers, Steam, IDEs) on demand.
- "Vibe Coder" workflow: Deep integration between the AI shell and the underlying Bash system.

**Technical Requirements for the Prototype:**
1. **Base:** Linux (Debian-based).
2. **Graphics Layer:** Use a programmatic Tiling Window Manager (like Hyprland or Sway) that can be controlled via CLI.
3. **AI Engine:** Ollama for local inference (with a "starter pack" of small models) and integration with Cloud APIs (Claude/Gemini).
4. **The "vibe-shell":** A custom wrapper that defaults to AI input but allows a seamless "escape hatch" to raw Bash.
5. **Orchestrator:** A system that translates natural language requests into window management and application launch commands.

**Immediate First Milestone:**
Please start by designing the **"Orchestrator"** and the **"vibe-shell"** wrapper. I need a proof-of-concept that can:
- Intercept user input.
- Route it to a local LLM (Ollama).
- Execute a bash command if the AI determines it's necessary.
- Send a command to the window manager to open a specific application.

Let's begin by planning the architecture for the `vibe-shell` wrapper and the integration with the window manager.
***
