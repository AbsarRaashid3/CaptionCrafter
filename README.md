# CaptionCrafter: Fine-Tuning BLIP-2 with LoRA on Flickr8k
CaptionCrafter is a vision-language fine-tuning project that combines the power of BLIP-2 and the efficiency of LoRA (Low-Rank Adaptation) to generate intelligent, human-like captions for images. Using the Flickr8k dataset, this project showcases how to fine-tune large multimodal models for image captioning tasks in a memory-efficient way—making cutting-edge AI more accessible.

# Project Overview
The goal of CaptionCrafter is to:

Fine-tune BLIP-2, a state-of-the-art vision-language model, for image captioning on the Flickr8k dataset.

Optimize training using LoRA, which updates only small trainable adapters instead of the full model.

Enable practical and efficient fine-tuning on limited hardware while achieving strong captioning performance.

# Project Description
This project demonstrates:

Fine-tuning Salesforce/blip2-flan-t5-xl to generate captions for images from Flickr8k.

Leveraging LoRA to reduce GPU memory consumption and training time.

Generating fluent, relevant captions for unseen images using learned visual-linguistic representations.

Ideal for:

 Researchers working on custom vision-language tasks.

 Developers seeking to reduce compute costs using LoRA.

 Enthusiasts exploring image understanding via language generation.

# Key Features
# BLIP-2 for Image Captioning
Fine-tunes the pre-trained BLIP-2 model on the Flickr8k dataset.

Learns to generate accurate, descriptive image captions from raw visual input.

# LoRA Integration
Incorporates LoRA for efficient training by freezing most of the model and updating only low-rank adapters.

Significantly reduces memory and computational cost without sacrificing performance.

# Flickr8k Dataset
Consists of 8,000 images, each with 5 human-written captions.

Suitable for training and evaluating image captioning models due to its caption diversity and manageable size.

# Evaluation Metrics
The performance of the fine-tuned model is evaluated using standard captioning metrics:

BLEU: Measures n-gram precision.

METEOR: Balances precision, recall, and synonym matching.

CIDEr: Consensus-based image description evaluation.

ROUGE: Measures overlap with reference captions.

# Tech Stack
Component	Tool/Model
Vision-Language Model	Salesforce/blip2-flan-t5-xl (HuggingFace)
LoRA Adapter	peft (HuggingFace PEFT library)
Dataset	Flickr8k (8,000 images, 5 captions/image)
Evaluation	BLEU, METEOR, CIDEr, ROUGE
Frameworks	PyTorch, HuggingFace Transformers, Datasets


# Developed by
Absar Raashid
