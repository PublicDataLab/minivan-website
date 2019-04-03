---
layout: default
title: Home
---

***MiniVAN (Visual Analyser of Networks)***

Networks are increasingly popular in the social sciences and in the humanities as interfaces for exploratory data analysis. "Visual Networks Analysis" (or VNA) allows scholars to analyse large relational datasets without having to deal with the full complexity of graph mathematics.

Current VNA tools, however, are either too complicated or unable to handle large datasets. Hence MiniVAN, a VNA tool, accessible to scholars with little knowledge of mathematics or coding and yet capable to scale up to graphs of several thousands of nodes.

MiniVAN draws on previous open source ([gephi.org](http://gephi.org), [sigmajs.org](http://sigmajs.org), [graphology.github.io](http://graphology.github.io)) and research projects ([climaps.eu](http://climaps.eu) and [fakenews.publicdatalab.org](http://fakenews.publicdatalab.org)).

MiniVAN is a project of the [Public Data Lab](http://publicdatalab.org/) with support from [Sage Ocean Concept Grant](https://ocean.sagepub.com/concept-grants/).
MiniVAN is currently under development and will be released in early 2019. Stay tuned!

<!--more-->

# Contact

Please direct any inquires about this project to the miniVAN team (Mathieu Jacomy, Guillaume Plique, Jonathan Gray, Tommaso Venturini and Axel Meunier) at [contact at publicdatalab.org](mailto:contact@publicdatalab.org).

# About

MiniVAN is a tool for the exploration of small and large networks, addressed to social scientists and everyone who is interested in graph analysis but has difficulties with graph mathematics. The challenge is to make sophisticated analytic techniques (clustering, spatializing, ranking, filtering, etc) available in a visual and user-friendly environment.

MiniVAN has several advantages over the existing software, but it's key strength is a long-standing reflection on the conceptual basis of Visual Network Analysis. MiniVAN will not only offer a collection of analytic functions, but also guide it users aligning different visualisations and metrics in a ordered inquiry.

The development of MiniVAN will be uphold by a series of discussions with potential alpha-users, through the support of the Public Data Lab a research network on digital data and public interventions. The PLD gathers scholars coming from many leading digital methods centres from across Europe (both from the social and the information sciences). It also entertains a network of contacts with practitioners, journalists, civil society groups, designers, developers and public institutions, which will be mobilised to specify the different needs that MiniVAN will try to respond to.

MiniVAN is composed of two distinct open source web applications:

1. The Analyser
	- Receives and parses a graph uploaded by the user;
	- Guides the user through the choice of the dimensions and the methods of the analysis;
	- Accompanies the user in the definition of the visual properties of the graph representation;
	- Produces a file bundle to be processed by the second application.
(The file bundle produced by the Analyser can be hosted by any web server or by a third-party solutions - such as Github's gists)


2. The Visualiser
	- Reads the data contained in the file bundle produced by the Analyser;
	- Displays multiple visualizations of the network;
	- Provides selected metrics and information about categories and relational structures;
	- Allows the proposed views to be further filtered/tweaked/explored etc. by the readers;
	- Generate a code snippet that can be embedded in any website.


# A few readings on Visual Network Analysis:

- Venturini, Tommaso, Mathieu Jacomy, and Pablo Jensen. Extract from ["What do we see when we look at networks an introduction to visual network analysis and force-directed layouts"](http://www.tommasoventurini.it/wp/wp-content/uploads/2018/10/VisualNetworkAnalysis-TheJazzNetwork.pdf), forthcoming

- Venturini, Tommaso, Mathieu Jacomy, Liliana Bounegru, and Jonathan Gray. 2018. [“Visual Network Exploration for Data Journalists”](http://www.tommasoventurini.it/wp/wp-content/uploads/2017/10/VenturiniEtAl_VisualNetworkExploration.pdf). In The Routledge Handbook to Developments in Digital Journalism Studies, edited by Scott II Eldridge and Bob Franklin. Abingdon: Routledge.

- Jacomy, Mathieu, Tommaso Venturini, Sebastien Heymann, and Mathieu Bastian. 2014. [“ForceAtlas2, a Continuous Graph Layout Algorithm for Handy Network Visualization Designed for the Gephi Software”](http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.0098679). PloS One 9 (6): e98679. doi:10.1371/journal.pone.0098679.

- Venturini, Tommaso, Liliana Bounegru, Mathieu Jacomy, and Jonathan Gray. 2017. [“How to Tell Stories with Networks: Exploring the Narrative Affordances of Graphs with the Iliad”](http://www.tommasoventurini.it/wp/wp-content/uploads/2016/01/How_to_Tell_Stories_with_Networks_PreprintVersion.pdf). In Datafied Society, edited by Mirko Tobias Schäfer and Karin van Es. Amsterdam: University Press.

- Bounegru, Liliana, Tommaso Venturini, Jonathan Gray, and Mathieu Jacomy. 2017. [“Narrating Networks”](http://www.tommasoventurini.it/wp/how-to-tell-stories-with-networks-exploring-the-narrative-affordances-of-graphs-with-the-iliad/). Digital Journalism 5 (6): 699–730. doi:10.1080/21670811.2016.1186497.

- Venturini, Tommaso, Anders Munk, and Mathieu Jacomy. 2018. [“Actor-Network VS Network Analysis VS Digital Networks Are We Talking About the Same Networks?”](http://www.tommasoventurini.it/wp/wp-content/uploads/2015/05/Venturini-Munk_Jacomy_ANT-vs-SNA-vs-NET.pdf). In DigitalSTS: A Handbook and Fieldguide (Forthcoming), edited by David Ribes and Janet Vertesi.

# Coordinated by

<img src="assets/images/logo-publicdatalab.svg" alt="drawing" width="200"/>
