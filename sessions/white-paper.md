# Visualizing Empire White Paper

**Award No.:** HAA-266490-19  
**Date of activities:** September 1, 2019 to August 31, 2020  
**By** Christopher Church and Katherine Hepworth  

## Project activities

### Project overview
This project advanced work toward generating ethical visualizations of historical corpora comprising the European cultural imagination prior to the twentieth century without reproducing ethnocentrism. Visually representing the historical place of misrepresented peoples and locales throughout the world requires interdisciplinary collaboration focused equally on critical theory, data visualization, ethics, machine learning, and text analysis. The grant funded a two-day workshop that united top experts from relevant fields to address the conceptual and logistical challenges of visualizing French colonial historical texts: 1) how to create ethical data visualizations--and their underlying forms of training and analysis--that grapple with inherent source biases; and 2) how to computationally process non-modern, non-English languages for humanities research in a critically engaged way.

### Project Activities
Over a two-day period, we hosted eight conference sessions, each addressing a key aspect of the project’s implementation plan: 1) scholarly framing; 2) metadata structure; 3) natural language processing workflow; 4) domain adaptation for early modern French; 5) data visualization ethics; 6) interface design and usability; 7) adapting open-source projects; and 8) long-term preservation. Each session was led by a domain-area expert, assisted by a scholar in an adjacent field, and was 75 minutes in length, with a 30 minute break between sessions for less formal conversations. There were two working lunches to continue conversations started during the formal sessions, as well as a working dinner to do the same.
The bulk of the first day of sessions addressed issues raised by the historical content, while the second dealt with the methodologies of data visualization and project management. Domain area experts from history, fine arts and design, journalism, computer science, machine learning, and the libraries contributed to the project.
A hired undergraduate assistant recorded all sessions and took graphical notes, which were then posted to the online Zenodo and GitHub along with the scholars’ slide decks.

### Changes/Alterations to Work Plan

#### Omissions and changes to key personnel
Several of our proposed participants were unable to attend the event on the proposed date and time. We replaced some key personnel with suitable equivalent experts in their fields.
#### Changes to subjects discussed
On the recommendation of our invited experts, a new topic ‘NLP workflow’ was added to our workshop discussion schedule and two of the previously proposed topics were folded into one discussion topic: ‘‘input and output (i/o), ongoing maintenance, and preservation’.
#### Changes to data management plan
Due to changes in personnel and structural developments at the UNR Library System, as well as recommendations made during the planning workshop itself, the data management plan had to be altered. Instead of despoting the planning workshop materials into the ScholarWorks repository at UNR, we were advised to use Zenodo, which integrates with GitHub, provides a unique document identifier, and is more public-facing than the university’s internal data repository.

#### Publicizing efforts
A Github Pages website was made as a public-facing entry into the workshop materials preserved online. Considerable effort was made to make the writing, formatting, and file access easy and accessible for non-expert audiences.

&nbsp;

-----------------------------

## Accomplishments
The planning stage for the project addressed two major technical goals: 1) how to mine historic corpora for named entities and their descriptors; and 2) then how to visualize them cartographically to demonstrate what nineteenth-century French imperialism looked like from a cultural and ideological perspective. In tackling these two goals, the project addressed how the tools of distant reading and visualization could be applied to a broad range of historical sources in ways that attend to cultural, geographic, and linguistic diversity. With “critical digital humanities” in mind, the workshop’s sessions melded technical concerns with humanistic ones, leading to rich discussions about identifying and preventing the visual perpetuation of pernicious narratives about historical subjects that have persisted from the past into the present.
The key findings from the planning stage of the project can be broken down into three main categories: 1) insights about the visualization of humanistic data, including pitfalls and methodological concerns; 2) technical problems related to the tools of analysis as well as the underlying nature of the humanistic data; and 3) project management revelations.

### Methodological concerns about visualizing humanistic data
The planning stage raised important questions about the nature of visualization, probing the inherent biases of mapping technologies specifically and data visualization more broadly. Across several sessions, we examined telling examples where visualization techniques worked at cross purposes to understanding, and we discussed how to mitigate the potential harm that visualization might cause.
One key takeaway from the discussion was the delineation of visualization for discovery versus visualization for impact, and the importance of not conflating the two. It is essential when creating a data visualization of any sort that one considers the purpose of the visualization, its frame and argument, the ethical considerations that might arise, and its potential impact on three groups: users of the visualization, subjects represented in the visualization, and people affected by those representations (for example, descendants of visualized subjects).

