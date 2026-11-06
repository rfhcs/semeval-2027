# CSCI-LING 5832 - NLP - git commit [SemEval 2027](https://semeval.github.io/SemEval2027/tasks.html)

For this course, we will be completing subtasks A and B. Note: Due to the nature of the dataset as well as the guidelines of this specific task, the dataset will not be uploaded into this repository. Please reach out to team members for any further questions or inquires.

## [Task 8: StereoQueerEval: Identification of Stereotypes and Hate Speech Targeting the LGBTQIA+ Community](https://stereoqueereval.github.io/#about)

## Task Description

Participants are asked to classify a YouTube user’s comment using the corresponding video title and description as contextual information. The challenge is organized into three subtasks:

- Subtask (A) Stereotype Detection: A binary classification task checking whether the comment contains a stereotype about LGBTQIA+ people.
- Subtask (B) Hate Speech Classification: A multiclass classification task distinguishing whether the comment expresses (i) explicit hate, (ii) implicit hate, or (iii) non-hateful or supportive content toward LGBTQIA+ individuals.
- Subtask (C) Target & Identity Identification: A multilabel, multiclass task that, for hateful comments only, identifies both the target type (individual or group) and any specific LGBTQIA+ identities referenced in the comment.

The task covers 4 languages across different cultural and geographical contexts:

- English: A high-resource global lingua franca with broad online coverage, enabling comparisons with many existing NLP benchmarks.
- Italian: A Romance mid‑resource language that extends earlier work and offers continuity within European research on LGBTQIA+ hate speech.
- Dutch: A mid‑resource Germanic language underrepresented in queer-focused NLP, providing Northern/Western European perspectives.
- Persian: A low‑resource Indo‑Iranian language that introduces culturally distinct patterns of discourse rarely covered in queer research. Note that the Persian data will be released for testing only.

## How to participate

If you would like to take part in the Identification of Stereotypes and Hate Speech Targeting the LGBTQIA+ Community (StereoQueerEval) at SemEval 2027 shared task and obtain the data:

- [x] Please complete the Data Usage Agreement. You will be added to the Google Group within 24 hours and will receive the password for the data ZIP archive.
- [x] Download the data from GitHub, together with the guidelines.
- [ ] Submit your runs on Codabench (available starting from October).
- [ ] Write the technical report that should include a brief description of your approach, focusing on the adopted algorithms, models and resources, a summary of your experiments, and an analysis of the obtained results.

## Terms of Use for this task's dataset

Terms of Use
By accessing or using this dataset, you agree to the following terms.

1. Permitted Use
   This dataset may be used only for academic, non-commercial research, and solely for participation in the StereoQueerEval shared task or directly related research.

2. No Redistribution
   You may not share, publish, or redistribute the raw dataset, or any substantial portion of it, to third parties in any form. This includes, but is not limited to, public repositories, websites, and supplementary materials.

3. No Commercial Use
   You may not use the dataset, or any derivative of it, for commercial purposes of any kind.

4. Retention
   You may keep the dataset after the shared task concludes for ongoing non-commercial research, provided you continue to comply with all other terms listed here.

5. Ethical Use
   This dataset contains content related to LGBTQ+ communities and stereotypes. Please handle it with care and respect. You may not use the dataset, any outputs derived from it, or any models trained on it in ways that could target, harm, discriminate against, or demean LGBTQ+ individuals or communities.

# Further Rules on data use, tools and resources

2.1 May we send data to commercial LLM APIs?
Yes. This case is not covered by term 2 of the agreement. That said, we encourage the use of open-source models over commercial ones.

2.2 May we use a private rented cloud GPU for fine-tuning?
Yes, provided that only people who have signed the agreement can access the machine and that the data is deleted from it when your participation ends.

2.3 Are pretrained encoders and open-weight LLMs allowed?
Yes, when run on your own hardware. Please name the models in your system description paper.

2.4 Are there restrictions on using LLMs for prompting, fine-tuning or synthetic data generation?
No, there are no restrictions. Please report the models, versions and prompts used, and confirm that no test instances were used.

2.5 May we use external datasets or unlabeled data?
Yes. All publicly available labeled and unlabeled data may be used for training, pre-fine-tuning or continued pre-training, as long as they do not overlap with the test data. Please cite all resources in your system paper.

2.6 May we use the gold labels from other subtasks (e.g. stereotype and target labels) as auxiliary training targets?
Yes. Training labels from all subtasks may be used as auxiliary targets. We place no restrictions on what you decide to use.

2.7 May the 100 Persian development examples be used for training?
Yes. They were released so participants could see what the data looks like, and using them for training is not restricted.

2.8 May team members share the data with each other?
Yes, between people who have each signed the agreement, and with no one else. A colleague who has not signed must sign before getting access.
