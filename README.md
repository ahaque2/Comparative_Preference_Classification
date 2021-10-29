## Pixie: Preference in Implicit and Explicit Comparisons

We present _Pixie_, a manually annotated dataset for _Comparative Preference Classification_ (CPC) from app reviews. While previous works have focused on direct explicit comparisons _(A is better than B)_, Pixie includes implicit _(B is slow)_ or indirect comparisons _(A is here immediately while B takes forever)_. Pixie contains comparative sentences that reveal user preferences without the use of linguistic comparative structures. 

src contains code for our experiments. We experiment with traditional machine learning approaches with BERT sentence embeddings and transformer-based methods on Pixie to identify preferred entities in comparative sentences from app reviews. We also compare our results with the existing state-of-the-art model in CPC trained on Pixie. 

We find that transformer-based pretrained models fine-tuned on \framework can achieve a weighted average F1 score of 85.23\% and notably outperform the previous state-of-the-art method (73.99\%).
