# P-BERT
# Introduction

This repository contains the implementation dataset for paper:
P-BERT: Towards Long Sequence Modeling by Enabling Language Representation with Prefix Sequence Compression, Soft Position Embedding, and Data Augmentation for Patent Relevance Assessment

# Abstract
Recent works have increasingly adopted pre-trained language models, such as BERT, to model technical semantics for patent relevance assessment. However, existing truncation and divide-merge strategies, used to handle input length constraints, results in feature loss and semantic isolation. This limits the effectiveness of pre-trained language models in capturing long sequence semantics for patent relevance assessment. Because patent relevance is evaluated based on local sequence semantics, this paper proposes a patent-oriented bidirectional encoder representation from transformers (P-BERT) to enable the semantic modeling ability of long sequences. The characteristics of P-BERT lie in a prefix sequence compression method, a soft position embedding method and a data augmentation method. The first one can retrain more technical features within the input constraints via transforming full sequences into partial sequences while the second one reconstructs local sequence semantics for partial sequences. As for the last one, it contains sample and feature augmentation to improve the generalization and robustness. Due to the scarcity of training corpus for patent relevance assessment, a dual constraint strategy is proposed to generate a supervised corpus, DualCons. Experimental results demonstrate that DualCons can help BERT obtain the best ranking performance compared with other strategies. 
Model evaluations show the effectiveness of P-BERT. It reaches an improvement of 2\%-6\% in recall-oriented metrics and an improvement of 1\%-5\% in accuracy-oriented indicators over the state-of-the-art baselines. All those would promote the engineering applications of pre-trained language models in patent relevance assessment.

# Paper and Dataset
Download Paper: http://doi.org/10.1109/ACCESS.2025.3545430

You can get patent evaluated corpus, DualCons, at https://pan.baidu.com/s/16EOvYvEOJ1W_6gR62azLTw?pwd=kieh

