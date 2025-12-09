# Workflow

![The SoFAIR workflow](https://sofairoa.github.io/documentation/img/workflow.png)

*Figure 1: The SoFAIR workflow*


The SoFAIR workflow (Figure 1) shows how stakeholders, tools and infrastructures work together.

1. An author deposits a piece of research software in a code repository.
2. The author then deposits a manuscript that contains either explicit or implicit mentions of that software.
3. The research paper is then harvested from the repository by CORE and software mentions extracted from the full text research paper using extended state-of-the-art ML tools (GROBID / Softcite (Lopez, et al., 2021)).
4. Via the CORE Repository Dashboard, a request to validate the extracted mentions is made available to the repository.
5. With the authorisation of the repository manager, the request is routed to the author (e.g. by means of an email notification) who validates this request.
6. Once validated, the repository issues an asset registration request to Software Heritage.
7. Software Heritage permanently archives the new software asset.
8. Software Heritage issues a permanent identifier for the new asset and sends this back to the repository.


For the full details on the workflow and the interactions between the various infrastructure component please follow the Workflow documentation at the link below:

[Workflow Documentation](https://sofairoa.github.io/documentation/)
