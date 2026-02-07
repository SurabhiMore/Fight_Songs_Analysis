# From Aggression to Tradition: The Evolution of Fight Song Tropes

## Overview

This project explores the evolution of college fight songs in the United States. While these songs have been a longstanding tradition, their lyrical content has shifted over time, from aggressive calls to fight and win in early songs to themes celebrating school spirit, identity, and tradition in modern eras.

Using data analysis and interactive visualizations, this project investigates common lyrical tropes and how they change across eras and athletic conferences.

---

## Dataset

The dataset 'fight-songs-updated.csv' contains information about U.S. college fight songs, including:

- Year of composition
- Conference affiliation
- Presence of lyrical tropes such as:
  - 'fight'
  - 'victory'  
  - 'win_won'  
  - 'rah'
  - 'nonsense'  
  - 'colors'
  - 'men'  
  - 'spelling'  

Tropes are marked as 'Yes' or 'No'.

---

## Methodology

1. **Data Preprocessing**  
   - Converted the 'year' column to numeric format.  
   - Assigned each song to an era:
     - Pre-1925  
     - 1925–1965  
     - 1966–1999  
     - 2000+  
     - Unknown  

2. **Trope Encoding**  
   - Converted 'Yes/No' values to binary '1/0' for analysis.

3. **Analysis**  
   - Calculated the mean presence of each trope by era and conference.  
   - Examined trends in lyrical content over time and across regions.

---

## Visualizations

### Radar Plot: Tropes by Era
- Shows the proportion of lyrical tropes for each era.
- Highlights the shift from aggressive early songs ('fight', 'victory', 'men') to more balanced modern songs.
- Includes an overall average for reference.

### Heatmap: Tropes by Era and Conference
- Displays how trope prevalence varies across eras and conferences.
- Captures regional differences in the adoption of traditions and cultural norms.

---

## Key Insights

- Early songs emphasized aggression, competition, and masculinity.  
- Modern songs emphasize school identity, colors, and tradition.  
- Regional differences exist; some conferences retain older tropes longer.  
- Fight songs adapt over time while continuing to unite fans.

---

## Tools & Libraries

- Python 3.x  
- [pandas](https://pandas.pydata.org/) – Data manipulation  
- [Plotly](https://plotly.com/python/) – Interactive visualizations  
- [NumPy](https://numpy.org/) – Numeric operations  

---

## Usage

1. Mount Google Drive (if using Colab) and load the dataset:
    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    ```
2. Import required libraries and read the CSV file.
3. Encode eras and tropes.
4. Generate radar plot and heatmap visualizations to explore trends.

---

## License

This project is for educational and research purposes. Please credit the author if used in derivative works.
