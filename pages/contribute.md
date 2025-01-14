---
layout: page
title: Contributing data
permalink: /contribute/
hero_image: "/../images/bg/IMG_7177.jpg"
---

We are continuously looking for new data to be included in **BioDeepTime**. Optimally, these should be uploaded to one of our [source databases]({{site.url}}{{site.baseurl}}/database/contributing/), from where we can access the data in the next update. However, if adding your data in such a way is not feasible, it can be incorporated directly into **BioDeepTime**. Please, [get in touch with us]({{site.url}}{{site.baseurl}}/contact/), if you would like to contribute! 

## Criteria for data to be contributed 

**BioDeepTime version 1.0** targeted the highest-quality available time series data with a goal of analyzing community turnover driven by environmental factors. As such, the following criteria were used to create the database.

### (1) Minimum 10 time points
* Shorter time series were omitted due to focus on longer-scale community dynamics and statistical power limitations.
* We define a time point as a unique combination of age and depth for a sample. In some time series, low resolution of ages has resulted in identical age estimates for neighboring samples but they are considered distinct because they occur at different depths.

### (2) Allows community-level analysis
* The intended use of the database is for community-level analyses. As such, it was required that all individuals in the sample were identified to the lowest possible taxonomic level (ideally species-level, but genus and family level are also present in the database). Data that focused only on selected species within the sample were omitted. 
* Data types included in BioDeepTime include counts, flux, relative abundances, or presence. 


### (3) Internally consistent taxonomy

* Ideally, taxonomy for all groups would be synonymized across time series; however, since analyses are being done per time series, we require the taxonomy within a time series to be consistent with itself.
* Outside of Neotoma and Triton, where extensive effort has been made to synonymize taxonomy across time series (e.g., Mottl et al. 2021; Fenton et al. 2021), we do not recommend combining data across multiple time series because differences in taxonomy will most likely  bias analyses.
* Taxonomy may not be consistent with accepted nomenclature because this was not strictly necessary for the intended community analyses.
* Whenever possible, higher level taxonomy (i.e., above Genus) should be included.

### (4) Available or calculable temporal information (with generally understood uncertainties)
* Intended community turnover analyses require absolute age estimates for samples, particularly when attempting to correlate to potential causative environmental drivers.
* Many fossil time series—for instance from the Paleobiology Database—were omitted because of inherent uncertainties in sample ages. For example, ages based solely on stratigraphic position at the resolution of a geological stage can have uncertainties of hundreds of thousands or millions of years. Future versions of BioDeepTime will attempt to include these types of records, after the age models associated with them have been improved.


## Spreadsheet template

If you wish to contribute data, feel free to check out our [new, simplified spreadsheet template]({{site.url}}{{site.baseurl}}/downloads/bdt_simplified_template.xlsx) for quick-formatting data to be added to BioDeepTime (see table and field descriptions on the [database structure]({{site.url}}{{site.baseurl}}/databases/structure/) page). 

