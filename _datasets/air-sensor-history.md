---
schema: default
title: Air sensor history
organization: Lewisham council
notes: >-
  this repo uses a github action to periodically scrape the londonair api,
  extracting sensor data collected within the lewisham jurisdiction, and adds
  them to a sqlite database suitable for use in e.g. datasette
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