# Electoral Bond Purchase Analysis

This project analyzes the electoral bond purchase behavior using data provided by the [Election Commission of India](https://www.eci.gov.in/disclosure-of-electoral-bonds). The data, available in PDF format, has been extracted and analyzed to uncover trends over time, identify the top purchasers, and explore purchase patterns among them.

## Project Structure

- `Electoral_Bond_Analysis.ipynb`: Jupyter notebook containing all the data extraction, cleaning, analysis, and visualization code.
- `data/`: Directory containing the extracted PDF files from the Election Commission of India website.
- `requirements.txt`: A file listing all Python libraries required to run the notebook.

## Getting Started

To run this analysis, you'll need Python installed on your machine, preferably through Anaconda to manage dependencies and virtual environments easily.

### Installation

1. Clone this repository to your local machine.
    ```bash
    git clone https://github.com/snehil03july/elecoralBondAnalysis.git
    ```
2. Navigate into the project directory.
    ```bash
    cd electoral-bond-analysis
    ```
3. Create a virtual environment (optional but recommended).
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
4. Install the required dependencies.
    ```bash
    pip install -r requirements.txt
    ```

### Running the Notebook

After installation, launch Jupyter Notebook or JupyterLab to open the `Electoral_Bond_Analysis.ipynb` notebook.

```bash
jupyter notebook

or

jupyter lab
