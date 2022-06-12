---
schema: default
title: Air sensor history
organization: Lewisham Insight
notes: "up-to-date history of records for londonair.org.uk sensors at five sites in lewisham going back to 2005. currently only NO2 data is collected here because that is the only particle type recorded at all lewisham sites.\r\n\r\nthe records are stored in sqlite, hosted in the cloud with datasette providing both a human interface and json api endpoint, with both queried with straight sql. fear not 'little johnny tables' the database is read-only and queries are time limited to safeguard the source."
resources:
  - name: sensor data
    url: >-
      https://lewisham-air-sensors-history.vercel.app/air-sensors/NO2?_sort_desc=%40MeasurementDateGMT
    format: api
license: 'https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/'
category:
  - APIs
  - Geodata
  - Environment
maintainer: 'Lewisham Insight '
maintainer_email: insight-and-delivery@lewisham.gov.uk
---