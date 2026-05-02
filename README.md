# AI Works

AI Works is a collection of applied artificial intelligence, machine learning, deep learning, NLP, retrieval augmented generation, computer vision, forecasting, and model deployment projects.

Most work is organized as Jupyter notebooks with supporting datasets, rendered HTML exports, presentations, PDFs, and saved model artifacts. The repository is intended as a portfolio-style workspace for coursework, experiments, and end-to-end ML project practice.

Repository: [github.com/an00pvijayan/ai_works](https://github.com/an00pvijayan/ai_works)

## Project Structure

| Folder | Project area | What it contains |
| --- | --- | --- |
| [`EasyVisa/`](EasyVisa/) | Visa approval prediction | Classification notebooks, EasyVisa dataset, rendered HTML reports, and presentation materials for predicting visa case outcomes. |
| [`Helmet Detection/`](Helmet%20Detection/) | Computer vision | Deep learning notebooks and HTML reports for detecting helmet usage in workplace safety imagery. |
| [`Medical assistance/`](Medical%20assistance/) | NLP and RAG | Medical document question-answering notebooks, RAG experiments, generated HTML reports, presentation material, and a medical diagnosis reference PDF. |
| [`ReneWind/`](ReneWind/) | Predictive maintenance | Wind turbine predictive maintenance notebook, train/test datasets, and final presentation/report exports. |
| [`SuperKart/`](SuperKart/) | Forecasting and deployment | Sales forecasting, model deployment, containerization, saved `.joblib` models, SuperKart dataset, and rental price prediction deployment work. |
| [`claude_workspace/`](claude_workspace/) | Notes | Scratch notes and temporary workspace material. |

Each major folder includes its own `README.md` with a more detailed description of the files inside.

## Root-Level Projects

The repository root also contains several standalone notebooks:

| File pattern | Description |
| --- | --- |
| `AIML_ML_Project_Full_Code_Notebook*.ipynb` | AllLife Bank personal loan purchase prediction using supervised machine learning. |
| `PYF_Project_Learner_Notebook_Low_Code.ipynb` | FoodHub order analysis project focused on exploratory data analysis and business insights. |
| `MLS_News_Article_Categorization_Notebook (1).ipynb` | News article categorization project using NLP and machine learning. |
| `ML0101EN-Reg-Simple-Linear-Regression-Co2.ipynb` | IBM simple linear regression exercise using CO2 emissions data. |

Rendered `.html` files at the root are exported notebook reports for quick viewing without running the notebooks.

## How To Browse This Repository

1. Start with the folder that matches the project area you want to inspect.
2. Open that folder's `README.md` for a short guide to the important files.
3. Use the main `.ipynb` notebook when you want to inspect or rerun the analysis.
4. Use `.html` exports when you only want to review results.
5. Use `.pptx`, `.pdf`, and `.key` files as presentation or final-report artifacts.

## Common File Types

| Type | Purpose |
| --- | --- |
| `.ipynb` | Main analysis, modeling, RAG, computer vision, forecasting, or deployment notebooks. |
| `.html` | Rendered notebook exports for read-only review. |
| `.csv` | Project datasets. |
| `.pptx`, `.key`, `.pdf` | Presentation and report artifacts. |
| `.joblib` | Serialized model artifacts used by deployment or forecasting workflows. |
| `.png` | Supporting visual assets. |

## Notes For Running Notebooks

Package requirements vary by project. Most notebooks use common Python data science libraries such as `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, and project-specific libraries for deep learning, NLP, embeddings, or deployment.

Some notebooks were originally designed for Google Colab or course environments, so paths and install cells may need small adjustments before running locally.

## Security

Do not commit API keys, Hugging Face tokens, OpenAI keys, service credentials, `.env` files, or private access tokens. If a notebook needs credentials, load them from environment variables or a local ignored config file.
