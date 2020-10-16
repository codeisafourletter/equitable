# equitable
Equitable - An Exploratory Deep Dive into Bias and Bylaws

Data is often stored in formats which are not ideal for analysis. Extracting usable data from pdf files, specifically scanned pdf files, can pose a frustrating and time-consuming problem. OCR is an amazing technology which can help to solve this problem; however, it also has its own pain points. Often you will wind up with unwanted artifacts where the software has converted a mark or smudge from the scanned image into ASCII characters. The goal of this project is to code a simple method to take scanned PDF files, convert to txt OCR, scrub the artifacts, clean up the formatting and then generate “true” digital pdfs, which can easily incorporated into one's workflow and for further analysis and characterization. 

My sample dataset will be from public land records, specifically the bylaws and Covenants, Conditions, & Restrictions from various local "common interest" development projects formed in the 1950’s & 1960’s. 

I will be using [ABBYY Cloud OCR SDK](https://www.ocrsdk.com/) for the initial processing of the image files. 
