# Seismic_inversion_with_segyio
The notebook in this repo aims at presenting a simple example of relative seismic inversion. 

Kerry3D data is used for demonstration as it is publicly available.

- Data is read from SEG-Y file using segyio 
- Relative seismic inversion is applied by means of pylops.avo.poststack.PoststackInversion 
- Inverted data is saved back to SEG-Y file using segyio

The code presented here are adpated from segyio documentation. The notebook can be used as preprocessing step (Inversion) in seismic interpretation 