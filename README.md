# AI Tools Colab Notebooks

Welcome to my collection of Google Colab notebooks for AI tools. This repository hosts free, easy-to-use notebooks that you can run directly in your browser.

[![YouTube](https://img.shields.io/badge/YouTube-Learn%20with%20Peter-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/@learnwithpeter)
[![Instagram](https://img.shields.io/badge/Instagram-learnwithpeterandstewie-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/learnwithpeterandstewie)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-blue?style=for-the-badge&logo=github)](https://github.com/Learnwithpeterandstewie)

## Notebooks

| Notebook Name | Description | Link | Video Tutorial |
| :--- | :--- | :--- | :--- |
| **HeartMuLa 3B Music Generator** | Free & Open Source AI Music Generation. BF16 Optimized for Colab Free Tier. | [<img src="https://colab.research.google.com/assets/colab-badge.svg" height="28" alt="Open In Colab"/>](https://colab.research.google.com/github/Learnwithpeterandstewie/free-voice-cloner/blob/main/learnwithperandstewie.ipynb) | [![Video Tutorial](https://img.shields.io/badge/Video-Tutorial-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@learnwithpeter) |

## How to use

1. Click the "Open in Colab" badge next to the notebook you want to use.
2. This will open the notebook in Google Colab.
3. Make sure to connect to a runtime (GPU is usually recommended for AI tasks) by going to **Runtime -> Change runtime type**.
4. Run the cells in order.

### Quick Start Guide

- **Cell 1:** Install dependencies (~3-5 min)
- **Cell 2:** Download AI models (~5-10 min, one-time only)
- **Cell 3:** Launch Gradio interface and generate music!

### Music Generation Tips

- Enter your lyrics or use the provided example
- Choose style tags: `piano, calm, acoustic` (comma-separated)
- Set duration (30-360 seconds)
- Click **Generate Music** and wait for results

### Generation Time Estimates

- **30 seconds:** 2-3 minutes
- **60 seconds:** 5-7 minutes  
- **90 seconds:** 7-10 minutes
- **120 seconds:** 10-14 minutes

### Genre & Style Tags

- **Piano & Classical:** `piano, classical, acoustic, orchestral`
- **Electronic & Synthwave:** `electronic, synthwave, upbeat, energetic`
- **Calm & Ambient:** `ambient, calm, peaceful, acoustic`
- **Upbeat Pop:** `pop, happy, upbeat, catchy`
- **Jazz & Lounge:** `jazz, saxophone, smooth, lounge`
- **Rock & Metal:** `rock, heavy, guitar, energetic`

## Features

- 🆓 **100% Free** - Runs on Google Colab's free T4 GPU
- 🎼 **Professional Quality** - Generate music with lyrics & style control
- ⚡ **BF16 Optimized** - Memory-efficient for free tier
- 🎚️ **Advanced Controls** - Temperature, Top-K, CFG Scale parameters
- 🎹 **Multiple Genres** - Piano, Rock, Jazz, Electronic, and more
- 💾 **No Setup** - Works directly in browser

## Troubleshooting

| Problem | Solution |
|---------|----------|
| **CUDA Out of Memory** | Reduce duration or restart runtime |
| **Model Download Fails** | Check internet & retry |
| **Poor Audio Quality** | Improve lyrics, adjust temperature to 0.9, CFG to 1.8 |
| **Session Timeout** | Upgrade to [Colab Pro](https://colab.research.google.com/signup) |

## Credits

- **HeartMuLa Model:** [HeartMuLa Team](https://github.com/HeartMuLa/heartlib)
- **Research Paper:** [arXiv:2601.10547](https://arxiv.org/abs/2601.10547)
- **BF16 Optimization:** [benjiaiplayground](https://huggingface.co/benjiaiplayground)
- **Framework:** [Gradio](https://www.gradio.app/)

## Contributing

Feel free to open issues or submit pull requests if you have suggestions or improvements for the notebooks.
