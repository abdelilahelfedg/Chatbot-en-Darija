
# Darija QA Chatbot

Ce projet vise à finetuner le modèle **Qwen3-4B** pour la génération de texte en **Darija (arabe marocain)** dans une tâche de **Question–Réponse (QA)**.  
Le fine-tuning est optimisé avec **Unsloth**, utilisant **LoRA (rank = 4)** et un entraînement supervisé via **SFTTrainer**.  
Le modèle est évalué avec plusieurs métriques de NLP (BERTScore, BLEU, ROUGE), et déployé sous forme de **chatbot interactif**.

## Fonctionnalités principales

- **Prétraitement complet** du corpus QA Darija :
  - Tokenisation  
  - Nettoyage du texte (caractères spéciaux, tags, doublons)
- **Fine-tuning LoRA** sur Qwen3-4B avec :
  - LoRA rank = 4  
  - Optimisation mémoire grâce à **Unsloth**
  - Entraînement supervisé avec **SFTTrainer**
- **Évaluation du modèle** :
  - **BERTScore**
  - **BLEU**
  - **ROUGE**
- **Chatbot Darija** :
  - Génération cohérente basée sur un corpus QA réel
  - Interface web simple et réactive
- Dataset utilisé :  
  👉 https://huggingface.co/datasets/AbdelilahFdg/QA


