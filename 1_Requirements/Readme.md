# Requirements
                               Extractive Text Summarization
## Introduction
Text summarization is the process of distilling the most important information from a source to produce an abridged version for a particular user and task. Humans are generally quite good at this task as we have the capacity to understand the meaning of a text document and extract salient features to summarize the documents using our own words. However, automatic methods for text summarization are crucial in today’s world where there is an over-abundance of data and lack of manpower as well as time to interpret the data. 
![image](https://github.com/Subhashini2046/ResearchProduct/blob/ProductSdlc/1_Requirements/dasum.png)

## Research

The intention of text summarization is to express the content of a document in a condensed form that meets the needs of the user . For more information than can realistically be digested is available on the World-Wide Web and in other electronic forms. News information, biographical information, minutes of meetings missed -- it isn't possible to read everything one would want to read and so some form of information condensation is needed. Secondly, the language of news media may be impenetrable to some people -- for example, children or people learning English as a foreign language. Some method of language simplication would be useful, as well as a method of providing the background knowledge adults take for granted. A solution that addressed both of those problems would enable a wider range of people to be aware of a greater amount of information.
Usefull Links:
1. Arpita Sahoo,Dr.Ajit Kumar Nayak,“Review Paper on Extractive Text Summarization”,In International Journal of Engineering Research in Computer Science and Engineering,April 2018.
2. Mehdi Allahyari, Seyedamin Pouriyeh, Mehdi Assefi, Saeid Safaei, Elizabeth D. Trippe, Juan B. Gutierrez, Krys Kochut,“Text Summarization Techniques: A Brief Survey” In Computation and Language,July  2017.

## Cost and Features 
**Cost**
Since the system uses only open source software, it is free of cost.

**Feature**

1. Summarizing reduces perusing time
2. While investigating reports, outlines make the determination procedure simpler
3. Summarization improves the adequacy of ordering
4. Summarization calculations are less one-sided than human summarizers
5. Personalized summaries are useful in question-answering systems as they provide personalized information
6. Utilizing programmed or Summarization frameworks empower business theoretical administrations to build the number of content archives they can process

## Defining the System
![image](https://github.com/Subhashini2046/ResearchProduct/blob/ProductSdlc/1_Requirements/model.png)
## SWOT ANALYSIS
![image](https://github.com/Subhashini2046/ResearchProduct/blob/ProductSdlc/1_Requirements/SWOT.png)
# 4W&#39;s and 1&#39;H

## Who:

This system is helpful for all the people who want the summary for any Text document.

## What:

The Extractive text Summarization System summarizes the text of any document.

## When:
 With the growing amount of data in the world, interest in the field of automatic summarization generation has been widely increasing so as to reducing the manual effort of a person working on it. In this fast-paced life, everyone wants shorthand information to save time.

## Where:

Used by any user who wants the information in a short text.

## How:

The user can directly open the web application and can enter the text. Once the text is entered, the user is required to hit the summarize button to get the final summary.

# Detail requirements
## High Level Requirements:
|      ID          |Description                          |Status                         |
|----------------|-------------------------------|-----------------------------|
|HR_01|Data Pre-processing |Implemented|
|HR_02| Feature Extraction |Implemented|
|HR_03|RBM Calcuation|Implemented|
|HR_04| Create Summary of English Text |Implemented|
|HR_05|Result Evaluation |Implemented|
|HR_06| Other Language Text Summary|Future|
|HR_06| Deep learning model|Future|




##  Low level Requirements:
|      ID          |Description                          |  HLR_ID  |Status               |
|----------------|-------------------------------|----------|-----------------------------|
|LR_01|Sentence Segmentation|HR_01|Implemented|
|LR_02|Tokenization|HR_01|Implemented|
|LR_03|Stop words and Panctuation|HR_01|Implemented|
|LR_04|TF-IDF|HR_02|Implemented|
|LR_05|Thematic words|HR_02|Implemented|
|LR_06|Nuber of numericals|HR_02|Implemented|
|LR_07|Centroid Similarity|HR_02|Implemented|
|LR_08|Feature Matrix|HR_02|Implemented|
|LR_09|Feature Matrix Enhancement|HR_02|Implemented|
|LR_10|Precision|HR_05|Implemented|
|LR_11|Recall|HR_05|Implemented|
|LR_12|F-measure|HR_05|Implemented|



