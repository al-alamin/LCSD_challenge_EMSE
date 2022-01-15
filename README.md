# LCSD Challenge EMSE
Replication package for journal version of low-code software development practitioners challenges discussed in Stack Overflow.


## Low Code Software Development
Low code software (LCS) development is an emerging paradigm that combines minimal source code with interactive graphical interfaces to promote rapid application development. LCS aims to democratize application development to software practitioners with diverse backgrounds. Given that LCS is a relatively new paradigm, it is important to learn about the challenges developers face during their adoption of LCSD platforms.

In this study, we download a large number of Stack Overflow posts that contain discussions about various low-code platforms. We apply topic modeling on the textual contents of the posts. We label the topics and categorize the topics into hierarchies. We analyze the popularity and difficulty of the topics. Our study offers several findings based on the four research questions as discussed below;

## Stack Overflow dataset
The data is collected from low-code development-related `33.7K` SO posts. The Stack Overflow July 2021 data dump is used. The dump can be downloaded from [archive.org](archive.org).

The final list of `64` low code related tags that we used to collect posts from StackOverflow is as follows:

```json
['apex-code', 'lotus-notes', 'domino-designer-eclipse', 'visualforce', 'salesforce-chatter', 'apex', 'salesforce-service-cloud', 'simple-salesforce', 'salesforce-ios-sdk', 'apex-trigger', 'oracle-apex-5', 'salesforce-lightning', 'salesforce-communities', 'oracle-apex-5.1', 'servicenow-rest-api', 'powerapps-formula', 'salesforce-marketing-cloud', 'powerapps-selected-items', 'powerapps-modeldriven', 'powerapps-collection', 'powerapps-canvas', 'oracle-apex-18.2', 'lwc', 'salesforce-development', 'oracle-apex-19.1', 'oracle-apex-19.2', 'outsystems', 'appian', 'quickbase', 'powerapps', 'oracle-apex', 'salesforce', 'zoho', 'mendix', 'servicenow', 'goolge-app-maker', 'pega', 'retool', 'vinyl', 'kissflow', 'bizagi', 'neutrinos-platform', 'rad', 'joget', 'filemaker', 'boomi', 'opentext', 'tibco', 'webmethods', 'conductor', 'temenos-quantum', 'shoutem', 'oracle-cloud-infrastructure', 'amazon-honeycode', 'convertigo', 'lotus-domino', 'genero', 'genesis', 'gramex', 'processmaker', 'orocrm', 'slingr', 'unqork', 'uniface', 'structr']
```

The extracted questions and answers based on these final tags are in `Questions.pkl` and `Answers.pkl` files, respectively.

### Replication Materials to Answer to RQs in the paper:
- __'Codes'__ folder includes all the data and code we used to filter data, run topic modeling, generate graphs, charts, tables etc inside a Jupyter notebook.

- __RQ1 supporting files__: TopicModelingRun.zip
- __RQ2 supporting files__: 'Codes' folder.
- __RQ3 and RQ4 supporting files__: RQ_Annotation.csv, Annotation Guideline.docx
- __RQ5 supporting files__: Popularity.xlsx, Difficulty.xlsx
