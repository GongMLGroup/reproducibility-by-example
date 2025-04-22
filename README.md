# Machine learning-driven determination of key absorber layer parameters in perovskite solar cells
These repository includes the python codes and data files corresponding to the paper:
Subba and Chatterjee, **_“Machine Learning-Driven Determination of Key Absorber Layer Parameters in Perovskite Solar Cells.”_** (https://doi.org/10.1016/j.mtcomm.2024.111113).

---

## Setup
### Install `uv` (Python Package Manager)
[Official Installation Guide](https://docs.astral.sh/uv/getting-started/installation/)

Restart your terminal, then verify:
```bash
uv --version
```

### Clone and Sync Project
Clone the dependencies branch and sync the project requirements.

```bash
git clone -b dependencies https://github.com/GongMLGroup/reproducibility-by-example.git
cd reproducibility-by-example
uv sync
```

---

### Notebooks and Files
Select `.venv` as your kernel of choice when running these notebooks.

#### Notebooks
* `1_Bandgap_preprocess.ipynb`
   * The preprocessing code
* `2_Bandgap_pred.ipynb`
   * Predictive ML models for Bandgap (BG)
* `3_CB_model.ipynb`
   * CatBoost model with optimized hyperparameters
   * BG data generation for VBM and CBM models' inputs
* `4_VBM.ipynb`
   * Predictive ML models for Valence Band Minimum (VBM)
* `5_CBM.ipynb`
   * Predictive ML models for Conduction Band Minimum (CBM)
>Note: in some of the codes BG is written as E_g

#### Data
Stored in the `data/` directory.
* `raw_data.csv`
* `cbm_vbm.csv`
* `cleaned_df_Eg.csv`
   * supplementary file S2
* `cbm_vbm_new.csv`
   * supplementary file S3.
 
#### Figures
Figures generated in notebooks are saved to `figures/"notebook_name"`.
> Note: `"notebook_name"` is replaced with the corresponding notebook name.