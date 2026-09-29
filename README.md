# IPClaim: CropSeek-LLM

## 1. CLAIMANT INFORMATION

- **Author/Claimant**: Darshani Persadh (@persadian)
- **Organization**: DARJYO
- **GitHub Handle**: arishma108
- **Hugging Face Handle**: @persadian

## 2. MODEL IDENTIFICATION

- **Model Name**: CropSeek-LLM
- **Hugging Face Repository**: https://huggingface.co/persadian/CropSeek-LLM
- **Model Type**: Causal Language Model (Fine-tuned with LoRA)
- **Base Model**: deepseek-ai/DeepSeek-R1-Distill-Qwen-7B
- **Training Dataset**: DARJYO/sawotiQ29_crop_optimization
- **Domain**: Agricultural reasoning and crop optimization
- **Training Hardware**: Nvidia Tesla T4 GPU
- **License**: DARJYO License v1.3

## 3. PUBLICATION AND CITATION

- **DOI**: 10.57967/hf/5849 [citation:23]
- **Citation**:
  Persadh, D. Darshani. R: CropSeek-LLM: Agricultural Domain Language Model. Hugging Face (2025). https://doi.org/10.57967/hf/5849

## 4. MODEL DESCRIPTION

CropSeek-LLM is a domain-specific agricultural language model designed to support agricultural reasoning, advisory systems, and applied AI research in crop science and agritech environments. The model is optimized for answering questions related to crop planting, soil conditions, pest control, irrigation, and other agricultural practices.

## 5. TECHNICAL SPECIFICATIONS

- **Parameters**: Fine-tuned from a 7B parameter base model
- **Checkpoint Size**: Approximately 1.5 GB
- **Training Method**: LoRA (Low-Rank Adaptation)
- **Training Time**: Approximately 10 hours on a T4 GPU
- **Inference Latency**: Average response time of 0.5 seconds on a T4 GPU

## 6. EVALUATION METRICS

- **Accuracy**: 92% on crop identification tasks
- **Precision**: 0.89
- **Recall**: 0.91
- **F1-Score**: 0.90

## 7. OWNERSHIP AND ATTRIBUTION

- **Model Lineage**: Fine-tuned from deepseek-ai/DeepSeek-R1-Distill-Qwen-7B using the DARJYO/sawotiQ29_crop_optimization dataset
- **Intellectual Property Claim**: The fine-tuning, domain adaptation, and training methodology applied to create CropSeek-LLM constitute original work by the claimant.

## 8. LICENSING AND USAGE RIGHTS

- **License**: DARJYO License v1.3
- **Permitted Uses**:
  - Research and academic experimentation
  - Fine-tuning for downstream agricultural applications
  - Integration into decision-support systems
  - Commercial deployment with attribution

## 9. VERIFICATION AND INTEGRITY

- **Model Hash/Checksum**: To verify downloaded files # sha256sum -c SHA256_SUMS.txt
- **Initial Commit**: February 23, 2025

## 10. DECLARATION

I, Darshani Persadh (@persadian), hereby claim intellectual property rights over the fine-tuning methodology, domain adaptation, and training procedures applied to create the CropSeek-LLM model as described in this document. This claim is made in good faith and is subject to the terms of the DARJYO License v1.3.

- **Signature**: Darshani Persadh
- **Date**: 2026-09-29
