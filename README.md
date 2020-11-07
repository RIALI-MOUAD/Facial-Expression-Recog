# Facial-Expression-Recognition
The project can be braodly divided into two parts -
1) Build and train a model in Keras for Facial Expression Recognition.
2) Deploy the model on web using FLASK and run it on videos.

# Steps to follow

1) Extract train and test images from ```data.rar``` file.
2) Run the jupyter notebook for training, ```model.json``` and ```model_weights.h5``` files will be created after training.
3) Add the correct path to the video file in camera.py [if you want a live streaming you can write 0]on line 11.
4) Now run  ```pipenv run python3 main.py```