### Technical concerns of the outlined project
The technical concerns that surfaced during the workshop concerned how to select and implement appropriate metadata standards, the challenges of both creating custom visualization tools and using off-the-shelf packages, how to determine which processes were most suitable for coding named descriptors in the xml text.
Over the course of the planning workshop, it became clear that the Journal des Voyages dataset was not as clean as promised by the third-party vendor hired prior to the start of the grant period. Moreover, the planning stage emphasized the necessity of dataset annotating in order to create a so-called gold standard set against which researchers can test the accuracy of machine learning algorithms. In the next stage of the project, the dataset must be further cleaned and annotated.
The workshop also highlighted the need to analyze the photographs, drawings, and other non-textual elements in the periodicals for key information. It became clear that the project would need higher resolution scans of images, necessitating international collaboration with donor libraries to make new scans of original documents as microform is a highly lossy medium. The next stage of the project will use higher resolution images from the National French Library, which has recently released higher resolution scans of many of its collections.
###Project management and collaborative revelations
During the planning workshop, the benefit of having diverse scholars conversing with one another was readily apparent. While it proved difficult to bring together colonial scholars with computer scientists, and to achieve representation of diverse ethnic, racial, national, and gender backgrounds, especially with the logistical concerns of long-distance international travel, doing so helped uncover blindspots often overlooked in digital, data-driven projects. For instance, it became clear that humanist inquiry and historical data push the boundaries of settled science in the domains of computer engineering and machine learning. Additionally, colonial scholars recognized the potential provided by digital analytical tools, but raised key concerns about the damage that could be done with the tools of aggregation and visualization at one’s disposal.
Finally, we discussed the broad project management question plaguing the digital humanities: if you build it, will they come? During the final sessions of the planning workshop, we discussed how much time and effort it takes to bring a project online, but it may serve a limited audience and only remain operational for a brief duration. The brevity of operation is caused by a host of factors falling under the domain of software maintenance and preservation, including, but not limited to, updates to the platform, security patches, and eventual planned or unplanned obsolescence of the technologies used. To mitigate these concerns, we concluded to ensure that key findings are accessible in “stable” textual formats and that the data be preserved in open standards so that it can be repurposed as technologies change.

&nbsp;

-----------------------------

## Audiences
The primary audience for the planning workshop included domain area experts in history, fine arts and design, journalism, computer science, machine learning, and library science. As this was a planning workshop for future stages of the project, data are not yet available with respect to the geographical reach of the planning stage’s findings. These findings are available online, but they are in the service of creating a larger public-facing project on the visualization of the French imperial imagination that has yet to be created.
That said, the workshop made clear the fruitfulness of interdisciplinary conversations, particularly between the computer sciences and the humanities. By having colonial scholars and people of diverse gender, racial, sexual, and cultural backgrounds participate in discussions about data visualization, the planning workshop uncovered blindspots in the “algorithmic” disciplines with respect to the potential for harm of data aggregation and visualization, while at the same time unearthing new possibilities for scholarly inquiry that includes the perspectives of colonized, marginalized, and subjugated peoples.

&nbsp;

-----------------------------

## Evaluation
The planning workshop was in itself an evaluation of our visualization project’s intellectual merits, practicability, appropriateness of its scope and audiences, and technical considerations. Collectively, the workshop participants verified that the project was considered important, relevant to academic communities, and feasible. The question of which open source tools might be adapted for use on the project was not sufficiently resolved, and will need to be pursued in the next stage of the project. In terms of evaluating our proposed activity, the most interesting outcome was that several expert participants raised questions about the necessity and/or dominance of a cartographic visualization in our proposed next stage visualization project. Instead, they suggested other visualization types might offer additional insights, such as network charts.

------------------------------

## Continuation of the Project
The planning workshop was held as a preliminary activity to building an interactive visualization for exploring the Journal des Voyages corpus. We will seek Office of Digital Humanities Stage 2 funding to continue the project.

