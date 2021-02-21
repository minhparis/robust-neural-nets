Context:
Machine learning models are deployed in various tasks including image classification, malware detection, etc. But recent work has shown that even advanced deep neural networks, which excel at these tasks, are vulnerable to a class of malicious inputs known as conflicting examples. These examples are non-random inputs that are almost indistinguishable from natural data and yet are misclassified.

Adversarial Examples:
By modifying some bits of the file that are benign, our systems could predict that it is a benign file (although it did not modify the malicious part of the file, so it should be classified as malware. ) and would not block it, posing a security risk to the computer.

Machine learning algorithms are generally designed assuming that the models are trained on samples drawn from a representative distribution of the test samples that we would subsequently make predictions about. However, this is not true in the case of conflicting examples.

This project aims to tackle the subject of adversarial attacks. That is, to succeed, by a modification as imperceptible as possible, to deceive a trained neural network for a classification problem.

Three approaches will be discussed here:

- Fast Gradient Sign Method
- Projected Gradient Descent
- Black Box attacks
