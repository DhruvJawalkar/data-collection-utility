# data-collection-utility
Uses google-cdn-download, tensorflow object detection api to crop and save persons doing yoga poses from images.

https://github.com/hardikvasa/google-images-download <br/>
https://github.com/opencv/opencv/wiki/TensorFlow-Object-Detection-API <br/>

Run a bulk task of downloading image results for list of keywords from google search. Then crop out exact category of interest(Ex: Persons) in the image and save, to create dataset of images.

<br/>

Raw:
![alt text](https://github.com/DhruvJawalkar/data-collection-utility/blob/master/samples/raw-images-from-google-cdn.png)

Cleaned:
![alt text](https://github.com/DhruvJawalkar/data-collection-utility/blob/master/samples/cleaned-exact-person-croped-images.png)

Download Images:
![alt text](https://github.com/DhruvJawalkar/data-collection-utility/blob/master/samples/google-cdn-download.png)

Process, create crops, send originals to trash:
![alt text](https://github.com/DhruvJawalkar/data-collection-utility/blob/master/samples/process-all-cdn-images-per-folder.png)





