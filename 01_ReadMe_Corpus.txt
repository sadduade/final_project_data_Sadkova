#====================================================================
# README file for the data set: The Choice of Aspect in the Russian Modal Construction with prixodit'sja/prijtis'_Corpus
#====================================================================

#====================== General information =========================
This data set contains the replication data for a corpus study on the construction prijtis' delat'/sdelat'.
The database contains 447 examples with prijtis' delat'/sdelat' taken from the Russian National Corpus and that are dated no earlier than 1950.
Each example was annotated for several factors. Some CART models were then run on the database in order to verify if the choice of aspect in the infinitive (delat'/sdelat') 
was determined by any of those contextual factors.

#====================== Annotation ==================================
The whole database is available in the file Database_Corpus.csv. 
Examples are provided in three columns and are annotated for eight factors.

LEFT_CONTEXT: context to the left of the main modal verb prijtis' in each example.

MODAL_VERB: main modal verb of the construction (prijtis') in the past (prišlos') or non-past (pridetsja) forms.

RIGHT_CONTEXT: context to the right of the main modal verb prijtis' in each example.

ASPINF, Aspect of the infinitive: whether the infinitive comes in the imperfective (delat’) or perfective (sdelat’) form.
This  will be the dependent variable in the statistical analysis.
Values: IPF = Imperfective, PF = Perfective

TENSEPRI, Tense of the modal verb prijtis’: whether it is past or non-past.
Values: PAST, NON-PAST

DO, Direct object: whether it is singular, plural, a pronoun or absent. 
Values: SG = singular, PL = plural, PRON = pronoun, NO = absent

DATIVE: whether the agent in the dative case is overt or not.
Values: YES = overt agent in dative, NO = no agent

MODIFIER: whether there is any element (adjective, adverb, clause, particle...) that modifies or determines the context. 
Values:YES, NO, CLAUSE

NEGATION: whether the main verb prijtis’ is negated or not.
Values: YES = negated predicate, NO = positive predicate

ORDER: whether the direct object comes before or after the verb. 
Values: PRE = the direct object comes before the verb, POST = the direct object comes after the verb




