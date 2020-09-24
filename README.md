# Cell Ontology Training

A free virtual training session for the [Cell Ontology](https://github.com/obophenotype/cell-ontology). This training session is open to all, please [register](https://docs.google.com/forms/d/e/1FAIpQLSdQud9QmKylV-6quqhWe6xIQxMu542qKqny3vOZRI9-XLreGA/viewform) in advance. All skills levels are welcome, prior experience with ontologies is not necessaary.

**Dates:**
Thursday, Sept 24, 2020 and Oct 01, 2020

**Time:**
8-11am PT / 11-2pm ET / 4-7pm UK

**Zoom:**
https://zoom.us/j/95194536310  
Password: Please [register](https://docs.google.com/forms/d/e/1FAIpQLSdQud9QmKylV-6quqhWe6xIQxMu542qKqny3vOZRI9-XLreGA/viewform) to obtain the password. 

Note - the entire session will be recorded.

## Agenda:

1. **[History and Structure of the Cell Ontology](https://drive.google.com/file/d/13Jxj36KLh5uQoD-vcIcZQnxZYzTWuWlX/view)** (Alex Diehl)
    - Decisions that have gone into why the structure is the way it is
    - Imported ontologies, such as Uberon, GO, PRO
    - Who has been using the CL
2.  **[Basic introduction to ontologies and ontology logic](https://docs.google.com/presentation/d/11WeCHCeGYSPEO7hUYFTdPivptxX4ajj5pVHDm24j4JA/edit?usp=sharing)** - why do we build ontologies and what we can do with them? (David Osumi-Sutherland)
    - Why we build the logic and how we do that
3. **[Practical application](https://docs.google.com/document/d/1owDKQjZG4MDrhQDAU9zjFjcxk9M0WAtXjsx38hR3T4w/edit?usp=sharing)** (Nicole Vasilevsky, Alex Diehl, David Osumi-Sutherland)
    - How to use [GitHub](https://github.com/obophenotype/cell-ontology/issues/) to request terms
    - Browsing, searching and querying in [Protege](https://protege.stanford.edu/)
    - Editing in [Protege](https://protege.stanford.edu/)
    - Pull Requests
    <!-- - Cell Ontology Practical Training materials are [here}(https://docs.google.com/document/d/1owDKQjZG4MDrhQDAU9zjFjcxk9M0WAtXjsx38hR3T4w/edit) -->
4. **Use cases**
    - Participant use cases - how do participants want to use the CL?
    - High throughput data - what should be captured in a Cell Ontology term
    - When to add a term, when will it be accepted?
    
## Preparation

Participants will need to have access to the following resources and tools prior to the training:
- **GitHub account** - register for a free GitHub account [here](https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)
- **Protege** - Please install Protege 5.5, download it [here](https://protege.stanford.edu/)
- Please try and install **ELK 0.5** (_For a video showing how to install Elk, click [here](https://www.dropbox.com/s/n3td2n48xmwd3mj/Install_ELK_0.5.mov?dl=0)._) 
  - Click here to get the latest [Protege Plugin latest build](https://oss.sonatype.org/service/local/artifact/maven/content?r=snapshots&g=org.semanticweb.elk&a=elk-distribution-protege&e=zip&v=LATEST) (this is available on the bottom of [ELK pages](https://github.com/liveontologies/elk-reasoner/wiki/GettingElk). This will download a zipped file.)
  - When downloaded, unzip and copy puli and elk jars (two .jar files) in the unpacked directory.
  -  Paste these files in your Protege plugin directory. This is in one of two locations:
    - ~/.Protege/plugins (note this is usually hidden from finder, but you can see it in the terminal) **or**
    - Go to Protege in Applications (Finder), right click, 'Show package contents' -> Java -> plugins
  - Restart Protege. You should see ELK 0.5 installed in your Reasoner menu. 
  - Important: it seems Elk 0.5. Does not work with all versions of Protege, in particular, 5.2 and below. These instructions were only tested with Protege 5.5!
- _Optional_ **GitHub Desktop** - Please make sure you have some kind of git client installed on your Machine. If you are new to Git, please install [GitHub Desktop](https://desktop.github.com/)
- Set your preferences in Protege, find your ID range is [here](https://github.com/obophenotype/cell-ontology/blob/master/src/ontology/cl-idranges.owl)

## Related Workshop: CELLS 2020 Workshop

[4th International Cells in Experimental Life Science Workshop, CELLS 2020](https://sites.google.com/view/cells-2020-workshop/home)   
A virtual workshop associated with ICBO 2020 and JOWO 2020  
Friday, September 25, 2020, 11 am to 1:30 pm, US Eastern Time Zone  

## Resources

- [Ontology tutorials and Resources](https://tislab.org/ontologyResources.html): Includes links to ontology browsers, past tutorials and slides, links to ontology tools and relevant publications.
- [Monkeying around with OWL: Musings on building and using ontologies](https://douroucouli.wordpress.com/): Blog posts by Chris Mungall.
- [Managing Translational Informatics Projects (MTIP)](https://data2health.github.io/mtip-tutorial): Includes GitHub tutorials.

## Slides and Recordings:
- [History and Structure of the Cell Ontology](https://drive.google.com/file/d/13Jxj36KLh5uQoD-vcIcZQnxZYzTWuWlX/view) (Alex Diehl)
- [Basic introduction to ontologies and ontology logic](https://docs.google.com/presentation/d/11WeCHCeGYSPEO7hUYFTdPivptxX4ajj5pVHDm24j4JA/edit?usp=sharing) (David Osumi-Sutherland)
- [Pracical application Day 1 Recording](https://www.dropbox.com/s/355bgyzr03gpqrk/CellOntologyTraining_Day1_PracticalApplication_2020-09-24.mp4?dl=0). (Nicole Vasilevsky, David Osumi-Sutherland, Alex Diehl). On Day 1 we covered:
    - create a ticket in the [Cell Ontology GitHub repository](https://github.com/obophenotype/cell-ontology/issues)
    - create a fork from GitHub
    - browsing, searching and querying the Cell Ontology
    - set up preferences in Protege. **Note** - you can find your ID range [here](https://github.com/obophenotype/cell-ontology/blob/master/src/ontology/cl-idranges.owl)

## Contact

Register [here](https://docs.google.com/forms/d/e/1FAIpQLSdQud9QmKylV-6quqhWe6xIQxMu542qKqny3vOZRI9-XLreGA/viewform).

**Slack**: Join the anatomy-and-cell-ontologies workspace [here](https://join.slack.com/t/anatomy-and-cell-onto/shared_invite/zt-h8mtt4s3-d4gymfzyflYJUE_K_IGnpw).

For questions, please contact cl_edit@googlegroups.com.

