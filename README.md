:arrow_heading_up: Go back to the [Reference System Sotfware repository](https://github.com/COPRS/reference-system-software) :arrow_heading_up:

# rs-issues
## Purpose
This repository is dedicated to the creation of **issues** related to the Reference System Software.

Issues can be EPICs, User Stories, Bugs... that need to be manipulated by the different teams within the development phases. 

Once a week, a meeting is held by a dedicated team to review new bugs and assign them to the developers. Existing bugs can also be updated to change the priority for e.g.

## Creating a new bug
When creating a bug, choose the template named ":lady_beetle: Bug User", unless you are from the development, ops and ivv team. If you don't know which template to choose, you are probably an end user, so it's safe to use the ":lady_beetle: Bug User" template. It comes with predefined labels and assignees, please **don't change** them. The end user shall only edit the content like *Environement*, *Steps To Reproduce* and attach evidences (logs and data set).

Before creating a new ticket, please make sure that an existing ticket with the same issue is not already created.

Click here to create a new ticket : [GitHub COPRS issues](https://github.com/COPRS/rs-issues/issues/new/choose)

## Labels
As this repository is the only source repository for every Zenhub workspaces, labels shall be used in order to classify tickets in the appropriate workspaces. The rule is the following: one label is linked to one workspace.
| Label | Description |
| :-- | -- |
|[![label](https://img.shields.io/static/v1?label=&message=ADS%20eng&color=024498)](https://github.com/COPRS/rs-issues/labels/ADS%20eng)|Tickets dedicated to ENG team|
|[![label](https://img.shields.io/static/v1?label=&message=Blocking&color=B60205)](https://github.com/COPRS/rs-issues/labels/Blocking)|Blocking issue|
|[![label](https://img.shields.io/static/v1?label=&message=bug&color=d73a4a)](https://github.com/COPRS/rs-issues/labels/bug)|Something isn't working|
|[![label](https://img.shields.io/static/v1?label=&message=CCB&color=6781B8)](https://github.com/COPRS/rs-issues/labels/CCB)|Issue for CCB|
|[![label](https://img.shields.io/static/v1?label=&message=COTS&color=308C5C)](https://github.com/COPRS/rs-issues/labels/COTS)|COTS used in sub-systems|
|[![label](https://img.shields.io/static/v1?label=&message=CR&color=BFD4F2)](https://github.com/COPRS/rs-issues/labels/CR)|Change Request|
|[![label](https://img.shields.io/static/v1?label=&message=CS-FRANCE%20dev&color=D4C5F9)](https://github.com/COPRS/rs-issues/labels/CS-FRANCE%20dev)|Ticket dedicated to CS-FRANCE development|
|[![label](https://img.shields.io/static/v1?label=&message=Deployment&color=0FB669)](https://github.com/COPRS/rs-issues/labels/Deployment)|Only bug handling deployment (use%20Epic%20for%20US)|
|[![label](https://img.shields.io/static/v1?label=&message=dev_bug&color=E22800)](https://github.com/COPRS/rs-issues/labels/dev_bug)|Something isn't working - internal to dev|
|[![label](https://img.shields.io/static/v1?label=&message=documentation&color=0075ca)](https://github.com/COPRS/rs-issues/labels/documentation)|Improvements or additions to documentation|
|[![label](https://img.shields.io/static/v1?label=&message=duplicate&color=cfd3d7)](https://github.com/COPRS/rs-issues/labels/duplicate)|This issue or pull request already exists|
|[![label](https://img.shields.io/static/v1?label=&message=enhancement&color=a2eeef)](https://github.com/COPRS/rs-issues/labels/enhancement)|New feature or request|
|[![label](https://img.shields.io/static/v1?label=&message=Epic&color=3E4B9E)](https://github.com/COPRS/rs-issues/labels/Epic)|Issue type is an epic|
|[![label](https://img.shields.io/static/v1?label=&message=good%20first%20issue&color=7057ff)](https://github.com/COPRS/rs-issues/labels/good%20first%20issue)|Good for newcomers|
|[![label](https://img.shields.io/static/v1?label=&message=help%20wanted&color=008672)](https://github.com/COPRS/rs-issues/labels/help%20wanted)|Extra attention is needed|
|[![label](https://img.shields.io/static/v1?label=&message=hmi&color=7D0367)](https://github.com/COPRS/rs-issues/labels/hmi)|hmi category|
|[![label](https://img.shields.io/static/v1?label=&message=infra&color=0e8a16)](https://github.com/COPRS/rs-issues/labels/infra)|Infra(structure%20,%20Platform%20and%20basic%20services) category|
|[![label](https://img.shields.io/static/v1?label=&message=invalid&color=e4e669)](https://github.com/COPRS/rs-issues/labels/invalid)|This doesn't seem right|
|[![label](https://img.shields.io/static/v1?label=&message=ivv&color=ABF941)](https://github.com/COPRS/rs-issues/labels/ivv)|Ticket created by the ivv team|
|[![label](https://img.shields.io/static/v1?label=&message=mon&color=98C033)](https://github.com/COPRS/rs-issues/labels/mon)|mon(itoring) category|
|[![label](https://img.shields.io/static/v1?label=&message=ops&color=72F652)](https://github.com/COPRS/rs-issues/labels/ops)|Ticket from ADS operation team|
|[![label](https://img.shields.io/static/v1?label=&message=perfo&color=834A0A)](https://github.com/COPRS/rs-issues/labels/perfo)|perfo(rmance) category|
|[![label](https://img.shields.io/static/v1?label=&message=priority:blocking&color=E01204)](https://github.com/COPRS/rs-issues/labels/priority:blocking)|Set the priority to blocking because the production is blocked|
|[![label](https://img.shields.io/static/v1?label=&message=priority:major&color=252774)](https://github.com/COPRS/rs-issues/labels/priority:major)|Set the priority to major because the production is heavily impacted|
|[![label](https://img.shields.io/static/v1?label=&message=priority:minor&color=f9d0c4)](https://github.com/COPRS/rs-issues/labels/priority:minor)|Set the priority to minor because the production is (almost) not impacted|
|[![label](https://img.shields.io/static/v1?label=&message=pro&color=B182B8)](https://github.com/COPRS/rs-issues/labels/pro)|pro(cessing) category|
|[![label](https://img.shields.io/static/v1?label=&message=question&color=AD027A)](https://github.com/COPRS/rs-issues/labels/question)|Further information is requested|
|[![label](https://img.shields.io/static/v1?label=&message=Reconsolidation&color=BFDADC)](https://github.com/COPRS/rs-issues/labels/Reconsolidation)|Issue had been pulled in sprint|
|[![label](https://img.shields.io/static/v1?label=&message=secu&color=3C5A15)](https://github.com/COPRS/rs-issues/labels/secu)|secu(rity) category|
|[![label](https://img.shields.io/static/v1?label=&message=Tech&color=EFFC09)](https://github.com/COPRS/rs-issues/labels/Tech)|Related to (new) technology|
|[![label](https://img.shields.io/static/v1?label=&message=test&color=48B113)](https://github.com/COPRS/rs-issues/labels/test)|test(ability) category|
|[![label](https://img.shields.io/static/v1?label=&message=WERUM%20dev&color=ECD168)](https://github.com/COPRS/rs-issues/labels/WERUM%20dev)|Ticket dedicated to WERUM development|
|[![label](https://img.shields.io/static/v1?label=&message=wontfix&color=ffffff)](https://github.com/COPRS/rs-issues/labels/wontfix)|This will not be worked on|
|[![label](https://img.shields.io/static/v1?label=&message=workaround&color=fef2c0)](https://github.com/COPRS/rs-issues/labels/workaround)|Workaround activated|

All labels can be found here: https://github.com/COPRS/rs-issues/labels
