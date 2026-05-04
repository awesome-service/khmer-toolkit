
# Khmer Toolkit — All-in-One Khmer TTS & Audio Suite

**Free AI toolkit for Khmer text-to-speech and audio processing target end user who don't know how to setup local sorfware (GPU relate)**

✨ Co-authored with AI agents Claude Opus & Gemini 3 Pro ✨

> [!CAUTION]
> **Use responsibly and at your own risk.**
> Do not clone or process voices, audio, or video of real people without explicit consent. Respect privacy and intellectual property laws. The authors are not liable for misuse. See **Legal Warnings** below.
>
> **Beta:** Features and APIs may change. Bugs are expected.

---

## Why Khmer Support Is Limited

Many software platforms lack Khmer support due to limited datasets, lower commercial demand, and the complexity of Khmer script and phonetics. This toolkit aims to help bridge that gap.

---

## Overview

Khmer Toolkit is a cross-platform AI suite built with a **Tauri v2 + Svelte 5 desktop app** and a **FastAPI backend**. Heavy ML processing runs separately from the UI, ensuring a fast, native desktop experience.

> **Free to use. Source is closed to prevent commercial resale or misuse.**

---

## Features

* **Khmer Text-to-Speech (TTS):** High-quality Khmer voice synthesis
* **Voice Conversion (RVC):** Voice cloning and singing voice transformation
* **Modular Architecture:** Scalable provider-based backend and frontend

---

## Tech Stack

* **Backend:** Python, FastAPI, `uv`
* **Frontend:** TypeScript, Rust, Tauri v2

---

## Legal Warnings

### Voice & Identity

* Do **not** impersonate or clone real individuals without **written consent**
* Deepfake misuse may violate laws (e.g., EU AI Act, US biometric laws, cybercrime regulations)
* Non-consensual or harmful content may be criminally punishable

### Responsible Use

Intended for:

* Khmer content creation
* Accessibility tools
* Research and education

Support may be withdrawn if used for harm.

### Disclaimer

Provided **“as-is”** without warranty. Authors are not liable for damages or misuse.

---

## License

> [!IMPORTANT]
> **Selling this software or offering it as a paid service is prohibited.**


| ✅ Allowed               | ❌ Not Allowed             |
| ----------------------- | ------------------------- |
| Personal use            | Selling the software      |
| Commercial internal use | Paid SaaS / hosting       |
| Research & education    | Charging for access       |
| Non-profit use          | Reselling or sublicensing |
| Modifying & forking     | Bundling for resale       |
| Free redistribution     | Any form of sale          |

---

##Third-Party Licenses

Selling the software is prohibited — see [LICENSE](LICENSE) for details.

This project depends on the following open-source packages. Their licenses
are listed below for attribution and compliance.

---

## edge-tts

- **License:** GNU Lesser General Public License v3.0 (LGPLv3)
- **Author:** rany2
- **Source:** https://github.com/rany2/edge-tts
- **PyPI:** https://pypi.org/project/edge-tts/

This library is used as a dynamically-linked dependency (imported at runtime).
Users may substitute it with any compatible alternative. The full LGPLv3 text
is available at: https://www.gnu.org/licenses/lgpl-3.0.html

---

## openai-whisper

- **License:** MIT License
- **Source:** https://github.com/openai/whisper

## voxcpm

- **License:** Apache License 2.0
- **Source:** https://huggingface.co/myshell-ai/OpenVoiceV2

## deep-translator

- **License:** MIT License
- **Source:** https://github.com/nidhaloff/deep-translator

## FastAPI

- **License:** MIT License
- **Source:** https://github.com/tiangolo/fastapi

## Tauri

- **License:** MIT License / Apache License 2.0
- **Source:** https://github.com/tauri-apps/tauri

## khmernormalizer

- **License:** MIT License
- **Source:** https://github.com/seanghay/khmernormalizer

## khmercut

- **License:** MIT License
- **Source:** https://github.com/seanghay/khmercut-rs



