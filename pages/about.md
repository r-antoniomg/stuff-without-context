---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="object_008" %} 

## About this collection

This demo collection features a random selection of digitized sketches and drawings by myself, and it was created for learning purposes. The site was built using [CollectionBuilder-CSV](https://github.com/CollectionBuilder/collectionbuilder-csv).

### Date ranges

The objects in this collection span an approximate date range between 2009-2021. For some images, a precise date could be obtained from the source itself, as in the following example:

{% include feature/image.html objectid="object_004" width="25" %}

As can be seen, in the upper-right corner of the sketch, a date was included in the original analogue document.

For a majority of the images in the collection, the date was instead inferred based on the creator's recollection of the context in which the image was created. For example, the following image was drawn while I was taking a course towards a certificate in [Surface Design](https://coned.georgebrown.ca/courses-and-programs/surface-design-program) through [Continuing Education at George Brown College](https://coned.georgebrown.ca/), during the COVID-19 pandemic.

{% include feature/image.html objectid="object_002" width="25" %}

### Location information

{% include feature/cloud.html fields="location" width="25"  %}

The metadata file that informs the content of this site is a .csv document which includes columns for location, as well as latitude and longitude information. These fields are part of the standard [CollectionBuilder-CSV template](https://github.com/CollectionBuilder/collectionbuilder-csv).

The data in these fields was kept in the file, but for the most part it's been hidden from public display, except for the location, which appears in the [Browse cards](/stuff-without-context/browse.html).

The data contained in these fields corresponds to the geographic location where the various images were made.

You may download select columns of the metadata file, as well as its full version, from the [Data](/stuff-without-context/data.html) page.