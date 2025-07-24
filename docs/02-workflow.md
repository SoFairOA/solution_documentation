# Workflow

The SoFAIR workflow (Figure 1) shows how stakeholders, tools and infrastructures work together. An author deposits a piece of research software in a code repository [1]. The author then deposits a manuscript that contains either explicit or implicit mentions of that software [2]. The research paper is then harvested from the repository by CORE and software mentions extracted from the full text research paper using extended state-of-the-art ML tools (GROBID / Softcite (Lopez, et al., 2021)) [3]. Via the CORE Repository Dashboard, a request to validate the extracted mentions is made available to the repository [4] and, with the authorisation of the repository manager, routed to the author (e.g. by means of an email notification) who validates this request [5]. Once validated, the repository issues an asset registration request to Software Heritage [6] who permanently archive the new software asset [7] and issue a permanent identifier for the new asset and send this back to the repository [8].

![The SoFAIR workflow](https://sofairoa.github.io/documentation/img/workflow.png)

*Figure 1: The SoFAIR workflow*


For the full details on the workflow and the interactions between the various infrastructure component please follow the Workflow documentation at the link below:

[Workflow Documentation](https://sofairoa.github.io/documentation/)

