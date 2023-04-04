# Hindi Politeness Datasets

This repository contains datasets, models, code and other resources that have been produced out of research on politeness in Hindi. The folder structure and their contents are as given below -

## v0.1

This directory contains the dataset used for training and testing the system described in the PhD thesis by [Ritesh Kumar](https://www.ctrans.in/research/clresearch), titled ["Politeness in Online Hindi Texts: Pragmatic and Computational Aspects"](http://sanskrit.jnu.ac.in/port/thesis/ritesh-thesis.pdf), submitted in 2014 under the supervision of [Prof. Ayesha Kidwai](https://www.jnu.ac.in/content/ayesha) and [Prof. Girish Nath Jha](https://www.jnu.ac.in/content/girishjha) at Jawaharlal Nehru University, New Delhi. A demo of the tool developed is available here - [Politeness Recognition Tool PoRT](http://sanskrit.jnu.ac.in/port/index.jsp)

The code and model trained for this system will soon be released as well.

### Data Structure

The train, dev and test data in this directory are in tab-separated format whereby the first column is the unique ID, the second column is the label given to the text and the third column is the text itself. This dataset is annotated using four classes - Neutral (neu), Polite (plt), Politic (ptc) and Impolite (imp). The details of the dataset are available in the above-mentioned thesis and in the [LREC 2014 paper](https://aclanthology.org/L14-1480/).


## v0.2

This directory contains an extension of the above-mentioned dataset with new data from different social media platforms being added to the older dataset. Moreover it is now annotated with three top-level classes - Neutral, Polite and Impolite (with politic and polite being merged into one class) - and a rich annotation of different kinds of structures viz honorific verb forms, honorific pronouns, subjunctive, passive, deontics, etc. This dataset forms the basis of the findings discussed in an upcoming book titled "Politeness in Hindi" to be published by Routledge (currently under review) and has been developed in association with the [UnReaL-TecE LLP](http://unreal-tece.co.in/).

### Data Structure

The train, dev and test data in this are in comma-separated format whereby the first column is the unique ID, the second column is the text, the third column is the top-level label given to the text and the rest of the columns gives a binary value to each of the different grammatical features being marked in the dataset, depending on whether they are present in the given text or not.


## Citation

If you are using the v0.1 dataset then you may cite either the thesis or the LREC 2014 paper or both -

Thesis Citation

    @phdthesis{kumar_politeness_2014,
        address = "New Delhi",
        title = "Politeness in "Online" "Hindi" "Texts": "Pragmatic" and "Computational" "Aspects"",
        url = "http://sanskrit.jnu.ac.in/port/thesis/ritesh-thesis.pdf",
        school = "Jawaharlal Nehru University",
        author = "Kumar, Ritesh",
        year = "2014",
    }   

LREC 2014 Paper Citation

    @inproceedings{kumar-2014-developing,
        title = "Developing Politeness Annotated Corpus of {H}indi Blogs",
        author = "Kumar, Ritesh",
        booktitle = "Proceedings of the Ninth International Conference on Language Resources and Evaluation ({LREC}'14)",
        month = may,
        year = "2014",
        address = "Reykjavik, Iceland",
        publisher = "European Language Resources Association (ELRA)",
        url = "http://www.lrec-conf.org/proceedings/lrec2014/pdf/594_Paper.pdf",
        pages = "1275--1280",
    }

## Acknowledgments

Thanks to Deepak, Atul and everyone else who helped in annotation of the v0.1 dataset.

Also thanks to Shyam, Siddharth, Sonal and Yogesh for annotating the parts of v0.2 of the dataset.

## Contact

For any queries / suggestions / offer for collaboration, you may contact ritesh78_llh@jnu.ac.in
