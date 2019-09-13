---
layout: default
---

## Experience 
---

### **Speech Emotion Recognition in Dialogues | NTU, Singapore**

*August 2019 - Present*

I am working as a research intern at the **Speech and Language Processing Group** under [Prof. Chng Eng-Siong](https://www.ntu.edu.sg/home/aseschng/). I am working on creating dialogue centric models to detect emotion from speech and text. I am currently experimeting with convolutional RNNs and plan to use a GCN model as well. Evaluation is being done on the IEMOCAP dataset.

---

### **Query AutoCompletion for Unseen Prefixes | Universität Hamburg, Hamburg**

*May 2019 - July 2019*

I worked at [Language Technology Lab](https://www.inf.uni-hamburg.de/en/inst/ab/lt/home.html) under [Prof. Chris Biemann](https://www.inf.uni-hamburg.de/en/inst/ab/lt/people/chris-biemann.html). I worked on a hybrid charcter+word level neural language model for generating completed queries for unseen prefixes. I experimented with the recently developed contextualized word embeddings such as BERT, Flair, ELMo as well as a combination of Fasttext and sent2vec, to capture the context of the query and provide better suggestions. I also used beam search for the query generation task and LambdaMART for re-ranking the suggestions. The model was able to beat the previous state-of-the-art by an increase of 2.2% in the MRR score on the AOL search log dataset.

---

### **BioJS Website | Google Summer of Code**

*May 2018 - August 2018*

I led the development of a new [website for BioJS](biojs.net), a library of over hundred JavaScript components that enables one to visualize and process data using current web technologies. The backend stack used Django and frontend used VueJS. Timely database updates are facilitated from Github and the npm-registry.

---

### **UAV Flight Planner with Shadow Exclusion | IIRS, ISRO**

*May 2018 - July 2018*

I worked at [Indian Institute of Remote Sensing](http://www.iirs.gov.in/), [Indian Space Research 
Organization (**ISRO**)](http://www.isro.gov.in/) in the summer of 2018. I was working in the project 
titled "*UAV Flight Planner with Shadow Exclusion*". The project involved the creation of an application that would automatically generate equally distant coordinates for capturing images by the **UAV for altitude varying terrain**, along with minimising the area covered that suffers from a shadow layer.

The main problem was that the UAV did not have on-board processors, and hence, I had to devise a way by which areas under a shadow could be identified beforehand. I took the advantage of the area of interest being mountaineous. I used **Bresenhamm's line drawing algorithm** to trace a ray from the ground point immediately below the UAV to the position of the sun at which the readings will be taken. I extracted height data from HGT files and using a raster map with height values below the ray formed, I checked if the graph value at a coordinate was more than the ray's coordinate, a method similar to the one used in video games to generate shadows. The idea worked. This project gave me the inspiration to face problems with novel, off-the-track ideas.  

---

## Projects

---
 
### **Toy Compiler | Mentor: [Dr. Vandana Agarwal](https://universe.bits-pilani.ac.in/pilani/vandana/profile)**

*January 2019 - April 2019*

Developed a small compiler for a dummy language in the C language, as a part of partial fulfilment of the course **Compiler Construction**. Different modules of the compiler included **lexer**, **parser** in the front-end and **AST generator**, **semantic analyzer**, **type checker** and **assembly code generator** in the backend.

---

### **Visual Question Answering | Mentor: [Dr. Dhiraj Sangwan](https://www.ceeri.res.in/profiles/dhiraj-sangwan/)**

*June 2018 - December 2018*

Created a model for visual question answering on the VQA dataset. Used **pre-trained VGG16** weights to extract image features and a **stacked LSTM** architecture for extracting question features. Used **multimodal low rank bilinear pooling** to combine both the feature matrices.

---
<!--
### **Distance Iris Recognition | Mentor: [Dr. Kamlesh Tiwari](http://www.bits-pilani.ac.in/pilani/kamleshtiwari/profile)**

*January 2017 - May 2017*

Iris Recognition is a well worked on the problem of recognizing people based on
biometric iris data. We worked on a solution for Iris Recognition on 
Distance images (low-quality Iris), using the CASIA Distance Dataset.

The model proposed performs well, with correct recognition rates of over
85%, with just preliminary filtering and enhancing 
of the low-quality Iris from the distance images. Gabor filters have been used for matching, after extracting the iris data after segmentation.

Future work will involve clearing the database of blurry images of varying
degrees and matching using both the eyes' iris, instead of the currently
used one-eye matching to further enhance the matching accuracy.

---

### **Ad Effectiveness and their Impact on Sales | Mentor: [Dr. Sangeeta Sharma](http://www.bits-pilani.ac.in/pilani/sang/profile)**

*January 2017 - May 2017*

I was working on correlating Sales with Advertisements to measure the effectiveness of Ads on Sales. 

I used NLP tools on Google Trends as well as consumer sales data correlate the Ads with Sales. 
The Sales data was obtained courtesy [Govt. of India](http://data.gov.in/). 
I also used YouTube comments on Ads to correlate sentiments with the particular Ad to show how more emotional ads have a stronger impact on sales.

---

### Mini Projects

* **PSO Optimized K-Means**: Studied and implemented Particle Swarm Optimization to improve clustering performance of K-Means Clustering Algorithm

* **Heading Generation using Speech Phonetics**: Created a crawler to obtain clean speech audio and generated a summary and its heading using phonetics and tone of the speaker

* **Parallel branch and bound**: Implemented a parallel skeleton for branch and bound to solve NP-Hard problems on a cluster of workstations. 

* **Compiler for ERPLAG**: Created a compiler in C for a dummy language as part of Compiler course. Implemented the parser and code generator.

* **Network Packet Sniffer**: Created a network packet sniffer to mimic the functions of Wireshark to sniff packets and display an analysis of packets being transmitted on the network.

* **One Class Classification**: Used Extreme Learning Machines to solve the problem of Outlier Detection using One Class Classification for Sensor Data.

---

## Competitions

---

### **APOGEE MapMyIndia Hackathon | BITS, Pilani**

*April 2017*

Was part of team *TrippyMinds*, which came **1st** in a Machine Learning hackathon 
organized by [MapMyIndia](www.mapmyindia.com/) on [Kaggle](https://inclass.kaggle.com/c/mapmyindia2), a famous platform for Machine Learning Contests, for APOGEE, the technical fest of BITS Pilani.

The problem consisted of solving the problem of detecting the speed limits 
of roads from street signs captured in images taken on the highways of India. Our approach consisted of an ensemble of custom trained 
HaarCascade Classifiers running under an ensemble of simple CNN to 
classify the extracted bounding boxes.

---

### **DECode Hackathon | HackerEarth**

*October 2017*

Participated and came **3rd** in a Machine Learning hackathon 
organized by D.E. Shaw on [HackerEarth](https://www.hackerearth.com/challenge/competitive/de-shaw-de-code/), a famous platform for Machine Learning and Competitive Coding Contests. 

The problem was to predict the Chances of Investment for different users for the Month of July using the data for investments from those users for January to June. I used XgBoost after feature engineering.

---

### **e-Yantra | Indian Institute of Technology, Bombay**

*March 18th and 19th 2016*

[e-Yantra](http://portal.e-yantra.org/) is an initiative to spread education in Embedded systems and Robotics
by [IIT Bombay](http://www.iitb.ac.in/). It is sponsored by the Ministry of Human Resource Development, 
Government of India. It is a group competition where students in a team of 4 
programs a given robotic platform to solve a given problem in 12-15 weeks.

The competition consisted of programming a FireBird-5 bot to solve a given problem
statement. I was a part of a team of four and after 3 months of coding the bot, 
we were selected for the finals of e-Yantra out of around 500 teams. 

We came **2nd** in our theme of "Hotel Room Service" out of 57 teams from all 
over India in the finals which were held on 18th and 19th March 2016, at the 
IIT Bombay Campus.

---

### Other Achievements

* **National Finalist** in Microsoft's [Build The Shield](https://buildtheshield.microsoft.com/india/), a Capture-The-Flag competition 2016.
* Awarded the "*Shri Ratan Lal Lahoti Memorial Award*" for being the **Board Topper** in Chemistry (100/100), [CBSE](http://cbse.nic.in/) Board Examination, 2014.
* Awarded the "*Shri Dharamveer Gajra Memorial Award*" for being the **School Topper** in Computer Science (99/100), CBSE Board Examination, 2014.
* Junior Science Talent Search (JSTS) Scholar - Department of Science, Directorate of Education.
* Secured **All India Rank** (AIR) - **1574** in *IIT-JEE* 2014.
* Awarded the INSPIRE Scholarship for being the top 1% of students in the CBSE Board Examination, 2014.
* Awarded the Institute Merit Scholarship for Semester 1 and 2 at BITS Pilani for excellence in Academics.

--- -->
