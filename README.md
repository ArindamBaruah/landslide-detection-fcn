# Landslide Detection with a Fully Convolutional Network

Landslide detection from imagery with a fully convolutional network, plus related spatial-analysis work.

## Contents

| File | What it is |
|------|------------|
| `notebooks/Alaska.ipynb` | Alaska |
| `notebooks/FCN_landslide_detection_256_v1.ipynb` | <h1> Landslide Mapping using FCNN and VHR satellite images using FCN</h1> |
| `notebooks/Spatial.ipynb` | Spatial |
| `notebooks/spatial_final.ipynb` | spatial final |
| `src/spatial.py` | spatial |

## Getting started

```bash
git clone https://github.com/<your-username>/landslide-detection-fcn.git
cd landslide-detection-fcn
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
pip install jupyterlab
jupyter lab   # then open a notebook in notebooks/
```

## Notes

- Training imagery is not included; point the notebooks at your own copy of the dataset.
