---
title: "Codebuch"
author: "Laura Wallenfels"
date: "12 12 2022"
output: html_document
---

**Codebuch**

**Node-Attribute**

\- id: Abkürzung

\- name: Name des Zeugen

\- sex: Geschlecht codiert nach männlich (m) und weiblich (f)

\- age: Alter nach Geburtsjahr

\- profession: Beruf


**Edge-Attribute**

\- relation: Entlastung (b) oder Belastung (a) Johnnny Depps durch den Zeugen oder neutrale Aussagen (c)

-from: Beziehung ausgehend von Johnny Depp

-to: Anwesende Zeugen

- relation: Beziehungen der Zeugen zu Johnny Depp und Amber Heard :

1 = work/contract     

2 = friendship

3 = love

4 = employed by

5 = medizinische dienstleister 

6= family 

7= extern

8= Wohnung in Wohnhauskomplex 

-WeightJD: Belastende und Entlastende Aussagen für JD

- WeightAH: Belastende und Entlastende Aussagen für JD

-Event: codiert ob Zeugen zu einem der Events ( KOT, Finger abschneiden, Polizeieinsatz, Wohnkomplex) ausgesagt haben oder nicht
