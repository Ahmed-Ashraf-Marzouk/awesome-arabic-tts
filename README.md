# Awesome Arabic TTS 🎙️

A curated list of Text-to-Speech (TTS) models, ranging from foundation models to dialect-specific fine-tunes.

---

## 🚀 The Awesome List

| Model Name | Tag | Dialect / Style | Source |
| --- | --- | --- | --- |
| **Qwen3-TTS** | `MSA` | Expressive, Streaming, Cloning | [GitHub](https://github.com/QwenLM/Qwen3-TTS) |
| **F5-TTS Arabic** | `MSA` | Flow Matching, High Fluency | [HF](https://huggingface.co/IbrahimSalah/Arabic-F5-TTS-v2) |
| **Spark TTS Arabic** | `MSA` | High Fidelity (300h training) | [HF](https://huggingface.co/IbrahimSalah/Arabic-TTS-Spark) |
| **EGTTS-V0.1** | `EG` | Cairene Accent | [HF](https://huggingface.co/OmarSamir/EGTTS-V0.1) |
| **Saudi TTS** | `SA` | Najdi / Hijazi | [HF](https://huggingface.co/AhmedEladl/saudi-tts) |
| **Habibi TTS** | `MSA` / `Dialect` | Multi-speaker / Expressive | [HF Space](https://huggingface.co/spaces/chenxie95/Habibi-TTS) |
| **Chatterbox Egyptian** | `EG` | Colloquial Egyptian | [HF](https://huggingface.co/oddadmix/chatterbox-egyptian-v0) |
| **XTTS-v2** | `MSA` | Zero-shot Voice Cloning | [HF](https://huggingface.co/coqui/XTTS-v2) |
| **FishSpeech** | `MSA` | SOTA Architecture & Fine-tuning | [GitHub](https://www.google.com/search?q=https://github.com/iiFadel/fish-speech-finetune) |
| **IMS-Toucan** | `MSA` | Controllable (7000+ languages) | [GitHub](https://github.com/DigitalPhonetics/IMS-Toucan) |
| **StyleTTS** | `MSA` | Human-level Prosody | [GitHub](https://github.com/yl4579/StyleTTS) |
| **FastSpeech 2** | `MSA` | Fast Inference Baseline | [GitHub](https://github.com/ming024/FastSpeech2) |
| **Parrot-TTS** | `MSA` | Official ParrotTTS Implementation | [GitHub](https://github.com/parrot-tts/Parrot-TTS) |
| **VoiceBox** | `MSA` | Generative Speech Model (Meta) | [Web](https://about.fb.com/news/2023/06/introducing-voicebox-ai-for-speech-generation/) |

---

## 🌍 Dialect Coverage Status

*Use these tags when contributing new models to the list.*

| Region | Tags | Status |
| --- | --- | --- |
| **Standard** | `MSA` | ✅ Available |
| **Nile Valley** | `EG` / `SD` | ✅ EG Available / ⏳ SD Pending |
| **Maghreb** | `MA` / `DZ` / `TN` / `LY` | ⏳ Pending |
| **Levant** |  `LB` / `SY` / `JO` / `PS` | ⏳ Pending |
| **Gulf** | `SA` / `AE` / `KW` / `QA` / `OM` / `BH` | ✅ SA Available / ⏳ Others Pending |
| **Mesopotamia** | `IQ` | ⏳ Pending |

---

## 🛠️ Proprietary & API Services

*Closed-source high-fidelity options.*

* **ElevenLabs:** Best-in-class emotional depth (`MSA` + `Dialect`).
* **Google Cloud TTS:** Stable production-grade `MSA`.
* **Resemble AI:** Real-time generation via Chatterbox-Multilingual.

---
## 📊 Benchmarks & Evaluation

*Tools and leaderboards to compare model performance, naturalness, and diacritization accuracy.*

* **[Arabic TTS Benchmark (Qualitative)](https://huggingface.co/spaces/silma-ai/arabic-tts-benchmark):** A leading qualitative benchmark by SILMA.AI for side-by-side auditory comparison of top Arabic speech models.
* **[Open-source Arabic TTS Benchmark](https://huggingface.co/spaces/silma-ai/opensource-arabic-tts-benchmark):** A dedicated community leaderboard focused exclusively on evaluating and ranking open-source Arabic TTS weights.
* **[ArFake Multi-Dialect Benchmark](https://huggingface.co/papers/2509.22808):** A 2025 research benchmark used to evaluate the realism of synthetic speech across various Arabic dialects (EG, MA, etc.) and its resistance to spoof detection.
* **[ClArTTS Evaluation](https://www.isca-archive.org/interspeech_2023/kulkarni23_interspeech.pdf):** A standard for Classical Arabic (Fusha) evaluation using F0 RMSE (pitch accuracy) and MOS (Mean Opinion Score).

---

Would you like me to add a **"Best for..."** section to help users choose between these based on their benchmark scores?
## 💡 How to Contribute

To add a model, simply append a row to the table above following this format:
`| **Model Name** | 🚩 [ISO Tag] | Dialect Description | [Link] |`
