# CD2H Resource Discovery Core

# Leadership
* Director: David Eichmann (University of Iowa)
* Co-Director: Kristi Holmes (Northwestern University)

# Other Core Members
Don't edit this - the RPPR generator populates this section

# Year 3 Budget
Don't edit this - the RPPR generator populates this section

# Specific Aim

The mission of the CD2H Resource Discovery Core is to support discovery of the rich landscape of expertise and resources available within the CTSA hubs and beyond, and to provide a robust infrastructure to enable attribution of the many different essential contributions by the translational workforce.

# Research Strategy
We leverage effective strategies and inventive approaches to build connections within and beyond the CTSA Program. We have adapted and expanded our existing research profiling infrastructure using open collaborative approaches. We are developing tools to identify, track, disseminate, and understand the contribution and impact of software, data, informatics, and other non-traditional scholarly products and activities to properly attribute credit. Finally, this extended knowledge about expertise across the CTSAs is being applied to assist in the creation and success of community-wide collaborative functions. This mission is manifest in activities such as:
* Provisioning a CTSA-wide index of all resources utilized across the full spectrum of CD2H activities;
* Creation of expertise visualizations and services for adoption and assimilation by CTSA hubs for use in
their local environments;
* Development and deployment of an open repository to support preservation, indexing, and discovery of resources at CTSA hubs; 
* Development of a data discovery engine to index and search data across hubs;
* Harmonization of educational resources from multiple existing platforms into a single shared discovery framework;
* Extending representation of expertise and related services across the CTSA consortium;
* Developing a practical, scalable model of contribution and fostering its adoption across the CTSA
Program.

## Significance
CTSA hubs experience serious challenges in maintaining awareness of existing resources, resulting in significant duplication of effort and lost opportunities for synergy. An effective discovery platform spanning the spectrum of expertise, services and resources holds great promise to change this.

## Innovation
We have developed an open, flexible architecture of resource identification, characterization and discovery based open open tools and able to be extended with new capabilities as needs are identified.

### Justification and Feasibility
While first identified as a core component of our proposal to create CD2H, we have received recurring comments regarding a need for such a capability from NCATS personnel, CTSA hub PIs, CTSA informatics directors, and the CTSA Consortium population in general.

Feasiblity has already been demonstrated with our proof-of-concept faceted search interface (see below).

### Summary of existing system and findings
See CD2H Labs (labs.cd2h.org) for our latest demonstration platforms. These include:
* the CD2H project dashboard
* CD2H faceted search
* a prototype of a CTSA Consortium-specific web harvesting and extraction platform (used for service characterizations so far)
* a platform for harvesting and search of CTSA-relevant GitHub repositories, owners and contributors
* a VIVO-compatible plaform integrating traditional research profiling data with GitHub information and connections to "grey" sources such as FigShare

## Approach
The approach employed by the Iowa team to date has been one of rapid prototyping of a harvesting platform for a newly identified information source, integration of the resulting metadata into the SciTS warehouse and then enabling discovery of those metadata in our faceted search engine. We plan on continuing this approach as long as new information sources arise. In year 3, we will be enhancing this overall framework with multiple means (JDBC, GraphQL, SPARQL) for hubs to directly interrogate the environment and embed both services and information into their local environments.

The Northwestern team uses Agile development methodology to support progress on projects (i.e., [menRva](https://github.com/data2health/menRva), [Personas](https://github.com/data2health/CTS-Personas), and [Architecting Attribution](https://github.com/data2health/architecting_attribution)). Development is separated into two-week sprints. The sprint kicks off with a planning meeting where the team decides what work will be completed in the two-week increment and how the work will be achieved. Any dependencies or blockers are discussed at this time, as well.  Teams have daily in-person or virtual stand-ups where reports of work are shared, as well as concerns or blockers so that course corrections can be made quickly. 

### Progress Report
As noted above, we have made significant progress in configuring SciTS as a central resource linking the various activities and tools in this core. This has been greatly informed by our engagement with the CTSA community - particulary in the areas of educational resources and hub services. We have multiple live services operational in CD2H Labs with frequent deliverables scheduled in the coming reporting period.

We are wrapping up the Personas project in Year 3 and will actively disseminate deliverables. Significant progress will be achieved by the Attribution and menRva teams, with software releases and other deliverables expected before year's end.
 and characterization of the roles assumed by CTSA personnel (see the Personas project for more information on this). 

We also made significant progress on menRva, Personas, and Attribution projects. We released a menRva alpha version (staging) (with basic deposits, powerful search, DOI minting, containerization) and a [Repository & Index Software comparison](https://github.com/data2health/repository-and-index-software). We made progress in the computable attribution work ([CRedIT ontology](https://github.com/data2health/credit-ontology) & [Contributor Role Ontology](https://github.com/data2health/contributor-role-ontology) released, draft annotation file, [research object assessment & mapping](https://docs.google.com/spreadsheets/d/1Mw8gK2NUGM8po7GGRtJTShRM2QNFoR19VJrjQuVCDW8/edit#gid=1619162717)). We held a small [Attribution F2F](https://docs.google.com/document/d/14usojjGshNBCXQ6oEtIFbpV3nGWmhWm_6KD1kOkIV7Q/edit) and are developing a demonstrator. The Personas project has completed extensive [information assessment](https://docs.google.com/spreadsheets/d/1SiBgnnKfhIMMLuUBBVpY0nF3ivU4ynG3uDELu7DpzKA/edit#gid=1518217027) and [literature](https://drive.google.com/drive/folders/1QRVwKfvjDNizvMrvWLkD-BHr2UMIeWzF) gathering & assessment to identify key job families, finalized a template, created a [sample profile](https://drive.google.com/file/d/1rBqkHNqFO0nZyZdCgP3I3F_zf4Pwap7P/view). We've also worked to welcome CTSA Program collabroators to the projects through orienting them to projects, with outreach at meetings and on calls, and other activities to build a community of practice. The Personas project wrap up prior to Year 3, with active dissemination of deliverables. 

### Current Projects

* [Architecting Attribution](https://github.com/data2health/architecting_attribution) ([RPPR](https://github.com/data2health/architecting_attribution/blob/master/RPPR.md))
* [Education Harmonization](https://github.com/data2health/edu-harmonization) ([RPPR](https://github.com/data2health/edu-harmonization/blob/master/RPPR.md))
* [menRva](https://github.com/data2health/menRva) ([RPPR](https://github.com/data2health/menRva/blob/master/RPPR.md))
* [Personas](https://github.com/data2health/CTS-Personas) ([RPPR](https://github.com/data2health/CTS-Personas/blob/master/RPPR.md))
* [Science of Translational Science Platform](https://github.com/data2health/scits-platform) ([RPPR](https://github.com/data2health/scits-platform/blob/master/RPPR.md))
