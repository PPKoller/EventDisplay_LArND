# EventDisplay_LArND
 Event display for neutrino events in the DUNE LAr Near Detector (ArgonCube). 

usage: event_display_LArND_raw.py [-h] [-a] [-c COLOR] [-e EVENT] [-g] [-l]
                                  [-r]
                                  root_file

positional arguments:
  root_file

optional arguments:
  -h, --help            show this help message and exit
  -a, --animation       See a 360 deg orbit animation.
  -c COLOR, --color COLOR
                        Select the tree entry to use as color. Default: dq.
  -e EVENT, --event EVENT
                        Select the event number. Default: 0.
  -g, --geom            Show rock geometry.
  -l, --logscale        Show logarithmic scaled colorbar.
  -r, --rock            Show rock volume.

example: python event_display_LArND_raw.py FHC_numu_argon_sim.root -c dq -l -e 3 -r
