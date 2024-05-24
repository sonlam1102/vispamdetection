# Detecting Spam Reviews on Vietnamese E-commerce website  
This dataset is used for spam review detection (opinion spam reviews) on Vietnamese E-commerce website. 
The dataset is used for research purposes.  
Baseline codes including:  
+ Deep neural model: TextCNN, BiLSTM, and GRU.    
+ Transformer models: PhoBERT and BERT4News.    

The baseline codes are shared by Jupyter notebook format. Please feel free to reuse or modify this code to adapt to your projects.     

# Meta-data Integration Source code 
Only Reviews:    
+ DNN: baseline/pt-vispam-dnn.  
+ Transformers: baseline/pt-vispam-transformers     
	
Metadata Integration (Category - Description):   
+ DNN:
		meta-data/DNN/pt-vispam-dnn-category.   
		meta-data/DNN/pt-vispam-dnn-description.   
		meta-data/DNN/pt-vispam-dnn-category-description.   
		
+ Transformers:
		meta-data/BERT/pt-vispam-phobert-category     
		meta-data/BERT/pt-vispam-bert4news-category.  
		meta-data/BERT/cinhvn/pt-vispam-vibert-category.  
		meta-data/BERT/pt-vispam-transformers-description.  
		meta-data/BERT/cinhvn/pt-vispam-transformers-category-description   
 
Others:
+ Sentence-BERT:    
		meta-data/sentence-embedding/pt-vispam-phobert-sentence-embedding-description    
		meta-data/sentence-embedding/pt-vispam-bert4news-sentence-embedding-description    
		
Inference: https://www.kaggle.com/cinhvn/pt-vispamreviews-inference.   

# Contact information  
Please contact Mr. Son Luu (Son T. Luu) if you want to use or discuss this dataset (both version 1 and version 2).   
Email: sonlt@uit.edu.vn.  
Alternative: son.lt1103@gmail.com     

# Publication  
Link to publication for the original work (version 1): https://arxiv.org/abs/2207.14636    
Meta-data Integration (version 2): https://arxiv.org/abs/2405.13292  
# Citation 
```
@InProceedings{10.1007/978-3-031-21743-2_48,
author="Van Dinh, Co
and Luu, Son T.
and Nguyen, Anh Gia-Tuan",
editor="Nguyen, Ngoc Thanh
and Tran, Tien Khoa
and Tukayev, Ualsher
and Hong, Tzung-Pei
and Trawi{\'{n}}ski, Bogdan
and Szczerbicki, Edward",
title="Detecting Spam Reviews on Vietnamese E-Commerce Websites",
booktitle="Intelligent Information and Database Systems",
year="2022",
publisher="Springer International Publishing",
address="Cham",
pages="595--607",
abstract="The reviews of customers play an essential role in online shopping. People often refer to reviews or comments of previous customers to decide whether to buy a new product. Catching up with this behavior, some people create untruths and illegitimate reviews to hoax customers about the fake quality of products. These are called spam reviews, confusing consumers on online shopping platforms and negatively affecting online shopping behaviors. We propose the dataset called ViSpamReviews, which has a strict annotation procedure for detecting spam reviews on e-commerce platforms. Our dataset consists of two tasks: the binary classification task for detecting whether a review is spam or not and the multi-class classification task for identifying the type of spam. The PhoBERT obtained the highest results on both tasks, 86.89{\%}, and 72.17{\%}, respectively, by macro average F1 score.",
isbn="978-3-031-21743-2"
}
```
