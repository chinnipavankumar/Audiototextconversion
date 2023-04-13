# Audiototextconversion

Hello ,I'm excited to showcase my project using Amazon Transcribe and Amazon S3 that converts audio files to text.

Amazon Transcribe is an automatic speech recognition (ASR) service that makes it easy for developers to add speech-to-text capability to their applications. 
Using the Amazon Transcribe API, you can analyze audio files stored in Amazon Simple Storage Service (Amazon S3) and have the service return a text file of the 
transcribed speech.

As a developer, creating transcriptions of customer service calls or generating subtitles on audio and video content are common challenges requiring speech-to-text 
capabilities. This challenge could be solved by building your own machine learning models from scratch. However, this option is time-intensive, expensive, and 
requires machine learning expertise. Instead of taking the difficult route, you can use Amazon Transcribe, a pre-trained and fully managed service, which provides 
fast and high-quality transcriptions.

NOTE: For doing this project you need aws management console account.

1--> Login to AWS Management console and in search box click S3 and give name of the bucket . And next change ACLs as enabled and next click on create bucket.

![1](https://user-images.githubusercontent.com/100197617/231859853-c98b1af2-71b7-4172-82c1-50607aa25a8b.png)


![2](https://user-images.githubusercontent.com/100197617/231860020-8c4ad689-b1b8-4c08-89f0-bf73b6a129d0.png)

2-->Now click on the bucket just now create and upload any audio file.

![3](https://user-images.githubusercontent.com/100197617/231860065-af3a1ad6-938a-4999-903c-f471b392c63a.png)

3-->Now go to amazon transcribe and on the left side there is transcription jobs and click on it.

![4](https://user-images.githubusercontent.com/100197617/231860110-dabbd56f-a4c4-4671-b000-3d9a61fabcad.png)

4-->Now click on create job after give the name.

<img width="960" alt="5" src="https://user-images.githubusercontent.com/100197617/231860228-cf8486e3-3e6c-46f2-90e1-cdb014102c6a.png">

5-->After that give the resource url. The resource url you can find it from S3.After that click on next review it and click on create.

![6](https://user-images.githubusercontent.com/100197617/231860337-6315a352-f33f-4056-8a77-1aed736ad250.png)

6-->After some time it will complete and you will get translated text.

![7](https://user-images.githubusercontent.com/100197617/231860420-9646f4bf-bb57-4110-82fa-72b3493a4bc2.png)

![8](https://user-images.githubusercontent.com/100197617/231860449-43843842-8095-4e24-9abb-a5590318a9ce.png)

Conclusion: You have learned how to translate audio file to text in aws using amazon transcribe and amazon s3.
Thanking You!



