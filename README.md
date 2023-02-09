# Classifying_emails-NLP-

# Overview

Bank BPIA (Banco Português de Inteligência Artificial) believes that AI has a great potential to transform organizations and challenge partners with the same mindset. A task force was born with the goal of researching techniques, methodologies and, in general, developing AI and advanced analytics projects.

Last week, the Bank proposed to the task force to study how AI can be used to identify the goal of Customers’ emails. This project aims to respond quickly and accurately to their questions and concerns. 

# Objective

In this Hackathon, you will try to classify emails from the customers! You will do this by analyzing the body of several emails, and trying to predict the class they belong to.

You will be given a dataset that includes: the date, language and body (“text”) of the emails in English only. The dataset was manually annotated by people with business knowledge. Each email has a label that corresponds to one of the 77 categories used by the Bank. These 77 categories have been grouped into 5 classes that link directly to specific Bank procedures. Mapping is provided in file mapping.csv.

This is a multi-class problem with unstructured data, we'll ask you to use a mean of all the per-class F1 scores (hint: there's a super easy way to do this with the libraries you already use). We suggest that you look and dedicate enough time to studying the data carefully. 

How much is enough???
What is your opinion on the way emails are linked to the final classes? An extra mark will be given to good insights on this issue.

# Evaluation criteria for your model
Hint: Much as poorly-written sentences, data can be misleading sometimes. Pay extra attention to this section so you don’t get misled by other optimistic measures.



## Evaluation Metric - F1-score. This metric is composed by a weighing of precision and recall, both of which you have used in this hackathon:

- TP: True Positive		
- FP: False Positives		 
- FN: False Negatives

- Precision (per class) = TPTP + FP 	
- Recall (per class) = TPTP + FN
- F1-score (per class) = 2 *Recall * PrecisionRecall + Precision

More specifically, we want you to focus on predicting the true sources, so we will be focusing on the f1-score of the true class:

- F1-scoretrue = 2 *Recalltrue * PrecisiontrueRecalltrue + Precisiontrue


