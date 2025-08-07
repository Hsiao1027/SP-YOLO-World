# Efficient Low-Light Object Detection via Smart Prompting with YOLO-World

> **ICASI 2025**  
> Cheng-Yen Hsiao, Shyang Chang, Shao-Kang Miau

---

## 🧠 Abstract

Low-light conditions pose significant challenges for object detection due to reduced visibility and low signal-to-noise ratios.  
We propose an efficient and modular prompting strategy integrated into **YOLO-World** to enhance its robustness under illumination-degraded scenes.  
By leveraging semantic priors and dynamically selected class prompts, our method:

- enhances the model's attention to relevant regions,
- improves both detection accuracy and inference efficiency,
- and requires **no additional training or image enhancement pre-processing**.

Our approach demonstrates superior performance across several low-light detection benchmarks, with minimal computational overhead.

---

## 📊 Visual Comparison: w/o SP vs. w/ SP

The following figure shows the impact of Smart Prompting (SP) under challenging low-light conditions.

<p align="center">
  <img src="assets/without_SP_vs_with_SP.png" width="700" alt="Comparison between YOLO-World w/o SP and with SP"/>
</p>

- **Left:** YOLO-World baseline without Smart Prompting (SP)  
- **Right:** Our method with SP – more focused and precise detections under poor lighting

---

## 📌 Highlights

- 💡 **Prompt-aware detection**: Integrates semantic guidance into the object detection pipeline.
- ⚙️ **No retraining required**: Plug-and-play with existing YOLO-World weights.
- ⚡ **Lightweight and generalizable**: Improves low-light detection on diverse datasets (ExDark, LLVIP, DARK FACE).

---

## 🔜 Coming Soon

- 🔧 Code for Smart Prompting module
- 🧪 Evaluation on public datasets
- 📦 Pre-trained prompts and demo script

---

## 🔗 Citation

```bibtex
@inproceedings{hsiao2025efficient,
  title={Efficient Low-Light Object Detection via Smart Prompting with YOLO-World},
  author={Cheng-Yen Hsiao and Shyang Chang and Shao-Kang Miau},
  booktitle={Proceedings of the 2025 International Conference on Advanced Smart Information (ICASI)},
  year={2025}
}
