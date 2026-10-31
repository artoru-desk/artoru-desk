<div align="center">

<img src="./banner.svg" alt="Artoru Desk & Artoru EDGE" width="100%" />

<br/>

# Artoru Desk
### **On-Device Intent Routing. Surgical Tool Dispatch. Built for Local Hardware.**
**Powered by `Artoru EDGE` (65M ONNX Router) · `v1.0` Drops 5 November 2026 · Apache-2.0**

[![Artoru EDGE on HF](https://img.shields.io/badge/ARTORU_EDGE-live_on_Hugging_Face-FF5500?style=for-the-badge&logo=huggingface&logoColor=white)](https://huggingface.co/artoru/edge-65m)
[![Org](https://img.shields.io/badge/HUGGING_FACE-artoru-F59E0B?style=for-the-badge&logo=huggingface&logoColor=white)](https://huggingface.co/artoru)
[![Desk v1.0](https://img.shields.io/badge/DESK_v1.0-DROPS_NOV_05-10b981?style=for-the-badge)](https://github.com/artoru-desk/artoru-desk)
[![License](https://img.shields.io/badge/LICENSE-Apache--2.0-blue?style=for-the-badge)](LICENSE)

<br/>

**Your PC. Your agents. Zero mandatory cloud accounts.**  
Stop burning massive cloud tokens just to decide which tool or agent should handle a task. **Artoru EDGE** triages intent on your machine in milliseconds. **Artoru Desk** is the local command center where agents research, debate, and execute under strict human-in-the-loop gates.

> ⚡ **The Brain is Live Today. The `v1.0` Workspace Drops November 5.**  
> Pull and benchmark [**`artoru/edge-65m`**](https://huggingface.co/artoru/edge-65m) right now on Hugging Face. **Click `★ Star` and `Watch` (top right)** to get notified the second the signed **Artoru Desk `v1.0`** release goes live on **5 November 2026**.

</div>

---

## Why Artoru Exists

Autonomous desktop software is currently broken in two ways:
1. **Bloated First-Hop Routing:** Frameworks route every trivial local command through slow, expensive frontier cloud models before a single action happens.
2. **Reckless Execution:** Unscoped scripts either hijack your host mouse/keyboard or execute destructive terminal and outbound actions without hard operator gates.

**Artoru fixes the stack from the metal up:**

```text
+-----------------------------------------------------------------------------------+
|  LOCAL HOST ([http://127.0.0.1:3445](http://127.0.0.1:3445) // Air-Gapped by Default)                      |
|                                                                                   |
|  [ Operator Prompt / Mobile Telegram Command ]                                    |
|          |                                                                        |
|          v                                                                        |
|  +-----------------------------------------------------------------------------+  |
|  | 1. FIRST TRIAGE: Artoru EDGE (v2 INT8 · ~65M ONNX Router · LIVE ON HF)      |  |
|  |    Sub-10ms on-device intent classification & deterministic dispatch.       |  |
|  |    Zero cloud round-trips. Zero API cost.                                   |  |
|  +-----------------------------------------------------------------------------+  |
|          |                                                                        |
|          v                                                                        |
|  +-----------------------------------------------------------------------------+  |
|  | 2. THE WORKSPACE: Artoru Desk (v1.0 Release · Drops 5 Nov)                  |  |
|  |    * Chief Engine : Local llama.cpp (GGUF), Ollama, or optional BYO keys    |  |
|  |    * Council      : Multi-agent adversarial debate rooms & trust tiers      |  |
|  |    * Ask-Wins     : Mandatory human sign-off for send / spend / delete / sh |  |
|  |    * Panic Switch : Top-bar emergency killswitch (<2s full process halt)    |  |
|  +-----------------------------------------------------------------------------+  |
+-----------------------------------------------------------------------------------+
