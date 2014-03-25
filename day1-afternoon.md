# day 1 - afternoon

## structured data - seeding schema.org in library systems

Scalable structured markup for rich snippets. [Schema.org](http://schema.org) released in 2011, offering a simple vocabulary for  the "short tail" of web results, as a reaction to the litany of overcomplicated semantic webs schemas.

Hierarchical types in schema.org. *Thing* is a parent type with generic attributes title, description, image. Children types of *thing* include *people*, *events*, *creative works*.

Using incremental change we can iterate toward linked data. Persistent URIs, HTML5, RDFa/microdata from schema.org

RDF in attributes (RDFa). RDFa Lite is pared down to just five attributes.

Schema available for ScholarlyArticle. Periodicals coming.

## next generation catalog - RDF as a basis for services

OPAC as Oslo Public Library - converted MARC to RDF. Helps with deduplication and author disambiguation. Using SPARQL methods to modify/cluster data.

[MARC2RDF on GitHub](https://github.com/digibib/marc2rdf)

## more like this: recommended items using subject headings	

Users are coming to expect personalization options (it's no longer a weird thing). And, when collection storage prohibits serendipitous discovery, web features that can help discovery are more important.

Virtual browse project was aleady underway. Shelf browse feature in catalog and in kiosk at library.

Algorithm matches based on subject headings. Assumption that first heading is most important - doesn't work as well as most headings in common algorithm.

Tech stack: quick implementation using python/flask to accept a bibliographic Id to find subjects and return a list or recommendations in JSON. Leaning on SOLR to do heavy lifting to index/return most related items.

Testing: 30 hand-picked titles across many subject areas; 20 random titles. Relevance results vary by genre and number of terms/subject headings. Gov Docs and Fiction have interesting recommendations that you can't get from shelf browse. Mileage varies depending on quantity/quality of metadata.

Interface considerations: cover-flow presentation catches the ey. "Similar titles" or "related items" headings made sense. 5 or so recommendations good.
