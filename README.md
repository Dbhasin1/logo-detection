Instructions for the training process

Move dataset.zip to logo-detection/data/ and unzip it there
Run the data_augmentation_final notebook to augment the images present in logo-detection/data/dataset
compress dataset and upload it on your google drive account
Open train.ipynb on google colab and mount your google drive account there, move the compressed dataset.zip file from content/gdrive/My Drive to /content
After you unzip the dataset.zip file, move the train and valid folders to content/ and the data.yaml file to content/yolov5
Manually change the value of 'nc' in content/yolov5/models/yolov5l from '80' to '527'
Instructions for the detection process

Upload the video in which you wish to run your detection on google drive
Open detect.ipynb in google colab and mount your google drive account
Move the video from content/gdrive/My Drive to content/ and your best_fin.pt file to content/yolov5/weights
