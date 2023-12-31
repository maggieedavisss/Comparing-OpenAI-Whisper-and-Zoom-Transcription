# Comparing Open AI Whisper and Zoom Transcription 
A group of 4 students worked together comparing 2 speech-to-text services, OpenAI Whisper and Zoom Transcription. 
We explored AWS Sagemaker, Boto3, S3 buckets, and ML API's such as OpenAI Whisper. We performed a comparative analysis between the OpenAI Whisper and Zoom speech-to-text transcription services.
# Furthering Our Work
You may want to explore if there are more differences between the OpenAI Whisper and Zoom transcription services when transcribing lectures covering different subjects! You could compare lectures on environmental science and economics. The choice is yours!
# Architectural diagram
![image](https://github.com/maggieedavisss/Comparing-OpenAI-Whisper-and-Zoom-Transcription/assets/151679687/63c5bdcc-c2cb-4d3d-b1c7-c5129ffec5ca)
First, we acquired two Zoom recordings from a professor lecturing on machine learning. The topics of these lectures included LDA/QDA and Regularization/Selection. Following this, we converted the lecture recordings into mp3 files. You can do this by simply using any mp3 converter! Next, we simply downloaded the Zoom transcriptions from the posted video recordings and saved them to our computers. Now, it wasn't that easy when acquiring the Whisper transcriptions of the two classes. First, we used Amazon Sagemaker, an online web application for machine learning and data science using Jupyter notebooks [[SageMaker Studio Lab]](https://studiolab.sagemaker.aws/faq#:~:text=Amazon%20SageMaker%20Studio%20Lab%20is,machine%20learning%20using%20Jupyter%20notebooks). Within this application, we first stored our Zoom mp3 files into an s3 bucket. An s3 bucket is a public cloud storage container for objects stored in a simple storage service (s3). Next, we used Python boto3 to access our mp3 files stored in s3 buckets to utilize OpenAI. Boto3 is the Python SDK for AWS that allows you to directly create, update, and delete AWS resources from your Python scripts [[Real Python]](https://realpython.com/python-boto3-aws-s3/#:~:text=Boto3%20is%20the%20name%20of,resources%20from%20your%20Python%20scripts). After this, we used the OpenAI machine learning model to transcribe our Zoom mp3 files. Lastly, we stored the Zoom and OpenAI Whisper text transcriptions in a transcription bucket. From here, we used Python to perform our comparative analysis. 
# Reproduce 
For directions on accessing Jupyter Studio Lab through Amazon Sagemaker and utilizing the OpenAI Whisper ML model, download the `AWS Sagemaker and OpenAI Whisper` notebook! 

To look through and build off our analysis, download the `Comparative Analysis` notebook! 
# Thank You! 
![image](https://github.com/maggieedavisss/Comparing-OpenAI-Whisper-and-Zoom-Transcription/assets/151679687/f8e2ae2d-9174-4efb-a08f-69eb974c1250)

