#====================================================================
# README file for the data set: The Choice of Aspect in the Russian Modal Construction with prixodit'sja/prijtis'_Questionnaire
#====================================================================

#====================== General information =========================

This data set contains the replication data for an experiment conducted with Russian native speakers 
on the choice of aspect in the modal construction prixodit'sja/prijtis' delat'/sdelat' šag/vid/vybor, 'have to take a step/pretend/make a choice'.
The experiment consists of a questionnaire made up of 17 examples taken from the Russian National Corpus that include the construction with one of the three direct objects selected
(see file: 05_Text_Questionnaire.pdf).
Each example was submitted two times: one with the original aspect and one with the other one.
Respondents had to evaluate the acceptability of the infinitive delat'/sdelat' in both examples on a scale from 1 to 3:
 1 = Nevozmožno, 'Impossible'
 2 = Dopustimo, 'Acceptable'
 3 = Otlično, 'Excellent'

Respondents could also comment on their choice at the end of each example.
One hundred and ten participants completed the survey (see file: 06_Answers_Questionnaire.pdf).

#========================Answers and annotation======================

Answers were included into a seven-columns table and annotated for four variables (see Database_Questionnaire.csv; 08_Database_Questionnaire.pdf; 09_Database_Questionnaire.txt).
Here we report all the variables and their values with a brief explanation.

ANSWER: answer to each question that evaluated the acceptability of the aspect of the infinitive delat'(imperfective)/sdelat'(perfective). 
Values: N = Nevozmožno'Impossible', D = Dopustimo 'Acceptable' O = Otlično'Excellent'.

PERSONID: each answer was given an ID that could individuate a single participant. This factor will be the random variable in the statistical model.
Values: A, AA, AB, ..., DD.

MATCHOR, Matches original: whether the aspect in the example matched with the original version form the corpus.
Values: YES = matches the original, NO = doesn't match the original.

ASPPRI, Aspect of prixodit'sja/prijtis': whether the modal verb in the example was imperfective (prixodit'sja) or perfective (prijtis').
Values: IPF = imperfective, PF = perfective.

DO, Direct Object: which was the direct object in the example.
Values: S = šag'step', V = vid 'pretend', VB = vybor 'choice'.






