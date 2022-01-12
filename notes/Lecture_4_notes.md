# Lecture 4 notes

# Celine Lecture

## What is research data? What to include in a data management plan

- Observations
- We don't want to include everything
- Could be raw or processed data

## What not to include in DMP?

- Preliminary analysis
- Personal communication with colleagues
- Peer review

## What is personal data?

### Suggestion

- Any data with which we can identify the person who the data is about

### Answer:

- Data that can directly identify a person e.g. name, home address, pictures, voice recordings
- Data that can indirectly identify a person e.g. MAC address

## What is sensitive personal data?

### Suggestion

- Maybe your IP address which can lead to a hack

### Answer

- More broadly, any data that can cause harm to the person
- It is forbidden to process sensitive data, Maybe allowed if
    - There is consent from the person
    - The data is made publicly
    - Important to safeguard human lives

# What is DMP?

It is a document that describes the how the data will be used before, during and after the research project

FAIR data: Findable, Accessible, Interoperable, Reusable

## Aims

- Safety, efficiency, comply with funding mandates

### Time efficieincy

- Helps to save time at the end of the day
- There are papers showing correlation between citation rate and sharing data
- Helps to clarify the budget

## Approach

- Before:
- During: how to maintain integrity
- After: Documentation

## What to consider at the very begging at the beginning of a project (Group discussion)?

## Data description

- Data to be re-used
    - Price, licenses
- New data
    - Justify why new data
- Explain data formats and justify e.g. Staff expertise, preferred for open formats etc.
    - Prefer open formats
- Detail the volume of data

## Documentation

- Describe the metadata describing the data,
- Use standards in the community
- Tools exist to generate metadata
- Use controlled vocabularies
- How will the documentation be captured and where will it be stored

## Storage and backup

- Where to store the data?
- Have at least 3 backups
- Data Security
    - Data access rights
    - Data recovery strategies

## Legal and ethical requirements

- In FR ask CNIL
- Responsabilities
    - Data protection officer
    - Lab director
- Collect as little data as necessary
- Collect as little personal data as necessary
- When collecting data, use consent forms to gain consent from participant
- Anonymise personal data (e.g. by hand or with tools like Amnesia, ARX)
- Ensure recipients of data are trusted

## Data sharing and long-term preservation

- When will the data be shared?
- What software will be needed to access the data?
- Carefully choose licenses

## Data management responsibilities

- Who will be responsible for Data Management

Be sure to adapt data management plan to

- Domain
- Local laws
- Funding organisations

# Homework comments

- Check where the data came from?
- How to make the data more persistent
    - Use a hash of the data
- Explore the data types of the columns
- What to do with data that are not understandable e.g. `XXXX` in year or `XX` for department
- Departments in France change over time
- How did _*Prenom_Rares* come about?
    - Look at the description of the data set

# Jean-Marc Lecture

## Data Production

- What is the purpose of the data set?
    - Who will be the target of the analysis
- What method was used?
    - Survey on the population
- How was the dataset produced?
    - Nature of the items in the data

## Analysis of the set of variables

- What are the variable types?
- Identify the roles of the variables?
- Build a metadata document

## Usage of variables

- Category of respondents

## Data Production process

Question ⇒ Experiment, Survey ⇒ Decision

Decision = Risk

- Quality of the data influences the quality of the decision

## Criteria for data quality

- Relevance
- Accuracy
- Time
    - e.g. doing experiments in the cloud is affected by the time the experiment was done
- Comparability
- Coherence

## Pre-processing of data

- Are there missing values
- Ratio of missing samples
- How to handle missing data (replace, remove)