<img src="logos/BioSB_logo_full_2000x1811.jpg" width="140" height="140">

# Machine Learning for Bioinformatics & Systems Biology

A yearly course, part of the [BioSB](https://www.biosb.nl) Research School
	
*Lecturers*
   * dr. ir. Perry Moerland (Amsterdam UMC, location: Academic Medical Center)   
   * prof. dr. ir. Marcel Reinders (Delft University of Technology)
   * prof. dr. Lodewyk Wessels (Netherlands Cancer Institute)

*Course coordinator*:
   * dr. ir. Perry Moerland
   * e-mail: p.d.moerland@amsterdamumc.nl
   * telephone: +31 20 5666945

## Learning objectives

After having followed this course, the student has a good understanding of a wide range of machine learning techniques and is able to recognize what method is most applicable to data analysis problems (s)he encounters in bioinformatics and systems biology applications.

## Target audience

The course is aimed at !PhD students with a background in bioinformatics, systems biology, computer science or a related field, and life sciences. Participants from the private sector are also welcome. A working knowledge of basic statistics and linear algebra is assumed. Preparation material on statistics and linear algebra will be distributed before the course, to be studied by students missing the required background.

## Description

Modern biology is a data-rich science, driven by our ability to measure the detailed molecular characteristics of cells, organs, and individuals at many different levels. Interpretation of these large-scale biological data requires the detection of statistical dependencies and patterns in order to establish useful models of complex biological systems. Techniques from machine learning are key in this endeavour. Typical examples are the visualization of single-cell RNA-seq data using dimensionality reduction methods, base calling for nanopore sequencing data using hidden Markov models and (recurrent) neural networks, and classification of high-throughput microscopy image data using convolutional neural networks. 

In this one-week course, the foundations of machine learning will be laid out and commonly used methods for unsupervised (clustering, dimensionality reduction, visualization) and supervised (mainly classification) learning will be explained in detail. Methods will be illustrated using recent examples from the fields of systems biology and bioinformatics. Methods discussed in the morning lectures will be put into practice during the afternoon computer lab sessions. The course has to be completed afterwards with a 5-10 page report describing the analysis of a biological dataset using some of the methods taught in the course.

## Registration

You can register for this course by filling out the BioSB [enrolment form](https://www.biosb.nl/archive-courses/machine-learning-for-bioinformatics-and-systems-biology-2020/). The maximum number of participants is 25, so register soon to be sure of a course seat! *Update: we reached the maximum number of participants for the 2020 edition. Registration is closed.* If you would like to be put on the reserve list, please send an email to [Femke Francissen](mailto:femke.francissen@biosb.nl). If you are interested in the 2021 edition of the course please fill out the [pre-registration form](https://www.biosb.nl/education/enrollment/pre-registration-courses/).

The course fee includes:

   * Course material: Lecture slides, a lab course manual and software required for the lab course (MATLAB toolboxes) will be made available online.
   <!--- * Catering: Coffee, tea, soft drinks and lunch will be provided.--->

 <!--- Information about hostel accommodation in Amsterdam can be found [[https://www.vu.nl/en/programmes/links/hotels.aspx][here]]. Accommodation is not included in the course fee.--->
 
 ## Course material

*All course material will be made available online* and includes the handouts of the slides, a lab course manual and the required data and Matlab toolboxes. 

For the moment you are already advised to have a look at the following documents:
   * To prepare for the course: a [self-evaluation test](background/Self-evaluation.pdf) on the prerequisite prior knowledge (probability theory and linear algebra). If you have a lot of trouble answering some of these exercises, consult the text books mentioned in the PDF, or a few [primers](background/Primers.zip) on these topics.
   * The lab courses will make extensive use of Matlab. You do not need to be a fluent programmer, but if you have never worked with Matlab before it may help to try to get a hold of a copy of Matlab (your university may have a campus license) before the course and have a look at the Appendices of the lab course [manual](manual/Manual.pdf). An extensive Matlab [primer](background/Matlab.pdf) is also available. 

<!---During the course Matlab and all software/data are available on the PCs in the lab, so there is no need to bring your laptop.--->

## Examination

Participants requiring a certificate of successful completion (3 ECTS) should make a final assignment. The student will analyse a biological dataset (preferably one from his/her own practice) using the tools provided in the course, and write a small report (5-10 pages) on the results. If the student has no dataset available, one will be provided. The report will have to be mailed to p.d.moerland@amsterdamumc.nl no later than three weeks after the course has finished (October 30, 2020). We will strictly adhere to this deadline; if you require extension, you should contact us well in advance. The proposal will be graded "fail" or "pass", with one possible resubmission. Those who choose not to make the final assignment will receive a certificate of participation (1.5 ECTS). 

## Schedule (2020 edition)

The course will run *October 5-9 2020*. Preparation material on statistics and linear algebra will be distributed before the course, to be studied by students missing the required background. After the course, 2-3 days will have to be spent on the report to be handed in. Each course day will have the following schedule:

   * 9.00 - 12.00 	Lecture and/or computer lab
   * 12.00 - 13.00 	Lunch break 
   * 13.00 - 17.00 	Lecture and/or computer lab 

## Course material
*Note that the course material is still going to change before and during ;-) the course week.*

*Monday* (October 5) -	[Introduction](Day1/Day1.pdf)
*Lecturer* 	Marcel Reinders %BR%
*Subjects* 	Introduction to machine learning: measurements, features, classification. Supervised vs. unsupervised learning, relation to regression. Bayesian framework: risk, cost; evaluation: ROCs, cross-validation. Density estimation: histograms, nearest neighbour, Parzen, Gaussian Bayesian classification. %BR%

*Tuesday* (October 6) -	*[Classifiers](Day2/Day2.pdf)* 
*Lecturer* 	Perry Moerland %BR%
*Subjects* 	Parametric classifiers: (D)LDA, (D)QDA. Nonparametric classifiers: k-NN, Parzen. Discriminant analysis: LDA, logistic regression. Decision trees and random forests. %BR%

*Wednesday* (October 7) - *[[%BI%/Day3.pdf][Feature selection and extraction]]* %BR%
*Lecturer* 	Lodewyk Wessels %BR%
*Subjects* 	Feature selection: criteria, search algorithms (forward, backward, branch & bound). Sparse classifiers: Ridge, LASSO. Feature extraction: PCA, Fisher. Embeddings: MDS. %BR%

*Thursday* (October 8) -	*[[%BI%/Day4.pdf][Clustering and HMMs]]* %BR%
*Lecturer* 	Perry Moerland %BR%
*Subjects* 	Hierarchical clustering. Agglomerative clustering. Model-based clustering: mixtures-of-Gaussians, Expectation-Maximization. Hidden Markov models. %BR%

*Friday*  (October 9) -	*[[%BI%/Day5.pdf][Selected advanced topics]]* %BR%
*Lecturer* 	Marcel Reinders %BR%
*Subjects* 	Artificial neural networks. Support vector machines. Classifier ensembles. Complexity and regularisation. Deep learning. %BR%

For more information about the course programme, please contact [Perry Moerland](mailto:p.d.moerland@amsterdamumc.nl); for more information about registration or logistics, please contact [Femke Francissen](mailto:femke.francissen@biosb.nl).





