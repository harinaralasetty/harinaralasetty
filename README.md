# Hi, I'm Hari 👋

**I build AI tools that run on your own machine:** turn any website into tools your agents can call, chat with your documents, see what an app can do before you open it, and let coding agents talk to each other.

Senior Data Scientist at [Turing](https://www.turing.com), based in India. 4+ years building LLM agents for production workflows, multimodal RAG (LLaMA, Whisper, BLIP), and LLM evaluation and RLHF fine-tuning.

[LinkedIn](https://www.linkedin.com/in/harinaralasetty) · [Kaggle](https://www.kaggle.com/hknaralasetty) · [LeetCode](https://leetcode.com/harinaralasetty/)

## Now shipping

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/harinaralasetty/site2mcp"><img src="https://raw.githubusercontent.com/harinaralasetty/site2mcp/main/docs/assets/social-preview.png?v=2" alt="site2mcp: turn any website into an MCP server your AI agents can call" width="100%"></a>
<b><a href="https://github.com/harinaralasetty/site2mcp">site2mcp</a></b>: use a website once in your browser, and your AI agents can call it as MCP tools. On PyPI.
</td>
<td width="50%" valign="top">
<a href="https://github.com/harinaralasetty/CORAG"><img src="https://raw.githubusercontent.com/harinaralasetty/CORAG/main/docs/assets/social-preview.png" alt="CORAG: chat with your PDFs, notes and recordings; answers name the file and page" width="100%"></a>
<b><a href="https://github.com/harinaralasetty/CORAG">CORAG</a></b>: chat with your PDFs, notes and recordings. Gemini, Claude, or a local Ollama model with no API key.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/harinaralasetty/underhood"><img src="https://raw.githubusercontent.com/harinaralasetty/underhood/main/docs/assets/social-preview.png" alt="Underhood: offline static analyzer for macOS apps and Windows executables" width="100%"></a>
<b><a href="https://github.com/harinaralasetty/underhood">Underhood</a></b>: see what an app is allowed to touch before you open it. It never runs the app.
</td>
<td width="50%" valign="top">
<a href="https://harinaralasetty.github.io/math-experiments/"><img src="https://harinaralasetty.github.io/math-experiments/assets/results.png" alt="Math Experiments: AI agents find 1,456 new terms for open math sequences, checked by independent programs" width="100%"></a>
<b><a href="https://harinaralasetty.github.io/math-experiments/">Math Experiments</a></b>: AI agents found 1,456 new terms for open OEIS sequences, each checked by two independent programs.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/harinaralasetty/agent-relay"><img src="https://raw.githubusercontent.com/harinaralasetty/agent-relay/main/docs/assets/social-preview.png" alt="Agent Relay: Codex CLI and Claude Code message each other" width="100%"></a>
<b><a href="https://github.com/harinaralasetty/agent-relay">Agent Relay</a></b>: Codex CLI and Claude Code message each other through one local MCP mailbox.
</td>
<td width="50%" valign="top">
<a href="https://github.com/harinaralasetty/caffeinate-ui"><img src="https://raw.githubusercontent.com/harinaralasetty/caffeinate-ui/main/docs/screenshots/social-preview.jpg" alt="Caffeinate UI: keep your Mac awake, keep your agents running" width="100%"></a>
<b><a href="https://github.com/harinaralasetty/caffeinate-ui">Caffeinate UI</a></b>: a menu-bar app that keeps your Mac awake while agents and builds run.
</td>
</tr>
</table>


## Try one in a minute

```sh
# Turn a recorded browser session (HAR) into tools your agents can call
pipx install site2mcp
site2mcp inspect session.har

# What is Calculator allowed to do? Nothing is launched, nothing is sent anywhere.
brew install harinaralasetty/tap/underhood
underhood /System/Applications/Calculator.app

# Keep your Mac awake while an agent works (Apple silicon, macOS 13+)
brew install --cask harinaralasetty/tap/caffeinate-ui
```

## Also built

- [**indic-legacy-pdf**](https://github.com/harinaralasetty/indic-legacy-pdf): turns legacy-encoded Hindi, Marathi and Telugu PDFs into Unicode
- [**Plum Plaza**](https://github.com/harinaralasetty/plum-plaza): three original browser games in one illustrated town ([play it](https://harinaralasetty.github.io/plum-plaza/))
- [**CLARA**](https://github.com/harinaralasetty/CLARA): answers clinicians' questions from a patient's history, built on CORAG (work in progress)
- [**Generative Upscaling**](https://github.com/harinaralasetty/Performance-Efficient-Generative-Upscaling-for-Image-Generation): diffusion + ESRGAN for 2048×2048 images on limited GPUs

## Tech

Python · PyTorch · TensorFlow · Transformers · LangChain · Stable Diffusion · vLLM · MCP · SQL · Go · Swift · TypeScript · C++ · Docker · Kubernetes · Airflow · GCP · AWS · Azure
