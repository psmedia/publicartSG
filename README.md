# publicartSG
data and code related to public art in Singapore

I put the basic dataset -- information on 147 artworks in (or once in) public space in Singapore — in the public domain in 2016 or so. Recently I've been working on republishing the data, and so converted the dataset to geoJSON. I'm now putting it on github as a public repository so other folks can use it. 

Key fields/properties in the data:

**Title**: Title of the artwork. May also include "untitled", which could either reflect the deliberate choice of the artist, or reflect the fact that we couldn't locate the title of a work.

**URL**: The URL of a page on the PublicArtSG website with more information about the work. This site is currently in development and password-protected. Will be updated with the final website URL when the site is launched.

**ArtistsName**: The name of the artist or group of artists credited with the work. 

**Longitude**: decimal formatting, six decimal points precision
**Latitute**: as above

**YearPlaces**: Year that the work was first placed in a public space in Singapore. *Not* the year the artwork was first created. See location notes in the website for more detailed information about the movement of artworks in public spaces. 

**InPublic**: Is the artwork currently in a public place? Yes, No or Unsure.

**Patron**: Who is credited as the commissioner or parton of the work. Taken from labels.

**KeyImage**: Is the current URL of a photograph of the work, currently hosted on our development site. 

