Verso TODO list
================

### Features and Improvements

* Allow arbitrary views in a page spread (the URL-fetched image view would be an included subspec)
* Better animation of the switch to/from single page mode.
* Arbitrary overlay views (decouple hotspots from the pagedView)
* Fetching and error views (a property of the singlePageContents view)
* Allow for an arbitrary view to appear after the last page
* Don't fetch/prefetch images for pages when animating to a new page.
* Animate image appearance
* Documentation & Cleanup


### Known Issues

* Occasionally scrolling will lock after doing a quick zoom in&out
* Two-page alignment has pixel rounding error (1/2 pixel visible inbetween pages)
* When on last page switching from Two page to single page means you scroll to a random page