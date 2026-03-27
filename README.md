# # 🧠 LLM System Requirements Calculator

A modern, browser-based tool to estimate the **hardware requirements (GPU, RAM, CPU)** needed to run Large Language Models (LLMs) locally.

---

## 🌐 Live Demo

👉 https://jaykumar122.github.io/LLM-System-Requirements-Calculator/

---

## 🚀 Features

* 📊 Estimate VRAM required for different LLM sizes
* ⚡ Calculate system RAM requirements
* 🧮 Supports multiple precisions (FP32, FP16, INT8, 4-bit)
* 🎯 Pre-configured model presets (LLaMA, Mistral, Gemma, etc.)
* 📈 Performance estimation (tokens/sec)
* 💻 GPU recommendations based on requirements
* 📱 Responsive and modern UI





## 📂 Project Structure

```bash
LLM-System-Requirements-Calculator/
│── index.html     # Main application (HTML + CSS + JS)
│── README.md
```

---

## ▶️ How to Use

### 🌐 Option 1: Use Online

Simply open the live demo:

```
https://jaykumar122.github.io/LLM-System-Requirements-Calculator/
```

---

### 💻 Option 2: Run Locally

1. Clone the repository:

```bash
git clone https://github.com/Jaykumar122/Rock-Paper-Scissors-Game.git
```

2. Open the folder

3. Double-click:

```
index.html
```

---

## ⚙️ How It Works

The calculator estimates memory usage based on:

* Model size (billions of parameters)
* Precision (bytes per parameter)
* Context length
* Runtime overhead (~25%)

It then:

* Calculates total VRAM/RAM required
* Suggests compatible GPUs
* Estimates inference performance

---

## 🧮 Example

| Model | Precision | Estimated VRAM |
| ----- | --------- | -------------- |
| 7B    | FP16      | ~14 GB         |
| 13B   | FP16      | ~26 GB         |
| 70B   | 4-bit     | ~35–45 GB      |

---

## 🛠️ Built With

* HTML
* CSS
* JavaScript

No frameworks, no dependencies — runs entirely in the browser.

---

## 📈 Future Improvements

* Multi-GPU support estimation
* Cloud cost calculator
* Save/share results
* More model presets
* Better accuracy tuning



## 📜 License

This project is open-source and available under the MIT License.

---

## ⭐ Support

If you found this useful, please ⭐ the repo!

---
