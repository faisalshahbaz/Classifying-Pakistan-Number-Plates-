Hi Matt,

We tried training a cascade for the number plates in Positive Images folder. We used to create more images (about 100 more) from the given images using different affine and non-affine transforms since we had limited data. We used about 600 negative examples, where as abround 150 positives. We used the methods prescribed in two links:

http://coding-robin.de/2013/07/22/train-your-own-opencv-haar-classifier.html
http://docs.opencv.org/doc/user_guide/ug_traincascade.html

If our number of stages were more than 7, it used to stuck, and never ended, even after 4 days. If the number of stages were 6 or less, the training was never good, giving a lot of false detections, and even missing the right stuff.
Please guide us a bit on this.


Thanking you in anticipation,
Syed Mohammad Yousaf.