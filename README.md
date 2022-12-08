Project title: Interlocking-Directorates Network Reconstruction

Foreword:
The project is a continuation of my academic work, where during my PhD and later on, 
together with my supervisor prof. Lucio Biggiero, we have studied and analysed the European Aerospace Industry Network (EASIN).
In more detail it can be defined as an inter-firm network analysis of an industry 
geographically from EU28 (as of 2019) and industrially as Aerospace Manufacturing (NACE:3030).
The deep analysis of networks of interlocking-directorates, interlocking-departments and hybrid-interlocks made between EASIN 
itself and its partners (from the whole world and from variety of industries) 
can be found in our book recently published book (https://link.springer.com/book/9783031173882).

Problem definition:
Interlocking inter-firm networks  are systems where strategic and operative knowledge flow 
governing and coordinating the structure of inter-firm relations, having access to insights on the structure,
which provides capability to position oneself more centrally, may turn out to be an invaluable business knowledge.

At the same time, public anti-trust/anti-monopoly institutions use interlocking-directorates as a foundation 
for inspecting if corporate businesses illegally co-operate forming larger, hidden business-groups 
and thus potentially distort free competition in open markets. Providing them with a tool 
able to predict existance of potentially damaging connections 
(considered as such could be all the false-positives achieved with a reasonably high threshold) 
could also prove significantly important. More information can be found in my recent article publication.

The data available for carrying out research is not always fully available and is often internally inconsistent.
This creates a situation, where in some contexts network reconstruction seems like the only way to predict how a network 
structure would look like had we had access to complete affiliation information, provided we can access other data - 
such as economic attributes (size and performance) and geolocation, which nonetheless should be widely available.

Results and Summary:
The three models provided similar, quite promising results. In each case models were very good at predicting the missing link (class 0) 
giving good precision and recoil. For the present links (class 1) they had a very high precision (~0.99) but usually only around 0.7-0.8 recoll. 
Meaning that the found existing links were identified with very high certainty, but only about 70-80% of the network was reconstructed correctly. 
The AUC score for models was 0.89 for LR, 0.95 for RF and 0.96 for GB. 

As a first version of the modelling the results are considered promissing, provided that comparison with random network models, 
such as ERGM, showed much higher performance.
