1. The files with bert_* or gpt2_* prefixes contain, for each hidden unit (static layer + each hidden layer's residual stream embeddings), its mean and SD of activation across a large collection of sentences from COCA. It was used in:
   Denning, J. M., Guo, X., Snefjella, B., & Blank, I. A. (2026). Do Language Models Know Who Did What to Whom?. Open Mind, 10, 923-950.
2. The file WangLikeGrammaticalityStimuli was created based (loosely) on the methods in the following paper:
   Wang, Y. S., Qiu, L., Wu, Z., Levy, R., & Kim, Y. (2026, July). Implicit Representations of Grammaticality in Language Models. In Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) (pp. 15035-15055).
3. The file generated_pairs_with_results.csv is the DAIS dataset from the following paper:
   Hawkins, R. D., Yamakoshi, T., Griffiths, T. L., & Goldberg, A. (2020, November). Investigating representations of verb bias in neural language models. In Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP) (pp. 4653-4663).
   The original repo is here: https://github.com/taka-yamakoshi/neural_constructions/tree/master/DAIS/data
