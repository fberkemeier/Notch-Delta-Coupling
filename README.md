# Notch-Delta Coupling Dynamics

This code was partially developed to support the simulations presented in the bioRxiv preprint [*Coupling dynamics of 2D Notch-Delta signalling*](https://doi.org/10.1101/2022.12.27.521688), by Francisco Berkemeier¹ and Karen Page². For any questions regarding the code, please contact fp409@cam.ac.uk. All rights reserved.

*Interactive Epithelium* (IEp, version 1.0.0) aims to provide a practical tool for testing parameter robustness while simulating the dynamics of the Notch-Delta signalling pathway in an epithelium.

In order to correctly reproduce the simulations presented in the preprint, we suggest using Interactive Epithelium (IEp) in parallel with the 'MainCode.nb' notebook, since some of the plots are only achievable after data storage from simulations in IEp. When needed, a message in light blue will prompt the user to run a specific model in IEp, which needs to be loaded first. In order to load models in IEp, simply load the text files in \InteractiveEpithelium\Models corresponding to the different figures ('Model[Figure_label].txt').

For accurate performance, we recommend running each code section in the order that they are presented in 'MainCode.nb'. Figures that did not require any computation are not shown here. Note that some results are averaged over multiple simulations.

To run IEp open the notebook 'iEpithelium v1.0.0.nb' with Mathematica and scroll down to the 'iEpithelium' cell (in green). Evaluate this cell (Shift+Enter) and the remaining cells will be evaluated (click 'Yes' on the popup window). IEp was developed in Mathematica 13.0.1, so it is recommended that the same version is used.


¹Department of Pathology, University of Cambridge, UK (fp409@cam.ac.uk)<br />
²Department of Mathematics and IPLS, University College London, UK (karen.page@ucl.ac.uk)
