---
layout: default
---

## Experience 
---

### **Open Domain Question Answering by Jointly Using Text and Knowledge Base | NTU-NLP, NTU, Singapore**

*August 2020 - Present*

Working under [Dr. Shafiq Joty](https://raihanjoty.github.io/) in collaboration with Salesforce Research Asia on open domain question answering. Jointly leveraging wikipedia text passages and the wikidata knowledge base for enhanced answer generation, currently for the Natural Questions Dataset.

---

### **Contextual Dialogue Generation; SER; API Gateway | NTU, Singapore**

*August 2019 - December 2019*

I worked as a research intern at the **Multimedia and Interactive Computing Lab** under [Prof. Chng Eng-Siong](https://www.ntu.edu.sg/home/aseschng/). I developed an API Gateway that acts as a common interface for modules already developed by fellow researchers, such as SUD and summarization. I further developed a production ready lightweight CNN based model for emotion recognition from speech ([RAVDESS](https://zenodo.org/record/1188976#.Xfz4G9YzbRY) dataset) as a contribution to the API Gateway. Along with this, I had a small collaboration where I worked on diversifying dialogue generation models using a context based generator-discriminator architecture.

---

### **Query AutoCompletion for Unseen Prefixes | Universität Hamburg, Hamburg**

*May 2019 - July 2019*

I worked at [Language Technology Lab](https://www.inf.uni-hamburg.de/en/inst/ab/lt/home.html) under [Prof. Chris Biemann](https://www.inf.uni-hamburg.de/en/inst/ab/lt/people/chris-biemann.html), under the [DAAD-WISE](https://www.daad.de/deutschland/stipendium/datenbank/en/21148-scholarship-database/?daad=1&detail=50015295&origin=4&page=1&q=wise&status=1&subjectGrps=) scholarship programme. I worked on a hybrid charcter+word level neural language model for generating completed queries for unseen prefixes. I experimented with the recently developed contextualized word embeddings such as BERT, Flair, ELMo as well as a combination of Fasttext and sent2vec, to capture the context of the query and provide better suggestions. I also used beam search for the query generation task and LambdaMART for re-ranking the suggestions. The model was able to beat the previous state-of-the-art by an increase of 2.2% in the MRR score on the AOL search log dataset.

---

### **BioJS Website | Google Summer of Code**

*May 2018 - August 2018*

I led the development of a new [website for BioJS](http://biojs.net), a library of over hundred JavaScript components that enables one to visualize and process data using current web technologies. The backend stack used Django and frontend used VueJS. Timely database updates are facilitated from Github and the npm-registry.

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
 
### **VQA Models that can read text | Mentor: [Dr. Yashvardhan Sharma](https://www.bits-pilani.ac.in/pilani/yash/profile)**

*January 2020 - April 2020*

Did a study oriented project on the [TextVQA](https://textvqa.org/) task. Did literature review and studied various methods of multimodal attention and optical character recognition. Identified some drawbacks about the baseline OCR method and used basic heuristics to improve the same. A book chapter highlighting the findings as well as on other applications of multimodal deep learning is in submission.


---
 
### **Toy Compiler | Mentor: [Dr. Vandana Agarwal](https://universe.bits-pilani.ac.in/pilani/vandana/profile)**

*January 2019 - April 2019*

Developed a small compiler for a dummy language in the C language, as a part of partial fulfilment of the course **Compiler Construction**. Different modules of the compiler included **lexer**, **parser** in the front-end and **AST generator**, **semantic analyzer**, **type checker** and **assembly code generator** in the backend.

---

### **Visual Question Answering | Mentor: [Dr. Dhiraj Sangwan](https://www.ceeri.res.in/profiles/dhiraj-sangwan/)**

*August 2018 - November 2018*

Created a model for visual question answering on the VQA dataset. Used **pre-trained VGG16** weights to extract image features and a **stacked LSTM** architecture for extracting question features. Used **multimodal low rank bilinear pooling** to combine both the feature matrices.

---

### **Feedback-based Retrieval System with Sentence Ranking | Mentor: [Dr. Poonam Goyal](https://www.bits-pilani.ac.in/pilani/poonam/Profile)**

*October 2018 - November 2018*

Designed and implemented an efficient retrieval framework for text documents. Used **tf-idf** based scoring methods to rank documents and used the **BM25** algorithm to find the best match in a document. Monitored user clicks on documents and made future recommendations based on these clicks. 

---

### **Convolutional Neural Networks in Scala | Mentor: [Dr. Lavika Goyal](https://www.bits-pilani.ac.in/pilani/lavikagoel/profile)**

*October 2018 - November 2018*

Developed a two layer deep convolutional neural network in scala using purely **functional programming concepts**, as a part of partial fulfilment of the course **Principles of Programming Languages**.

---
