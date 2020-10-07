# Library Loans
This folder contains data regarding Devon Libraries loans. The data is published in line with [open data schema for library open data](https://schema.librarydata.uk/loans).

## Definition
A loan is the issuing of an item of stock to a member of the library service. A renewal of an item already on loan is counted as an additional loan. This data currently only contain physical issues

## Data
The data is published under the following headings:

**Local Auhority**; which in this data is always Devon, but is included so the data can be combined with other local authority library data where they are using the open data schema.
**Library name**; the library the data relates to. Most people will be interested in the named library buildings or mobile library services. There are however a number of other categories that issue items which the management system counts and are counted as a loan. These might be central services or local specific stock.
**Month**; the month that the number of loans is counted for, given as the Year-Month. i.e. 2020-06 is June 2020.
**Type**; the categories of library stock is broad, and has over time changed. As we manage two different library authorities they have also given different names to the same thing. To make the data simpler we have used compiled the data against a narrower set of categories, these are:
- Adult Audiobook
- Adult Fiction
- Adult Non Fiction
- Children and Teen Fiction
- Children and Teen Non-Fiction
- Children Audiobook
- DVD
- Misc
- Music CD
- Play
- Sheet Music
**Loans**; the number of loans of that type, made at the defined library in the defined month

The data is from April 2015 through to the current month and should be updated monthly.

## Missing Data
Due to changes in the library management system, data with this level of detail is not available for November and December 2017.

## Licence
All data in this repository in published under an [Open Government Licence (OGL)](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)

This means you are free to:

- copy, publish, distribute and transmit the Information;
- adapt the Information;
- exploit the Information commercially and non-commercially for example, by combining it with other Information, or by including it in your own product or application.

When doing so you must acknowledge the source of your data in your content. Please see the full licence for details.

## Further Information
If you require any further information about this data set, notice any errors, or make use of it in anyway we would be pleased to hear from you. Please email data@librariesunlimited.org.uk or raise a GitHub issue if you are familiar with the system.
