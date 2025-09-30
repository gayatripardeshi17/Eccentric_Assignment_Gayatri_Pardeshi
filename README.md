# 🌟 AI Image Generation Assignment
*Author: Gayatri Pardeshi*

---

## 🎯 Objective
The objective of this project is to generate **nine unique, high-quality images** of three Indian locations using only **open-source models**:
- **Bandra–Worli Sea Link (Mumbai)**
- **Hawa Mahal (Jaipur, Rajasthan)**
- **Nagpur Rainforest**

Each location is represented with **three distinct images** that capture different angles, lighting conditions, and atmospheres.

---

## 📸 Reference Collection
Reference photographs of each location were collected from publicly available sources.  
These references guided **prompt engineering** to ensure accurate representations of landmarks and landscapes.

---

## ⚙️ Tools & Models
- Google Colab with GPU runtime  
- Hugging Face `diffusers` library (Stable Diffusion v1.5)  
- Python scripting for automated generation and seed control  
- Real-ESRGAN for high-resolution upscaling of selected outputs  

---

## 🔄 Workflow / Pipeline
1. Designed detailed prompts describing **camera angles, times of day, and visual styles**.  
2. Set up **Stable Diffusion** on Google Colab using Hugging Face `diffusers`.  
3. Generated large batches of images with varying **random seeds**.  
4. Reviewed outputs and selected the **best three per location**.  
5. Upscaled final images to **1024×1024 pixels** using Real-ESRGAN.  
6. Packaged the final images, prompts, and seeds for reproducibility.  

---

## ⚡ Model Settings
- **Guidance scale:** 7.5  
- **Inference steps:** 30  
- **Output resolution:** 1024×1024  
- **Seeds:** Recorded for every final image (see below)  

---

## 📝 Prompts and Seeds
| Location | Image | Prompt (summary) | Seed |
|----------|-------|------------------|------|
| **Bandra–Worli Sea Link** | sea link 1 | Aerial drone shot at golden hour, cinematic | 42 |
|  | sea link 2 | Side coastline view, midday, clear sky | 1234 |
|  | sea link 3 | Night long-exposure with light trails | 2025 |
| **Hawa Mahal** | hawa mahal 1 | Front façade at golden hour, warm sandstone texture | 3141 |
|  | hawa mahal 2 | Wide-angle street view, bright daylight | 2718 |
|  | hawa mahal 3 | Close-up of windows and carvings, shallow depth of field | 1618 |
| **Nagpur Rainforest** | rainforest 1 | Dense rainforest, misty morning, lush green foliage | 5150 |
|  | rainforest 2 | Trail through rainforest with thick canopy, damp soil | 6174 |
|  | rainforest 3 | Waterfall hidden inside rainforest, cinematic lighting | 7201 |

---

## 📂 Repository Structure
