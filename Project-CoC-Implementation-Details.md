# OpenJSF Project Code of Conduct Implementation Details

This document is a guide for Projects to safely implement the OpenJS Foundation Code of Conduct policy.  

## Adding the Foundation Code of Conduct to your Project

Adopting the Foundation Code of Conduct is a requirement for all OpenJSF projects. Completing this action will meet the first requirement in the [Project Onboarding Checklist](https://github.com/openjs-foundation/project-onboarding/blob/master/ISSUE_TEMPLATE/00-project-onboarding-checklist-template.md).

Projects may add the Foundation's Code of Conduct a few different ways - the choice is left to the project based on what best suits its size and community. 

You may place your CoC file in an Admin or Meta repository but it must be discoverable from any project repo. 

### Option 1 - Leverage .github Directory

Create a CODE_OF_CONDUCT.md file, copying [Code of Conduct](https://code-of-conduct.openjsf.org/) in its entirety. In the [`Reporting - Project Spaces` section](https://github.com/openjs-foundation/cross-project-council/blob/master/CODE_OF_CONDUCT.md#project-spaces), update the language to include your project's reporting email: 

`For reporting issues in spaces managed by <YOUR PROJECT NAME>, use the email <YOUR REPORTING EMAIL>`

Save this file in your organization's .github directory (this is a root directory, the same directory you may already use for things like issue templates). For better discovery of the Code of Conduct, link to it in your .github directory via the project README, or via a CoC.md file that links there.

### Option 2 - Linking

Create a CODE_OF_CONDUCT.md file for your project repositories with the following text:

`This project adheres to the [OpenJS Foundation Code of Conduct](https://code-of-conduct.openjsf.org/). Please email <PROJECT REPORTING EMAIL> with questions or to report a violation.`

### Option 3 - Full Document

Create a CODE_OF_CONDUCT.md file for each of your project repositories, copying [Code of Conduct](https://code-of-conduct.openjsf.org/) in its entirety. In the [`Reporting - Project Spaces` section](https://github.com/openjs-foundation/cross-project-council/blob/master/CODE_OF_CONDUCT.md#project-spaces), update the language to include your project's reporting email: 

`For reporting issues in spaces managed by <YOUR PROJECT NAME>, use the email <YOUR REPORTING EMAIL>` 