# Ransomware_detection_system

## Introduction :
Ransomware typically spreads through phishing emails, malicious websites, or infected software downloads.Once a user clicks on a malicious link or downloads an infected file, the ransomware is installed on their system. After installation, the ransomware will encrypt the hardware.This encryption uses strong cryptographic algorithm which is almost impossible to decrypt.

## Scope of the project :
The project will focus on designing a signature-based ransomware detection system with an automated backup functionality, ensuring effective detection and quick recovery from ransomware attacks.Implementing a detection system that scans for known ransomware signatures to prevent infection.Developing a notification system and recovery process that triggers data restoration from backups if ransomware is detected.

## Source :
A collection of ransomware signatures, typically provided by cybersecurity research institutions, antivirus vendors, or open-source malware repositories.(eg: VirusTotal, Hybrid Analysis, or open-source threat intelligence feeds)Used to identify known ransomware by comparing file patterns, hashes, or binary code signatures with those in the database.

## Approach:
1. Data Collection
2. Data Preprocessing
3. Design and Development of Detection System
4. Development of Automated Backup System
5. Detection and Backup Integration
6. Evaluation and Testing
7. Performance Metrics and Model Evaluation
8. Deployment and Maintenance

## Installation :
To run this project, you will need to have Python installed on your machine. Follow these steps to set up the environment:

Clone the repository:
```
git clone https://github.com/Reebak04/Ransomware_detection_system.git
cd Ransomware_detection_system
```
Install the required packages:
```
pip install -r requirements.txt
```
## Video Demonstration :
[Video_Presentation](https://youtu.be/MKr-tPu-QKA?si=jQjXW6Sv15dVkGye)

## Sequence Diagram :
![image](https://github.com/user-attachments/assets/f5ac1282-9450-45d3-94ee-cb05d9a1067d)

## Result of our project :
### Accuracy :
![image](https://github.com/user-attachments/assets/4be7df09-ad28-4c1a-8c0d-f75ef406ef59)
### Data visualization : Confusion matrix
![image](https://github.com/user-attachments/assets/dc336b2c-af63-49d8-b85d-18f72ff2ea64)
### Data visualization : Feature importance
![image](https://github.com/user-attachments/assets/1a5f3c32-9042-4a61-8c58-049187cde8c3)
### Model accuracy :
![image](https://github.com/user-attachments/assets/16cad068-5ce4-4476-9119-82df1435b539)


## Future Work :
Future enhancements will focus on integrating machine learning algorithms for advanced anomaly detection, allowing the system to identify unknown ransomware threats and improving overall detection accuracy and responsiveness.Additionally, expanding cloud backup options and incorporating blockchain technology for secure data integrity will enhance the system’s resilience against cyber threats, providing users with greater confidence in their data protection strategies.

## Conclusion :
The Ransomware Detection and Automated Backup System project successfully addresses the growing threat of ransomware by integrating robust detection mechanisms with efficient data backup processes. By leveraging advanced algorithms and proven technologies, the project enhances the security posture of users and organizations against malicious attacks.
