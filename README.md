# NOC to O*Net Crosswalk
To learn more about what we did: visit this blog (currently unpublished)
This repository currently contains 1 CSV file, with 1038 rows (1039 with the headers)

# Methodology
We crosswalked NOC to O*Net using a two-stage process. First, we leveraged the existing crosswalk between NOC and ISCO (International Standard Classification of Occupations) and between ISCO and O*Net. From this base-level matching, we manually went through the result and adjusted these matchings to the degree that makes the most sense. Most importantly, we followed the principle that every NOC occupation has to have at least one matching O*Net occupation. This approach made sense for 2 reasons. Firstly, there were less NOC than O*Net, so a one-to-many matching between NOC to O*Net was more likely. Secondly, as we’re interested in Canadian occupations, this allows us to make sure we have every single Canadian occupations categorized.

# License
This work is licensed under MIT License.
