Data set name: PMST Monsang

Data set developer(s): Linda Konnerth, Sandra Auderset

Data sheet author(s): Linda Konnerth, Sandra Auderset

Others who contributed to this data set: Koninglee Wanglar


# Motivation

**For what purpose was the dataset created?**

This data set was created to investigate the dynamics of person forms in Monsang and other South-Central Trans-Himalayan languages.
Further background and motivation can be found in X (JOHD paper).

**Who created the data set (for example, which team, research group) and on behalf of which entity (for example, company, institution, organization)?**

The data set was created by a team of researchers at the Department of Linguistics at the University of Bern (PI Linda Konnerth) in collaboration with local linguists and language experts in Northeast India.

**Who funded the creation of the data set?**

This work is funded SNSF (Swiss National Science Foundation) Grant 10.000.946 to Linda Konnerth at the University of Bern.


# Composition

Paralex datasets document paradigms of inflected forms.

**Are forms given as orthographic, phonetic, and or phonemic sequences ?** 

Forms are provided as orthographic and phonemic sequences.
The orthography is either the practical one used by the community or a version of the IPA used by linguists and language experts.
For Monsang, it is an IPA version used by linguists and language experts.

**How many instances are there in total?**

-   Number of inflected forms: 338

-   Number of unique inflected forms: 195

-   Number of unique scenarios (person, number, TAM, polarity combinations): 163

-   Number of inflected forms per paradigm and subparadigm:

    +----------+----+----------------+----+
    | Paradigm | n  | Tags           | n  |
    +==========+===:+================+===:+
    | Pronouns | 16 | default        | 3  |
    |          |    |                |    |
    |          |    | unspec.var     | 13 |
    +----------+----+----------------+----+
    | NFUT.AFF | 88 | default        | 87 |
    |          |    |                |    |
    |          |    | pragm.m        |  1 |
    +----------+----+----------------+----+
    | NFUT.NEG | 75 | default        | 73 |
    +----------+----+----------------+----+
    | FUT.AFF  | 86 | default        | 70 |
    |          |    |                |    |
    |          |    | pragm.m        | 10 |
    |          |    |                |    |
    |          |    | emph           |  3 |
    |          |    |                |    |
    |          |    | hort           |  3 |
    +----------+----+----------------+----+
    | FUT.NEG  | 73 | default        | 72 |
    +----------+----+----------------+----+

**Language varieties**

-   BCP-47 language tag: NA
-   Glottocode: mons1234
-   Language variety description: The autonym of Monsang (both as a designation of the community and the language) is Sirti. The language is spoken by 2,000 people in six villages located in Chandel District, Manipur, Northeast India. Monsang is closely related, and to some degree mutually intelligible with, Moyon. Monsang belongs to the Northwestern subbranch of South Central Trans-Himalayan.

**Does the data pertain to specific dialects, geographical locations, genre, etc ?**
The data in this data set come primarily represent the language as spoken in Liwachangning village, Chandel District, Manipur.

**Does the dataset contain all possible instances or is it a sample (not necessarily random) of instances from a larger set?** 
By providing 4 types of (in/)transitive paradigms, the dataset aims to include all person marking morphemes found in the language, both verbal indexes and pronouns. Hortative forms were not included in the dataset (see below for explanation).

**Is any information missing from individual instances?** 
In the intransitive and transitive future affirmative paradigms, there are gaps for scenarios with an inclusive S/A argument. In these cases, hortative forms are used instead.

**Are there any errors, sources of noise, or redundancies in the dataset?** 
No.

**Is the dataset self-contained, or does it link to or otherwise rely on external resources (for example, websites, tweets, other datasets)?** 
The dataset is self-contained.

**If linking to vocabularies from other databases (such as databases of features, cells, sounds, languages, or online dictionnaries), were there any complex decisions in the matching of entries from this dataset to those of the vocabularies (eg. inexact language code) ?**
NA

**Does the dataset contain data that might be considered confidential (for example, data that is protected by legal privilege or by doctor-patient confidentiality, data that includes the content of individuals' non-public communications)?**
The dataset pertains to small or indigenous language communities, namely those of the Monsang people in Manipur.
The data are published here with the consent of the community.

**Any other comments?**
NA

# Collection process.

**What is provenance for each table (lexemes, cells, forms, frequencies, sounds, features), as well as for segmentation marks if any ? Are any information derived from other datasets ?** 
The data comes from fieldwork conducted by Linda Konnerth. Specific forms were taken from a combination of a text corpus, elicitation, and field notes. This work also forms the basis for the segmentation. 

**How were paradigms separated (eg. in the case of homonyms or variants)? What theoretical or practical choices were made?**
Design principles and theoretical choices implemented for this data set are explained in "Paper in JOHD".

**How was the paradigm structure (set and labels of paradigm cells) decided? What theoretical or practical choices were made?**
Design principles and theoretical choices implemented for this data set are explained in "Paper in JOHD".

**What is the expertise of the contributors with the documented language ?** 
Linda Konnerth: linguist specializing in South-Central Trans-Himalayan, currently working on a grammar of Monsang
Koninglee Wanglar: native speaker and linguist

**Who was involved in the data collection process (for example, students, crowdworkers, contractors) and how were they compensated (for example, how much were crowdworkers paid)?**
Only the contributors listed at the beginning of this file.

**Over what timeframe was the data collected?** 
The data was collected between 2015 and 2025.


# Preprocessing/cleaning/labeling.

**How were the inflected forms obtained ?**
All forms were collected from speakers. See above.

**How were the phonological or phonemic transcriptions obtained?** 
The phonological transcriptions were generated with the qlcData package in R using an orthography profile that maps graphemes to IPA.
The mappings are based on the phonological analysis of the language.

**If relevant, how were the forms segmented?**
Manually based on expert knowledge.

**Was any preprocessing/cleaning/labeling of the data done (for example, discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values, cleaning of labels, mapping between vocabularies, etc)?** 
No.

**Was the "raw" data saved in addition to the preprocessed/cleaned/labeled data (for example, to support unanticipated future uses)?**
Yes (not publicly available yet).

**Is the software that was used to preprocess/clean/label the data available?** 
The data was prepared for Paralex with the open source software R using RStudio.


# Uses

**Has the dataset been used for any published work already?** 
No.

**What (other) tasks could the dataset be used for?**
It can be used for descriptive and comparative analyses.

**Are there tasks for which the dataset should not be used?**
No.


# Distribution.

**Will the dataset be distributed to third parties outside of the entity (for example, company, institution, organization) on behalf of which the dataset was created?**
No.

**How will the dataset be distributed (for example, tarball on website, API, GitHub)?** 
The dataset is available on GitHub at X and on Zenodo as part of the Paralex collection at X.

**Will the dataset be distributed under a copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?** 
The dataset is distributed under a CC-BY-SA 4.0 license.


# Maintenance

**If others want to extend/augment/build on/contribute to the dataset, is there a mechanism for them to do so?** 
For suggestions or error reports please open an issue on GitHub.
