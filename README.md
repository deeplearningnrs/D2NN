# D3NN
We collected the news data using New York Times API[1] by retrieving the URL of the articles. We used a Python tool [2] that serves as API Wrapper for New York Times to
retrieve the comments and other interactions on the news articles. Those interactions were retrieved with respect to the timeline of retrieved news data. 

[1] https://developer.nytimes.com/
[2] Python tools for getting data from the New York Times Article API. Retrieves JSON from the API, stores it, parses it into a TSV file.
New York Times Article API Docs: http://developer.nytimes.com/docs/read/article_search_api_v2
Requesting an API Key for the Times API: http://developer.nytimes.com/docs/reference/keys

Our news data is uploaded to this repository.
The interactions on the news are too large files and can not be uploaded on Git repository due to size limit, so a sample of interaction files matching with the timeline of news data can be accessed via this link https://drive.google.com/drive/folders/1f9oy_VjX6gMP1eepQ3VHumkmwmPYBWZ1?usp=sharing


# Baseline:
Our baselines are given as:
[1] DKN: https://github.com/hwwang55/DKN

[2] LSTUR: https://github.com/nvagus/mnexp

[3] DMF: https://github.com/RuidongZ/Deep_Matrix_Factorization_Models

[4] HURA: we implemented ourselves

[5] GRU4Rec+: extended the functionality of https://github.com/hidasib/GRU4Rec as per paper

[6] SASRec: https://github.com/kang205/SASRec

[7] SRGNN : https://github.com/userbehavioranalysis/SR-GNN_PyTorch-Geometric

[8] BERT4Rec: https://github.com/FeiSun/BERT4Rec


[1]	H. Wang, F. Zhang, X. Xie, and M. Guo, “DKN: Deep knowledge-aware network for news recommendation,” in Proceedings of the 2018 World Wide Web Conference, 2018, pp. 1835–1844.

[2]	M. An, F. Wu, C. Wu, K. Zhang, Z. Liu, and X. Xie, “Neural News Recommendation with Long- and Short-term User Representations,” in Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics, Florence, Italy, 2019, pp. 336–345, doi: 10.18653/v1/P19-1033.

[3]	H.-J. Xue, X. Dai, J. Zhang, S. Huang, and J. Chen, “Deep Matrix Factorization Models for Recommender Systems,” in Proceedings of the Twenty-Sixth International Joint Conference on Artificial Intelligence, Melbourne, Australia, Aug. 2017, pp. 3203–3209, doi: 10.24963/ijcai.2017/447.

[4]	C. Wu, F. Wu, J. Liu, S. He, Y. Huang, and X. Xie, “Neural Demographic Prediction using Search Query,” in Proceedings of the Twelfth ACM International Conference on Web Search and Data Mining, Melbourne VIC Australia, Jan. 2019, pp. 654–662, doi: 10.1145/3289600.3291034.

[5]	B. Hidasi and A. Karatzoglou, “Recurrent Neural Networks with Top-k Gains for Session-based Recommendations,” in Proceedings of the 27th ACM International Conference on Information and Knowledge Management, Torino Italy, Oct. 2018, pp. 843–852, doi: 10.1145/3269206.3271761.

[6]	W.-C. Kang and J. McAuley, “Self-Attentive Sequential Recommendation,” in 2018 IEEE International Conference on Data Mining (ICDM), Singapore, Nov. 2018, pp. 197–206, doi: 10.1109/ICDM.2018.00035.

[7]	S. Wu, Y. Tang, Y. Zhu, L. Wang, X. Xie, and T. Tan, “Session-Based Recommendation with Graph Neural Networks,” AAAI, vol. 33, pp. 346–353, Jul. 2019, doi: 10.1609/aaai.v33i01.3301346.

[8]	F. Sun et al., “BERT4Rec: Sequential Recommendation with Bidirectional Encoder Representations from Transformer,” arXiv:1904.06690 [cs], Aug. 2019, Accessed: Dec. 03, 2019. [Online]. Available: http://arxiv.org/abs/1904.06690.


We ran all the model variants and baselines on our dataset.

thanks

