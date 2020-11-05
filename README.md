# PyCloze-Transferts de chaleur
- auteur: [Christian Ghiaus](mailto:cghiaus@gmail.com), [INSA Lyon](https://www.insa-lyon.fr)
- date: nov. 2020

[Banque de questions][BanqueQuestions] à réponse intégrées ([cloze][QuestionCloze]) en format [XML][xml2moodle] générés en [Python 3](https://www.python.org) pour obtenir des tests [Moodle 3](https://moodle.org) à [questions aléatoires][QuestionsAléatoires].

Les tests sont utilisables pour :

- Des questions de 10 min. dans les cours magistraux (CM) :  les fichiers notés `Q*.xml` ;

- Des problèmes de 2 h dans les travaux dirigés (TD) : les fichiers notés `P*.xml`.

- Des examens de 1h30 - 2h00 en utilisant des [tests][TestsMoodle] composés de plusieurs questions (typiqument une question `Q*.xml` et deux questions `P*.xml`).


Les fichiers en format [XML Moodle][XML] sont obtenus en utilisant la procédure :

**PyCloze**

[![DOI](https://zenodo.org/badge/302832801.svg)](https://zenodo.org/badge/latestdoi/302832801)

A la demande, les enseignants peuvent obtenir les fichiers Python qui génèrent les questions. Cela donne la possibilité de changer le nombre des [points][QuestionCloze] accordés à chaque réponse et/ou de modifier le texte de la question.

## Guide d'utilisation rapide

- Télécharger les fichiers `.xml`.

- [Importer][ImporterQestionXML] les questions en Moodle depuis un fichier `*.xml` (voir [tutoriel][Tutorial_xml2moodle] pour la crétion des tests en Moodle).


## Sommaire

### Questions

[Q01](Q01.md) Résistance et flux thermique

[Q02](Q02.md) Estimation des coefficients d'échange convectif

[Q03](Q03.md) Emissivité totale hémisphérique

[Q04](Q04.md) Facteurs de forme

[Q05](Q05.md) Estimation de la température de la voûte céleste

### Problèmes

[P01](P01.md) Mur soumis aux conditions limites de type Dirichlet

[P02](P02.md) Conduction en régime permanant avec création interne de chaleur

[P03](P03.md) Mur en régime permanent avec conductivité variable

[P04](P04.md) Mur soumis aux échanges superficiels convectifs

[P05](P05.md) Mur soumis aux échanges superficiels convectifs et radiatifs

[P06](P06.md) Étude en régime permanant d'un chauffage électrique par plancher

[P07](P07.md) Isolation thermique des tubes cylindriques

[P08](P08.md) Trempe d'une bille métallique (régime dynamique)

[P09](P09.md) Oscillation thermique dans le sol (régime dynamique)

[P10](P10.md) Rayonnement d’un disque

[P11](P11.md) Effet de serre

[P12](P12.md) Facteurs de forme

[P13](P13.md) Échanges radiatifs dans un local de forme cubique

[P14](P14.md) Échanges radiatifs entre surfaces noires et grises

## Licence
Ces documents sont sous licence <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />

--------------

[TestsMoodle]:https://docs.moodle.org/2x/fr/Construire_un_test

[QuestionsAléatoires]:https://docs.moodle.org/2x/fr/Construire_un_test#Ajout_de_questions_al.C3.A9atoires

[BanqueQuestions]:https://docs.moodle.org/2x/fr/Banque_de_questions

[XML]:https://docs.moodle.org/3x/fr/Format_XML_Moodle

[QuestionCloze]:https://docs.moodle.org/2x/fr/Question_cloze_à_réponses_intégrées

[ImporterQestionXML]:https://docs.moodle.org/3x/fr/Importer_des_questions#Importer_des_questions_depuis_un_fichier

[xml2moodle]:https://github.com/cghiaus/PyCloze/blob/main/Tutorial_xml2moodle.md

[Tutorial_xml2moodle]:https://github.com/cghiaus/PyCloze/blob/main/Tutorial_xml2moodle.md
