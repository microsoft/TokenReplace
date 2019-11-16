---
page_type: sample
languages:
- yaml
products:
- azure-devops
description: "This is a simple example of how to replace tokens in code on-the-fly during a build script."
urlFragment: "https://github.com/microsoft/TokenReplace"
---

# Official Microsoft Sample

<!-- 
Guidelines on README format: https://review.docs.microsoft.com/help/onboard/admin/samples/concepts/readme-template?branch=master

Guidance on onboarding samples to docs.microsoft.com/samples: https://review.docs.microsoft.com/help/onboard/admin/samples/process/onboarding?branch=master

Taxonomies for products and languages: https://review.docs.microsoft.com/new-hope/information-architecture/metadata/taxonomies?branch=master
-->
## Introduction
This is a simple example of how to replace tokens in code on-the-fly during a build script.  Two examples are provided, one using a build variable (declared as an evironment variable in the build script), the other using project secrets (maintaed under settings -> ssecrets).

## Contents

Outline the file contents of the repository. It helps users navigate the codebase, build configuration and any related assets.

| File/folder         | Description                                        |
|---------------------|----------------------------------------------------|
| `README.md`         | This README file.                                  |
| `LICENSE`           | The license for the sample.                        |
|                     |                                                    |
| `.github/workflows` | Sample search/replace build action                 |
| `Example.json`      | Sample json file with UName and PWord placeholders |
| `Example.xml`       | Sample xml file with a CString placeholder         |

## Prerequisites

GitHub account with build/actions enabled.

## Setup

Simply copy the .yml file provided and modify to suit the project needs.

## Runnning the sample

GitHub will automatically run .yml files stored in the .github/workflows folder.  To enable it on your own repository, simply ensure the .yml file you use is located in your respective repo in the same location.

## Key concepts

The purpose of this tool is to show how one can replace text inside of a source file at build-time and replace it with either secrets or environemnt (build) varaibles.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
