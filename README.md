# Scikit-Matter - ORE Paper Data and Figures

Jupyter notebooks used to produces results of the paper

> Goscinski, A, VP Principe, G Fraux, S Kliavinek, BA Helfrecht, P Loche,
  M Ceriotti, and RK Cersonsky. 2023. “Scikit-Matter : A Suite of
  Generalisable Machine Learning Methods Born Out of Chemistry and
  Materials Science \[Version 1; Peer Review: 1 Approved, 1 Approved with
  Reservations\].” *Open Research Europe* 3 (81).
  <https://doi.org/10.12688/openreseurope.15789.1>.

# Installation

To run the notebooks use Python 3.8.10 and install the required packages using
```bash
pip install -r requirements.txt
```
or directly use the conda environment
```bash
conda env create -f environment.yml
```
In the conda evironment also the dependencies are fixed.

# Figures

You can find the notebooks in `paper/`

- Figure 1:  manually created
- Figure 2: `atomrings.ipynb` and `NeighborFig.ipynb`
- Figure 3:  manually created
- Figure 4: `PCovR Charge Model.ipynb`
- Figure 5: `PCovR Charge Model.ipynb`
- Figure 6: `WhoDataset-PCovR.ipynb`
- Figure 7: `Ice Selection.ipynb`
- Figure 8: `WhoDataset-Selection.ipynb`
- Figure 9: `convex_hull_toy_figure.ipynb`

# License

The **code** is licensed undere BSD-3. For the ice dataset please refer to
https://archive.materialscloud.org/record/2018.0010/v1
