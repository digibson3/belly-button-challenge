# Belly Button Biodiversity Dashboard

This interactive dashboard visualizes the biodiversity of bacteria found in human belly buttons. The data comes from a study of microbial species inhabiting the navels of healthy individuals.

##  Project Features

- **Dropdown Selection**: Choose a test subject to explore individual microbial profiles.
- **Bar Chart**: View the top 10 OTUs (Operational Taxonomic Units) found in each subject.
- **Bubble Chart**: Visualize the full OTU spectrum with color and size scales.
- **Metadata Panel**: View demographic information about each test subject.

## Technologies Used

- **JavaScript (D3.js, Plotly.js)** for data handling and visualizations
- **HTML/CSS + Bootstrap** for page layout and styling
- **Hosted Data Source**: JSON data fetched from [EdX/Static URL](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json)

## File Structure

├── index.html # Main webpage layout
├── static/
│ └── js/
│ └── app.js # JavaScript logic for fetching data and creating charts

## How to Use

1. Clone or download this repository.
2. Open `index.html` in your web browser.
3. Use the dropdown to explore data for different test subjects.

## Sample Data Fields

The JSON data used contains:
- `names`: List of subject IDs
- `metadata`: Demographic info (age, gender, location, etc.)
- `samples`: OTU IDs, labels, and sample values per subject

