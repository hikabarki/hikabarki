<div align="center">

![Hika Barki — Biomedical AI Research, VLM, & LLM Engineer](assets/profile-banner.svg)

**Biomedical AI · Multimodal Learning · LLM Engineer · Reproducible Systems**

[Research publications](https://scholar.google.com/citations?user=tGNh80cAAAAJ&hl=en) · [Hugging Face](https://huggingface.co/Hikaf143) · [Selected portfolio](https://huggingface.co/collections/Hikaf143/korean-llms-and-synthetic-clinical-text-safeguards-6acdc88354cc57f9dc7a9421) · [Company work](https://github.com/MKD-CORP)

My other GitHub account: **[mkd-hika](https://github.com/mkd-hika)** — earlier work, activity, and GitHub achievements.

</div>

## About

I am a biomedical AI researcher and machine learning engineer working across physiological signal analysis, wearable sensing, medical imaging, and transformer-based learning. My publication record includes first-author work in **IEEE Journal of Biomedical and Health Informatics**, **IEEE Sensors Journal**, and **IEEE BioCAS**.

At MKD, I work on Korean–English language-model workflows and the engineering systems around data preparation, fine-tuning, evaluation, and local deployment. I build tools that make those workflows easier to inspect and reproduce, connecting research ideas with practical Python APIs, command-line tools, and usable interfaces.

My interests include multimodal learning, subject-level evaluation, reliable language-model systems, and privacy-conscious AI for healthcare and enterprise applications.

## Featured engineering projects

| Project | What to inspect |
|---|---|
| **[SFT Dataset Builder](https://github.com/hikabarki/sft-dataset-builder-1)** | Local conversion of documents, images, audio, and video into structured training datasets; Python API, CLI, and Streamlit UI. |
| **[LLM Dataset Inspector](https://github.com/hikabarki/llm-dataset-inspector)** | Dataset structure, duplicate checks, chat formats, token budgets, and train/evaluation leakage, with evidence and remediation suggestions. |
| **[MKD Fine-Tuning Platform](https://github.com/hikabarki/MKD--Finetuning-platform)** | Gradio and FastAPI interfaces for NVIDIA GPU fine-tuning of text and vision-language models; setup and deployment documentation. |
| **[SkillForge](https://github.com/hikabarki/skillforge)** | Reproducible training-data pipeline and fixture evaluation for agent-skill selection and abstention. CPU pipeline implemented; model training pending. |

## Research and selected publications

My research spans biomedical signals, multimodal sensing, medical-image analysis, and transformer-based classification. Selected first-author publications:

- **[Optimized XGBoost for Multimodal Affective State Classification Using In-Ear PPG and Behind-the-Ear EEG Signals](https://doi.org/10.1109/JBHI.2025.3598354)** — IEEE Journal of Biomedical and Health Informatics; early access 2025, final issue 2026.
- **[Detection and Classification of Mental Stress Using In-Ear Plethysmography and a Vision Transformer](https://doi.org/10.1109/JSEN.2024.3512595)** — IEEE Sensors Journal; early access 2024, volume 25(2).
- **[Stress-ViT: In-Ear Plethysmography for Mental Stress Classification with Vision Transformer](https://doi.org/10.1109/BioCAS58349.2023.10389058)** — IEEE BioCAS 2023.

[Full publication profile](https://scholar.google.com/citations?user=tGNh80cAAAAJ&hl=en) · [Supplied bibliography and publication details](https://huggingface.co/spaces/Hikaf143/synthetic-emr-safeguards/blob/main/PUBLICATIONS.md)

## Reproduce and explore

- **[Dataset Builder examples](https://github.com/hikabarki/sft-dataset-builder-1/tree/main/examples):** inspect bundled inputs and reproduce the dataset-building workflow.
- **[Dataset Inspector examples](https://github.com/hikabarki/llm-dataset-inspector/tree/main/examples):** inspect audit evidence and generated reports.
- **[SkillForge examples](https://github.com/hikabarki/skillforge/tree/main/examples):** reproduce the CPU fixture pipeline and baseline reports.
- **[Synthetic EMR demo](https://huggingface.co/spaces/Hikaf143/synthetic-emr-safeguards):** inspect patient-level splits, identifier redaction, exact evidence citations, and refusal when information is absent.

The EMR demo uses fully synthetic records and a deterministic extraction baseline. It is an engineering safeguards prototype prepared with AI coding assistance, not a clinically validated system or an evaluation of a clinical LLM. Published biomedical studies and company models are separate work with their own evidence and attribution.

## Tools and methods

**Python · PyTorch · Transformers · FastAPI · Gradio · Streamlit · Docker · Git**

Biomedical signal processing · Vision transformers · Multimodal learning · Training-data quality · Fine-tuning pipelines · Local model serving · Reproducible evaluation

---

Explore each repository's README for implementation status, setup instructions, authorship, licensing, and known limitations. Original team and upstream credits are retained in company projects and fork-derived repositories.
