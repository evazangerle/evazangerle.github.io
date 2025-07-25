---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: news
    content:
      title: News
      text: |-
            * RecSys 2025 news: Our short paper "Beyond Top-1: Addressing Inconsistencies in Evaluating Counterfactual Explanations for Recommender Systems" and Michael's Doctoral Symposium paper "Advancing User-Centric Evaluation and Design of Conversational Recommender Systems" have been accepted [07/2025].    
            * Our journal paper "Nuanced Music Emotion Recognition via Semi-Supervised Multi-Relational Graph Neural Network" has just been published at TISMIR, joint work together with Andreas Peintner, Marta Moscati, Yu Kinoshita, Richard Vogl, Peter Knees, Markus Schedl, Hannah Strauss, and Marcel Zentner [06/2025].  
            * Our workshop proposal "Beyond Algorithms: Reclaiming the Interdisciplinary Roots of Recommender Systems (BEYOND 2025)" has been accepted at RecSys 2025 - together with Christine Bauer and Alan Said [04/2025].  
            * Our paper "Hypergraph-based Temporal Modelling of Repeated Intent for Sequential Recommendation" was accepted at The Web Conference 2025 as a full paper (acceptance rate 19.83%, A*) [01/2025].  
            * The report on our Dagstuhl seminar ["Evaluation Perspectives of Recommender Systems: Driving Research and Education (Dagstuhl Seminar 24211"](https://drops.dagstuhl.de/entities/document/10.4230/DagRep.14.5.58) is out [11/2024].  
            * Our paper "Efficient Session-based Recommendation with Contrastive Graph-based Shortest Path Search" has just appeared in ACM Transactions on Recommender Systems [11/2024].  
            * Our paper "Are We Explaining Flawed Recommenders? Incorporating Recommender Performance for Evaluating Explainers" has been accepted at RecSys 2024 as an LBR paper [09/2024].  
            * Our paper ["Assessing aesthetic music-evoked emotions in a minute or less: A comparison of the GEMS-45 and the GEMS-9"](https://doi.org/10.1177/10298649241256252) was accepted for publication in the Musicae Scientiae journal [08/2024].  
    design: 
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: |-
      filters:
        folders:
          - publication
        featured_only: false
    design:
      columns: '2'
      view: citation
  - block: markdown
    id: projects
    content:
        title: Selected Projects
        text: |-
          * [Humans and Recommender Systems: Towards a Mutual Understanding](https://humrec.github.io/) (principal investigator)  
            funded by Austrian Research Fund (FWF)  
            2021-2025, 600,000 EUR
          * [GoStudent - Q\&A Matching](https://dbis.uibk.ac.at/gostudent-question-answering-system) (principal investigator)  
            funded by Austrian Research Promotion Agency (FFG)  
            2019-2020, 89,000 EUR 
          * [Digitization and Visualization of Archives and Collections](https://dbis-digivis.uibk.ac.at/mediawiki/index.php/Project_Digivis) (co-principal investigator)  
            funded by Region of Tyrol   
            2018-2020, 200,000 EUR
    design: 
      columns: '2'
  - block: markdown
    id: service
    content:
      title: Professional Service
      text: |-
        ### Conference Organization  
        * Conference on User Modeling, Adaptation and Personalization (UMAP) 2026 (Doctoral Consortium Chair)
        * Austrian Computer Science Day 2025 (Organizer)  
        * ACM Conference on Recommender Systems (RecSys) 2024 (Workshop Chair)  
        * Conference on User Modeling, Adaptation and Personalization (UMAP) 2024 (Track Chair Personalized Recommender Systems)
        * ACM Annual Conference on Intelligent User Interfaces (IUI) 2024 (Workshop and Tutorials Chair)  
        * Conference on User Modeling, Adaptation and Personalization (UMAP) 2022 (Track Chair Personalized Recommender Systems)
        * ACM Hypertext 2022 (Track Chair Adaptive Web and Recommender Systems)
        * Conference on User Modeling, Adaptation and Personalization (UMAP) 2021 (Late Breaking Results and Demo Chair)
        * International Society on Music Information Retrieval Conference (ISMIR) 2020 (Publication Chair)
        * International Society on Music Information Retrieval Conference (ISMIR) 2019 (Tutorials Chair)
        * Women in MIR at International Society on Music Information Retrieval Conference (ISMIR) 2018 (WiMIR Chair)

        ### Workshop Organization

        * [BEYOND 2025 Workshop](https://beyondrecsys.github.io/2025/): Beyond Algorithms: Reclaiming the Interdisciplinary Roots of Recommender Systems at ACM Recommender Systems 2025.    
        * [INTROSPECTIVES 2024 Workshop](https://introspectives.github.io/): Reflections on Recommender Systems Past, Present, and Future at ACM Recommender Systems 2024.    
        * Dagstuhl Seminar: [Evaluation Perspectives of Recommender Systems: Driving Research and Education 2024](https://www.dagstuhl.de/de/seminars/seminar-calendar/seminar-details/24211).  
        * [PERSPECTIVES 2023 Workshop](https://perspectives-ws.github.io/2023/): 3rd Perspectives on the Evaluation of Recommender Systems Workshop at ACM Recommender Systems 2023.  
        * [PERSPECTIVES 2022 Workshop](https://perspectives-ws.github.io/2022/): 2nd Perspectives on the Evaluation of Recommender Systems Workshop at ACM Recommender Systems 2022.
        * [PERSPECTIVES 2021 Workshop](https://perspectives-ws.github.io/2021/): Perspectives on the Evaluation of Recommender Systems Workshop at ACM Recommender Systems 2021.
        * 2nd WiMIR Workshop at International Society on Music Information Retrieval Conference (Project Guide for Multi-Dimensional User Models for MIR).
        * 1st International Workshop on Multi-Method Evaluation of Personalized Systems @UMAP 2018 – User Modelling, Adaptation and Personalization, 2018.
        * 23rd Workshop Grundlagen von Datenbanken 2011.

        ### Challenge Organization 
        * Multi-Author Analysis Task, PAN@CLEF 2025 (Task Chair)
        * Multi-Author Analysis Task, PAN@CLEF 2024 (Task Chair)
        * Multi-Author Analysis Task, PAN@CLEF 2023 (Task Chair)
        * Multi-Author Analysis Task, PAN@CLEF 2022 (Task Chair)
        * Style Change Detection Task, PAN@CLEF 2021 (Task Chair)
        * Style Change Detection Task, PAN@CLEF 2020 (Task Chair)
        * Style Change Detection Task, PAN@CLEF 2019 (Task Chair)


        ### Editorial Service
        * Guest editor: Special Issue "Perspectives on Recommender Systems Evaluation" in ACM Transactions on Recommender Systems (together with Christine Bauer and Alan Said) [2022-2024]  

        ### Reviewing for Conferences
        * ACM International Conference on Recommender Systems (RecSys) [2018-2022; best reviewer award nominee 2018; senior PC member 2024-2025]  
        * ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR) [2022, senior PC member 2023-2025]
        * Conference on User Modeling, Adaptation and Personalization (UMAP) [2019-2021, 2023-2024; senior PC member 2025; best reviewer award nominee 2023]
        * European Conference on Information Retrieval (ECIR) [2019, 2021-2023, 2024 (workshops), 2025]
        * Conference and Labs of the Evaluation Forum (CLEF) [2025 (Lab Proposals)]   
        * ACM International Conference on Information and Knowledge Management (CIKM) [2024, senior PC member for short papers 2024]
        * International Society for Music Information Retrieval Conference (ISMIR) [2016, meta-reviewer 2017-2022, 2024]
        * MuRS: Music Recommender Systems Workshop [2024-2025]  
        * First International Workshop on Graph-Based Approaches in Information Retrieval [2024]  
        * ACM International Conference on Web Search and Data Mining (WSDM) [2023]
        * The Web Conference [2022, senior PC member 2023]
        * International Workshop on Algorithmic Bias in Search and Recommendation [2020-2023]
        * Workshop on Adaptive and Personalized Explainable User Interfaces [2022]
        * International Symposium on Open Collaboration (OpenSym) [2021]
        * Workshop on Computational Humanities Research [2020-2021]
        * ACM International Conference on Multimedia (ACMMM) [2019-2020]
        * ACM Symposium on Applied Computing (SAC) [2015-2020]
        * Explainable User Models and Personalized Systems Workshop (ExUM) [2020]
        * ACM Conference on Web Science (WebSci) [2019]
        * Sound & Music Computing Conference (SMC) [2019]
        * Workshop on Explainable and Holistic User Modeling [2019]
        * Workshop Engineering Accountable Information Systems [2019]
        * International Workshop on Transparent Personalization Methods based on Heterogeneous Personal Data [2019]
        * International Conference on New Music Concepts (ICNMC) [2014-2019]
        * Hawaii International Conference on System Sciences (HICSS) [2016-2019]
        * Conference on Affective Computing and Intelligent Interaction (ACII) [2017, 2019]
        * CHI Conference on Human Factors in Computing Systems (CHI) [2018]
        * Workshop on Social Aspects in Personalization and Search (SoAPS) [2018]
        * International Conference on Semantic Systems (SEMANTiCS) [2014-2018]
        * Digital Humanities Austria (DHA) [2017-2018]
        * Workshop on Social Media for Personalization and Search (SoMePeaS) [2017]
        * International Conference on Advances in Semantic Processing (SemaPro) [2017]
        * Workshop on Linked Enterprise Data Services, Provenance, Linking and QualitY (LEDSPLaY) [2017]
        * Workshop on Engineering Computer-Human Interaction in Recommender Systems (EnCHIReS) [2016]
        * European Conference on Information Systems (ECIS, Social Media in Business and Society) [2016]
        * International Conference on Semantic Systems (SEMANTiCS), Poster Track [2014-2016]
        * Affect and Sentiment in Multimedia Workshop (ASM) [2015]
        * International Workshop on Social Media Retrieval and Analysis (Somera) [2014-2015]
        * European Conference on Information Systems (ECIS, Social Media Research and Analytics Track) [2015]
        * International Semantic Web Conference (ISWC) [2014]
        * International Conference on Semantic Systems (I-Semantics) [2012-2013]

        ### Reviewing for Journals
        * ACM Transactions on Recommender Systems (distinguished reviewer)  
        * ACM Computing Surveys  
        * ACM Transactions on Information Systems (TOIS)
        * ACM Transactions on Intelligent Systems and Technology (TIST)
        * Data Mining and Discovery
        * Data Mining and Knowledge Discovery
        * Engineering Applications of Artificial Intelligence: The International Journal of Intelligent Real-Time Automation
        * EPJ Data Science 
        * EURASIP Journal on Audio, Speech, and Music Processing
        * Expert Systems with Applications Journal
        * Frontiers in AI - Natural Language Processing (member of editorial team)
        * Frontiers in Research Metrics and Analytics - Research methods (member of editorial team)
        * Information Sciences (Informatics and Computer Science Intelligent Systems Applications)
        * International Journal of Multimedia Information Retrieval (IJMIR)
        * International Journal on Human-Computer Studies
        * Journal Concurrency and Computation: Practice and Experience
        * Journal of Grid Computing
        * Journal of Social Network Analysis and Mining (SNAM)
        * Knowledge and Information Systems (KAIS)
        * PLOS One
        * Transactions of the International Society for Music Information Retrieval (TISMIR)
        * User Modeling and User-Adapted Interaction (UMUAI)
    design: 
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: Dr. Eva Zangerle
      text: 
      email: eva.zangerle@uibk.ac.at
      phone: 
      appointment_url: 'https://calendar.app.google/hcoKrALACU8awZQk6'
      address:
        street: Technikerstr. 21A
        city: Innsbruck
        postcode: '6020'
        country: Austria
        country_code: AT
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
