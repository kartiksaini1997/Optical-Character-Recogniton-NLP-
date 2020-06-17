# Optical-Character-Recogniton-NLP-

OCR = Optical Character Recognition. In other words, OCR systems transform a two-dimensional image of text, that could contain machine printed or handwritten text from its image representation into machine-readable text. OCR as a process generally consists of several sub-processes to perform as accurately as possible. The subprocesses are:

Preprocessing of the Image
Text Localization
Character Segmentation
Character Recognition
Post Processing
The sub-processes in the list above of course can differ, but these are roughly steps needed to approach automatic character recognition. In OCR software, it’s main aim to identify and capture all the unique words using different languages from written text characters.

For almost two decades, optical character recognition systems have been widely used to provide automated text entry into computerized systems. Yet in all this time, conventional OCR systems have never overcome their inability to read more than a handful of type fonts and page formats. Proportionally spaced type (which includes virtually all typeset copy), laser printer fonts, and even many non-proportional typewriter fonts, have remained beyond the reach of these systems. And as a result, conventional OCR has never achieved more than a marginal impact on the total number of documents needing conversion into digital form.


Optical Character Recognition process (Courtesy)
Next-generation OCR engines deal with these problems mentioned above really good by utilizing the latest research in the area of deep learning. By leveraging the combination of deep models and huge datasets publicly available, models achieve state-of-the-art accuracies on given tasks. Nowadays it is also possible to generate synthetic data with different fonts using generative adversarial networks and few other generative approaches.

Optical Character Recognition remains a challenging problem when text occurs in unconstrained environments, like natural scenes, due to geometrical distortions, complex backgrounds, and diverse fonts. The technology still holds an immense potential due to the various use-cases of deep learning based OCR like

building license plate readers
digitizing invoices
digitizing menus
digitizing ID cards
In this blog post, we will try to explain the technology behind the most used Tesseract Engine, which was upgraded with the latest knowledge researched in optical character recognition. This article will also serve as a how-to guide/ tutorial on how to implement OCR in python using the Tesseract engine. We will be walking through the following modules:

Tesseract OCR Features
Preprocessing for OCR using OpenCV
Running Tesseract with CLI and Python
Limitations of Tesseract engine


