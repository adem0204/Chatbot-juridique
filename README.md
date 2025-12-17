🤖 Chatbot Juridique – Droit du Travail (RAG)

📌 Introduction

Chatbot spécialisé en droit du travail, basé sur une approche Retrieval-Augmented Generation (RAG). Il utilise uniquement le Code du travail français pour fournir des réponses fiables et limiter les hallucinations des modèles de langage.

🎯 Objectifs

Pédagogiques : comprendre le NLP appliqué au droit, manipuler des documents juridiques, réduire les hallucinations.

Techniques : extraction PDF 📄, segmentation en chunks, embeddings avec Sentence-BERT, recherche via FAISS, génération de réponses via LLM, interface interactive 💬.

📚 Corpus

Source : Code du travail français (PDF officiel Légifrance).

But : garantir la fiabilité et limiter les questions hors périmètre.

🏗 Architecture

Extraction et prétraitement

Embeddings + indexation FAISS

Recherche sémantique

Génération de réponses via LLM

Interface utilisateur Gradio

⚙️ Fonctionnement

Texte découpé en chunks avec chevauchement

Conversion en vecteurs pour recherche rapide

Récupération des passages pertinents pour générer la réponse

Réponse hors périmètre : « Je ne sais pas » ❌

✅ Résultats

Questions droit du travail : réponses correctes et fiables ✔️

Questions hors périmètre : réponse explicite ❌

Exemple :

Q : Quels sont les droits du salarié en cas de licenciement ?

R : Basée sur les articles du Code du travail.

⚠️ Limites

Dépend uniquement du Code du travail

Métadonnées limitées → citations imprécises

Qualité dépend de l’extraction PDF

🚀 Pistes d’amélioration

Ajouter d’autres sources (jurisprudence, guides CNIL) 📖

Enrichir les chunks avec métadonnées

Re-ranking des passages

Interface affichant les sources 📌

🏁 Conclusion

Ce projet montre qu’un chatbot juridique RAG est fiable pour des questions sensibles. Base solide pour des assistants juridiques avancés.

