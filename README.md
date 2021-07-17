## We have updated the github reporitory and all code for model, dataset and baselines can be accessed at D2NN_latest. Due to space limitation in Github, we are unable to upload whole bunch of files in Github, so we are giving the google drive link here link
https://drive.google.com/file/d/1QOXynsrDfsNthZcVi2GHanuUfSBDzk4j/view?usp=sharing

************************************************************************************************************************************************

# D2NN
We collected the news data using New York Times [API](https://developer.nytimes.com/) by retrieving the URL of the articles. We used a Python tool [1] that serves as API Wrapper for New York Times to retrieve the comments and other interactions on the news articles. Those interactions were retrieved with respect to the timeline of retrieved news data. 

[1] [New York Times Article API Docs](http://developer.nytimes.com/docs/read/article_search_api_v2), 
    [Requesting an API Key for the Times API](http://developer.nytimes.com/docs/reference/keys)


## Acknowledgements
The data was collected with the help of New York Times API to retrieve URL of the articles.
The URL used to retrieve comments from a given article in the code in the [package](https://github.com/AashitaK/nyt-comments).

## Baseline:
Our baselines are given as:

[1] [DKN](https://github.com/hwwang55/DKN)

[2] [LSTUR](https://github.com/nvagus/mnexp)

[3] [DMF](https://github.com/RuidongZ/Deep_Matrix_Factorization_Models)

[4] [CDAE](https://github.com/henry0312/CDAE)

[5] [GRU4Rec+](https://github.com/hidasib/GRU4Rec). extended the functionality of paper

[6] [SASRec](https://github.com/kang205/SASRec)

[7] [SRGNN](https://github.com/userbehavioranalysis/SR-GNN_PyTorch-Geometric)

[8] [BERT4Rec](https://github.com/FeiSun/BERT4Rec)


[1]	H. Wang, F. Zhang, X. Xie, and M. Guo, “DKN: Deep knowledge-aware network for news recommendation,” in Proceedings of the 2018 World Wide Web Conference, 2018, pp. 1835–1844.


We have updated the github repository for D2NN and the code for model, baselines and dataset can be found in the folder 

[2]	M. An, F. Wu, C. Wu, K. Zhang, Z. Liu, and X. Xie, “Neural News Recommendation with Long- and Short-term User Representations,” in Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics, Florence, Italy, 2019, pp. 336–345, doi: 10.18653/v1/P19-1033.

[3]	H.-J. Xue, X. Dai, J. Zhang, S. Huang, and J. Chen, “Deep Matrix Factorization Models for Recommender Systems,” in Proceedings of the Twenty-Sixth International Joint Conference on Artificial Intelligence, Melbourne, Australia, Aug. 2017, pp. 3203–3209, doi: 10.24963/ijcai.2017/447.

[4]	Wu Y, DuBois C, Zheng AX, Ester M. Collaborative denoising auto-encoders for top-n recommender systems. InProceedings of the Ninth ACM International Conference on Web Search and Data Mining 2016 Feb 8 (pp. 153-162).

[5]	B. Hidasi and A. Karatzoglou, “Recurrent Neural Networks with Top-k Gains for Session-based Recommendations,” in Proceedings of the 27th ACM International Conference on Information and Knowledge Management, Torino Italy, Oct. 2018, pp. 843–852, doi: 10.1145/3269206.3271761.

[6]	W.-C. Kang and J. McAuley, “Self-Attentive Sequential Recommendation,” in 2018 IEEE International Conference on Data Mining (ICDM), Singapore, Nov. 2018, pp. 197–206, doi: 10.1109/ICDM.2018.00035.

[7]	S. Wu, Y. Tang, Y. Zhu, L. Wang, X. Xie, and T. Tan, “Session-Based Recommendation with Graph Neural Networks,” AAAI, vol. 33, pp. 346–353, Jul. 2019, doi: 10.1609/aaai.v33i01.3301346.

[8]	F. Sun et al., “BERT4Rec: Sequential Recommendation with Bidirectional Encoder Representations from Transformer,” arXiv:1904.06690 [cs], Aug. 2019, In Proceedings of the 28th ACM International Conference on Information and Knowledge Management (pp. 1441-1450).


We ran all the model variants and baselines on the NYTimes dataset (sample files with this repository) and the [MIND] (https://msnews.github.io/) dataset.

Thanks




