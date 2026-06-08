# Exporter scripts to export models from Fusion 360 #

This repository contains three scripts which will export all of your models in Fusion 360:

## 1. Fusion 360 Total Exporter ('original') ##
This is a copy from https://github.com/Jnesselr/fusion-360-total-exporter which was archived in April 2024.

This was tested at June 2026, and failed with my 'Not for Commercial Use' account as it tries to export in IGES format.

I have amended the sketch code to fix some of the issues I experienced - namely:
- catching the error exporting in IGES
- ignoring exporting sketches for some components which causes Fusion 360 to freeze indefinitely

This new code is in the folder called fusion-360-total-exporter-original-fixes.

## 2. Forked version (rewrite) of Fusion 360 Total Explorer ('new')
This is a copy from https://github.com/TehDmitry/fusion-360-total-exporter

## 3. Fusion 360 Exporter ##
This is a copy from https://github.com/aconz2/Fusion360Exporter
