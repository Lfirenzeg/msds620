# Marvel Character Co-Appearance Network

This project explores a subset of the Marvel Universe character network using graph analysis techniques. The dataset comes from [KONECT](http://konect.cc/networks/marvel/) and includes character appearances in comic books published from 1961 to 2002.

## Files Included

| File Name              | Description                                         |
|------------------------|----------------------------------------------------
| `marvel_network.ipynb` | Jupyter Notebook with all analysis and visualization steps |
| `out.marvel`           | Raw edge list (bipartite graph: character ↔ comic) |
| `character_names.txt`  | Mapping of vertex IDs to character names (1–6486)  |
| `comic_names.txt`      | Mapping of vertex IDs to comic titles (6487–19428) |

---

## How to Run This Notebook

1. Clone or download the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/marvel-network-analysis.git
   cd marvel-network-analysis

2. Open the notebook:

- In Anaconda: Launch Jupyter Notebook or JupyterLab and open marvel_network.ipynb

- Or in terminal:
   ```bash
   jupyter notebook marvel_network.ipynb

3. Ensure the following files are in the same folder:

- out.marvel
- character_names.txt
- comic_names.txt

4. Run each cell from top to bottom.


##  Data Source
Dataset: KONECT  Marvel Universe: http://konect.cc/networks/marvel/
Original source: Marvel Chronology Project: https://bioinfo.uib.es/~joemiro/marvel.html

