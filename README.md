# Open Data Everywhere

[Presentation](https://docs.google.com/presentation/d/1qCjCK7lwv2kNcCf-k3Uq8w1kd5_jpX9bqN8NtmlRrMU/edit?usp=sharing)


## Objectives

 1. **Discovery**
    Be a central index or repository for open data everywhere. Crowd-source sources. Make adding sources easy: eg., CKAN crawl+import.

 2. **Useability**
    _Current reality: download a dataset, spend hours cleaning, converting, transforming, before starting to do any work on it._
    For every available dataset, allow user-contributed cleaning and conversion scripts. For end users, this is the USP: someone makes the data useable once for the benefit of everyone, for each dataset.

 3. **Feedback & Improvement**
    Create avenues for the primary sources to improve their data and publishing methods, further widening the benefit of the scripts.


## Risks + Mitigation

  * Aggregating data is obvious, so there's a big n+1 problem.
    - Most aggregations I found in research were:
        * List of lists of data sources, often one-offs
        * Big vertical data platforms that suck up data and present a unified tool. Not open, don't have everything, no feedback.

  * Network effect is hard
    - Each script added can create a lot of value. Can save users hours or even days of effort. Maybe this creates enough value to overcome the initial network effect cost.
    - DG can invest in bootstrapping the platform for key data sources. CKAN import plugin is open source, and we have a lot of data in AidData.

  * Data integrity
    - Scripts can fix data issues, but can also create issues.
    - For users of the data, now they are relying on the acuracy of both the original source, and the primary script author.
    - Hopefully publishers can be incented through the feedback mechanisms to help: "bless" certain scripts? re-publish cleaned data?

  * Scope creep
    - There are a ton of ways this can go.
    - Pick a small set of features that create a lot of value.
    - Pick a small scope of data theme: Datasets provided by government?


## Questions

  * Open Contracting -- I don't know enough about Open Contracting to know, would this have any use to Open Contracting data + users?
