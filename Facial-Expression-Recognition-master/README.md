# Facial-Expression-Recognition
This project is a part of Coursera's Guided Project - [Facial Expression Recognition with Keras]


The project can be braodly divided into two parts -
1) Build and train a model in Keras for Facial Expression Recognition.
2) Deploy the model on web using FLASK and run it on videos.

# Steps to follow

1) Extract train and test images from ```data.rar``` file.
2) Install dependencies using

   ```pip install pipenv```

   ```pipenv install```

3) Run the jupyter notebook for training, ```model.json``` and ```model_weights.h5``` files will be created after training.
4) Add the correct path to the video file in camera.py on line 11.
5) Now run  ```pipenv run python3 main.py```