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
| Qwen3-VL-2B-Instruct-CT-LoRA | CT | [Download](LINK_TO_MODEL) |
| Qwen3-VL-2B-Instruct-MRI-LoRA | MRI | [Download](LINK_TO_MODEL) |
| Qwen3-VL-2B-Instruct-XRay-LoRA | X-Ray | [Download](LINK_TO_MODEL) |
| Qwen3-VL-2B-Instruct-Ultrasound-LoRA | Ultrasound | [Download](LINK_TO_MODEL) |
| Qwen3-VL-2B-Instruct-Dermoscopy-LoRA | Dermoscopy | [Download](LINK_TO_MODEL) |
| Qwen3-VL-2B-Instruct-Fundus-LoRA | Fundus | [Download](LINK_TO_MODEL) |
| Qwen3-VL-2B-Instruct-OCT-LoRA | OCT | [Download](LINK_TO_MODEL) |
| Qwen3-VL-2B-Instruct-Microscopy-LoRA | Microscopy | [Download](LINK_TO_MODEL) |

---

### 🔹 InternVL2-1B based LoRA

| Model Name | Modality | Download Link |
|------------|----------|---------------|
| InternVL2-1B-CT-LoRA | CT | [Download](LINK_TO_MODEL) |
| InternVL2-1B-MRI-LoRA | MRI | [Download](LINK_TO_MODEL) |
| InternVL2-1B-XRay-LoRA | X-Ray | [Download](LINK_TO_MODEL) |
| InternVL2-1B-Ultrasound-LoRA | Ultrasound | [Download](LINK_TO_MODEL) |
| InternVL2-1B-Dermoscopy-LoRA | Dermoscopy | [Download](LINK_TO_MODEL) |
| InternVL2-1B-Fundus-LoRA | Fundus | [Download](LINK_TO_MODEL) |
| InternVL2-1B-OCT-LoRA | OCT | [Download](LINK_TO_MODEL) |
| InternVL2-1B-Microscopy-LoRA | Microscopy | [Download](LINK_TO_MODEL) |

---

## 🧪 Evaluation Dataset

The benchmark evaluation dataset can be downloaded here:

👉 **[MergeMedBench Test Set](LINK_TO_TEST_DATASET)**

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
