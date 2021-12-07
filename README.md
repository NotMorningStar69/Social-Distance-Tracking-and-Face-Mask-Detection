# Social Distance Tracking and Face Mask Detection

1. Download yolov3.weights from https://pjreddie.com/media/files/yolov3.weights and place it in "yolo-coco" folder.
2. Download facemask dataset from https://kaggle.com and place it in a folder "dataset". For images with face mask place it in "dataset/with_mask". For images without face mask, place it in "dataset/without_mask".
3. Install the requirements from requirements.txt

Run the notebook file either in Google Colab or Jupyter Notebook. If using Google Colab, place all the files in your Drive and mount the drive (code available in ".ipynb" file). If using Jupyter Notebook, ignore that code.

Instructions on how to run the face mask training program is giving inside the code. As of now training program won't work in Google Colab. Run it in your machine and after training completes, copy classifier.model from the folder "models" to your "models" folder in Drive (if using Google Colab, otherwise it's fine).


