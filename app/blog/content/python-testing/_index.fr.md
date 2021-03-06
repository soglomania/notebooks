---
title: "Liste des modules de test en Python"
description: ""
date: 2020-03-24T10:45:00+01:00
lastmod: 2020-04-16T15:20:12+01:00
draft: false
type: "docs"
icon: "ti-book"
keywords: ["python", "tests", "devops"]
---

Trois principaux modules de tests disponibles sur PyPi:

- unittest
- pytest
- nose2

| unitest | pytest | nose |
| :----- | :----- | :---- |
| - **unittest** est par défaut installé lors de l'installation de Python <br/> - **unittest.TestCase** est la classe de base que toute les classes doivent hérité pour écrire des tests | - **pytest** propose plus de fonctionnalité que unittest par exemple les fixtures qui permettent de mocker des données et de préparer l'environnement de test  <br/> - Avec pytest on peut faire de la découverte de test (regex test_.*) |  - **nose2** est similaire à **pytest** mais ne supporte pas les fixtures |



Les principaux modules utiles pour enrichir ses tests

- factoryboy
- mock
- pytest
- pytest-coverage
- click 
- argparse
- selenium


**Framework Django**

Les modules de test en django sont basés sur **unittest**.

- **SimpleTestCase** : Classe à hérité si pas de base de donnée
- **TestCase** : Classe à hérité s'il y a une base de donnée, gestion des transactions
- **LiveServerTest** : classe à hérité pour tester les IHM (possibilité d'utiliser **selenium**)


