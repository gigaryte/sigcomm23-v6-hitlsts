# sigcomm23-v6-hitlsts
Artifacts (7.2M IPv6 /48s) for Erik Rye &amp; Dave Levin's SIGCOMM 23 paper "Be Careful What You Wish For: IPv6 Hitlists at Scale".

## Details

The file `uniq-48s.txt` contains the 7,205,127 IPv6 /48s (full first 48 bits shown with no zero compression or /48, e.g. `2001:0db8:0000`) we obtained by running a measurement infrastructure of 27 NTP servers as part of the NTP Pool between January and August 2022. Note that there are non-Globally Unique Address (GUA) prefixes contained within this data; for instance, both Unique Local Address (ULA) and Link-Local Address prefixes appeared as source addresses in NTP requests that reached our servers. 

More information about this project can be found [here](http://v6-research.cs.umd.edu/). 
