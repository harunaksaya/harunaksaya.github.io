---
title:          "Aspect-Based Sentiment Analysis of Turkish School Reviews: A Comparative Study of Recurrent and Transformer Architectures"
date:           2026-10-26 00:01:00 +0300
selected:       true
pub:            "Electronics"
pub_last:       ' <span class="badge badge-pill badge-publication badge-primary">Article</span> <span class="badge badge-pill badge-publication badge-success">MDPI</span>'
pub_date:       "2026, 15(21), 4949"
semantic_scholar_id:
abstract: >-
  Aspect-based sentiment analysis (ABSA) of user-generated Turkish text remains underexplored, and no aspect-level resource exists for the education domain. We introduce a manually annotated dataset of 1533 school reviews from okul.com.tr, yielding 2620 (sentence, aspect) pairs over 19 aspect categories, imbalanced 2.3:1 toward positive polarity; a stratified 200-instance subset gave Cohen's Kappa = 0.702. Given the aspect category, nine systems were compared under a 5-fold cross-validation protocol partitioned at the review level to prevent review-level leakage: four non-pre-trained baselines, two recurrent models (BiLSTM, BiGRU), and three fine-tuned transformers—the Turkish-specific BERTurk together with the multilingual mBERT and XLM-R, the three trained under identical hyperparameters, with class-imbalance handling applied where relevant. TF-IDF with a linear SVM reached a Macro-F1 of 0.836, exceeding both recurrent models, while all transformers exceeded every non-pre-trained system. In this dataset and experimental setting, BERTurk obtained the highest Macro-F1 (0.927) and accuracy (0.938), 0.091 above the strongest classical baseline. The advantage over mBERT concentrated on the minority class: F1-Negative exceeded mBERT's by 0.034 points, roughly twice the accuracy gap. Its margin over XLM-R was small and not statistically established. The benefit of language-specific pre-training therefore appears to narrow as the multilingual model's pre-training corpus grows.
cover:          /assets/images/covers/pubs/article.svg
authors:
  - Harun Aksaya#
  - Sevinç Gülseçen
links:
  DOI: https://doi.org/10.3390/electronics15214949
  MDPI: https://www.mdpi.com/2079-9292/15/21/4949
---
