# schema.sql

beer.db database schema (tables, views, etc.) scripts (in SQL) and documentation


The `beer.db` includes the following tables:

- beers       (belongs to brewery n brand)          e.g. Guiness Extra Stout
- brands      (has many beers; belongs to brewery)  e.g. Guiness
- breweries   (has many brands n beers)             e.g. St. James's Gate Brewery / Guinness Brewery
- tags                                              e.g. irish_dry_stout, stout
- taggings (join table)

For more see the beer.db.sql script.



## Questions? Comments?

Send them along to the
[Open Beer, Breweryn n Brewpub Data Forum/Mailing List](http://groups.google.com/group/beerdb).
Thanks!
