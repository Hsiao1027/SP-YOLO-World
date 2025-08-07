# Efficient Low-Light Object Detection via Smart Prompting with YOLO-World

> **ICASI 2025**  
> Ricky Christanto, Cheng-Yen Hsiao, Shaou-Gang Miaou

---

## Abstract

Object detection in low-light environments is critical for surveillance, autonomous driving, and robotics applications, yet it remains challenging due to weak contrast and high noise levels. Traditional methods often rely on image enhancement techniques to address these issues, but such approaches come with high computational costs and increased latency. To overcome these limitations, we propose a novel method that leverages smart prompting (SP) within the YOLO-World framework, an open-vocabulary model designed to detect key object features without requiring image enhancement modules. By focusing on critical object hints, our approach reduces computational overhead while maintaining robust detection performance. Experimental evaluations on the ExDark dataset demonstrate that SP YOLO-World outperforms YOLOv8n with image enhancement regarding mean Average Precision (mAP) while achieving significantly lower latency. This balance between accuracy and efficiency makes SP YOLO-World well-suited for real-time object detection in challenging low-light scenarios. Our findings highlight the potential of smart prompting as a lightweight yet effective solution for improving object detection performance in resource-constrained environments.

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
