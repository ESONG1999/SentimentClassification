# SentimentClassification APP on AWS with S3 and EC2
The [pretrained model](https://huggingface.co/huawei-noah/TinyBERT_General_4L_312D) is fintuned with [IMDB](https://raw.githubusercontent.com/laxmimerit/All-CSV-ML-Data-Files-Download/master/IMDB-Dataset.csv) dataset for sentiment classification. The model weight is then uploaded to AWS S3. And the model is then deployed on AWS EC2. 

To run the app, use:
```
streamlit run app.py
```
