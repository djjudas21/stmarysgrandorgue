# St Mary's, Fishponds

[GrandOrgue](https://grandorgue.com/) organ definition file for
[St Mary's, Fishponds](https://stmarysfishponds.org.uk/music/organ/).

The organ at St Mary's, Fishponds has never been sampled.
However, the sound can be approximated by borrowing samples of other organs with similar-sounding stops.

It has been a mission to find a suitable donor organ because not many English organs have been sampled
(at least not available for free) but European organs tend to have different types of stops - especially
the reeds. Clarinet stops are quite rare on European organs.

Up until now I have been using a sampleset cobbled together from two different donor organs, but I
encountered problems with tuning and acoustics between the organs.

This sampleset for St Mary's, Fishponds is borrowed entirely from
[St. John Cantius in Cracow, Poland ](https://piotrgrabowski.pl/cracow-st-john-cantius/), which is the
first sampleset I have found which contains all of the stops I need in the same instrument.

St John Cantius sampleset is available free of charge from the amazing [Piotr Grabowski](https://piotrgrabowski.pl).
To use this definition file, you will need to download that sampleset.

`St Marys from Krakow.odp` is a project file for a tool called [Organ Builder](https://drive.google.com/open?id=0B7o0RGQx9qJgWFkyN0R4QmJPREk).
Unfortunately, the project seems to have been abandoned in late 2014/early 2015 and the website for Organ Builder is defunct,
but the tool still works. This file contains a basic definition of the St Mary's console but uses dummy pipe samples.

`St Marys from Krakow.organ` is a GrandOrgue defintion file, exported by Organ Builder and with extensive work to transplant in the samples
from Krakow and model some behaviours specific to St Mary's, such as:

* The Gravitas 32' is a resultant stop which draws a fundamental and a quint from a 16' rank
* The Bassoon 16' is part of the Swell organ, but the same rank is also playable from the pedals

The end result is a virtual organ which sounds good and is reasonably representative - certainly good enough for practice.

## How to use this organ definition

1. Download and unpack the St John Cantius, Krakow sampleset.
2. Locate the file `Cracov st John Cantius.organ`
3. Copy `St Marys from Krakow.organ` from this repo and place it alongside `Cracov st John Cantius.organ`
4. Open `St Marys from Krakow.organ` in GrandOrgue and enjoy playing

## Comparison with the real St Mary's organ

The flue pipes (diapasons and flutes) are a pretty good match. There are some variations in voicing,
but the general sound is close enough that registrations for this sampleset should work on the real St Mary's organ.

The reeds are not quite such a close match. The Bassoon 16' rank in particular is more aggressive-sounding
at Krakow than the organ at St Mary's. The Oboe 8' is reasonably close, and the Trumpet 8' from Krakow is
a pretty good match for the Cornopean 8' at St Mary's.

The Clarinet 8' is the biggest discrepancy, largely because English Clarinet stops are generally
orchestral/imitative, while European Clarinets, where they even exist, are not imitative and usually
sound more like a Cromorne/Krummhorn.

The reverb on the Krakow sampleset is also more generous than St Mary's church.
