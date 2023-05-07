Download Link: https://assignmentchef.com/product/solved-ml-homework3-perceptron
<br>
<ol>

 <li><strong> Perceptron. </strong>Implement the Perceptron algorithm (in the file name perceptron.py). Do not forget to normalize the samples to have unit length (i.e., k<em>x<sub>i</sub></em>k = 1).</li>

</ol>

<ul>

 <li><strong> </strong>Use only the first <em>n </em>= 5<em>,</em>10<em>,</em>50<em>,</em>100<em>,</em>500<em>,</em>1000<em>,</em>5000 samples as an input to Perceptron. For each <em>n</em>, run Perceptron 100 times, each time with a different random order of inputs, and calculate the accuracy of the classifier on the test set of each run. You should therefore have 100 accuracy measurement per <em>n</em>. Print a table showing, for each <em>n</em>, the mean accuracy across the 100 runs, as well as the 5% and 95% percentiles of the accuracies obtained.</li>

 <li><strong> </strong>The weight vector <em>w</em>, returned by Percepton, can be viewed as a matrix of weights, with which we multiply each respective pixel in the input image. Run Perceptron on the entire training set, and show <em>w</em>, as a 28×28 image, for example with imshow(reshape(image, (28, 28)), interpolation=’nearest’). Give an intuitive interpretation of this image.</li>

 <li>Calculate the accuracy of the classifier trained on the full training set, applied on the test set.</li>

 <li><strong> </strong>Choose one (or two) of the samples in the test set that was misclassified by Perceptron (with the full training set) and show it as an image (show the unscaled images). Can you explain why it was misclassified?</li>

</ul>