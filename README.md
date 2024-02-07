# Welcome to the Model Atlas of The Earth (M@TE)

## Model submission overview and objectives

* M@TE models begin their life as github repositories, based on a [simple template](https://github.com/ModelAtlasofTheEarth/mate_model_template)
* New models are spawned using the [github issues functionality](https://github.com/ModelAtlasofTheEarth/Model_Submission/issues), within this repostory
* We provide workflows (using github actions) that aim to reuse as much existing metadata as possible
* The result is a model repository that comes with a rich metadata document, based on the [Ro-Crate](https://www.researchobject.org/ro-crate/) project
* This process also assembled material so we can feature you model on the [M@TE website](https://mate.science)

## What happens and when

*  M@TE models begin their life as Github repositories
*  To manage large file payloads, and to provide long term storage,  we copy your model repository to our server on NCI
*  This process also results in a DOI being minted for your model

## Model submission workflow:

_Note: Workflows are currently in development!_

**Make a new model request:** 
* open a new issue using the [New model request](https://github.com/ModelAtlasofTheEarth/Model_Submission/issues/new/choose)
* fill in as much information as you can and submit the issue
* This will trigger workflows that source metadata relavant to your model
* At the bottom will see a report on the information for

**Request a review:**
* If you are satisfied with the information contained in the report, 
* add a https://github.com/ModelAtlasofTheEarth/Model_Submission/labels/review%20requested label to the issue

**Model repository creation**
* The [model_reviewers`](https://github.com/orgs/ModelAtlasofTheEarth/teams/model_reviewers) team will add an https://github.com/ModelAtlasofTheEarth/Model_Submission/labels/approved label to the issue
* this triggers the creation of a repository for your model based in this template

**Upload model to our [NCI](https://nci.org.au/) Server**
* Add an htts://github.com/ModelAtlasofTheEarth/Model_Submission/labels/upload%20to%20NCI label to the model submission issue
* The [model_reviewers`](https://github.com/orgs/ModelAtlasofTheEarth/teams/model_reviewers) team will contact you via email to provide accesss to out server
* This will allow the large file payload to be added to you model

Model published
* Your model will be https://github.com/ModelAtlasofTheEarth/Model_Submission/labels/published on the NCIs GeoNetworkCatalog
* It will recieve a DOI and this will be automatically added to your model metadata
* Your model will be featured on the M@TE website
