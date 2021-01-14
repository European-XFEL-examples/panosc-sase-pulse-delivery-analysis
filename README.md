# USE CASE 4 - SASE Pulse Delivery Analysis

## Abstract

An analysis workflow implemented to a Jupyter notebook was used to look at XGM (X-ray Gas Monitor) data that were recorded in the same time interval, but in different parts of European XFEL. It essence, pulse energy (intensity) values from one XGM in SASE1 were compared to another set from an XGM in SASE3. These data stem from alternating X-ray pulses sent through one or the other tunnel and recorded separately. The aim was to determine the suppression rate for intensity from unwanted residual photons in each "non-pulse" time interval.
Conceptually and technically, this analysis makes use of the data-object xarray.DataArray within the EXtra-data framework and implements a simple form of error propagation. It is already public as example notebook in the EXtra-data documentation: https://extra-data.readthedocs.io/en/latest/xpd_examples2.html, and could be of value to PaNOSC due to its transferability to the general case of data comparison and/or error determination.

## Scientists

Theophilos Maltezopoulos, Jan Grünert, Thomas Kluyver, Fabio Dall'Antonia

## References
  1. Tiedtke et al., Gas-detector for X-ray lasers , J. Appl. Phys. 103, 094511 (2008) - DOI 10.1063/1.2913328
  2. Sorokin et al., J. Synchrotron Rad. 26 (4), DOI 10.1107/S1600577519005174 (2019)
  3. Th. Maltezopoulos et al., J. Synchrotron Rad. 26 (4), DOI 10.1107/S1600577519003795 (2019)
