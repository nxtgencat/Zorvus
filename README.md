# ⚡ Zorvus

**Zorvus** is an undetectable AI that reads your screen and hears your space and answers — in real time, invisibly.

<img width="700" height="480" alt="zorvus" src="https://github.com/user-attachments/assets/85efe2d5-91d1-4c81-93e2-f0de0a57024a" />

---

## 🚀 Features

### 📸 Screenshot + AI Analysis
- Capture screenshots instantly
- Analyze images using multiple AI models (Gemini, GPT-4, DeepSeek, etc.)
- Supports multi-screenshot stitching
- Stealth mode to work seamlessly in screen-sharing situations

### 🎙️ Transcribe Mode
- Real-time speech-to-text transcription using Speechmatics
- Pause/Resume transcription with hotkeys
- Send transcript to AI for intelligent responses

<img width="700" height="480" alt="transcribe" src="https://github.com/user-attachments/assets/be0050f0-692c-4303-80af-9d3c0851475d" />

### 🧠 AI Assistant
- Supports multiple models: `gemini`, `gpt4`, `gpt4_mini`, `deepseek_v3`, `gemini_lite`
- Instant code help, explanations, and debugging suggestions
- Fast response (<1s for Gemini Lite)

### ⚙️ Smart UI
- Floating windows for a non-intrusive experience
- Move, resize, and reset windows with keyboard
- Click-through mode and profile toggling
- Tray icon for background operation

### 🔐 Auth + Add-ons
- Secure login and session validation
- Add-on gated features: e.g., `copy_paste`, `transcribe_ai`

---

## ⌨️ Hotkeys

### 🌟 General Actions

| Hotkey            | Action                                           |
|-------------------|--------------------------------------------------|
| `Z + A`           | Ask AI based on current screenshot/transcript    |
| `Z + S`           | Enter Capture Mode                               |
| `Z + T`           | Enter Transcribe Mode                            |
| `Z + Q`           | Exit current mode                                |
| `Z + Space`       | Capture screenshot / Toggle transcription        |
| `Z + Tab`         | Switch AI model                                  |
| `Z + X`           | Toggle UI visibility                             |
| `Z + P`           | Open login/profile screen                        |
| `Z + C`           | Copy selected Q&A (requires `copy_paste` addon)  |
| `Z + .`           | Reset transcript (in Transcribe mode)            |

### 🔍 Navigation

| Hotkey            | Action                                           |
|-------------------|--------------------------------------------------|
| `Z + ↑/↓/←/→`     | Scroll view in respective direction              |
| `Z + Shift + ↑/↓` | Select previous/next question                    |

### 🪟 Window Management

| Hotkey            | Action                                           |
|-------------------|--------------------------------------------------|
| `Z + Alt + ↑/↓/←/→` | Move window                                     |
| `Z + Alt + R`     | Reset window positions                           |

---

## 👁️ Stealth Mode

- Hides UI during screen sharing
- UI windows are movable, transparent, and click-through enabled
- Use double `Ctrl` to toggle Z key modifier suppression

**Pro Tips:**  
- The focused question is indicated with a `>>` symbol.  
- Use `Z + C` to copy the focused question's answer.  
