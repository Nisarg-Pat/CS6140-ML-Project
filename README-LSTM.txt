These steps are required for CNN-LSTM code to work.

1. The COCO dataset being a large dataset around 18 GB, needs to be downloaded from https://cocodataset.org/#download. 
	Right click on 2017 Train images [118K/18GB] and click on Save Link As (For Windows).
	Save the images in a folder and change the BASE_DIR in CNN LSTM Image Captioning.ipynb to refer to that folder.
2. caption_to_img.json contains the captions and the respective image_ids. Keep it in the same directory as CNN LSTM Image Captioning.ipynb.
3. The pretrained features for training_data can be loaded from features.npy
4. The pretrained model is in ./working folder. You can load model directly from here instead of training
5. You can predict any image by giving the image_id to generate_captions. 