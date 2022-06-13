---
schema: default
title: Commonplace.is consultations
organization: Lewisham Insight
notes: "Pooling together of various lewisham consultations into one sqlite database
\r\n\r\nthe records are stored in sqlite, hosted in the cloud with datasette providing both a human interface and json api endpoint, with both queried with straight sql. fear not 'little johnny tables' the database is read-only and queries are time limited to safeguard the source."
resources:
  - name: commonplace.is consultations
    url: >-
      https://lite.datasette.io/?url=https://lb-lewisham.github.io/lewisham-commonplaces/commonplaces.db
    format: api
license: 'https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/'
category:
  - APIs
maintainer: 'Lewisham Insight '
maintainer_email: insight-and-delivery@lewisham.gov.uk
---