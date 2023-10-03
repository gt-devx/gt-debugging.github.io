---
title: Sessions 2022
order: 1
---
Le GT Debugging aura deux sessions de présentations aux journées du GDR-GPL 2022 :
- Mercredi 8 juin de 14h à 15h30
- Jeudi 9 juin de 11h à 12h30
Le programme complet de la journée du GDR le 8 juin est visible ici https://gdr-gpl-2022.sciencesconf.org/program

Les présentations et animations du GT-Debugging seront donc réparties en deux sessions.

## Session 1 : 8 Juin, 14h00 - 15h30

### 1 - Bug Stories

**Steven Costiou** - Inria.

**Abstract**

Cette présentation introduit la session du GT Debugging, et pour s'échauffer nous raconterons quelques histoires de bugs terrifiantes...

### 2 - SciHook: A Language-Agnostic Python-Based Instrumentation Library for Scientific Computing.

**Benoit Combemale** - Diverse, Univ Rennes, CNRS, Inria, IRISA - UMR 6074.

**Abstract**

Runtime monitoring and logging are fundamental techniques for analyzing and supervising the behavior of computer programs. However, supporting these techniques for a given language induces significant development costs that can hold language engineers back from providing adequate logging and monitoring tooling for new domain-specific modeling languages. Moreover, runtime monitoring and logging are generally considered as two different techniques: they are thus implemented separately which makes users prone to overlooking their potentially beneficial mutual interactions. We propose SciHook, a language-agnostic, unifying framework for runtime monitoring and logging and demonstrate how it can be used to define loggers, runtime monitors and combinations of the two, aka. moniloggers.


### 3 - Deboguage du compilateur C vérifié CompCert.

**David Monniaux** -  VERIMAG, Centre National de la Recherche Scientifique : UMR5104, Université Grenoble Alpes, Institut polytechnique de Grenoble (Grenoble INP).

**Abstract** 

CompCert est un compilateur C formellement vérifié, c'est-à-dire qu'il y a une preuve mathématique que le code produit correspond au code source, au sens qu'il produit les mêmes exécutions. Toutefois, il contient des bugs, qui parfois conduisent à générer du code incorrect. Cela peut paraître paradoxal ; nous expliquerons comment cela est possible, et ce que nous avons fait pour rechercher des bugs (ou parfois en trouver un peu par hasard), et ce qu'il faudrait faire pour aller plus loin.

### 4 - Debuggable test cases for domain-specific models.

**Gerson Sunyéc** - NaoMod, Nantes Software Modeling Group Laboratoire des Sciences du Numérique de Nantes.

**Abstract**

Cette présentation résume les travaux de l'équipe Naomod et plus particulièrement ceux de la thèse de Faezeh Khoram, sur le test et le déboggage appliqués aux langages du domaine. Ces travaux s'organisent autour du langage Test Description Language, TDL, et consistent à: - Adapter TDL à différents langages du domaine - Exécuter les cas de test écrits en TDL - Appliquer l'analyse de mutation pour évaluer la qualité des cas de test - Proposer un débogueur interactif, capable de contrôler aussi bien l'interpréteur TDL que celui du DSL du système sous test La présentation est illustrée par plusieurs exemples de systèmes sous test, de taille et complexité différentes.

## Session 2 : 9 Juin, 11h00 - 12h30

### 5 - Practical Debugging: a hands on tutorial with Pharo
**Maximilian Ignacio Willembrinck Santander, Steven Costiou** - Inria.

**Abstract**

Nous présenterons des techniques et outils de debugging classiques et avancées, quand les utiliser, et comment les mettre en pratique de manière systématique.

Dans une première partie, nous présenterons les outils de base communs à tout type de debugger, dans quels cas de figure et comment les utiliser. Dans une second partie, nous présenterons des techniques de debugging avancées, et comment les utiliser pour construire vos propres outils lorsque les debuggers de base ne sont plus adaptés.

Chaque technique sera illustrée par une démonstration et mise en pratique via des exercices, pour lesquels nous utiliserons le langage Pharo.

_Programme de l'atelier_

Part 1 - Basic debugging. Expected duration: 40 mins

1. Basic debuggers
2. Halting & Breakpoints
3. (Creating your own) Logging Utility

Part 2 - Advanced debugging. Expected duration: 40 mins

1. Instrumentation with Reflection techniques
2. Scripting your debugger
3. Demo: time-traveling debugging using Seeker, a time-traveling debugger built in Pharo