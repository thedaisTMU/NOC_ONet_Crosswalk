# NOC to O*Net Crosswalk
To learn more about what we did: visit this blog: https://brookfieldinstitute.ca/crosswalk-blog-post/
This repository currently contains 3 CSV file, noc2016_onet20.csv allows crosswalk between NOC 2016 and ONET version 20 with 1038 rows (1039 with the headers) It has the following columns:
*  **noc**: NOC-4 Codes
*  **noc_title**: Title of the NOC Occupation
*  **onet** O\*Net code
*  **onet_title** Title of the O\*Net Occupation

noc_2016_onet_10 allows crosswalk between NOC 2016 and ONET version 10 (you can then use a NOC 2016 to NOC 2006 to get NOC 2006 to ONET 10). It has 1113 rows.

noc2021_onet26 allows crosswalk between NOC 2021 and ONET version 26. It was 1468 rows.

# Methodology
We crosswalked the NOC to O*Netusing a two-stage process. First, we leveraged the existing crosswalks between NOC and ISCO (International Standard Classification of Occupations) and between ISCO and O*Net. From this base-level matching, we manually went through the results and adjusted these matchings, primarily through using job titles associated with each occupational groups. Most importantly, we followed the principle that every NOC occupation has to have at least one matching O*Net occupation. As we’re interested in Canadian occupations, this allows us to make sure we have all Canadian occupations categorized.

# License
This work is licensed under MIT License.
