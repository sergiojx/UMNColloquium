# UMNColloquium

## Cray Colloquium: 3D Scene Understanding with a RGB-D Camera
 Cray Distinguished Speaker Series   
October 14, 2019 - 11:15am to 12:15pm   
Thomas Funkhouser   
Affiliation:      
Princeton/Google   
Abstract: Three-dimensional scene understanding is important for computer systems
that respond to and/or interact with the physical world, such as robotic
manipulation, autonomous navigation, and augmented reality.  For
example, they may need to estimate the 3D geometry of the surrounding
space (e.g., in order to navigate without collisions) and/or to
recognize the semantic categories of nearby objects (e.g., in order to
interact with them appropriately).   In this talk, I will describe
recent work on 3D scene understanding at Princeton and Google.   I will
focus on three projects that infer 3D structural and semantic models of
scenes from partial observations with a RGB-D camera.   The first learns
to infer 3D geometry from color in cases where the depth sensing is not
possible.  The second learns to infer the 3D structure and semantics of
a complete surrounding environment.  The third infers a temporal model
of semantic object instances from RGB-D scans acquired at sparse time
intervals.   For each project, I will discuss the problem formulation,
scene representation, network architecture, dataset curation, and
potential applications.

This is joint work with Angela Dai, Maciej Halber, Jingwei Huang,
Matthias Niessner, Shuran Song, Andy Zeng, and Yinda Zhang.


Bio: Thomas Funkhouser is a senior research scientist at Google and the David
M. Siegel Professor of Computer Science, Emeritus, at Princeton
University.  He received a PhD in computer science from UC Berkeley in
1993 and was a member of the technical staff at Bell Labs until 1997
before joining the faculty at Princeton.  For most of his career, he
focused on research problems in computer graphics, including
foundational work on 3D shape retrieval, analysis, and modeling.   His
most recent research has focused on 3D scene understanding in computer
vision.   He has published more than 100 research papers and received
several awards, including the ACM SIGGRAPH Computer Graphics Achievement
Award, ACM SIGGRAPH Academy, ACM Fellow, NSF Career Award, Emerson
Electric, E. Lawrence Keyes Faculty Advancement Award, Google Faculty
Research Awards, University Council Excellence in Teaching Awards, and a
Sloan Fellowship.
### Resources
https://www.cs.princeton.edu/~funk/  
## Automated Support for Improving Software Quality Before and After Release
October 7, 2019 - 11:15am to 12:15pm  
Mattia Fazzini  
Affiliation:  
CS&E  
Location:   
3-180 Keller Hall  
Abstract: Due to the importance of software quality, companies invest a great number of resources in software verification, and in particular in testing. It is therefore crucial to develop and use testing approaches that are both effective and efficient. At the same time, because testing techniques cannot generally reveal all bugs, companies release software containing latent bugs. Additionally, the environment in which software operates changes quickly and these changes introduce new bugs. The ability to react effectively to reported latent bugs and changes to the environment is therefore also essential to resolve bugs, but the support for these tasks is still limited and based on mostly manual, human-intensive approaches. The overarching goal of my research is to improve software quality by devising novel techniques that account for software bugs before and after release.  

In particular, this talk will present the work I did towards my goal in the context of mobile applications (or simply apps). The talk will cover a family of testing and maintenance techniques: Barista, DiffDroid, Yakusu, and AppEvolve. Barista records, encodes, and runs platform-independent test cases to help developers in testing apps. DiffDroid identifies inconsistencies in the behavior of an app running on different platforms and reports these inconsistencies to developers. Yakusu translates natural-language bug reports into test cases, so that developers can use the generated tests to debug failures caused by latent bugs and quickly fix their apps. AppEvolve accounts for bugs caused by changes to the environment; it does so by automatically updating API usages (i.e., interactions with the underlying environment) in an app based on how developers of other apps performed corresponding changes. I will conclude my talk with a discussion of open challenges and in-progress research work.  

Bio: Mattia Fazzini is an Assistant Professor in the Computer Science & Engineering Department at University of Minnesota. His research interests lie primarily in the area of software engineering, with emphasis on techniques for improving software quality. The central theme of his research is the development of techniques for testing and maintenance of mobile applications. He is also interested in defining techniques for improving the security of software.  
### Resources
https://www-users.cs.umn.edu/~mfazzini/index.html  

