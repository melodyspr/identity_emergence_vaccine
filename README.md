Identity Emergence in the Context of Vaccine Criticism in France

This repository contains the code and notebooks for the study “Identity Emergence in the Context of Vaccine Criticism in France”, which forms part of my doctoral research on how collective identities emerge, evolve, and transform in digital environments.
The project examines French Twitter activity around President Emmanuel Macron’s July 2021 COVID-19 vaccination speech, focusing on how language contribute to the formation of collective identity.

📖 Overview
The analysis investigates how users’ linguistic behavior changed before and after Macron’s announcement, tracing:
Shifts in pronoun use (from je to nous) as markers of collective identity.
Differences in outgroup labeling across established and newly engaged users.
Semantic similarity between groups over time.

The study combines Natural Language Processing (NLP) with social science theory to analyze tweets.

📁 Repository Structure

1_clean_dataset.ipynb	Cleans and preprocesses the raw Twitter dataset.
2_manual_labelling_antivax_provax.ipynb	Manual labeling of tweets for stance classification (critical of vaccination and related policies in France/non-critical).
3_train_camembert_classifier_frenchantivax.ipynb	Fine-tunes CamemBERT for stance classification on French-language tweets.
4_label_whole_dataset.ipynb	Applies the trained model to label the full dataset.
5_eda.ipynb	Exploratory Data Analysis: temporal trends, user engagement.
6_pronouns_use.ipynb	Examines personal pronoun use (1SG and 1PL) across user groups and time.
7_outgroup_labels.ipynb	Identifies and quantifies outgroup labeling in tweets.
8_create_tweet_embeddings.ipynb	Generates tweet embeddings using sentence transformers for semantic similarity analysis.
9_similarity_between_groups_changing_cutoff.ipynb	Compares cosine similarity between groups varying thresholds.
10_fighting_words.ipynb	Uses the Fighting Words method to identify distinctive terms across user groups.
11_bot_detection.ipynb	Detects and filters potential bots and investigates their impact.

Research Question:
How did Macron’s July 2021 announcement catalyze the emergence of a collective identity among Twitter users criticizing the vaccine and related policies in France?

⚙️ Requirements
Python 3.8+
Recommended libraries:
pandas
numpy
torch
transformers
scikit-learn
matplotlib
umap-learn
gensim
convokit

GPU recommended for model fine-tuning.

📄 Citation
If you use this repository, please cite:
Sepahpour-Fard, M. (2025). Performing, Transforming, and Amplifying Identity Online: Computational Insights into the Dynamic Interplay between Language, Audience, and Events. [Doctoral Thesis].
and
Sepahpour-Fard, M., Quayle, M., MacCarron, P., Mannion, S., & Nguyen, D. (2024). Identity Emergence in the Context of Vaccine Criticism in France. arXiv preprint arXiv:2410.12676.

📬 Contact
Melody Sepahpour-Fard
University of Limerick
📧 [melody.sepahpourfard@ul.ie]
🔗 [0000-0002-8472-9514]
