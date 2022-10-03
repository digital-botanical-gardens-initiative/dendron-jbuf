---
id: af6esocr7vhbkunxmlier56
title: Root
desc: ''
updated: 1664814502103
created: 1655570826398
---
# Species list of the Botanical Garden of the University of Fribourg (BGUniFr)


## What is this website ?

This website is a Dendron based website. If you don't know what this is about have a look at [The Dendron Home Page](https://wiki.dendron.so/).

This project is part of the [Digital Botanical Garden Initiative](https://www.dbgi.org/dendron-dbgi/).
In the frame of the DBGI, we have curated the species list of the Botanical Garden of the University of Fribourg ([BGUniFr](https://www.unifr.ch/jardin-botanique/fr/)), which is displayed in the current website.



## How to use this website ?

You can use the [Dendron lookup functionality](https://wiki.dendron.so/notes/a7c3a810-28c8-4b47-96a6-8156b1524af3/) (the search bar at the top of this page) to look for a specific plant. You can also look for upper taxa such as the botanical family. Here is for example a list of all [[taxo-jbuf.archaeplastida.streptophyta.magnoliopsida.gentianales.apocynaceae]] of the garden.

You should also be able to navigate through the taxonomy using the menu on the left.

At the lower level (species), for each entry you should have a view of the compounds reported in LOTUS for the given entry. 
You do not know what is LOTUS. Have a look at the paper : https://lotusnprod.github.io/lotus-manuscript/
You should be able to download the compounds table as a csv file directly from this page.

You will also find the [Open Tree of Life](https://opentreeoflife.github.io/) and the [Wikipedia](https://www.wikipedia.org/) entry.


Example : This is the page you should land on if you look for _Coffea arabica_.


![[taxo-jbuf.archaeplastida.streptophyta.magnoliopsida.gentianales.rubiaceae.coffea.coffea-arabica]]



## How was this website made ?

Starting point is the [raw species list](https://github.com/digital-botanical-gardens-initiative/taxonomical-preparator/blob/43bc1f9a5b444c391db243f2c0393e512c4f1b8b/data/in/species_list.csv).

See over there for the taxonomical curation scripts https://github.com/digital-botanical-gardens-initiative/taxonomical-preparator

This is the [cleaned output list](https://github.com/digital-botanical-gardens-initiative/taxonomical-preparator/blob/43bc1f9a5b444c391db243f2c0393e512c4f1b8b/data/out/species_list_croisee_final.csv) 

The Dendron structure seemed particularly adapted for the navigation within a taxonomy. We thus wrote a [script](https://github.com/digital-botanical-gardens-initiative/taxonomical-preparator/blob/43bc1f9a5b444c391db243f2c0393e512c4f1b8b/src/03_dendronificator.py) to create a Dendron note for each of the species of the garden.


## I have a question or a comment !

Use the link at the bottom of any of the pages to create an issue on Github.

