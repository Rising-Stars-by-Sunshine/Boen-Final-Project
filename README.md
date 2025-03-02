# Social Bot Detection through Structural Holes and Centrality Measures: Analyzing the Position of Humans and Bots in Networks  

## Authors  
**Boen Liu** – Brainstorming, Writing, Coding, Social Network Analysis, Visualizations  

## Disclaimer  
This project was submitted for **STATS201: Machine Learning for Social Science**, instructed by **Prof. Luyao Zhang** at **Duke Kunshan University** in Spring 2025.  

## Acknowledgments  
- Special thanks to **Prof. Luyao Zhang** for valuable suggestions and guidance throughout the project.  
- Appreciation also goes to my **two classmates** for their insightful feedback and revisions.  
- This project benefited from **ChatGPT** and **Whimsical** for **language refinement** and **creating flowcharts**.  
- Thanks to **open-source software** such as **numpy**, **pandas**, **easygraph**, **networkx**, **torch**, and other libraries for **coding and analysis**.  

## Statement of Intellectual and Professional Growth  
This project has been a valuable learning experience, teaching me how to **systematically and rigorously conduct research**—from formulating research questions to identifying appropriate datasets, generating ideas, conducting experiments, and writing up findings. The process also enhanced my skills in **social network analysis, visualization, and applying machine learning to social science problems**.  

## Poster
![Bot Detection in Social Media Poster](https://github.com/Rising-Stars-by-Sunshine/Boen-Final-Project/blob/main/poster.png)  

## Table of Contents  

| Section                        | Description |
|---------------------------------|-------------|
| [`code`](./code)                | Contains all scripts for **explanation(main), prediction, and causal inference**. |
| [`code/Explanation.ipynb`](./code/Explanation.ipynb)  | Script for **Social Network Analysis**. |
| [`code/causal_inference.ipynb`](./code/causal_inference.ipynb)  | Script for **Regression Discontinuity Design (RDD)** analysis. |
| [`code/prediction.ipynb`](./code/prediction.ipynb)  | Script for **Bot Detection Model**. |
| [`data`](./data)                | Stores the dataset used in this study. |
| [`visualizations`](./visualizations) | Includes all generated plots and visual representations. |
| [`docs`](./docs)                | Contains the final report and related documentation. |
| [`docs/Final-Report.pdf`](./docs/Final-Report.pdf) | The **final report** for the study. |


## Code Execution  
To run the code, follow these steps:  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Rising-Stars-by-Sunshine/Boen-Final-Project.git
   cd Boen-Final-Project
   ```
   
2. Install dependencies using `pip`:

    ```bash
    pip install -r requirements.txt
    ```
    or to install specific libraries individually, use:

    ```bash
    pip install networkx==2.5 Easygraph==1.4.1 pandas==1.3.2 statsmodels==0.13.2 matplotlib==3.4.3 seaborn==0.11.2 torch==1.9.0 numpy==1.21.1 sklearn==0.24.2
    ```
    
3. **Navigate to the code directory**
   ```bash
   cd code
   ```
   
4. Run the Jupyter Notebook
   - For explanation analysis: Open and run `Explanation.ipynb`
   - For prediction tasks: Open and run `prediction.ipynb`
   - For causal inference: Open and run `causal_inference.ipynb`

## Dependencies

### Required Libraries and Versions:
- **Python 3.9**
- **networkx==2.5**
- **easygraph==1.4.1**
- **pandas==1.3.2**
- **statsmodels==0.13.2**
- **matplotlib==3.4.3**
- **seaborn==0.11.2**
- **torch==1.9.0**
- **numpy==1.21.1**
- **torch.nn** (included in the `torch` library)
- **sklearn==0.24.2**


## Example Usage

1. **Running Social Network Analysis(Main)**:
   - For social network analysis, run the following notebook to analyze centrality measures and structure holes for bots and humans:

    ```bash
    jupyter notebook Explanation.ipynb
    ```

2. **Training and Evaluating Predictive Models**:
   - To train a hypergraph neural network model for bot detection, run the following:

    ```bash
    jupyter notebook prediction.ipynb
    ```

3. **Running Causal Inference Analysis**:
   - To perform Regression Discontinuity Design (RD) analysis on the impact of Twitter’s subscription program, execute:

    ```bash
    jupyter notebook causal_inference.ipynb
    ```







