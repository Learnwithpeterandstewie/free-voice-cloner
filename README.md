# 🎵 HeartMuLa 3B - AI Music Generator

<div align="center">

[![Python 3.8+](https://img.shields.io/badge/python-3.8%2B-blue?style=flat-square&logo=python)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-Open%20Source-green?style=flat-square)](LICENSE)
[![Google Colab](https://img.shields.io/badge/Open%20in-Google%20Colab-F9AB00?style=flat-square&logo=googlecolab)](https://colab.research.google.com/github/[YOUR-USERNAME]/HeartMuLa-3B/blob/main/HeartMuLa_by_AIQUEST%20(1).ipynb)
[![GitHub Stars](https://img.shields.io/github/stars/[YOUR-USERNAME]/HeartMuLa-3B?style=flat-square&color=yellow)](https://github.com/[YOUR-USERNAME]/HeartMuLa-3B/stargazers)

### Generate Professional AI Music on Google Colab's Free Tier 🎼

*Create stunning, royalty-free music with advanced lyrics control, style tags, and neural generation—no GPU purchase needed!*

[🚀 Quick Start](#-quick-start) • [✨ Features](#-features) • [💻 Setup](#-setup) • [📚 Guide](#-usage-guide) • [🎥 YouTube](#-connect-with-us)

</div>

---

## 🚀 Quick Start

### Open in Google Colab ⚡
**Click the button below to get started immediately—no installation required!**

<div align="center">

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/[YOUR-USERNAME]/HeartMuLa-3B/blob/main/HeartMuLa_by_AIQUEST%20(1).ipynb)

**OR** paste this link in your browser:
```
https://colab.research.google.com/github/[YOUR-USERNAME]/HeartMuLa-3B/blob/main/HeartMuLa_by_AIQUEST%20(1).ipynb
```

</div>

---

## ✨ Features

| Feature | Details |
|---------|---------|
| 🆓 **100% Free** | Runs on Google Colab's free T4 GPU (15GB VRAM) |
| 🎼 **Professional Quality** | Generate music with lyrics, style control, and multiple genres |
| ⚡ **Fast Generation** | 5-7 minutes per minute of audio (optimized BF16 inference) |
| 🎚️ **Advanced Controls** | Temperature, Top-K sampling, CFG scale adjustments |
| 🌍 **Multilingual** | Support for multiple languages in lyrics |
| 🎹 **Style Tags** | Piano, rock, jazz, electronic, acoustic, and more |
| 💾 **No Setup** | Works directly in browser—no code required |
| 🔒 **Privacy** | All processing happens on your Colab session |

---

## 🎯 What Can You Create?

Generate music across multiple genres with full creative control:

- 🎹 **Classical & Piano** - Soft, ambient, cinematic tracks
- 🎸 **Rock & Metal** - Heavy, upbeat, energetic compositions
- 🎷 **Jazz & Lounge** - Smooth, sophisticated background music
- 🎧 **Electronic & Synthwave** - Futuristic, high-energy beats
- 🎤 **Pop & Hip-Hop** - Catchy, rhythmic vocal-friendly tracks
- 🌿 **Acoustic & Folk** - Warm, natural, storytelling music
- 🎼 **Orchestral & Cinematic** - Epic, dramatic soundtracks

---

## 🛠️ Setup (3 Simple Steps)

### Step 1️⃣: Open the Notebook
Click the Colab badge above to open the notebook in your browser. No downloads needed!

### Step 2️⃣: Run the Setup Cells
1. Execute **Cell 1** - Installs dependencies (~3-5 min)
2. Execute **Cell 2** - Downloads AI models (~5-10 min, one-time only)
3. Execute **Cell 3** - Launches the web interface

### Step 3️⃣: Generate Music! 🎵
- Enter your lyrics (or use the example)
- Choose style tags (piano, happy, calm, etc.)
- Set duration and generation parameters
- Click **Generate Music** and wait for magic!

**Total First Run:** ~15-20 minutes (includes setup)
**Subsequent Runs:** ~5-10 minutes (models cached)

---

## 📚 Usage Guide

### Basic Music Generation

#### Lyric Format
```
[Intro]
Optional intro text here

[Verse]
Main verse lyrics with emotional depth

[Chorus]
Catchy, memorable chorus

[Bridge]
Optional bridge section

[Outro]
Closing thoughts or outro lyrics
```

#### Style Tags (Examples)
Choose from these or mix your own:
- **Emotions:** happy, sad, energetic, calm, melancholic, uplifting
- **Instruments:** piano, guitar, violin, saxophone, drums, strings
- **Genres:** pop, rock, jazz, classical, electronic, acoustic, folk
- **Moods:** ambient, cinematic, lounge, upbeat, soothing

**Example Tags:**
```
piano, calm, morning, acoustic, gentle
```

### Advanced Parameters

| Parameter | Range | Effect |
|-----------|-------|--------|
| **Temperature** | 0.7 - 1.3 | Higher = more creative & experimental |
| **Top-K** | 20 - 100 | Controls diversity (50 = balanced) |
| **CFG Scale** | 1.0 - 3.0 | Style adherence (1.5-2.0 recommended) |
| **Duration** | 30-360s | Audio length (5-7 min generation per minute) |

### Generation Time Guide

| Duration | Est. Time | Notes |
|----------|-----------|-------|
| 30 seconds | 2-3 min | Quick test |
| 60 seconds | 5-7 min | Standard track |
| 90 seconds | 7-10 min | Medium composition |
| 120 seconds | 10-14 min | Full song |
| 180 seconds | 15-21 min | Extended track |

**⚠️ Colab Tip:** Sessions timeout after 90 minutes of inactivity. Keep the tab open!

---

## 💡 Pro Tips & Tricks

### ✅ Tips for Better Results
- **Start Small:** Begin with 60-90 second generations to test ideas
- **Detailed Lyrics:** More specific lyrics = better quality output
- **Tag Combinations:** Mix genres for unique sounds (e.g., "jazz, electronic, lounge")
- **Balanced Settings:** Temperature 1.0 + CFG 1.5 works well for most cases
- **Iterate:** Generate variations with slight parameter tweaks

### 🎯 Genre-Specific Settings

**Piano & Classical**
```
Tags: piano, classical, acoustic, orchestral
Temp: 0.9 | TopK: 45 | CFG: 1.8
```

**Electronic & Synthwave**
```
Tags: electronic, synthwave, upbeat, energetic
Temp: 1.1 | TopK: 55 | CFG: 1.5
```

**Calm & Ambient**
```
Tags: ambient, calm, peaceful, acoustic
Temp: 0.8 | TopK: 40 | CFG: 1.6
```

**Upbeat Pop**
```
Tags: pop, happy, upbeat, catchy
Temp: 1.0 | TopK: 50 | CFG: 1.5
```

---

## 🔧 Technical Details

### System Requirements
- ✅ **Google Colab Account** (free)
- ✅ **Internet Connection** (stable)
- ✅ **Modern Web Browser** (Chrome, Firefox, Safari, Edge)

### Colab Specifications
- **GPU:** NVIDIA T4 (15GB VRAM)
- **RAM:** 12GB system RAM
- **Storage:** ~15GB for models (auto-cached)
- **Runtime:** 90 min max (free tier) / Unlimited (Colab Pro)

### Models Included

| Model | Purpose | Size |
|-------|---------|------|
| **HeartMuLa-oss-3B** | Main music generation | ~3GB |
| **HeartCodec-oss** | Audio encoding/decoding | ~1GB |
| **HeartMuLaGen** | Tokenization & config | ~500MB |

All models are optimized in **BF16 precision** for memory efficiency.

---

## 🎓 Learning Resources

### Research & References
- 📄 **Original Paper:** [HeartMuLa Research](https://arxiv.org/abs/2601.10547)
- 🔗 **GitHub Repository:** [HeartMuLa/heartlib](https://github.com/HeartMuLa/heartlib)
- 🤗 **Model Hub:** [Hugging Face Models](https://huggingface.co/benjiaiplayground)

### Video Tutorials
- 🎥 **Getting Started:** Check YouTube for detailed walkthroughs
- 💻 **Advanced Techniques:** Learn parameter tuning and style combinations

---

## 🌟 Example Generations

Try these example prompts to see what's possible:

### Example 1: Morning Jazz
```
Lyrics:
[Verse] Soft piano begins / Morning light fills the room
[Chorus] New day arriving / Life feels fresh and bright

Tags: jazz, piano, calm, morning, smooth
Duration: 90s | Temp: 0.9 | TopK: 45 | CFG: 1.6
```

### Example 2: Epic Synthwave
```
Lyrics:
[Verse] Neon lights paint the street / Pulse beneath my feet
[Chorus] Alive tonight / Feeling right

Tags: electronic, synthwave, energetic, upbeat
Duration: 120s | Temp: 1.1 | TopK: 55 | CFG: 1.5
```

### Example 3: Acoustic Folk
```
Lyrics:
[Verse] Quiet morning light / Peace within my soul
[Chorus] Simple moments here / Mean the world to me

Tags: acoustic, folk, gentle, guitar, calm
Duration: 90s | Temp: 0.8 | TopK: 40 | CFG: 1.8
```

---

## ⚠️ Important Notes

### Limitations
- ⏱️ **Generation Time:** 5-7 minutes per minute of audio (neural model requirement)
- 💾 **Session Duration:** Colab free tier = 90 min max (upgrade to Colab Pro for unlimited)
- 🔄 **Model Reloading:** First run includes ~15 min setup (models cached for future runs)
- 📊 **Quality Variance:** Output quality depends on lyrics and parameter tuning

### Best Practices
- ✅ Keep detailed, descriptive lyrics
- ✅ Use appropriate style tags for genres
- ✅ Test with shorter durations first (30-60s)
- ✅ Keep the Colab tab open during generation
- ✅ Download audio before session ends

---

## 🐛 Troubleshooting

### Issue: "CUDA Out of Memory" Error
**Solution:** Reduce audio duration or restart the runtime (Runtime → Restart runtime)

### Issue: Model Download Fails
**Solution:** Check your internet connection and retry (sometimes HuggingFace has rate limits)

### Issue: Audio Quality is Poor
**Solution:** Improve lyric detail, adjust temperature to 0.9-1.0, and increase CFG scale to 1.8

### Issue: Generation Takes Too Long
**Solution:** This is normal! 5-7 min per audio minute is expected. Use shorter durations for testing.

### Issue: Colab Session Timed Out
**Solution:** Upgrade to [Colab Pro](https://colab.research.google.com/signup) for unlimited runtime

---

## 📜 License & Attribution

### License
This project uses open-source AI models and is shared under an **Open Source License**.

### Credits & Attribution

| Component | Creator | Link |
|-----------|---------|------|
| **HeartMuLa Model** | HeartMuLa Team | [GitHub](https://github.com/HeartMuLa/heartlib) |
| **Research Paper** | HeartMuLa Authors | [arXiv:2601.10547](https://arxiv.org/abs/2601.10547) |
| **BF16 Optimization** | benjiaiplayground | [Hugging Face](https://huggingface.co/benjiaiplayground) |
| **Colab Integration** | Learn with Peter & Stewie | This Repository |
| **Framework** | Gradio | [gradio.app](https://www.gradio.app/) |

### Usage Rights
- ✅ **Free to use** for personal, educational, and non-commercial projects
- ✅ **Attribution appreciated** but not required
- ✅ **Generated music:** Check individual model licenses for commercial use

---

## 🎥 Connect With Us

Love this tool? Follow for more AI & music resources:

<div align="center">

| Platform | Link | Content |
|----------|------|---------|
| 🔴 **YouTube** | [@learnwithpeter](https://youtube.com/@learnwithpeter) | Tutorials & AI guides |
| 📸 **Instagram** | [@learnwithpeterandstewie](https://instagram.com/learnwithpeterandstewie) | Behind-the-scenes & tips |
| ⭐ **GitHub** | [Follow](https://github.com/[YOUR-USERNAME]) | Latest updates & projects |

</div>

---

## 🚀 Quick Links

<div align="center">

[🎵 **Open in Colab**](https://colab.research.google.com/github/[YOUR-USERNAME]/HeartMuLa-3B/blob/main/HeartMuLa_by_AIQUEST%20(1).ipynb) • 
[📖 **View Docs**](#-usage-guide) • 
[🐛 **Report Issue**](https://github.com/[YOUR-USERNAME]/HeartMuLa-3B/issues) • 
[⭐ **Star This Repo**](https://github.com/[YOUR-USERNAME]/HeartMuLa-3B)

</div>

---

## 📞 Support & Feedback

Have questions or suggestions? 
- 💬 **Open an Issue:** [GitHub Issues](https://github.com/[YOUR-USERNAME]/HeartMuLa-3B/issues)
- 📧 **Connect:** Follow us on social media (links above)
- ⭐ **Show Support:** Star this repository if you find it helpful!

---

<div align="center">

### Made with ❤️ for Creators & Musicians

**Happy Creating! 🎵**

*Remember: The only limit is your imagination.*

---

Last Updated: 2026 | Repository Version: 1.0
</div>
