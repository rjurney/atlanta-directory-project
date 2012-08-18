atlanta-directory-project
=========================

Summary
=======

Processing Atlanta Directories from Emory University to understand the demographics of race and class in Atlanta in the Late 19th and early 20th centuries. This data was brought to my attention by Doctor Stewart Varner, Digital Scholarship Coordinator at Emory University.

I intend to parse, analyze, geolocate and visualize it. Help wanted.

The Data
========

The dataset of interest consists of Atlanta Directories from the late 19th and early 20th century.  A plaintext version of this data is in the data/ directory, but a more comprehensive set of formats can be viewed at (http://archive.org/search.php?query=title:(Atlanta%20City%20Directory)%20AND%20contributor:(emory%20university))

Example Data from the 1922 Atlanta Directory
============================================

```" Jas (c) carp rl95 Love 
" Jas fc) lab h59 N Doray 
" Jas (c) lab hl3 Jetts al 
" Jas (c) tailor rl86 E Ellis 
" Jas B (c) lunch 1 Irwin h do 

" Jas H (Mary L) barber hSoO S Whlte- 
foord av 

" Jas M (Kate) blksmth h Grand View 
av```

Lets look at what we can learn from this data by manually parsing it:

1) Race of occupants. '(c)' means 'colored.' There's no way around this. Atlanta was a segregated, racist place in 1922. Get past the shock for a moment... this directory tells us racial demographics! Wow, fascinating.
2) Occupation of occupants. 

To summarize, an African American carpenter with the first or last name Jas lived at 95 Love St., Atlanta, GA in 1922.

Lets check that out on Google Maps: https://maps.google.com/maps?q=95+love+st,+atlanta,+ga&hl=en&ll=33.734271,-84.384742&spn=0.000889,0.001135&hnear=95+Love+St+SE,+Atlanta,+Georgia+30315&gl=us&t=h&z=21

I don't know about you, but I'm amped! Now I want a historical map. I want to determine each person's name, address, race and occupation and map them from each entry in each directory to show shifts over time. Which brings us to our mission.

Project Mission
===============

1) Parse Atlanta directories from 188X to 192X to determine each resident's name, address, race and occupation.
2) Map these entries to historical maps of Atlanta.
3) Map occupation to class.
4) Visualize changes in race and class over time.
