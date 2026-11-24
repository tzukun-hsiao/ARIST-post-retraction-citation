Data files
- data/225-included-in-Dimensions.csv: Seed articles used for citation searching
    - Column descriptions:
        - eppi_id: EPPI-Reviewer ID
        - doi: DOI of the article
        - short_ti: Short article title
        - title: Full article title
        - dimensions_pub_id: Dimensions AI article ID. Only articles have Dimensions AI article IDs were used for citation searching.

- data/manually_identified_ASJC_all.csv. This file lists articles for which two researchers manually examined and assigned subject areas.
    - Column descriptions:
        - ID: EPPI-Reviewer ID
        - Year: Publication year
        - Title: Article title
        - Journal: Journal title
        - Venue in field/Similar Venues: Venue used to assign the subject area.
        - ASJC 1: Assigned scopus ASJC code
        - ASJC 2: Assigned scopus ASJC code
        - ASJC 3: Assigned scopus ASJC code
        - ASJC 4: Assigned scopus ASJC code
        - batch: either "review_original" or "review_r1". Review_original indicates that the article is included in the initial submission. Review_r1 indicates that the article is newly included in the revision.

- data/PostRetractionCitationData_20261119-EH_cleaned.csv. This file contains data extracted from the included studies.

