---


---

<h3 id="maxpooling">MaxPooling</h3>
<p>Max pooling helps to reduce the data size and helps to reduce the number of parameters in the model. It reduces the cost by achieving better performance. Max pooling can also help to prevent over-fitting.</p>
<p>Max pooling is performed by selecting the maximum cell value within the input matrix. For example if 4x4 input and 2x2 filter with stride 2 is used, max pool will reduce the size 4x4 to 2x2 as shown in the image below. We can also say that max pooling is a down sampling technique in convolution neural networks.</p>
<p><img src="http://cs231n.github.io/assets/cnn/maxpool.jpeg" alt=""></p>
<h3 id="dropout">Dropout</h3>
<p>Dropout means dropping out neurons (units) in a neural network. This can be applied to visible or hidden units. Dropout is a technique used to prevent over-fitting. Over-fitting means the model preforms well on the training set but not well on test set. Prediction works well on the training set only and the prediction is very poor on the new data. Instead learning the general features, the model has learnt some specific features available only in the training set. Dropout is achieved by ignoring some neurons during the training phase of some set of neurons which are selected. The selection of neurons to dropout are done at random.</p>
<p><img src="https://cdn-images-1.medium.com/max/1000/1*iWQzxhVlvadk6VAJjsgXgg.png" alt=""></p>
<h3 id="fractionally-slided-or-transpose-or-deconvolution">Fractionally Slided or Transpose or Deconvolution</h3>
<p>Transpose convolution is like a reverse process of normal convolution. It tries to re-create the original input from the normal convolution output. Convolution usually reduces the data size and deconvolution cannot recreate the whole data back. Still it helps in many encoder - decoder architectures. It will not do the actual reverse mathematical process. Instead it does some fancy padding and to the input and does another convolution to produce the same size of data which is bigger and similar to the original input. Transpose convolution will not be using the same filters which was used for the original convolution. It is useful in image and video processing to enhance resolution and encode and decode data.<br>
<img src="https://cdn-images-1.medium.com/max/1200/1*Lpn4nag_KRMfGkx1k6bV-g.gif" alt=""></p>

