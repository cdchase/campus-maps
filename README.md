# HOW MAPS CAN USE DATA FOR ENHANCEMENT USING MONGODB & NODEJS

We all need maps. Our campuses are huge! Ours is state-wide! Only showing the location of buildings is not enough. We need to integrate data about those buildings, what occurs in them, and do so in multiple formats as required. Searching for locations in a mobile-driven world is always needed, and geo-search is an excellent enhancement to any map. Geo-centric search can be done efficiently with a NoSQL database such as MongoDB. The location map of Empire State College is an example of using this technique along with how NodeJS and a web API separates the data from the web page to allow it to be used on multiple pages as needed.  Get a taste for modern web development!

[View slides](https://cdchase.github.io/campus-maps/#/)

## Presentation History
 
- [HighEdWeb 2017](https://2017.highedweb.org/schedule/#AIM8) - AIM8, Tuesday, October 10, 2017, 10:45 am - 11:30 am. Rooms 14 & 15.

## Notes

The recent site redesign at SUNY Empire State college included a new location listing with an integrated map. 
As our 'campus' is the entire state of New York, it is a little different than most campuses with a single location and multiple buildings.
However, in the function of a 'map,' there is a great deal of similarity.

I wanted to centralize the management of the data about the locations as we use the same data to provide in-page maps on single location pages,
as well as for form-based registration services. Having this data managed in one place helps us be consistent, and not overlook to updating some part.

