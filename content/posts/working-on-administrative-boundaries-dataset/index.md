+++
title = "Unifying Administrative Boundaries Datasets"
date = 2024-10-09T15:30:20-04:00
draft=true
+++

In geospatial analysis, defining metrics for regions can be very important. For multilateral development organizations, these regions often include countries, states, provinces, districts, neighborhoods, and other nested subdivisions. Surprisingly, finding standardized administrative boundaries datasets for these areas can be a challenge.

For national boundaries, the [World Bank Data Catalog](https://datacatalog.worldbank.org/search/dataset/0038272/World-Bank-Official-Boundaries) offers a good dataset, including names, ISO codes, GDP and population estimates, and classification levels for almost every country. However, finding similar subnational boundary data is less straightforward. While many sources provide level 1 and level 2 administrative boundaries, it’s rare to find data on subdivisions beyond these levels. The United Nations Office for the Coordination of Humanitarian Affairs (OCHA) offers one of the most comprehensive and reliable datasets for subnational boundaries available at the [Humanitarian Data Exchange (HDX)](https://data.humdata.org/), covering levels 3 and 4 (and occasionally even level 5), though its coverage remains incomplete across all countries.

In response to requests from colleagues and departments at the Inter-American Development Bank (IDB), I began developing a unified, standardized database of national and subnational boundaries. While the IDB primarily focuses on Latin America and the Caribbean, finding a complete and unified source for administrative boundaries across all countries proved challenging. This project is the result of a dedicated effort to consolidate the best available data into a single, cohesive resource.

I started by obtaining the [World Bank Official Boundaries dataset](https://datacatalogfiles.worldbank.org/ddh-published/0038272/DR0046659/wb_countries_admin0_10m.zip?versionId=2024-05-14T14:58:01.5696428Z)
