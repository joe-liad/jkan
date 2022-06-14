---
schema: default
title: Fixmystreet history
organization: Lewisham Insight
notes: "Up-to-date history of fixmystreet requests for lewisham going back to 2007
\r\n\r\nthe records are stored in sqlite, hosted in the cloud with datasette providing both a human interface and json api endpoint, with both queried in straight sql. fear not 'little johnny tables' the database is read-only and queries are time limited to safeguard the source."
resources:
  - name: fixmystreet history
    url: >-
      https://lewisham-fixmystreet-history.vercel.app/fixmystreet/requests?_sort_desc=requested_datetime#g.mark=circle&g.x_column=requested_datetime&g.x_type=temporal&g.y_column=interface_used&g.y_type=ordinal
    format: api
license: 'https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/'
category:
  - APIs
  - Geodata
  - Public Realm
maintainer: 'Lewisham Insight '
maintainer_email: insight-and-delivery@lewisham.gov.uk
---