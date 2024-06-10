Sentiment Analysis of COVID-19 Vaccine in Indonesia Using Pretrained Language Model XLMR and Augmentation Data Methods

COVID-19 vaccination is one of the long-term solutions to address the COVID-19 pandemic
in Indonesia. The topic of COVID-19 vaccination has become a hot discussion, especially on
social media. Various pros and cons regarding the vaccination program continue to emerge,
making research on public analysis of the COVID-19 vaccination program very useful for
public communication. This study focuses on five types of vaccines widely used in Indonesia,
namely AstraZeneca, Moderna, Pfizer, Sinopharm, and Sinovac.

A total of 252,805 data were collected through social media Twitter using the Twitter
API in 2021. Then, 11,361 were randomly selected to be manually annotated. Subsequently,
the classification process was performed using the XLMR language model and several baseline
methods based on pre-trained language models, deep learning, machine learning, and lexicon.
Data augmentation such as Easy Data Augmentation (EDA), An Easier Data Augmentation
(AEDA), and Seqgan was also carried out to balance the number of minority class data. The
division of training data and test data was done using two methods, namely simple random
sampling and stratified sampling, to determine the performance of the trained model.

The results of the study show that the proposed method, XLMR, has high performance
compared to other baseline methods, with an accuracy of 71.91% before augmentation and
72.19% after augmentation using Seqgan with the simple random sampling data splitting
method. Then, using the stratified data splitting method, XLMR also had the best performance
with an accuracy of 59.96% before augmentation and 74.37% after augmentation using EDA.
This research will be very useful for public communication with similar cases. In the future,
this research can be continued by conducting domain transfer to improve model performance.

https://ijphs.iaescore.com/index.php/IJPHS/article/view/23134
