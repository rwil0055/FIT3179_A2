# FIT3179 A2 - Dog Adoption Statistics Visualization

This project visualizes dog adoption statistics in Victoria, with interactive graphs and a proportional symbol map. The data visualized includes adoption vs. purchasing statistics, euthanasia rates over time, and a comparison of dog ownership costs between adoption and purchasing.

## Repository Overview

- **Repository Name**: `rwil0055.github.io`
- **Project**: Visualizing dog adoption and rescue statistics in Victoria
- **Language**: HTML, CSS, JavaScript (using Vega-Lite for data visualization)
- **Data Files**: CSV files are used to store data for visualization.
- **Dependencies**: Vega, Vega-Lite, Vega-Embed for interactive charts

## Getting Started

### Prerequisites

You need to have PHP installed on your machine to run the local development server. This project uses a PHP server to serve the static HTML files.

### How to Run the Project Locally

Follow these steps to set up the project and start a local development server:

1. **Clone the Repository**:
   
   If you haven't cloned the repository yet, clone it using the following command:

   ```bash
   git clone https://github.com/rwil0055/rwil0055.github.io.git
   ```

2. **Navigate to the Project Directory**:
   
   Once cloned, navigate to the project directory:

   ```bash
   cd rwil0055.github.io
   ```

3. **Start the PHP Server**:
   
   Start a local PHP server to view the website locally:

   ```bash
   php -S localhost:8000
   ```

4. **View the Site**:
   
   Open your web browser and go to:

   ```
   http://localhost:8000
   ```

   This will load the website on your local machine, and you can interact with the visualizations.

## Project Structure

```
/rwil0055.github.io/
│
├── /assets/              # Folder containing images and other assets
├── /data/                # Folder containing the CSV data files
├── index.html            # Main HTML file for the project
├── styles.css            # CSS for styling the website
├── script.js             # JavaScript containing the chart specifications
└── README.md             # This readme file
```

### CSV Data Files:

- **Dog_Ownership_Costs.csv**: Contains data comparing adoption and purchasing costs for dog ownership.
- **Euthanasia_Rates.csv**: Contains euthanasia rates over several years.
- **Rescues_Per_Municipality.csv**: Contains animal rescue data by municipality, latitude, longitude, and the number of animals rescued.

### Data Visualizations:

1. **Cost Comparison Between Adoption and Purchasing**: 
   - Diverging bar chart comparing the costs of adopting vs. purchasing a dog.
2. **Euthanasia Rates Over Time**: 
   - A dual-axis line graph showing the number of euthanized dogs and the percentage over time.
3. **Percentage of Puppies from Puppy Farms**: 
   - Pie chart showing the percentage of puppies that come from puppy farms vs. registered breeders.
4. **Adopted vs Purchased**: 
   - Pie chart showing the proportion of dogs that are adopted versus purchased.
5. **Total Animals Rescued by Municipality**: 
   - Proportional symbol map showing the total number of animals rescued by municipality in Victoria.
6. **Word Cloud of Adopter Testimonials**: 
   - A word cloud visualization representing the most frequently mentioned words by adopters.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check out the [issues page](https://github.com/rwil0055/rwil0055.github.io/issues) if you'd like to contribute.

---

### Breakdown of Updates:
1. **New Visualizations**: Includes new visualizations like the pie charts and the word cloud.
2. **Updated CSV File Names**: Reflects the updated data file names used in the current version of the project.
3. **Project Structure**: Updated the file structure to reflect all the essential files.
4. **New Chart Descriptions**: Describes all visualizations in the current version of the project. 

If you'd like to save and push these changes to your GitHub repository, follow the steps below:

1. **Add the `README.md` to your project**:

   ```bash
   git add README.md
   git commit -m "Update README with current project structure and visualizations"
   git push origin main
   ```
