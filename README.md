SpectralPhenoClimatron Control
========

Control software for the SpectralPhenoClimatron growth chambers and heliospecta LED arrays

Installation:
============

To install this software, please run:
```python3 setup.py install```
(Preferably within a virualenv)

Running spcControl:
=================

All configuration values are stored in two .ini configuration files. These are
chamber.ini and monitor.ini.

To run the control module, please run:
```python3 -m spcControl <csv_path> [<ini_path>]```

By default, the spcControl module uses "./chamber.ini" as its config file.
You now must supply the CSV file on the command line.

To run the monitor module, please run:
```python3 -m spcControl.monitor [<ini_path>]```

By default, the spcControl module uses "./monitor.ini" as its config file.
