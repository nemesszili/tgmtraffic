# tgmtraffic

## Installation
1. Download and install [SUMO](http://prdownloads.sourceforge.net/sumo/sumo-win64-1.3.1.msi?download)
2. Make sure you also have Python (>= 2.7) installed

## Create new scenario

See the [tutorial](http://sumo.sourceforge.net/userdoc/Tutorials/OSMWebWizard.html).

Default command:

```
python "c:\Program Files (x86)\eclipse\Sumo\tools\osmWebWizard.py"
```

## Open existing scenario

1. Load the scenario
    1. Open SUMO GUI via Windows and load the scenario's `.sumocfg` file
    2. Run the `.\run.bat` command in the scenario's folder

2. Click on the colored circle to edit the view, select `Vehicles`, tick the checkbox with `Draw with constant size when zoomed out` and increase the minimum size as seen fit.

3. Run the simulation with `Ctrl+A`

## Edit scenario

1. With the scenario loaded in the GUI, press `Ctrl+T` to open it in NETEDIT

2. Modify as seen fit or look up IDs for given components

3. Add new flows according to the content of `osm.passenger.trips.xml`