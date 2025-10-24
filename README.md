# 🧠 Image Segmentation Research & Implementation

> A collection of reviews, notes, and code implementations based on key research papers in **Deep Learning-based Image Segmentation**.

---

## 📚 Review Paper 1  
### **Image Segmentation Using Deep Learning: A Survey**  
🧾 *By Shervin Minaee, Yuri Boykov, Fatih Porikli, Antonio Plaza, Nasser Kehtarnavaz, and Demetri Terzopoulos*

---

### 🔍 Topics Covered & Progress

| # | Method | Description | Status | Notes |
|---|---------|--------------|--------|-------|
| 1️⃣ | **Fully Convolutional Networks (FCN)** | First pure CNN-based segmentation approach. | ✅ *Explored* | Code done & tested |
| 2️⃣ | **Encoder–Decoder Networks (SegNet, U-Net)** | Symmetric architecture with upsampling-decoder blocks. | 🟡 *Ongoing* | Implementing **SegNet** |
| 3️⃣ | **Multiscale / Pyramid Methods** | Combines multi-resolution features (like SIFT pyramid). | 🔴 *Pending* | To be explored |
| 4️⃣ | **Region-based (R-CNN, Mask R-CNN)** | Uses region proposals for object segmentation. | 🔴 *Pending* | Will explore region-proposal logic |
| 5️⃣ | **Attention-based Models** | State-of-the-art, used in many VLLMs. | 🔴 *Pending* | Recent transformer-based methods |

---

## 🧩 1️⃣ Fully Convolutional Networks (FCN)
📄 **Paper:** *Fully Convolutional Networks for Semantic Segmentation*  
✍️ **Authors:** Jonathan Long, Evan Shelhamer, Trevor Darrell  

**Implementation:** ✅ Completed  
**Observation:**  
> ❗ Doesn’t perform well with image data directly collected from Google — possibly due to dataset bias and noise.  

---

## 🔧 2️⃣ Encoder–Decoder Networks
📄 **Paper:** *SegNet: A Deep Convolutional Encoder–Decoder Architecture for Robust Semantic Pixel-Wise Labelling*  
✍️ **Authors:** Vijay Badrinarayanan, Alex Kendall, Roberto Cipolla  

**Status:** 🟡 Ongoing  
**Focus:**  
> Building and experimenting with **SegNet** to compare against FCN performance.

---

## 🧱 Upcoming Tasks in Encoder - Decoder
- [ ] Explore **U-Net** and **DeepLabv3+** for medical and general segmentation tasks.  

---

## 🧮 Tools & Frameworks
- 🧰 **Frameworks:** PyTorch  
- 🖼️ **Datasets:** Pascal VOC, Cityscapes, Custom scraped images  
- 💾 **Environment:** Python 3.10+, CUDA enabled  

---

## 📊 Progress Tracker

| Category | Status |
|-----------|---------|
| Literature Review | 🟡 Ongoing |
| FCN Implementation | ✅ Completed |
| Encoder–Decoder Implementation | 🟡 In Progress |

---

## 🧠 Key Insight
> Deep learning segmentation evolved from simple CNN-based pixel prediction (FCN) → structured feature reconstruction (SegNet/U-Net) 

---

