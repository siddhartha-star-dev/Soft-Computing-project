This repository is dedicated to use of Deep learning for sentiment analysis for different approaches<br/>
Link for Children Stories data
https://drive.google.com/drive/folders/13RuaaE4iNsFYRTLIt8ldSh-Wei0NN-uf?usp=drive_link

## Multimodel Sentiment Analysis of Hinglish memes
#Link for Multimodel Sentiment Analysis of Hinglish memes
https://www.kaggle.com/datasets/williamscott701/memotion-dataset-7k

### Multimodal Model Structure
Text Processing: Handled by DistilBERTMulti, capturing semantic nuances and contextual cues from the text.
Image Processing: Handled by VGG16, extracting visual features from images.
Feature Fusion: Combines features extracted from both text and images to learn joint representations that capture both visual and textual semantics.

### Results
Average score for both sentiment analysis and Emotion Sentiment Analysis
Model	                                Accuracy	Precision	Recall	F1-score
Multimodal (DistilBERTMulti + VGG16)	0.8203	  0.7972	  0.8203	0.7882

### Conclusion
This project demonstrates the effectiveness of multimodal learning techniques in classifying internet memes, particularly those with Hinglish content. By combining the strengths of textual and visual models, the proposed approach achieves competitive performance in sentiment analysis. 
