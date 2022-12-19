# Text-Summarization-Abstract-Vs-Extractive-

https://colab.research.google.com/drive/1CVzKxOEV1_GM_MlTi2RC8fMPbw66FV86?usp=sharing 


# Objective:

The objective of this ICP is to comapare the performance of Abstracive and extractive GPT-2 summarizer.

# Approaches

At first, necessary libraries are imported. Sample data are extracted from several sources like literature review, research summary and extractive summarizer like "csebuetnlp/mT5_multilingual_XLSum"
, "sshleifer/distilbart-cnn-12-6", "gpt2-medium" and abstractive summarizer like BART, t-5 base, 't5-small'are implemented on the excerpt and similarity between the summarizer is 
evaluated

# Datasets

For this ICP, several excerpt from several sources are used.

# Results:

Results are generated with several libraries and similarity between summarizer are evaluated.

                                                Extractive Summary:   Similarity   Model
                                                                        0.65%       BERT VS GPT-2
                                                                        
                                                                        0.67%      BERT VS T5 small
                                                                        
                                                Abstractive Summary:     0.68%      GPT-2  VS T5 base   

# Challenges

For this icp, I tried to implement my data. but it is showing a lot of errors.
