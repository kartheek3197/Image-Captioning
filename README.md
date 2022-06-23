# Image-Captioning

**Introduction**

Just prior to the recent development of Deep Neural Networks Image-Captioning problem was inconceivable even by the most advanced researchers in Computer Vision. But with the advent of Deep Learning this problem can be solved very easily if we have the required dataset.

This problem was well researched by Andrej Karapathy in his PhD thesis at Stanford https://cs.stanford.edu/people/karpathy/cvpr2015.pdf, who is also now the Director of AI at Tesla.

The purpose of this blog post is to explain (in as simple words as possible) that how Deep Learning can be used to solve this problem of generating a caption for a given image, hence the name Image Captioning.


**Prerequisites**

This post assumes familiarity with basic Deep Learning concepts like Multi-layered Perceptrons, Convolution Neural Networks, Recurrent Neural Networks, Transfer Learning, Gradient Descent, Backpropagation, Overfitting, Probability, Text Processing, Python syntax and data structures, Keras library, etc.


**Applications**

We must first understand how important this problem is to real world scenarios. Let’s see few applications where a solution to this problem can be very useful.

1) Self driving cars — Automatic driving is one of the biggest challenges and if we can properly caption the scene around the car, it can give a boost to the self driving system.
2) Aid to the blind — We can create a product for the blind which will guide them travelling on the roads without the support of anyone else. We can do this by first converting the scene into text and then the text to voice. Both are now famous applications of Deep Learning. Refer this link where its shown how Nvidia research is trying to create such a product.
3) CCTV cameras are everywhere today, but along with viewing the world, if we can also generate relevant captions, then we can raise alarms as soon as there is some malicious activity going on somewhere. This could probably help reduce some crime and/or accidents.
4) Automatic Captioning can help, make Google Image Search as good as Google Search, as then every image could be first converted into a caption and then search can be performed based on the caption.



**Data Collection**

There are many open source datasets available for this problem, like Flickr 8k (containing8k images), Flickr 30k (containing 30k images), MS COCO (containing 180k images), etc.

But for the purpose of this case study, I have used the Flickr 8k dataset which you can download on Kaggle by using this link https://www.kaggle.com/datasets/adityajn105/flickr8k. Also training a model with large number of images may not be feasible on a system which is not a very high end PC/Laptop.

This dataset contains 8000 images each with 5 captions (as we have already seen in the Introduction section that an image can have multiple captions, all being relevant simultaneously).


**References**
1) https://cs.stanford.edu/people/karpathy/cvpr2015.pdf
2) https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/
3) https://www.youtube.com/watch?v=yk6XDFm3J2c
4) https://www.appliedaicourse.com/


**PS: Feel free to provide comments/criticisms if you think they can improve this blog, I will definitely try to make the required changes.**
