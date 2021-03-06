
Solar Cell Cracks and Finger Failure Detection using Statistical Parameters of Electroluminescence Images and Machine Learning 

This is a private repo to share the code and necessary material to understand the project. The repo has the following structure:

ML paper code: Contains the python code used for classifying solar cell cracks and finger failures through three supervised ML methods. 

Manuscript: Contains the published paper

Dataset (crackccells, fingerfailurecells, crackcmask, fingerfailuremask): Contains a subset of images and their respective binary mask of each failure class used for analysis.

Results: Contains the image file of all the results used in the paper.

Abstract: A wide range of defects, failures, and degradation can develop at different stages in the lifetime of photovoltaic modules. To accurately assess their effect on the module performance, these failures need to be quantified. Electroluminescence (EL) imaging is a powerful diagnostic method, providing high spatial resolution images of solar cells and modules. EL images allow the identification and quantification of different types of failures, including those in high recombination regions, as well as series resistance-related problems. In this study, almost 46,000 EL cell images are extracted from photovoltaic modules with different defects. We present a method that extracts statistical parameters from the histogram of these images and utilizes them as a feature descriptor. Machine learning algorithms are then trained using this descriptor to classify the detected defects into three categories: (i) cracks (Mode B and C), (ii) micro-cracks (Mode A) and finger failures, and (iii) no failures. By comparing the developed methods with the commonly used one, this study demonstrates that the pre-processing of images into a feature vector of statistical parameters provides a higher classification accuracy than would be obtained by raw images alone. The proposed method can autonomously detect cracks and finger failures, enabling outdoor EL inspection using a drone-mounted system for quick assessments of photovoltaic fields.
