# Running Scripts

Given a tab-delimited file with three fields (`ia_id`, `cce_id`, `match_quality`):

1. `cat f1.tsv| ./add-ia-metadata > f2.tsv`
1. `cat f2.tsv| ./add-cce-metadata > f3.tsv`
1. `cat f3.tsv| ./add-classify-metadata > f4.tsv`
1. `cat f4.tsv| ./add-oclc-date-check > f5.tsv`