###Collaborative partnerships
The workshop initiated collaborative relationships between the University of Nevada, Reno and The Bancroft Library and the Information School at the University of California, Berkeley, CNRS/LORIA at Université de Lorraine, the School of Fine Arts at the Universidade Federal do Rio de Janeiro, Swinburne University of Technology, The Alan Turing Institute at the British Library, and LIRIS at the National Institute of Applied Sciences. These partnerships will continue through the next stage of project activities, as all participants have expressed interest and willingness to contribute to the project going forward. Additional partnerships are currently being negotiated for related projects.

### Project decisions for next steps across domains
See below separate pages containing full details of each session.

1. [Scholarly framing — digital humanities & French colonial history](sessions/1.md)
2. [Metadata structure](sessions/2.md)
3. [Natural language processing (NLP) workflow](sessions/3.md)
4. [Domain adaptation (for early modern French)](sessins/4.md)
5. [Ethical data visualization](sessions/5.md)
6. [Mapping and interface design usability](sessions/6.md)
7. [Adapting and integrating existing open source projects](sessions/7.md)
8. [Input and output (i/o), ongoing maintenance & preservation](sessions/8.md)

&nbsp;

-----------------------------
## Long term impact
This workshop, and intellectual activity leading up to it, have resulted in several related projects. The materials for each of these activities are made publicly available via Github repositories under open source licenses, and in some cases, as Github Pages websites. The main long-term impact of these activities is preparation for the next stage of the project, namely creating a visualization to explore the Journal des Voyages corpus.

### Ethical visualization workflow
We have also done extensive work on a prototype ethical visualization workflow, tested with present day materials from the humanities and the sciences. The workshop will allow adaptation of this workflow for ethical visualization of historical textual sources and non-English text mining. For the latest development of this work, see: <https://kathep.github.io/ethics/>

### Ethical Data Visualization: Taming Treacherous Data course
We teach the method described above as well as how to navigate the concerns explored in this project in the course 'Ethical Data Visualization: Taming Treacherous Data'. This course was offered in 2018 and 2019 at the Digital Humanities Summer Institute (DHSI) at the University of Victoria, Vancouver Island, Canada, and in 2019 at DHDownunder at the University of Newcastle, New South Wales, Australia. See the [DHSI course content](https://github.com/cmchurch/DHSI-ethical-dataviz) and [DHDownunder course content](https://github.com/kathep/DHDownunder-ethical-dataviz) in these repositories.

### Racism in the Machine paper
We wrote a paper on work preparatory to this workshop, it is available here:
Katherine Hepworth and Christopher Church. 2018. [“Racism in the Machine: Visualization Ethics in Digital Humanities Projects.”](http://www.digitalhumanities.org/dhq/vol/12/4/000408/000408.html) *Digital Humanities Quarterly* 12:4.

### Make Me Care paper
This paper incorporates some considerations explored at the workshop, and applies them to an expanded view of ethical visualization, beyond the digital humanities.
From Hepworth, K. 2020. (forthcoming) "Make Me Care: Ethical Visualization for Impact in the Sciences and Data Sciences", *HCII Conference 2020 Proceedings*.

### Additional long term impact
The additional long-term impacts of these activities are that: 1) approximately 70 scholars have been trained in our considered approach to ethical visualization; 2) several government organizations, startups, and research groups are currently using the Ethical Visualization for Impact method, greatly expanding the scope and reach of our project beyond what we expected.

&nbsp;

-----------------------------

## Award products

#### Visualizing Empire project
The grant period produced several different products, foremost among them a comprehensive plan for future project stages that takes into account the advice from the diverse range of scholars participating in the planning workshop.

#### Paper on process REPLACE WITH PAPER NAME
The award also contributed to the drafting of a peer-reviewed paper that will be submitted to Digital Scholarship in the Humanities outlining a method for computationally processing non-modern, non- English languages for humanities research in a critically engaged way.

#### Github repository
All materials from the planning workshop have been collected into [this online repository](), accessible via GitHub and deposited at Zenodo with a document object identifier. These materials include recordings of all discussions and copies of all slide decks from the planning workshop itself, as well as a summary of the key findings from the grant period.

#### *Journal des Voyages* dataset
They also include the dataset of the Journal des Voyages corpus produced through a combination of OCR scanning with keyed re-entry. Alongside the *Encyclopedie* dataset hosted by Stanford University, these data will ultimately be used to create a training model for natural language processing and named-entity recognition in non-modern French.
