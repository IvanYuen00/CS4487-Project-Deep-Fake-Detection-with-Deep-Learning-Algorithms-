# CS4487 Project - Deep Fake Detection with Deep Learning Algorithms
The realism of bogus content has dramatically increased with the development of deep learning technologies. These fake photos can be further broken down into deepfake and face-to-face fake images. Modern deepfake images are primarily created by Generative Adversarial Networks, as opposed to face-to-face fake photos, which are normally created by changing a source's facial expression into a target. Someone might use deepfake photos for illicit purposes if we are unable to tell those fake facial images apart from genuine faces with accuracy. As a result, research in DeepFake Detection has picked up steam.

Three channel facial photographs with the size of 299 * 299 are the inputs for this course project, and the desired output is a binary label indicating whether or not a particular image is false. There are 12,000 photos total in the training set, with the labels f2f fake, deep fake, and real, respectively. The ratio of fake to actual images, if we generalise the f2f fake and deep fake as fake images, is 2 to 1.

2,985 unviewed photos make up the test dataset. To train a representative model on the full training set and attain the highest test accuracy on the test set is the goal that we are trying to accomplish.

When faced with a common image classification issue, it makes sense to consider a cutting-edge solution, such as a deep neutral network. Additionally, there have been many alternative network models developed over the years, some of which have produced state-of-the-art results in picture classification tasks. Our team has selected a few well-known network models and individually evaluated each one's performance.
