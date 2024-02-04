---
DOI: doi.org/10.1007/s10207-020-00506-7
Date: "2020"
Rating: 5/5
Title: Using homomorphic encryption for privacy‑preserving clustering of intrusion detection alerts
ShortSummary: Cyber-security attacks are becoming more frequent and more severe day by day. To detect the execution of such attacks, organizations install intrusion detection systems. It would be beneficial for such organizations to collaborate, to better assess the severity and the importance of each detected attack. On the other hand, it is very difficult for them to exchange data, such as network traffic or intrusion detection alerts, due to privacy reasons. A privacy-preserving collaboration system for attack detection is proposed in this paper. Specifically, homomorphic encryption is used to perform alerts clustering at an inter- organizational level, with the use of an honest but curious trusted third party. Results have shown that privacy-preserving clustering of intrusion detection alerts is feasible, with a tolerable performance overhead.
---
#Clustering #reviewpaper 


# Using homomorphic encryption for privacy‑preserving clustering of intrusion detection alerts
*Adlina*

> [!tldr] Summary
> Cyber-security attacks are becoming more frequent and more severe day by day. To detect the execution of such attacks, organizations install intrusion detection systems. It would be beneficial for such organizations to collaborate, to better assess the severity and the importance of each detected attack. On the other hand, it is very difficult for them to exchange data, such as network traffic or intrusion detection alerts, due to privacy reasons. A privacy-preserving collaboration system for attack detection is proposed in this paper. Specifically, homomorphic encryption is used to perform alerts clustering at an inter- organizational level, with the use of an honest but curious trusted third party. Results have shown that privacy-preserving clustering of intrusion detection alerts is feasible, with a tolerable performance overhead.



### Aim of Paper
The aim of this paper is to present a privacy-preserving system for clustering intrusion detection alerts from multiple organizations. The paper uses homomorphic encryption to enable the processing of encrypted data without revealing any sensitive information. The paper also describes the design, implementation, and evaluation of the proposed system.

#### Key insights
- The paper proposes a **privacy-preserving collaborative system** for clustering intrusion detection alerts from different organizations, using **homomorphic encryption** and a **trusted third party**.
- The paper uses the **Paillier cryptosystem** to enable the processing of encrypted alerts without revealing any sensitive information to the third party or other organizations.
- The paper employs the **K-medoids algorithm** to cluster the alerts based on their similarity, using four features: external IP address, alert signature, alert class, and time stamp.
- The paper evaluates the proposed system in terms of **accuracy, performance, scalability, and privacy**. The paper shows that the system can achieve comparable accuracy to non-privacy-preserving methods, with a tolerable overhead and minimal privacy leakage.


![[spathoulas2020.pdf]]