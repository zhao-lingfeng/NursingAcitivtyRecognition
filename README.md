# 🧍‍♀️ Nursing Activity Recognition using Pose Estimation and LLMs

This project presents a skeleton-based human activity recognition system for short and subtle medical actions, particularly in **gastrostomy tube feeding (GTF)** procedures. 

We combine pose estimation, machine learning, and large language models (LLMs) to enhance the recognition of brief nursing actions by generating contextual and temporal features from human keypoint data.

---

## 📌 Features

- Pose estimation and keypoint extraction (YOLO11-based)
- Activity classification using ML models (Random Forest)
- LLM-guided feature generation:  
  - 🧠 **Chain-of-Thought prompting**
  - 📂 **Task decomposition prompting**
- Support for sequential and temporal modeling
- Post-processing for smoothing and short action enhancement

---

## 📁 Notebook Overview

| Notebook | Description |
|----------|-------------|
| `yolo11_keypoint_extraction.ipynb` | Extract keypoints using pose estimation models |
| `activity_recognition.ipynb` | Main training and classification pipeline |
| `llm_based_recognition_demo.ipynb` | Initial demo integrating LLM-based features |
| `chain_of_thought_results.ipynb` | Results from chain-of-thought prompting (LLM output features) |
| `task_decomposition_results.ipynb` | Results from task decomposition prompting |
| `Sequence.ipynb` | Experiments using sequential modeling (window-based) |
| `Temporal.ipynb` | Time-aware feature generation and preprocessing |
| `Temporal and Sequence.ipynb` | Combined temporal + sequential pipeline analysis |
| `convert_srt.ipynb` | Convert SRT annotations into time-aligned segments |

---

## 🛠 Technologies

- Python  
- SMOTE 
- Random Forest
- HuggingFace Transformers (LLM prompting)
- ......
