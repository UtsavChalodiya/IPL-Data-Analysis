# IPL Data Analysis

A Python analytics project exploring Indian Premier League match and ball-by-ball data. The analysis looks beyond scorecards to compare team efficiency, player output, bowling performance, toss decisions and performance in pressure situations.

## Questions explored

- Do higher-scoring teams consistently convert runs into wins?
- How do batter run totals compare with strike rate?
- Which bowlers combine wicket-taking impact with economical bowling?
- How are toss decisions associated with match outcomes across venues?
- What can late-over performance reveal about teams under pressure?

## Analysis areas

- Team scoring and win performance
- Batter output and scoring rate
- Bowler economy and wicket-taking
- Toss decisions and match outcomes
- Team efficiency and pressure-focused comparisons

The project uses descriptive analysis and visual comparisons. These are exploratory associations, not proof that a single factor causes a match result.

## Technology

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook

## Run the project

1. Clone the repository:

   ```bash
   git clone https://github.com/UtsavChalodiya/IPL-Data-Analysis.git
   cd IPL-Data-Analysis
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   # Windows
   .venv\Scripts\activate
   # macOS / Linux
   source .venv/bin/activate
   ```

3. Install the analysis libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Open the notebook in Jupyter and run its cells in order. Keep the source CSV files in the locations expected by the notebook.

## Reproducibility and interpretation

The notebook expects match-level and delivery-level CSV data. Check the input paths in the notebook before running it on a new machine. Add the dataset source and licence here when redistributing or sharing the data.

When presenting results, include the date range, sample size and definitions used for metrics such as team efficiency and pressure performance.

## Author

**Utsav Chalodiya**  
[GitHub profile](https://github.com/UtsavChalodiya)
