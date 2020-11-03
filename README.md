# PyCloze-TC
Une collection de problèmes de transferts de chaleur en format XML Moodle générés en Python pour obtenir des tests à questions aléatoires.

# PyCloze : Transferts de chaleur

- auteur: [Christian Ghiaus](mailto:cghiaus@gmail.com), [INSA Lyon](https://www.insa-lyon.fr)
- date: nov. 2020

**PyCloze : Transfert de chaleur** est une collection de problèmes en format [XML][xml2moodle] générés en [Python 3](https://www.python.org) et importable en [Moodle 3](https://moodle.org) pour obtenir des [tests][TestsMoodle] à [questions aléatoires][QuestionsAléatoires]. Les tests sont utilisables pour :

- les cours magistraux (CM) : les fichiers notés `Q*.xml` ;

- les travaux dirigés (TD) et les examens (DS) : les fichiers notés `P*.xml`.


Les fichiers en format [XML Moodle][XML] sont obtenus en utilisant la procédure :

**PyCloze**

[![DOI](https://zenodo.org/badge/302832801.svg)](https://zenodo.org/badge/latestdoi/302832801)

A la demande, les enseignants peuvent obtenir les fichiers Python qui génèrent les questions. Cela donne la possibilité de changer le nombre des [points][QuestionCloze] accordés à chaque réponse et/ou de modifier le texte de la question.

## Licence
Ces documents sont sous licence <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />

## Guide d'utilisation rapide

- Télécharger les fichiers `.xml`.

- [Importer][ImporterQestionXML] les questions depuis le fichier `*.xml`. 


## Sommaire

### Questions


### Problèmes

[Tutorial_py2xml.md](Tutorial_py2xml.md): on how to generate cloze questions with **Python** and export them as `.xml` file.  `PyCloze00.py` is used as an walk through example.

[Tutorial_xml2moodle.md](Tutorial_xml2moodle.md): on how to set up a quiz and import `.xml` random questions in **Moodle**.

[Tips&Tricks.md](Tips&Tricks.md): on useful habits and pitfalls to avoid useful info

### Examples

#### Description
[Description4quizzes.md](Description42quizzes.md) presents three quizzes:

1. PyCloze00: given the names and the ages of three children, find the mean age, the eldest child and the longest name.
2. PyCloze01: find the thermal resistance, the heat flux and the heat transfer rate of a flat wall. 
3. PyCloze02: find the coefficient of heat exchange in forced and in natural convection.


#### Python implementation

`PyCloze00.py` a simple example with inputs of type string and numerical and outputs of type numerical, multichoice and short answers (discussed in [Tutorial_py2xml.md](Tutorial_py2xml.md)).

`PyCloze01.py` an example with numerical inputs and numerical outputs.

`PyCloze02.py` a more complicated example.

#### .xml files

`PyCloze00.xml` file generated with `PyCloze00.py`.

`PyCloze01.xml` file generated with `PyCloze01.py`.

`PyCloze02.xml` file generated with `PyCloze02.py`.

[calculated_q]:https://docs.moodle.org/39/en/Calculated_question_type

[cloze]:https://docs.moodle.org/39/en/Embedded_Answers_(Cloze)_question_type

[Import_questions]:https://docs.moodle.org/39/en/Import_questions#Importing_questions_from_an_existing_file

[Moodle]:https://moodle.org/?lang=en

[Tutorial_MarkDown]:https://agea.github.io/tutorial.md/

[random_q]:https://docs.moodle.org/39/en/Random_question_type

[penalty]:https://docs.moodle.org/39/en/Multiple_Choice_question_type#Penalty_factor



--------------

[TestsMoodle]:https://docs.moodle.org/2x/fr/Construire_un_test

[QuestionsAléatoires]:https://docs.moodle.org/2x/fr/Construire_un_test#Ajout_de_questions_al.C3.A9atoires

[XML]:https://docs.moodle.org/3x/fr/Format_XML_Moodle

[QuestionCloze]:https://docs.moodle.org/2x/fr/Question_cloze_à_réponses_intégrées

[ImporterQestionXML]:https://docs.moodle.org/3x/fr/Importer_des_questions#Importer_des_questions_depuis_un_fichier

[xml2moodle]:https://github.com/cghiaus/PyCloze/blob/main/Tutorial_xml2moodle.md
