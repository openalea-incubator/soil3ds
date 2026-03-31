====================================
README for '3DS soil model' (soil3ds)
====================================

This is '3DS soil model' (soil3ds), a 3D Soil model of soil for water and N balances adapted from the STICS soil module.

See 
- Louarn G, Faverjon L, Migault V, Escobar-Gutiérrez A, Combes D. (2016). Assessment of ‘3DS’, a soil module for individual-based models of plant communities. In: IEEE International Conference on Functional-Structural Plant Growth Modeling, Simulation, Visualization and Applications (FSPMA), 125–132. doi: 10.1109/FSPMA.2016.7818298
- N. Brisson, M. Launay, B. Mary, N. Beaudoin (2008) Conceptual basis, formalisations and parameterization of the STICS crop model, Quae, Versailles.
- N. Brisson & A. Perrier (1991). A semi-empirical model of bare soil evaporation for crop simulation models. Water resources research, 27(5), 719-727. 
- Lebon, E., Dumas, V., Pieri, P., & Schultz, H. R. (2003). Modelling the seasonal dynamics of the soil water balance of vineyards. Functional Plant Biology, 30(6), 699-710.


### Installation

First, **Conda** needs to be installed, see instruction on [openaleala documentation](https://openalea.readthedocs.io/en/latest/install.html).

#### for user
Creating a new conda environment with soil3ds and its dependencies installed
```bash
mamba create -n soil3ds -c openalea3 -c openalea3 -c conda-forge openalea.soil3ds
```

#### for developer
```bash
mamba env create -f ./conda/environment.yml
```
This will create a conda environment with dependencies installed and install soil3ds in editable state.

### Examples

To run a simulation example :

* 1. place yourself in folder `examples`
  2. run from the console:
		```bash
        python example_3D.py
        ```

## Contact

For any question, send an email to <gaetan.louarn@inrae.fr>.

## Authors

**Gaëtan LOUARN**, **Eric LEBON** - see file [AUTHORS](AUTHORS) for details

## License

This project is licensed under the CeCILL-C License - see file [LICENSE](LICENSE) for details
