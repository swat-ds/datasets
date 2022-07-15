# Philadelphia African American Census 1847
This survey of Philadelphia's Black population, conducted by a committee of Quakers in 1847, contains forty-three elements of information for each of more than four thousand households. Source material from, and dataset prepared by, [Friends Historical Library of Swarthmore College](http://www.swarthmore.edu/friends-historical-library)

## About the census

In 1847, a committee of Quakers appointed by the Meeting for Sufferings of Philadelphia Yearly Meeting (Orthodox) set out to document Philadelphia's African American residents. The purpose of the committee initially was to prepare a report on the slave trade, but after further consideration, the committee determined that it was also important to examine the condition of the African-American population of Philadelphia both to document the existence of an "industrious and thriving" portion of that population and to discover what portion of the community may have been in need of attention and assistance. Their survey was distilled into a 44 page report published as [_A Statistical Inquiry into the Condition of the People of Colour of the City and Districts of Philadelphia_ (1849)](paac1847censusreport.pdf).

For more information visit the [online exhibit accompanying the  study](https://ds-pages.swarthmore.edu/paac/).

Original source: Census of Black People, 1847, [Philadelphia Yearly Meeting (Orthodox) Representative Committee records, RG2/Pho](http://archives.tricolib.brynmawr.edu/repositories/9/resources/5742), Friends Historical Library of Swarthmore College.

## About the project
As of February 2022, a live version of the Philadelphia 1847 Census Project can be found on https://ds-pages.swarthmore.edu/paac/. For more detail about the project, see the readme for [1847-sof-black-census](https://github.com/swat-ds/1847-sof-black-census). A brief, non-exhaustive history of the project is as follows:
- 2002 Original site built.
- 2017 Dataset put on GitHub at [datasets/1847census](https://github.com/swat-ds/datasets/tree/main/1847census)
- 2019 summer. New website built as part of Swarthmore Projects for Educational Exploration & Development (SPEED). See [1847-sof-black-census](https://github.com/swat-ds/1847-sof-black-census).
- 2020 summer. Digital Scholarship librarians make some tweaks to [1847-sof-black-census](https://github.com/swat-ds/1847-sof-black-census), and add the derivative CSVs created during SPEED to the datasets repo [datasets/1847census](https://github.com/swat-ds/datasets/tree/main/1847census).
- 2020 fall. Digital Scholarship librarian creates [paac-jekyll](https://github.com/swat-ds/paac-jekyll). At this point some changes were made (e.g., linking to the 2002 site through the Wayback Machine)
- 2021 Feb-Mar. Digital Scholarship librarian has Lib-Lab students work on making [paac-jekyll](https://github.com/swat-ds/paac-jekyll) more accessible. It seems that paac-jekyll becomes the basis for the live site around this time.
- 2021 (spring?). Links to Ancestry.com scans of census are added to https://ds-pages.swarthmore.edu/paac/about/, but changes aren't pushed to GitHub.
- 2021 summer. Digital Scholarship librarian makes a few changes to [datasets/1847census](https://github.com/swat-ds/datasets/tree/main/1847census) before departing Swarthmore College
- 2021 fall. Friends Historical Library student worker cleans up the data in [datasets/1847census](https://github.com/swat-ds/datasets/tree/main/1847census).
- 2022 February. Friends Historical Library digitizes original census volumes and edits [paac-jekyll](https://github.com/swat-ds/paac-jekyll) to link to digitized volumes
- 2022 July. Friends Historical Library student worker digitizes and indexes Blockley Almshouse census data. Uploads to GitHub at [datasets/1847census](https://github.com/swat-ds/datasets/tree/main/1847census).

## About the data
The dataset contains forty-three elements of information for each of more than four thousand African American households in Philadelphia. Data from the Blockley Almshouse is also included. Above and beyond the basic information of name and address, the 1847 census is incredibly rich in detail, including such datapoints as: occupation, education, literacy, rent and taxes paid, whether the person was born in slavery, amount paid for freedom, and much more.

### Main datasets
These contain all or most of the data from the manuscript ledger.
- `sofaac-raw-export` / Filemaker database export from initial manuscript ledger transcription
- `sofaac-transcribed` / ID, household data columns as transcribed excluding duplicate rows
- `sofaac-normalized` / ID, cleaned and normalized columns (does not include all transcribed columns)
- `sofaac-blockleycensus` / Transcribed and cleaned data from Blockley manuscript
- `sofaac-blockley-avgs&totals` / Transcribed data on the averages and totals of people in the Almshouse from 1846-1848

### Secondary datasets
These contain topical subsets of the overall data.
- `sofaac-names` / ID, Last Name, First Name, Street Number, Street Name
- `sofaac-*-occupations` / ID, Household, Normalized Occupation, Count / Created for the [occupations visualization](https://ds-pages.swarthmore.edu/paac/occupations/)
- `sofaac-*-occupations-freq` / Normalized Occupation, Total / Created for the [occupations visualization](https://ds-pages.swarthmore.edu/paac/occupations/)

Data cleaned and normalized with the help of Alice Huang ('22), Bilal Soukouna ('22), Helen Huh ('21), and Katie Knox ('21) as part of 2019 Swarthmore Projects for Educational Exploration & Development ([SPEED](https://www.swarthmore.edu/its/swarthmore-projects-educational-exploration-and-development-speed-program)). Additional data cleaning by Yolanda Hu ('22) in 2021. Data from the Blockley Almshouse digitized and added by Whitney Grinnage-Cassidy ('24) in 2022.

## Using the data
This dataset is licensed as [Creative Commons Attribution-ShareAlike (CC BY-SA)](https://creativecommons.org/licenses/by-sa/4.0/)

**Please cite this dataset:**

Philadelphia Yearly Meeting (Orthodox) Representative Committee, _Philadelphia African American Census 1847_, Friends Historical Library of Swarthmore College, [version or date of last update], [url].
