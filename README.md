# MergeMedBench: A Benchmark for Merging Medical LVLMs

This repository provides **MergeMedBench**, a benchmark for evaluating model merging methods for medical large vision-language models (LVLMs).

It corresponds to the paper:

👉 **[Model Merging for Medical LVLMs: A Benchmark and a Winner-Take-All Approach](PASTE_PAPER_LINK_HERE)**

---

## 📦 LoRA Checkpoints

We release LoRA adapters for **two foundation LVLMs** across 8 medical imaging modalities.

### 🔹 Qwen3-VL-2B-Instruct based LoRA

| Model Name | Modality | Download Link |
|------------|----------|---------------|
| Qwen3-VL-2B-Instruct-CT-LoRA | CT | [Download](https://huggingface.co/MergeMedBench/Qwen3-VL-2B-Instruct-CT-LoRA) |
| Qwen3-VL-2B-Instruct-MRI-LoRA | MRI | [Download](https://huggingface.co/MergeMedBench/Qwen3-VL-2B-Instruct-MRI-LoRA) |
| Qwen3-VL-2B-Instruct-XRay-LoRA | X-Ray | [Download](https://huggingface.co/MergeMedBench/Qwen3-VL-2B-Instruct-XRay-LoRA) |
| Qwen3-VL-2B-Instruct-Ultrasound-LoRA | Ultrasound | [Download](https://huggingface.co/MergeMedBench/Qwen3-VL-2B-Instruct-Ultrasound-LoRA) |
| Qwen3-VL-2B-Instruct-Dermoscopy-LoRA | Dermoscopy | [Download](https://huggingface.co/MergeMedBench/Qwen3-VL-2B-Instruct-Dermoscopy-LoRA) |
| Qwen3-VL-2B-Instruct-Fundus-LoRA | Fundus | [Download](https://huggingface.co/MergeMedBench/Qwen3-VL-2B-Instruct-Fundus-LoRA) |
| Qwen3-VL-2B-Instruct-OCT-LoRA | OCT | [Download](https://huggingface.co/MergeMedBench/Qwen3-VL-2B-Instruct-OCT-LoRA) |
| Qwen3-VL-2B-Instruct-Microscopy-LoRA | Microscopy | [Download](https://huggingface.co/MergeMedBench/Qwen3-VL-2B-Instruct-Microscopy-LoRA) |

---

### 🔹 InternVL2-1B based LoRA

| Model Name | Modality | Download Link |
|------------|----------|---------------|
| InternVL2-1B-CT-LoRA | CT | [Download](https://huggingface.co/MergeMedBench/InternVL2-1B-CT-LoRA) |
| InternVL2-1B-MRI-LoRA | MRI | [Download](https://huggingface.co/MergeMedBench/InternVL2-1B-MRI-LoRA) |
| InternVL2-1B-XRay-LoRA | X-Ray | [Download](https://huggingface.co/MergeMedBench/InternVL2-1B-XRay-LoRA) |
| InternVL2-1B-Ultrasound-LoRA | Ultrasound | [Download](https://huggingface.co/MergeMedBench/InternVL2-1B-Ultrasound-LoRA) |
| InternVL2-1B-Dermoscopy-LoRA | Dermoscopy | [Download](https://huggingface.co/MergeMedBench/InternVL2-1B-Dermoscopy-LoRA) |
| InternVL2-1B-Fundus-LoRA | Fundus | [Download](https://huggingface.co/MergeMedBench/InternVL2-1B-Fundus-LoRA) |
| InternVL2-1B-OCT-LoRA | OCT | [Download](https://huggingface.co/MergeMedBench/InternVL2-1B-OCT-LoRA) |
| InternVL2-1B-Microscopy-LoRA | Microscopy | [Download](https://huggingface.co/MergeMedBench/InternVL2-1B-Miscroscopy-LoRA) |

---

## 🧪 Evaluation Dataset

The benchmark evaluation dataset can be downloaded here:

👉 **[MergeMedBench Test Set](https://huggingface.co/datasets/MergeMedBench/MergeMedBenchTest/tree/main)**

---

## 📌 Notes

- All LoRA adapters are trained on modality-specific medical datasets.
- The benchmark supports evaluation of:
  - Model merging strategies
  - Cross-modal generalization
  - Multi-domain medical LVLM performance

---

## 📖 Citation

If you use this benchmark or models, please cite:

```bibtex
@article{mergemedbench2026,
  title={Model Merging for Medical LVLMs: A Benchmark and a Winner-Take-All Approach},
  year={2026}
}
