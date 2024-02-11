# Negative attitudinal function identification (WIP)
## Introduction
Ngeative attitudinal function identification is presented as a NLP task that goes beyond emotion detection and dialog act classification for the classification of attitudinal functions from text messages (Fernández-Martínez, 2024). Thus, this is a sequence classification task. Unlike emotion detection and dialog act classification, which focus on the identification of emotions and generic speech acts, respectively, this task encompasses the identification of expressions of different types of attitudinal phenomena: the expression of emotion, judgments, and appreciations. This task is linguistically grounded, in that it is based on insights from different linguistic frameworks: the communicative approach in foreign language teaching, speech act theory, and the appraisal framework in systemic functional linguistics.

Attitudinal functions are a subtype of communicative functions: the concept of communicative functions comes from the communicative approach in English as a Foreign Language (EFL) (Finocchiaro & Brumfit, 1983). A communicative function is defined as a communicative act or the use of linguistic utterances for a given purpose or intention, typically to express the speaker's attitude (Milanovic & Saville, 2012).

## Dataset
Due to the different taxonomies found in the literature, we decided to focus on the one presented by Blundel et al. (1982), a practical EFL coursebook that contains a wide range of attitudinal, informative, and active communicative functions. From this, we obtained a basic taxonomy of 18 negative attitudinal functions.

On the basis of this, we built a synthetic dataset of constructions. The dataset will be made publicly available in this repository.

## Evaluation
We developed several supervised approaches with the synthetic dataset and evaluated it with state-of-the-art emotion detection datasets of tweets (i.e. EmoEvent, GoEmotions, CARER, AIT) that were automatically mapped to the attitudinal function categories of our taxonomy. For details about the emotion detection datasets used, including the files themselves, we refer the readers to the original papers. 

The experiments that were carried out for each dataset, including each of the supervised approaches (Naïve Bayes, fine-tuning, semantic similarity through contextualized sentence embeddings, zero-shot classification through Natural Language Inference) will be made publicly available in this repository.

## Additional information
Further details about this task, dataset creation, mapping, experimental setup, evaluation, results, discussion, limitations, challenges, and future research dirctions can be found in the original paper in Fernández-Martínez (2024).

## Funding
Financial support for this research has been provided under grant PID2020-112827GB-I00, funded by the Spanish Ministry of Science and Innovation MCIN/AEI/10.13039/501100011033, and grant number 101017861[project SMARTLAGOON] funded by the European Union's Horizon 2020 research and innovation program

## References

- Blundell, Jon, Higgens, Jonathan, & Middlemiss, Nigel. (1982). *Function in English*. Oxford University Press.
- Fernández-Martínez, N.J. (2024). Introducing the NLP task of negative attitudinal function identification. Unpublished manuscript.
- Finocchiaro, M., & Brumfit, C. (1983). *The functional-notional approach: from theory to practice*. Oxford University Press.
- Milanovic, Michael, & Saville, Nick. (2012). The Theoretical Foundations for functions in the Council of Europe modern languages projects and the Common European Framework of Reference for languages. In *Language Functions Revisited*. Cambridge University Press. Retrieved from www.cambridge.org
