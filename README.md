# 📦 Apple-Intelligence Image Editing Dataset (AIE-Dataset)
### *Device-Aware On-Device Generative AI Edit Detection*

<p align="center">
  <img src="https://img.shields.io/github/stars/your-username/your-repo?style=flat-square" />
  <img src="https://img.shields.io/github/forks/your-username/your-repo?style=flat-square" />
  <img src="https://img.shields.io/github/issues/your-username/your-repo?style=flat-square" />
  <img src="https://img.shields.io/github/license/your-username/your-repo?style=flat-square" />
  <img src="https://img.shields.io/badge/Dataset%20Size-~3K%20Images-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Devices-Macbook%20%7C%20iPhone%20%7C%20iPad-green?style=flat-square" />
</p>

---

## 📌 Overview
The **AIE-Dataset** is a curated dataset of images edited using **Apple Intelligence** on MacBook Pro, iPhone, and iPad.  
All original images were sourced legally from **pixel.com** and edited via on-device generative AI tools (Cleanup, Object Removal, Fill, Scene Completion).

---

## 🛠 Dataset Structure
```
AIE-Dataset/
├── original/
├── macbook/
│   ├── Original Images
│   ├── Edited Image
│ 
├── iphone/
│   ├── Original Image
│   ├── Edited Image
│   
├── ipad/
│   ├── Original Image
│   ├── Edited Image
│   

```

---

## 🎯 Motivation
On-device generative AI leaves subtle forensic traces.  
This dataset supports research in:
- Real vs AI-edited detection  
- Device attribution  
- Edit localization  
- VLM-based edit captioning  
- Semantic edit detection  

---

## 🔍 Types of Edits
- Object Removal  
- Cleanup / Dust / Blemish removal  
- Background reconstruction  
- Inpainting / Fill  
- Scene completion  
- Neural hallucinations  

---

## 📚 Intended Use Cases
- Image Forensics  
- VLM Captioning  
- Device Attribution  
- Edit Localization  
- Deep Learning Classification  

---

## 🧪 Suggested Baselines
| Task | Baselines |
|------|-----------|
| Real vs Edited | ResNet50, EfficientNet, Swin-T |
| Device Attribution | Swin-B, Noiseprint++, NFA-ViT |
| Edit Captioning | Qwen-VL, BLIP-2, LLaVA |
| Localization | U-Net, SAM + forensic heatmap |

---

## 📜 License
- Original images from **pixel.com** (free license)  
- Edited images released under **MIT**  

---

## 🤝 Citation
```
@dataset{AIE2025,
  title={AIE-Dataset: Apple-Intelligence Based Image Editing Dataset},
  author={Soumik, Mohd Farhan Israk},
  year={2025},
  url={https://github.com/your-username/your-repo}
}
```

---

## 🙌 Contributors
- Mohd. Farhan Israk Soumik (SIUC)
- WKM Mithsara(SIUC)
- Abdur Rahman Bin Shahid, Ph.D.
- Ahmed Imteaj, Ph.D.

---

## 📞 Contact
- Email: **farhan.soumik@gmail.com**
- Issues: GitHub Issues tab
