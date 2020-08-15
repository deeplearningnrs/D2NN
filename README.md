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

[5] GRU4Rec+: https://github.com/wubinzzu/NeuRec

[6] SASRec: https://github.com/kang205/SASRec

[7] SRGNN : https://github.com/userbehavioranalysis/SR-GNN_PyTorch-Geometric

[8] BERT4Rec: https://github.com/FeiSun/BERT4Rec

We ran all the model variants and baselines on our dataset.

thanks

