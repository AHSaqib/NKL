# Noor Keyboard Layout (NKL)

🖋️ **Noor Keyboard Layout (NKL)** is a custom keyboard layout project designed to make typing in **Bangla and Arabic** more comfortable and user-friendly.

Most existing layouts require complex key combinations for Arabic diacritics (Harakat such as Fatha, Kasra, Damma, Sukun, etc.) or certain commonly used letters. NKL simplifies this by placing frequently used characters and marks in logical, easy-to-reach positions.

---

## ✨ Features

* Separate layouts for Bangla and Arabic.
* Easy access to Arabic diacritics (Harakat):

  * `f` → Fatha (َ)
  * `d` → Kasra (ِ)
  * `s` → Damma (ُ)
  * `Shift+f/d/s` → Tanwin (ً ٍ ٌ)
  * `Shift+a` → Shadda (ّ)
* Reduced reliance on Shift for common letters:

  * `d` → د (Dal)
  * `Shift+d` → ذ (Dhal)
* Bangla layout uses standard Unicode characters with a few custom shortcuts.

---

## 📂 Repository Structure

```
NKL/
├── src/ # Source .klc files
│ ├── bangla/ # Bangla keyboard layout source
│ └── arabic/ # Arabic keyboard layout source
│
├── build/ # Compiled installers (dll/msi)
│
├── docs/ # Layout diagrams, usage guide, documentation
│
├── LICENSE # Apache 2.0 license
├── README.md # Project description
└── .gitignore # Ignored build/output files
```

---

## ⚙️ Installation

1. Download the latest `.msi` installer from the [Releases](../../releases) section.
2. Install it, then add `Noor Keyboard Layout` from Windows **Language & Keyboard settings**.
3. Optionally, set it as your default keyboard.

---

## 🎯 Goals

* Provide a modern, ergonomic, and open-source keyboard layout for both Bangla and Arabic.
* Greatly simplify typing with Arabic diacritics for students, teachers, and researchers.

---

## 📜 License

This project is licensed under the [Apache License 2.0](LICENSE).
You are free to use, modify, and distribute it, but copyright notices must be preserved.

---

## 🤝 Contributing

* Suggest new layout improvements.
* Report bugs or open feature requests.
* Contribute code or documentation through Pull Requests.
