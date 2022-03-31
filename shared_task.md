---
layout: main
title: Shared Task
order: 3
collection: pages_2022
permalink: /sharedtask
---


# Overview:
The CreativeSumm 2022 shared task is divided into four sub-tasks, namely:

- summarization of chapters from novels
- summarization of movie scripts
- summarization of primetime television transcripts
- summarization of daytime, “soap opera” transcripts

The training data for each sub-task comes from existing, well-established datasets, but for 3 of 4 datasets we will provide new, unseen test inputs for evaluation (see below).
<br>
# Corpora

## Novel Chapters/BookSum (Ladhak et al., 2020; Kryściński et al., 2021)
This dataset pairs chapters of novels released as part of Project Gutenberg with corresponding summaries. For this shared task, we provide the novel chapters here (add link to new repo for this workshop). We unfortunately cannot provide the summaries, as the study guide websites are copyrighted. The provided data, however, for each novel chapter, does have a link to the page where the summary text may be found.

Please see the associated papers Ladhak et al 2020 and Kryściński et al 2021 for more information on how they collected the summaries.

For the novel chapter summarization task, please do not use the test splits (of either NovelChapter or BookSum) for either training or development. We will use the test set of BookSum as part of the final evaluation. We may or may not provide new, unseen test inputs for the final evaluation as well.

## Scriptbase (Gorinski & Lapata, 2015)
This dataset pairs movie transcripts with their corresponding Wikipedia summaries. The data may be downloaded from here. See the main repository for additional information.
SummScreen, Forever Dreaming (Chen et al., 2022)
This dataset pairs TV transcripts from primetime shows with their corresponding Wikipedia summaries. The data may be downloaded from the shared task repository.

## SummScreen, TV Megasite (Chen et al., 2022)
This dataset pairs soap opera transcripts with summaries written by TV Megasite contributors. The data may be downloaded from the shared task repository.

# Evaluation
Submitted summaries will be evaluated using standard automatic evaluation metrics, including ROUGE, METEOR, and pretrained automatic metrics.

# Important Dates:
All deadlines are 11.59 pm UTC -12h (“anywhere on Earth”).

- Training data released: Mar 31, 2022
- Deadline for Registration: Jul 1, 2022
- Blind Test Set Release: Jul 5, 2022
- System Summaries Due: Jul 12, 2022
- Shared Task Paper Submission: Aug 1, 2022
- Shared Task Paper Camera-Ready submission: September 5, 2022 
- Workshop Date: Oct 16th or 17th (TBD)

# Contact
Divyansh Agarwal, divyansh.agarwal@salesforce.com <br>
Bryan Li, bryanli@seas.upenn.edu  <br>
Sam Wiseman, swiseman@cs.duke.edu

# References
Mingda Chen, Zewei Chu, Sam Wiseman, Kevin Gimpel. 2022. SummScreen: A Dataset for Abstractive Screenplay Summarization. In ACL.

Philip John Gorinski, Mirella Lapata. 2015. Movie Script Summarization as Graph-based Scene Extraction. In NAACL.

Wojciech Kryściński, Nazneen Rajani, Divyansh Agarwal, Caiming Xiong, Dragomir Radev. 2021. BookSum: A Collection of Datasets for Long-form Narrative Summarization. 

Faisal Ladhak, Bryan Li, Yaser Al-Onaizan, Kathlen McKeown. 2020. Exploring Content Selection in Summarization of Novel Chapters. In ACL.

{: .two-column}