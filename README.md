# MLCS Lab Experiments

## EXP 1 – Time Series Decomposition

- Generated 120 days of synthetic network traffic data.
- Performed time series decomposition into **Trend, Seasonal, and Residual** components.
- Used Python, Pandas, NumPy, Matplotlib, and Statsmodels. :contentReference[oaicite:0]{index=0}

## EXP 2 – Network Traffic Forecasting using ARIMA

- Generated hourly network traffic data with DDoS-like spikes.
- Applied **ARIMA(2,1,2)** to forecast the next 10 hours.
- Classified traffic as **Normal Traffic** or **Possible DDoS Attack** using a threshold of 500. :contentReference[oaicite:1]{index=1} :contentReference[oaicite:2]{index=2} :contentReference[oaicite:3]{index=3}

## Technologies

Python | Pandas | NumPy | Matplotlib | Statsmodels

## EXP 3 – Cyber-Attack Classification using Random Forest

Generated a cybersecurity dataset with network traffic features such as Packet Count, Packet Size, and Connection Duration.
Implemented Random Forest ensemble learning to classify traffic as Normal or Cyber Attack.
Evaluated the model using Accuracy, Classification Report, and Confusion Matrix.

## Technologies

Python | Pandas | NumPy | Matplotlib | Scikit-learn

## EXP 4 – URL Classification using Logistic Regression
Extracted URL-based features such as URL Length, Number of Dots, Hyphens, Digits, Special Characters, HTTPS Presence, and Slashes.
Applied Logistic Regression to classify URLs as Legitimate or Malicious.
Evaluated the classification performance using prediction and accuracy.

## Technologies

Python | Pandas | NumPy | Scikit-learn

## EXP 5 – URL Classification using SVM
Extracted numerical features from URLs, including URL Length, Number of Dots, Hyphens, Digits, Special Characters, HTTPS Presence, and Slashes.
Implemented Support Vector Machine (SVM) with a linear kernel to classify URLs as Legitimate or Malicious.
Evaluated the model using predicted labels and accuracy.

## Technologies

Python | Pandas | NumPy | Scikit-learn

## EXP 6 – URL Anomaly Detection using Isolation Forest
Performed feature engineering on URLs using features such as URL Length, Dots, Hyphens, Digits, Special Characters, Slashes, HTTPS Presence, and @ Symbols.
Applied the Isolation Forest algorithm to identify Normal and Anomalous URL patterns.
Detected unusual URLs based on their feature patterns without requiring predefined malicious labels.

## Technologies

Python | Pandas | NumPy | Scikit-learn

## EXP 7 – Network Event Classification using Decision Tree

- Generated a wireless sensor network dataset containing timestamps, source IP addresses, and event types.
- Applied a Decision Tree Classifier to classify network events as Normal or Malicious.
- Tested new network events and predicted their security status using the trained model.

## Technologies

Python | Pandas | Scikit-learn | IP Address Processing

## EXP 8 – Database Intrusion Detection using Decision Tree

- Generated a database security dataset with features such as Record Length, Special Characters, SQL Keywords, and Failed Attempts.
- Implemented a Decision Tree Classifier to identify Normal and Malicious database records.
- Evaluated the model using Accuracy, Classification Report, and predictions on new database records.

## Technologies

Python | Pandas | Scikit-learn

## EXP 9 – Network Anomaly Detection using K-Means Clustering

- Generated normal and abnormal network traffic data using features such as Duration, Packets, Bytes, and Failed Connections.
- Applied K-Means Clustering to group network traffic into Normal and Abnormal categories.
- Evaluated model accuracy and visualized network traffic clusters using a scatter plot.

## Technologies

Python | NumPy | Pandas | Matplotlib | Scikit-learn

## EXP 10 – Email Spam Detection using Naive Bayes

- Created an email dataset containing Spam and Not Spam messages.
- Used CountVectorizer to convert email text into numerical features.
- Implemented Multinomial Naive Bayes to classify emails and evaluated the model using Accuracy and Classification Report.

## Technologies

Python | Pandas | Scikit-learn

## EXP 11 – Email Spoofing Detection using Random Forest

- Generated an email dataset with sender details, SPF, DKIM, and DMARC authentication features.
- Applied feature engineering to identify suspicious domains, sender mismatches, and email authentication failures.
- Implemented Random Forest Classifier to detect Legitimate and Spoofed emails and analyzed feature importance.

## Technologies

Python | Pandas | NumPy | Scikit-learn

## EXP 12 – CAPTCHA Recognition using CNN

- Generated a CAPTCHA character dataset containing uppercase letters and digits with variations in rotation, position, and noise.
- Built a Convolutional Neural Network (CNN) using convolution, pooling, and dense layers to recognize CAPTCHA characters.
- Evaluated model performance using Test Accuracy and predicted character recognition.

## Technologies

Python | NumPy | Pillow | TensorFlow | Keras | Scikit-learn
