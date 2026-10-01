# Getting started

[Back to overview](../README.md) · [Topic guide](NOTEBOOK_GUIDE.md)

## Read without running

Open [HandsOnMachineLearning.ipynb](../HandsOnMachineLearning.ipynb) on GitHub. Its saved tables, plots, and training output are included. Use the contents page at the top of the notebook or the [topic guide](NOTEBOOK_GUIDE.md) to find an example.

## Open in Colab

1. [Open the GitHub notebook in Colab](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb).
2. Save a copy to your own Drive if you want to keep edits.
3. Use Colab's table of contents to select a chapter.
4. Run the chapter's setup cells, then its examples in order. A link to a subsection only changes your reading position; it does not initialize the preceding cells.

The PyTorch section chooses CUDA, Apple MPS, or CPU according to availability. Its Colab setup installs `optuna` and `torchmetrics`; the notebook also checks the installed Python, scikit-learn, and PyTorch versions.

## Local setup

The decision tree and PyTorch chapters explicitly require **Python 3.10+** and **scikit-learn 1.6.1+**. The PyTorch chapter also requires **PyTorch 2.6.0+**. These are requirements stated by notebook cells, not a tested environment lockfile.

Create an isolated environment from the repository root:

```bash
git clone https://github.com/AgentQ1/HandsOnMachineLearning.ipynb.git
cd HandsOnMachineLearning.ipynb
python3 -m venv .venv
source .venv/bin/activate
python -m pip install jupyterlab nbconvert numpy pandas matplotlib scipy \
  'scikit-learn>=1.6.1' 'torch>=2.6.0' torchmetrics optuna graphviz packaging joblib
jupyter lab HandsOnMachineLearning.ipynb
```

On Windows, activate the environment with `.venv\Scripts\Activate.ps1` in PowerShell. The Graphviz Python package also needs the **Graphviz system executable** for the decision tree diagram; confirm it is available with `dot -V`.

The package list above is drawn from the notebook's imports and setup cells. It is a starting point for local use; compatibility across every historical example has not been validated.

## Datasets and generated files

| Data | Used for | Loaded from |
| :--- | :--- | :--- |
| California housing archive | End-to-end regression workflow | `ageron/handson-ml` via the notebook's download helper |
| MNIST | Digit classification and denoising examples | OpenML through `fetch_openml` |
| Iris | Decision tree classification | scikit-learn's bundled `load_iris` dataset |
| Synthetic examples | Linear regression, moons, and quadratic regression | NumPy and scikit-learn generators |
| California housing via scikit-learn | PyTorch regression | `fetch_california_housing` |

Internet access is needed for downloaded datasets. The notebook creates files such as `datasets/`, `images/`, `my_model.pkl`, and `my_iris_tree.dot`; these are excluded from Git by `.gitignore`.

## Execution notes

- **Saved results:** the outputs are retained from the original Colab notebook. They were not regenerated during repository organization.
- **Shared state:** cells reuse names such as `X_train`, `model`, and `housing`. Run the setup and prerequisite cells for the chapter you are exploring before running a later subsection.
- **Mixed example generations:** the notebook combines older examples with newer scikit-learn and PyTorch chapters. Some legacy API calls may need adjustment in a fresh environment.
- **Runtime:** MNIST downloads, cross-validation, grid searches, and neural network training can take time. Reading saved results requires no training.

To check a complete clean execution after installing the dependencies and Graphviz, run this from the repository root. It writes a separate executed copy and leaves the committed notebook intact:

```bash
jupyter nbconvert --execute --to notebook \
  --ExecutePreprocessor.timeout=-1 \
  --output HandsOnMachineLearning.executed.ipynb \
  HandsOnMachineLearning.ipynb
```

This full execution has not been run as part of the presentation update. Notebook structure, navigation targets, and preservation of code and saved outputs were checked separately.
