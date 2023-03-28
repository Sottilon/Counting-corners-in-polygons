Project suggestion 1.

Counting corners in polygons. Training images contain random polygons
ranging from triangles (3 corners) up to polygons with 10 corners. The
polygons are "easy" in the sence that two corners are not too close to
each other and that angles in the polygons are not too close to 180
degrees.

The task is to train a CNN model that can predict the number of
corners in a given image.

The folders polyAll-trn and polyAll-tst contain training and test
images, respectively. The files 'polyAll-trn_trg.csv' and
'polyAll-tst_trg.csv' contain info regarding the number of corners for
each file.

The python script 'polygon_read.py' contain function to read the image
data such that you can use it with your CNNs.


