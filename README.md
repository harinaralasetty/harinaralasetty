# Hi, I'm Hari 👋

**I build AI tools that run on your own machine:** chat with your documents, let coding agents talk to each other, and see what an app can do before you open it.

Senior Data Scientist at [Turing](https://www.turing.com), based in India. 4+ years building LLM agents for production workflows, multimodal RAG (LLaMA, Whisper, BLIP), and LLM evaluation and RLHF fine-tuning.

[LinkedIn](https://www.linkedin.com/in/harinaralasetty) · [Kaggle](https://www.kaggle.com/hknaralasetty) · [LeetCode](https://leetcode.com/harinaralasetty/)

## Now shipping

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/harinaralasetty/CORAG"><img src="https://raw.githubusercontent.com/harinaralasetty/CORAG/main/Screenshot.png" alt="CORAG answering a question from an uploaded PDF with a local Ollama model"></a>
<br><b><a href="https://github.com/harinaralasetty/CORAG">CORAG</a></b> <img src="https://img.shields.io/github/stars/harinaralasetty/CORAG?style=social" alt="GitHub stars for CORAG"><br>
Chat with your PDFs, notes and recordings. Answers name the file and page they came from. Gemini, Claude, or a local Ollama model with no API key.
</td>
<td width="50%" valign="top">
<a href="https://github.com/harinaralasetty/underhood"><img src="https://raw.githubusercontent.com/harinaralasetty/underhood/main/docs/assets/hero.svg" alt="Underhood summarising what macOS Calculator is allowed to do"></a>
<br><b><a href="https://github.com/harinaralasetty/underhood">Underhood</a></b><br>
What can this app touch? An offline inspector for macOS apps and Windows executables. It never runs the app, and every finding cites its evidence.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/harinaralasetty/agent-relay"><img src="https://raw.githubusercontent.com/harinaralasetty/agent-relay/main/docs/assets/hero.svg" alt="Codex CLI and Claude Code passing five acknowledged messages through Agent Relay"></a>
<br><b><a href="https://github.com/harinaralasetty/agent-relay">Agent Relay</a></b><br>
Codex CLI and Claude Code message each other through one local MCP mailbox, with acknowledgments, linked replies and resumable sessions.
</td>
<td width="50%" valign="top">
<b><a href="https://github.com/harinaralasetty/caffeinate-ui">Caffeinate UI</a></b><br>
Keep your Mac awake while your agents and builds run. A native menu-bar app with a session timer and coffee awards.
<br><br>
<b><a href="https://github.com/harinaralasetty/indic-legacy-pdf">indic-legacy-pdf</a></b><br>
Turns PDFs with legacy or broken Indic text into Unicode: Hindi and Marathi font encodings, Telugu glyph-ID recovery.
<br><br>
<b><a href="https://github.com/harinaralasetty/plum-plaza">Plum Plaza</a></b><br>
Three original browser games in one illustrated town. <a href="https://harinaralasetty.github.io/plum-plaza/">Play it</a>.
</td>
</tr>
</table>

## Try one in a minute

```sh
# What is Calculator allowed to do? Nothing is launched, nothing is sent anywhere.
brew install harinaralasetty/tap/underhood
underhood /System/Applications/Calculator.app

# Keep your Mac awake while an agent works (Apple silicon, macOS 13+)
brew install --cask harinaralasetty/tap/caffeinate-ui
```

## Also built

- [**CLARA**](https://github.com/harinaralasetty/CLARA): answers clinicians' questions from a patient's history, built on CORAG (work in progress)
- [**Generative Upscaling**](https://github.com/harinaralasetty/Performance-Efficient-Generative-Upscaling-for-Image-Generation): diffusion + ESRGAN for 2048×2048 images on limited GPUs

## Tech

Python · PyTorch · TensorFlow · Transformers · LangChain · Stable Diffusion · vLLM · MCP · SQL · Go · Swift · TypeScript · C++ · Docker · Kubernetes · Airflow · GCP · AWS · Azure
