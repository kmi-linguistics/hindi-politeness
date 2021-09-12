# Hindi Politeness Datasets

This repository contains datasets that have been used for research on politeness in Hindi. THe folder structure and their contents are as given below -

## v0.1

This directory contains the dataset used for training and testing the system described in the PhD thesis by Ritesh Kumar, titled "Politeness in Online Hindi Texts: Pragmatic and Computational Aspects", submitted in 2014 under the supervision of Prof. Ayesha Kidwai and Prof. Girish Nath Jha at Jawaharlal Nehru University, New Delhi. A demo of the tool developed is available here - [Politeness Recognition Tool PoRT] (http://sanskrit.jnu.ac.in/port/index.jsp)

The code and model trained for this system will soon be released as well.

### Data Structure

The train, dev and test data in this are in tab-separated format whereby the first column is the unique code, the second column is the label given to the text and the third column is the text itself. This dataset is annotated using four classes - Neutral (neu), Polite (plt), Politic (ptc) and Impolite (imp). The details of the dataset are available in the above-mentioned thesis.


## v0.2

This directory contains an extension of the above-mentioned dataset with new data from different social media platforms being added to the older dataset. Moreover it is now annotated with three top-level classes - Neutral, Polite and Impolite (with politic and polite being merged into one class) - and a rich annotation of different kinds of structures viz honorific verb forms, honorific pronouns, subjunctive, passive, deontics, etc. This dataset forms the basis of the findings discussed in an upcoming book titled "Politeness in Hindi" (currently under review).

### Data Structure

The train, dev and test data in this are in comma-separated format whereby the first column is the unique code, the second column is the text, the third column is the top-level label given to the text and the rest of the columns gives a binary value to each of the different grammatical features being marked in the dataset, depending on whether they are present in the given text or not.
