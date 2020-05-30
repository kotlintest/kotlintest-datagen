# kotest-datagen

[![Build Status](https://travis-ci.org/kotest/kotest-datagen.svg?branch=master)](https://travis-ci.org/kotest/kotest-datagen)
[<img src="https://img.shields.io/nexus/s/https/oss.sonatype.org/io.kotest.datagen/kotest-datagen.svg?label=latest%20snapshot&style=plastic"/>](https://oss.sonatype.org/content/repositories/snapshots/io/kotest/datagen/)

Fake data producers for use in tests (or in your applications)


| Producer  	| Details  	|
|---	|---	|
| FirstNameProducer | Produces random english or hispanic first names |
| LastNameProducer | Produces random last names based on US census data |
| NameProducer | Produces random first and last names |
| StockExchangeProducer | Produces random stock exchanges, eg `New York Stock Exchange / NYSE / US` |
| DomainProducer | Produces random domain names, eg `www.wibble.co.uk` |
| CountryProducer | Produces random country objects, eg `Botswana / BW / Africa` |
| ContinentProducer | Produces random continents from the list of seven |
| ColorProducer | Produces random named colours, eg, midnight blue |
| BrandProducer | Produces random brand names, eg Betty Crocker |
| GoogleTaxonomyProducer | Produces random google product categories, eg `Furniture > Office Furniture > Desks` |
| VineyardProducer	| Produces random vineyard names, eg `Château Montus Prestige` |
| RegionProducer	| Produces a random wine region, eg `Chassagne-Montrachet` |
| WineProducer | Combines several wine details producers to return full wine objects |
| WineReviewProducer | Combines wine producer and adds in random review scores and usernames |
