# Divertimento per li Regazzi - a digital edition
This page documents the ongoing work on a digital edition of the drawing series *Divertimento per li Regazzi* created by the Venetian artist Giovanni Domenico Tiepolo in the late 18th century.

## Research Question

The drawing series *Divertimento per li Regazzi* created by Giovanni Domenico Tiepolo lies at the intersection of narrative and figurative art: It features scenes that depict *Pulcinella*, the well-known character from the *Commedia dell’Arte*, in what appears to be different stages of his life, his birth, his adolescence or his death. Thus, the series can be ‘read’ as a kind of life story of *Pulcinella*. However, other than in linear narratives, the exact sequence of the drawings is unclear and even inconsistent. Furthermore, it is subverted by a playful arrangement of motifs that establish paradigmatic relationships between single drawings of the series or interlink them to works of other artists. 

To present the *Divertimento* in its full complexity, we employ a digital edition that is based on a graphdata model and the [CIDOC-CRM](www.cidoc-crm.org)

## Data Model

We are using CIDOC-CRM as a reference model for our data. For our project, CIDOC-CRM has two advantages: 1. It is a de-facto standard and 2. it is event-based, which helps us to model a 'virtual' life-story of *Pulcinella* in the *Divertimento*, which we use as a sort of 'backbone' to arrange the single drawings. Like it is the case with all models, this does not mean that our proposal to 'read' the Divertimento is the only way to do it, but rather one possible way for a meaningful arrangement of the data. 

A first beta of our data model can be found [here](https://github.com/Gabvie/Divertimento/blob/master/Divertimento.owl). It is based on the [Erlangen-CRM](http://erlangen-crm.org/) implementation of the CIDOC.
