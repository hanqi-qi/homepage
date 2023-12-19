
[Google Scholar](https://scholar.google.com/citations?user=YmWi1lgAAAAJ&hl=en) / [Github](https://github.com/hanqi-qi) / [Twitter](https://twitter.com/yan_hanqi) / [LinkedIn](https://www.linkedin.com/in/hanqi-yan-9211a91b1/?originalSubdomain=uk)

Hanqi Yan 颜寒祺
Email: [hanqi.yan@kcl.ac.uk](hanqi.yan@kcl.ac.uk)

I am a Ph.D. student(2020fall) at the [University of Warwick](https://warwick.ac.uk/) & Kings' College London ([KCL](https://www.kcl.ac.uk/)) with professor [Yulan He](https://sites.google.com/view/yulanhe/home). I finished my M.S. at [Peking University](https://english.pku.edu.cn/) (2017-2020) in Academy for Advanced Interdisciplinary Studies and my B.E. at [Beihang University](https://ev.buaa.edu.cn/) (2013-2017) in Information Engineering Department. 

During Ph.D., I started my Causality Journey in visiting professor [Kun Zhang](https://www.andrew.cmu.edu/user/kunz1/) affiliated with **Causal Learning and Reasoning Group at CMU** (2022.10-2023.02). Before Ph.D., I started my NLP journey in visiting professor [Wenjie Li](https://www4.comp.polyu.edu.hk/~cswjli/) affiliated **Natural Language Processing Group @PolyU Hong Kong** (2019.07-2019.10).

> I study **interpretable** and **robust** NLP models across supervised, unsupervised and in-context learning settings:
 * In the LLM era, I focus on constrained planning (search) in the model decoding/fine-tuning phases , to achieve _safe_, _reliable_ and _fair_ outputs.
 * Align the models' behaviors with human knowledge in self-explanatory framework, which in turns improves the models' transparency and reliability.
 * Empirical and principled methods to alleviate spurious correlation and learn robust representations for various test inputs.

> I am expected to graduate in October 2024 and will be on academic job market in the UK and US.

## Education
* 2020 - 2023. Ph.D. at University of Warwick & Kings' College London(KCL). Interpretable and Robust NLP
* 2018 - 2020. M.S. at Peking University. Sentiment Analysis & Spatial Data Mining
* 2013 - 2017. B.E. at Beihang University. Information Engineering

## Selected Publications

### _Large Language Model_
* [Arxiv 2023]  Y. Zhou, J. Li, Y.Xiang, **H.Yan**, L. Gui, Y. He. [The Mystery and Fascination of LLMs: A Comprehensive Survey on the Interpretation and Analysis of Emergent Abilities.](https://arxiv.org/abs/2311.00237)
![survey](/images/survey_macro.png){: width="350" height="150" style="display:block; margin-left:auto; margin-right:auto"}
  * In-Context Learning can learn Different Algorithms without gradient descent, e.g, Regression, Bayesian. 

* [Under Review] **H. Yan**, Q. Zhu, X. Wang, L. Gui, Y. He. <ins>_Steer the LLMs in the self-refinement loop via unsupervised Reward_.</ins>


### _Efficient Robust Learning for Transformer-based models_

* [UAI2021, Spotlight] **H. Yan**, L. Gui, Y. He. [Addressing Token Uniformity in Transformers via Singular Value Transformation](https://proceedings.mlr.press/v180/yan22b.html)
![softdecay](/images/softdecay.png){: width="350" height="150" style="display:block; margin-left:auto; margin-right:auto"}
  * Token uniformity (Cosine Similarity between every two token representations) values increase as BERT layer increases, implying  more vanished dimensions in the embedding space. _SoftDecay_ is proposed to a range of transformer-based language models and improved performance is observed in semantic textual similarity evaluation and a range of GLUE tasks. 

* [EACL23 findings] **H. Yan**, H. Li, Y. Li, L. Qian, Y. He and L. Gui. [Distinguishability Calibration to In-Context Learning](https://arxiv.org/abs/2302.06198)
![incontext_adaptor](/images/incontext_adaptor.png){: width="350" height="140" style="display:block; margin-left:auto; margin-right:auto"}
* Token uniformity issue is still observed in in-context learning, we proposed an adaptor for more discriminative representation learning and improved performance is observed in fine-grained text classification tasks.

### _Self-Explainable Framework for Supervised Model_

* [Under Review] **H. Yan**, L. Gui, M. Wang, K. Zhang and Y. He. [Explainable Recommender with Geometric Information Bottleneck](https://arxiv.org/abs/2305.05331)
![In-Context Learning can Learn Different Algorithm](/images/giant.png){: width="400" height="120" style="display:block; margin-left:auto; margin-right:auto"}
  * To avoid the expensive human annotation process and to generate explanations beyond individual reviews, we propose to incorporate a geometric prior learnt from user-item interactions into the latent factors from user-item reviews.

* [Computational Linguistics, Present at EMNLP23] **H. Yan**, L. Gui, Yulan He. [Hierarchical Interpretation of Neural Text Classification](https://direct.mit.edu/coli/article/doi/10.1162/coli_a_00459/112768/Hierarchical-Interpretation-of-Neural-Text).
![Giant](/images/hint.png){: width="350" height="210" style="display:block; margin-left:auto; margin-right:auto"}
  * An unsupervised self-explanatory framework for long document classification. It can extract word-, sentence-, and topic-level rationales explaining the document-level decision.
  
* [ACL21, Oral] **H. Yan**, L. Gui, G. Pergola and Y. He. [A Knowledge-Aware Graph Model for Emotion Cause Extraction](https://aclanthology.org/2021.acl-long.261.pdf).
![kag](/images/kag_new.png){: width="300" height="150" style="display:block; margin-left:auto; margin-right:auto"}
* Position bias is observed in a cause identification dataset and we proposed to leverage ConceptNet to extract invariant feature, i.e., causal commonsense knowledge, to tackle the distribution shift. 

### Unsupervised disentanglement learning under distribution shift

* [Neurips23, Poster] **H. Yan**, L. Kong*, L. Gui, Y. Chi, Eric. Xing, Y. He, K. Zhang. [Counterfactual Generation with Identifiability Guarantee](https://neurips.cc/virtual/2023/poster/71063).
![matte](/images/matte_new.png){: width="200" height="120" style="display:block; margin-left:auto; margin-right:auto"}
* We provide identification guarantees for latent-variable models by leveraging the relative sparsity of the influences from different latent variables. This principled representations can shed light on the constrained, i.e., safe and moral generation for large language models with noisy pertaining data.

## Professional Service

* Event Organizer:  Co-Chair of AACL-IJCNLP (Student Research Workshop) 2022 
* Reviewers for NLP Community: ACL23', EMNLP22',23', NAACL24', EACL23', AACL24', ACL Rolling Review, UAI23', AISTATS24', Neurocomputing, Transactions on Information Systems (TOIS)

## Blog Posts
* [_Reading List For Large Language Model_](https://github.com/hanqi-qi/Large_language_modeling/blob/main/Reading_Material.md)
* _Induction Head_ contribute to In-context Learning [[Blog](https://zhuanlan.zhihu.com/p/652269984)]
* _Causal101_ [[slides](https://github.com/hanqi-qi/NLPReadingGroup/blob/main/CausalInference/CausalInference_Intro_hanqi.pdf)]
* _Debised Recommendation with Causality_ [Slides](https://github.com/hanqi-qi/NLPReadingGroup/blob/main/CausalInference/CausalInference_RS_hanqi.pdf)
* _TakeAways from EMNLP23 Causality Tutorial_ [slides](https://drive.google.com/file/d/1u57NrYyKyEkMRGdYf5Mgdp0lBmK2UxZi/view)
* _Identifiability101 in Causality_ [Blog](https://zhuanlan.zhihu.com/p/665841340)
