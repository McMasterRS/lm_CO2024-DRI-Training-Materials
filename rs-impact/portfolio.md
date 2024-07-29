---
layout: default
title: Building Portfolio
parent: Research Software and Research Impact
nav_order: 3
---

## Building Your Researcher Portfolio with ORCID

DOIs and ORCIDs work together to enhance the credibility, visibility, and attribution of scholarly research. DOIs provide unique identifiers for individual research outputs, while ORCIDs provide unique identifiers for researchers themselves. By linking the two, your scholarly works can be accurately attributed to you, facilitating better tracking of research impact and establishing reliable connections between researchers and their contributions. In the upcoming section we will explore the steps to connect your research software development with DOI and ORCID persistent identifiers to create a research profile.  

### Generate a DOI for Your Research Software

To generate a DOI for software, we will use the public and popular [Zenodo](https://about.zenodo.org/) repository. Zenodo is a free, open-access research data repository and publishing platform that facilitates the sharing, archiving and dissemination of research outputs. It is an initiative developed and operated by CERN (European Organization for Nuclear Research) and is part of the European OpenAIRE project.  

In this example, we will demonstrate how to create a repository on Zenodo directly from your _public_ repository on GitHub. (You cannot create a DOI to a private repository.) Per your Software Management Plan, this repository should include your software license as well as licenses for any software libraries included.

It is worth noting here, again, that while GitHub is a good version control system for managing software versions, performing collaborative development, it is not considered a persistent repository for software. There are too many reaosons why a git repository might have its location or reference change. We use Zenodo in this example as such a persistent software repository, which is necessary for identifiers like DOIs to be persistent.

### Steps to Generate a DOI for Your Research Software

First, create a Zenodo account. You may use an email + password authentication method or single sign-on with GitHub or ORCID accounts.  

![zenodo-sso](assets/img/zenodo-sso.png)  

Once you have created and logged into your Zenodo account, click the drop-down menu (in the banner, top-right), which contains your Zenodo registration email, and select GitHub.  

![zenodo-1](assets/img/zenodo-1.png)  

Follow the instructions provided to link your GitHub account with Zenodo. Once you have linked your GitHub account with Zenodo, you will see all your public repositories from the Zenodo side. In Zenodo, scroll to the repository you want to index and toggle the switch box next to it to turn on automatic preservation. In the screenshots below we demonstrate these actions on the software repository `quantum-stable-matching`.

![zenodo-2](assets/img/zenodo-2.png)  

Then go to the GitHub repository and [create a release](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository). Zenodo will then automatically download the sources of the release and register a DOI. Once you have created a release, you will see the repository is marked as "Received" (in yellow) in Zenodo.  

> Zenodo will create a project-specific DOI and a version-specific DOI when indexing the first release. For subsequent releases, only version-specific DOIs will be created. You are encourage to share the project-specific DOIs to promote your software, as the project-specific DOIs will direct the users to the latest version of your project, and uses the version-specific DOIs in scenarios where reproducibility is desired.  

![zenodo-3](assets/img/zenodo-3.png)  

It will take approximately 1 hour for Zenodo to generate a DOI and about a day for the DOI to be effective on [doi.org](https://www.doi.org/) through their respective background automation processes.

![zenodo-4](assets/img/zenodo-4.png)

### Adding Your Research Software to Your ORCID Record

Now that you have a DOI for your research software project, it is time to add it to your ORCID profile.  

If you do not yet have an ORCID record, [Register on ORCID](https://orcid.org/register) to create one.

Log in to your ORCID record. Go to "Works" and click the "Add" button. Select "Add DOI". Enter the DOI of your project and then click "Retrieve work details from DOI".  

![orcid-1](assets/img/orcid-1.png)  
![orcid-2](assets/img/orcid-2.png)  

Edit the work details and the click "Add this work to your ORCID record".  

![orcid-3](assets/img/orcid-3.png)  

You will see the new entry in the ORCID work record.  

![orcid-4](assets/img/orcid-4.png)  

At this point you will have deposited a persistent copy of your software release on Zenodo, created a DOI for this software project and release, and linked this work with your ORCID profile. 
