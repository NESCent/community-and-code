---
title: Phylotastic 1
layout: index
---

## Phylotastic: the Tree of Life, as you need it

**EventID**: 6

**Shortname**: phylotastic1

**URL**: [http://www.evoio.org/wiki/Phylotastic1](http://www.evoio.org/wiki/Phylotastic1)

**Original proposal**: [NESCent HIP working group proposal](http://www.evoio.org/wiki/EvoIOWorkingGroupProposal)

* [Description](#description)
* [Pitches](#pitches)
* [Subgroups](#subgroups)
* [Comments](#comments)

<h2 id="description">Description</h2>

A problem faced in many areas of life sciences research, from community ecology to comparative genomics to biomedical genetics, is to put the data available for a set of species into a phylogenetic context, based on a "species tree". For all we know, scientists are facing this type of problem hundreds of times every day. The past decade of efforts to assemble a large "tree of life", a phylogeny for all species, have produced many "megatrees" or "supertrees", usually limited to a particular group of organisms such as fungi, mammals or plants. Most scientists don't know how to use such huge trees. Yet, it ought to be possible to address the scientific demand for species trees by taking the existing supertrees, pruning away unneeded parts, and grafting on (where possible) missing species.

An existing tool called "phylomatic" does precisely this: starting with a user-supplied list of species and a huge phylogenetic topology for plant families, it grafts the species onto the tree wherever it can match the family name, and it prunes away all the rest. This is just a topology, so users find ways to add branch lengths to the resulting tree. The result is that the user, so long as she is only interested in plants, can get a phylogeny for an arbitrary list of named species. Phylomatic rocks: its frequent use shows that big species trees are highly useful for applications in ecology, biodiversity, & trait analysis,when the interfaces that serve user needs— and the mega tree providing vast coverage— are available.
This suggests that if a more general tool can be built, it will be extraordinarily useful, especially if
* it is an open standard that can be implemented in many ways
* the back-end data store is populated with large phylogenies available for fungi, fish, mammals, butterflies, etc (not just plants)
* the core functionality (name-matching, grafting & pruning) is modularized in open-source bioinfo toolboxes
* methods for adding branch lengths are easier and more generalized
* all of the above operations are wrapped up as web services that can be invoked from existing computing environments

If this were a web service, we could plug it into Mesquite, and users could load up their species-based character matrix, then get a tree for it. In fact, lets go back a step, to consider users with only a list of species, and no data to compare: consider an even more open-ended discovery environment, which we could implement in Galaxy or Taverna (given that this is all based on web services). The user starts with a list of species (or a higher taxon), and a request for some useful types of data that could be obtained by querying various available sources, e.g., whether it has a cyt oxidase sequence in GenBank, whether it is found in California, where is the nearest specimen, etc.

<h2 id="pitches">Pitches</h2>

Here is the [list of pitches](https://docs.google.com/document/d/1L2vhSR_F_2PyuGiWLlxUo5BJIpL8OfwfT056lcvCmIE/edit) made at the event. 

<h2 id="subgroups">Subgroups</h2>

List of final subgroups: [Subgroups](http://www.evoio.org/wiki/Phylotastic1#Subgroups)

<h2 id="comments">Comments</h2>

The [schedule](http://www.evoio.org/wiki/Phylotastic/Schedule) provides a very detailed view of the agenda and the information provided to partiticipants on the first day, including links to the slides for various informational talks and bootcamps.  

There was extensive followup to this hackathon, including a [multi-author publication](http://www.biomedcentral.com/1471-2105/14/158), and a grant proposal recommend for NSF funding as of Feb, 2015.  Many of the demos ended up on a [live demo web server](http://www.phylotastic.org/).  
