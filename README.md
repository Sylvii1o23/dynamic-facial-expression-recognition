Due to file size limitations, the dataset and model weights have been placed in the <a href="(https://drive.google.com/drive/folders/13F5SdpsM021hzls0vAxgC8UPK8rI70X0?usp=sharing)">cloud folder</a> If you could not have access to the cloud link, please contact s112065541@m112.nthu.edu.tw.

<h1>Description</h1>
<ul>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
</ul>

<h1>How to use</h1>
We will now demonstrate how to use our model to perform dynamic emotion recognition on sample videos. Please follow the steps below:

<ol>
  <li>Please first download 'test_model_v4.pth' from the cloud folder and place it into the 'saved_models' directory.</li>
  <li>Download 'ResNet3D.py', 'test_prediction.py', and the three folders: 'extracted_frames', 'saved_models', and 'est_videos'. Save them following the file hierarchy in this repository.</li>
  <li>run 'test_prediction.py' to perform emotion category predictions on the sample videos in the 'test_videos' folder.</li>
</ol>

<b>P.S. If you want to perform emotion recognition on your own videos, please modify 'test_prediction.py' by changing video_folder = "./test_videos" to the folder containing your videos, and update video_file = "Fear.mp4" with the name of your video file.</b>