## Data Systems for Human Data Interaction
Colloquia 
September 23, 2019 - 11:15am to 12:15pm 
Remco Chang 
Affiliation:  
Tufts University 
Location:   
3-180 Keller Hall
Host:  
Evan Suma Rosenberg 
Abstract: Visualization and visual analytics have become an integral part of data science as data become larger and more complex. With the democratization of data and data analysis, visualization is now used by scientists, domain experts, decision makers, and everyday citizens. Such widespread use of visualization has subsequently increased the challenge of designing generalizable systems that can suit the diverse needs of a wide audience. In this talk, I will present four research projects at the Visual Analytics Lab at Tufts (VALT) that aim to address the challenge. The four projects can be categorized into: (1) data systems for supporting interactive data exploration at scale, and (2) data systems that integrate automated machine learning (autoML) for model search and selection. The techniques used in these systems span disciplines, including database optimization, machine learning, and deep learning. However, the glue that ties these systems together is in their use and facilitation of human-in-the-loop data analysis.
 
Bio: Remco Chang is an Associate Professor in the Computer Science Department at Tufts University. He received his BA from Johns Hopkins University in 1997 in Computer Science and Economics, MSc from Brown University in 2000, and PhD in Computer Science from UNC Charlotte in 2009. Prior to his PhD, he worked for Boeing developing real-time flight tracking and visualization software, followed by a position at UNC Charlotte as a research scientist. His current research interests include visual analytics, information visualization, HCI, and databases. His research has been funded by the NSF, DARPA, the Walmart Foundation, Army, Navy, DHS, MIT Lincoln Lab, and Draper. He has had best paper, best poster, and honorable mention awards at InfoVis, VAST, CHI, and VDA. He is currently an associate editor for the ACM TiiS journal and the papers chair for the IEEE Visual Analytics conference (2018-2019). He received the NSF CAREER Award in 2015.

### Resources
http://dsail.csail.mit.edu/index.php/kyrix/  
https://www.cs.tufts.edu/~remco/


## Making the Black Box Effective: What Statistics Can Offer?

Colloquia 
Cray Distinguished Speaker Series 
February 3, 2020 - 11:15am to 12:15pm 
Emmanuel Candes 
Affiliation:  
Stanford 
Location:  
3-180 KH 
Host:  
Joe Konstan 
Abstract: The ongoing data science revolution has been driven by impressive technological advances in the capture, storage, and processing of data, across a wide range of domains. Of particular interest is the recent progress in machine learning which provides us with many potentially effective tools to learn from datasets of ever increasing sizes and make useful predictions. For instance, this year, the Turing Award recognizes the impressive empirical success of deep learning models. Some of these tools have proven to be powerful and extremely complex at the same time. While many scientists and engineers are, for good reasons, slowly getting comfortable with the idea of using models that are extremely difficult to interpret — black boxes if you will — two things cannot be compromised upon. The first is the reproducibility of scientific results. If I use a black box to determine which genomic regions influence a trait, e.g. the susceptibility to autism, how do I make sure that my findings can be reproduced in follow-up studies?  How do I make sure they are robust and will not be rapidly dismissed? The second concerns the validity of predictions. As we are increasingly turning to machine learning systems to support human decisions, how do we determine their validity? If a learning algorithm predicts the GPA of a prospective college applicant, what guarantees do I have concerning the accuracy of this prediction? In this talk, we will review recent progress in statistics which addresses these concerns. I will present broad methodologies that can be wrapped around any black box as to produce results that can be trusted. I will do my best to highlight the level of creativity underpinning these methodologies.  

Bio: Candes is the Barnum-Simons Chair in Mathematics and Statistics, and Professor of Electrical Engineering (by courtesy) at Stanford University. He graduated from the Ecole Polytechnique in 1993 with a degree in science and engineering, and received his Ph.D. in Statistics from Stanford University in 1998.
Candes is very grateful for the awards he has received over the years. These include the 2006 Alan T. Waterman Award from NSF, which recognizes the achievements of early-career scientists; the George Polya Prize awarded by the Society of Industrial and Applied Mathematics (SIAM) (2010), the AMS-SIAM George David Birkhoff Prize in Applied Mathematics (2015), the Prix Pierre Simon de Laplace from the Société Française de Statistique (2016), the Ralph E. Kleinman Prize from SIAM (2017). He was selected as the Wald Memorial Lecturer by the Institute of Mathematical Statistics (2017). He is a member of the National Academy of Sciences (elected in 2014) and the American Academy of Arts and Sciences (elected in 2014). In 2017, He received a MacArthur Fellowship popularly known as the ‘genius award’.  
 
Candes’ work lies at the interface of mathematics, statistics, information theory, signal processing and scientific computing, and is about finding new ways of representing information and extracting information from complex data. For example, he helped launch the field known as compressed sensing, which has led to advances in the efficiency and accuracy of data collection and analysis, and can be used to significantly speed up MRI scanning times. In the last ten years, he has developed statistical techniques to address the reproducibility of scientific results and the validity of predictions made by very complex machine learning systems. 

### Resources
http://statweb.stanford.edu/~candes/
https://statweb.stanford.edu/~candes/publications/
https://statweb.stanford.edu/~candes/software/
