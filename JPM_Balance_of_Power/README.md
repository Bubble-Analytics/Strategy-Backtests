# JPMorgan Chase (JPM): Balance of Power

[Read the article](https://www.bubble-analytics.com/blog/JPMorgan-Chase-JPM-Balance-of-Power-2026-10-14).

From this folder, install the dependencies and open `JPM_Balance_of_Power.ipynb`:

```sh
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt jupyterlab
python -m jupyter lab
```

On Windows, activate with `.venv\Scripts\activate` instead. Choose **Run All Cells**. The `data/` folder contains the frozen inputs needed to reproduce the article; keep it beside the notebook. Generated tables go into `snapshots/` and are ignored by Git.

`TEMPLATE.ipynb` is copied unchanged from the existing repository template. Its input placeholders are for building another strategy; run the named backtest notebook for this article.

The notebook explains the sample, execution assumptions and limitations. This material is for education and research.
