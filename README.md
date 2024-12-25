<h1>Dynamic Facial Expression Recognition</h1>

Due to file size limitations, the dataset and model weights have been placed in the <a href="https://drive.google.com/drive/folders/13F5SdpsM021hzls0vAxgC8UPK8rI70X0?usp=sharing">cloud folder</a>. If you can not access the cloud link, please contact s112065541@m112.nthu.edu.tw.

<h1>Description</h1>
<ul>
  <li>ResNet3D.py: The content includes the functions, classes, and packages required for emotion recognition prediction on videos. It also contains commented code used during model training.</li>
  <li>test_prediction.py: This is the main code for performing emotion recognition tasks on videos. When running it, you may need to install any missing packages, which are listed in the import section at the top.</li>
  <li>saved_models: A folder used to store the model weights.</li>
  <li>test_videos: A folder used to store our sample videos.</li>
  <li>extracted_frames: A folder used to store the images sampled from the videos. Once the video to be predicted is loaded into our function, the sampled images will be automatically saved to this folder.</li>
</ul>

<h1>How to use</h1>
We will now demonstrate how to use our model to perform dynamic emotion recognition on sample videos. Please follow the steps below:

<ol>
  <li>Please first download 'test_model_v4.pth' from the <a href="https://drive.google.com/drive/folders/13F5SdpsM021hzls0vAxgC8UPK8rI70X0?usp=sharing">cloud folder</a> and place it into the 'saved_models' directory.</li>
  <li>Download 'ResNet3D.py', 'test_prediction.py', and the three folders: 'extracted_frames', 'saved_models', and 'est_videos'. Save them following the file hierarchy in this repository.</li>
  <li>run 'test_prediction.py' to perform emotion category predictions on the sample videos in the 'test_videos' folder.</li>
</ol>

<b>P.S. If you want to perform emotion recognition on your own videos, please modify 'test_prediction.py' by changing video_folder = "./test_videos" to the folder containing your videos, and update video_file = "Fear.mp4" with the name of your video file.</b>
