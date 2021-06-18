# Face Recognition in Real-time
This application is developed using OpenCV library

## Requirments
```bash
pip install opencv-python
pip install numpy
pip install Pillow
```

## Usage
1. `Face_taker.py` takes a photo of the user a certain number of times, saves it to `images` folder.

2. `Face_train.py` train a model to recognize all the faces from the images taken using `Face_taker.py` script, and save the training output in the `training.yml` file.

3. `Face_recognizer` is the main script. The program will recognize the face according to the id given in the `Face_taker.py` script. Add name to the `names = ['None', 'Andrew']` list. For example `Andrew` has an `id` of `1`.
