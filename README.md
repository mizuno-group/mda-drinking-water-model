# MDA drinking-water model

Analysis code, tabular data, and figure panels for the TAA and MDA drinking-water mouse models.

## Contents

- `notebooks/`: Figure generation and statistical analysis
- `data/`: Experimental tables and sample metadata
- `results/`: Figure panels (PNG and SVG) and statistical results
- `environment/`: Python environment information

## Usage

The analyses use Python 3.12. In a Jupyter environment with an IPython kernel, install the required packages:

```bash
python -m pip install -r environment/requirements-lock.txt
```

Start Jupyter from the repository root and run `notebooks/main_fig.ipynb`. Outputs are saved under `results/`.

For the GO analysis, place the MSigDB-derived gene-set as a pickle at `data/references/go_mouse_msigdb.pickle`.

## Authors

- [Takumi Iwasaka](https://github.com/T-IWASAKA) — main contributor
- [Tadahaya Mizuno](https://github.com/tadahayamiz) — corresponding author

## Contact

Questions and feedback are welcome via [GitHub Issues](https://github.com/mizuno-group/mda-drinking-water-model/issues) or email to Tadahaya Mizuno at [tadahaya@gmail.com](mailto:tadahaya@gmail.com).

## Citation

Citation metadata are provided in `CITATION.cff`.

## License

MIT License. See `LICENSE`.
