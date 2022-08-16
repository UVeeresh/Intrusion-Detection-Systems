# Intrusion-Detection-Systems
A Network Traffic Analyzer that classifies traffic into any of the application layer attacks like DoS,DDoS,BruteForce,SQL injections,FTP BruteForce.
--The SVM Model for the Intrusion Detection System
  -CSE CIC dataset used.
  -Data Preprocessing done.
  -Heatmap utilized to obtain correlation amongst attributes.
  -The output variale identified for performing training and testing of the dataset.
  -Sklearn used for the train_test_split() to train the dataset.80% of the dataset-->training and 20%-->testing.
  -Sklearn modules inbuilt functionality, SVCclassifier is utilized for training the dataset with svm model.

--The Pyshark packet capture for testing the SVM model or the Network Traffic Analyzer
  -The Filecapture() and LiveCapture() are utilized to capture the hosts activities.
  -Sniff() and Sniff_Continuously() were also utilized to sniff packets which would then be analyzed for classifying the traffic into non-malicious and malicious          traffic.
