<h2> Effects of haze removal on image segmentation in self-driving cars </h2>

<h3> This is my project for Pattern Recognition and Computer Vision (DS-5110) at Northeastern University. </h3>

<p> Fully autonomous cars aren’t a reality yet, but they are not very far away in
the future. However, technology has enabled several advanced driver assistance
features, most of which require environmental perception. There are various
techniques that are used for environmental perception like image segmentation.
It is the process of assigning a label to every pixel in an image such that pixels
with similar characteristics share the same label. This gives ideal results when the
road users and surroundings are clearly visible to the camera, however bad weather
conditions like haze, snow, rain, or fog can degrade the quality of segments. So we
need a system in place to make sure that we can still collect valuable data in real
time. In this paper we discuss the performance of a dark channel prior based image
defogging technique on a set of densely hazy images. An image segmentation
model using U-net architecture is trained on around 2900 images. We used this
model to observe the effect of haze on segmentation by comparing segments in
hazy vs non-hazy images. Experimental results show that the segmentation results
improve after haze removal from the images, although haze removal itself is a
challenging task, especially in images with high density haze.</p>


<h4> Datasets <h4>

<ol>
  <li> https://www.kaggle.com/datasets/dansbecker/cityscapes-image-pairs </li>
  <li> https://data.vision.ee.ethz.ch/cvl/ntire19//dense-haze/ </li>
</ol> 



