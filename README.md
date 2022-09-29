# data-crab-face-recognition
This project was developed during the hackathone with "educational security" track.

In notebook *Extract Face Encoding From Image* you can find usage of MTCNN model from *dlib* to extract encodings of face images. It works both with single-face and several faces on the picture. This part of developed system sends these encodings to another service where takes place comparison of encodings from a person at school checkpoint. For example we might use cosine-similarity metric to check this.

In notebook *Pre-Trained_Model* you can find visualisation of detected faces on given pictures. Also you can check some information about facial features.
