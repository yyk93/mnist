##### Author: Vincent Yeo

## Image Recognition with MNIST dataset

#### Background:

The MNIST database contains 70000 images of handwritten digits from 0 to 9, a subset of the [NIST](https://www.nist.gov/srd/nist-special-database-19) database, that has been preprocessed in normalising size and centering of the image.

The authors have offer it to the world for machine learning and pattern recogrnition methods

From LeCun, Y., Cortes, C. & Burges, C. J. C (n.d.). THE MNIST DATABASE of handwritten digits. Retrieved from http://yann.lecun.com/exdb/mnist/

#### Task:
Classify the digits correctly.

#### Results and Analysis:
The CNN has achieved a 96.2% test accuracy.

Based on each precision score, the model's prediction would be realised truely for 
+ the digit `0`, 97% of the time.
+ the digit `1`, 98% of the time.
+ the digit `2`, 97% of the time.
+ the digit `3`, 95% of the time.
+ the digit `4`, 96% of the time.
+ the digit `5`, 95% of the time.
+ the digit `6`, 96% of the time.
+ the digit `7`, 95% of the time.
+ the digit `8`, 96% of the time.
+ the digit `9`, 96% of the time.

Based on each recall score, the model's prediction for
+ the digit `0` has about 99% being correct.
+ the digit `1` has about 99% being correct.
+ the digit `2` has about 95% being correct.
+ the digit `3` has about 96% being correct.
+ the digit `4` has about 96% being correct.
+ the digit `5` has about 96% being correct.
+ the digit `6` has about 97% being correct.
+ the digit `7` has about 95% being correct.
+ the digit `8` has about 95% being correct.
+ the digit `9` has about 94% being correct.

Based on each f1 score, the weighted average of the precision and recall for
+ the digit `0` is 98%
+ the digit `1` is 98%
+ the digit `2` is 96%
+ the digit `3` is 95%
+ the digit `4` is 96%
+ the digit `5` is 95%
+ the digit `6` is 97%
+ the digit `7` is 95%
+ the digit `8` is 95%
+ the digit `9` is 95%