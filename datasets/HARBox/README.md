
# HARBox Dataset: Daily Activity Recognition using Smartphones

In this dataset, we developed and released an Android App named ["HARBox"](https://github.com/Xavierpku/HARBox-code) to collect HAR data using users’ own smartphones in a crowdsourcing manner. The App collects 9-axis IMU data of users’ smartphones when the user conducts five activities of daily life (ADL), including walking, hopping, phone calls, waving and typing. The users will label the activities themselves by clicking the “start” and “end” buttons shown in the app before and after performing each activity. After removing the invalid and repeated data from total 137 submissions, we finally obtained valid data submissions from 121 users (17-55 years old) with 77 different smartphone models. We resample the original IMU data at 50Hz, with a sliding time window of 2s, and generate a 900-dimension feature for each data sample. This dataset is larger and more heterogeneous, which can be used to evaluate the scalability and robustness of different methods.

| <img src="https://github.com/xmouyang/FL-Datasets-for-HAR/blob/main/datasets/HARBox/HARBox-collect.png" class="img-responsive"> |
|:---:|
| Large-scale HARBox Dataset: Five activities of daily life (ADL) are recorded using an Android App. We received data record from 121 users with 77 different models of smartphones in total. |
