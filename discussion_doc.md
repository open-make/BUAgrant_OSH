 # BUA grant discussion
 
 # title: Towards open and FAIR hardware.
 
 # summary
 
We want to help researchers disseminate the hardware they are designing and get credit for that work, all this while reducing the time they need to invest in the process to a minimum, so they can focus on doing research. Setting up one's hardware is a common process in different research disciplines, even if this is rarely recognized as an important skill. However, there 
 is very few recommandation, certification or example for hardware documentation, which makes the transfer of knowledge difficult in the lab and between labs. 
We want to build on the open next project experience and upon advances in software and data management (for instance applying the FAIR principles) to design 
 better workflows in hardware engineering in academia.
 

 After analysing processes researchers are using when their hardware get re-built, we will write recommendations and create a toolbox to help hardware builders to work more efficiently and more collaboratively. On the other hand, we will build a review system to assess the re-usability of hardware, making it possible to give a qualitative measure of the work quality and deriving a recognition sytem.
 
 
 # Problems to solve
  - Researchers and funding agencies have not developed sufficient mechanisms to evaluate technical documentation which makes it difficult to justify the necessary funding.
 - Researchers do not know how to document their hardware.
 - Researchers and technicians have no way to get recognition on their work as hardware engineers.
 - Researchers are spending too much time solving other people issue when dessiminating their hardware solutions.
 ~~- Researchers do not know where to find open hardware they could use.~~
 
 # Work packages
 
 ## WP1: analysis of existing workflow and infrastructures (line 2)
 
 - Suvey of researchers (cross domain) about their habits in production of hardware, pain point, existing solutions.
 (done via lime survey provided by the HU CMS)
 - Search and define specific hardware piece that were well dessiminated in their community (buridan paradigm in flies, airtrack system, and others), analyse the dessimination process.
 - resutls will be used to refine our plan, and look for adoption point of the developed workflow (below)
 
 ##  WP2: Towards FAIR ~~and open source~~ hardware (line 1)
 
### review system (IR)

Building on the [review system that is prototyped in the open next project](https://en.oho.wiki/wiki/Home), we will demonstrate how to review technical documentaion of FAIR and open source hardware created in the academic labs  or as prototypes in publicly funded research projects (using specific hardware defined in WP1).
 
We will optimise the underlying review process and provide a guide and "standardised research hardware folder structure" (See GIN-Tonic project for data) to help researchers to prepare their hardware and its documentation for its peer review.

We will define different level of certification, in order to lower the barrier for researchers to use that system.  

### Publication system (FA)

 While the peer review can be used without or prior to the publication of the hardware,
 we will provide a way for researchers to publish their work as non-traditional research outputs.
 We will consider both the production of a DOI for a snapshot of the repository (via Zenodo, Dspace or GIN), 
 or the production of a paper similar to what JOSS is doing, or via a OJS system, as is developed in the [modern publishing project in Hamburg](https://oa-pub.hos.tuhh.de/en/).

(Recognition and incentives):

The system will be compatible with but different from the current publishing industry, in order to facilitate hardware citation, but avoiding unnecessary costs and a strengthening of the publish or perish paradigm.
On the other hand, we will implement a contributor role taxonomy ([CREDIT or CRO](http://credit.niso.org/)), to report the role of each author in a computer readable form, allowing for more specific recognition of hardware building and sharing skills.
 
### Prototyping the integration of hardware review in the publication system(s)

 
 We will extend the prototype mentioned above to be compatible with a publication workflow happening on a git-based platform. We will consider the possiblity to use 
 (1) the [JOSS infrastructure](joss.theoj.org/), where the review happens on the GitHub platform,
 (2) a Gitlab infrastructure,
 (3) a GIN-like infrastructure (https://gin.g-node.org/).
 
 The three tools use a similar wiki system, that would be compatible with the existing prototype.
 The development or application of a bot similar to the weadon bot used at JOSS or the Tonic bot used with GIN and gitlab will be created.

## WP3: Towards open source hardware (line 2)
  
Bring open science practice into hardware creation projects:

   - license prescription: Cooperations on licensing issues for FAIR and open source data sharing will also be explored with relevant initiatives such as the [CERN OHL from the Open Hardware Repository](https://ohwr.org/project/cernohl/wikis/Documents/CERN-OHL-version-2/).
   - additional information needed for open projects: guide for collaboration rules, code of conducts, ways to make it more inclusive. Build on mozilla, open life science, OSMOOC prescriptions. Also built on the results of WP1.
  

 
## expected outputs

- recommandation of building open FAIR hardware (updatable book)
- several published hardware (as examples)
- one or several hardware peer review and publication platform(s), probably decentralised.


# Financial plan
Start: ASAP, for 2 years

- 42 T€: 1 TVL14 position 35 % for 2 years (HU: Julien Colomb), project coordination, cooperation with other partners
- 145 T€: 2 TVL13 position 50% for 2 years (TU: Robert Mies, N.N.), Hardware evaluation process/system + Recognition
- 6 T€: 1 Student assistant 40h per months for two years (TU)
- 109 T€: 2 TVL13 position 50% for 1.5 years (TBA: TBA), Hardware FAIRification
- 3 T€: material for hardware replication ?


 
