# Why RAP?

Reproducible Analytical Pipelines require a range of tools and techniques to implement that can be a challenge to overcome; so why bother learning to RAP?

* Does your team spend too much time moving data between various softwares?
* Could you reproduce your most recent publication's stats? How about from five years ago?
* What would your team do with their time if it was freed up from copying and pasting?
* What proportion of spreadsheets contain errors?

## The current statistics production process

Here we use the production of official statistics in Government; altough this process varies widely perhaps it looks something like this?

<a href="https://gdsdata.blog.gov.uk/2017/03/27/reproducible-analytical-pipeline/" target="_blank"><img src="images/messy_pipeline.png" style="display: block; margin: auto;" /></a>

Broadly speaking, data are extracted from a datastore (whether it is a [data lake](https://en.wikipedia.org/wiki/Data_lake), [database](https://en.wikipedia.org/wiki/Database), spreadsheet, or [flat file](https://en.wikipedia.org/wiki/Flat_file_database)), and are manipulated in a proprietary statistical software package, and possibly in proprietary spreadsheet software. Formatted tables are often then ‘copy and pasted’ into a word processor, before being converted to pdf format, and finally published to [GOV.UK](https://www.gov.uk/). This is quite a simplification, as statistical publications are usually produced by several people, so this process is likely to be happening in parallel many times.

### The problem with this approach



A key element in this process is quality assurance (QA). Each publication is meticulously checked to ensure the accuracy of the statistics being produced. This may take place throughout the production process or at the end prior to publication. Traditionally, QA has been a manual process which can take up a significant portion of the overall production time of a publication, as any changes will require the manual process of production to be repeated.
