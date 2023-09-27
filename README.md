
# News Scrapper 📰

Introducing **News Scrapper**, a Python-based tool designed to fetch, process, and store news articles related to specified companies. Primarily focused on Apple, this application extracts recent news from Bloomberg, offering insights into the media's coverage of the tech giant.

## 🚀 Features

- **News Data Retrieval**: Fetch recent news articles related to Apple from Bloomberg using the NewsAPI.
- **Data Storage**: Store extracted news articles in both JSON and CSV formats.
- **Data Cleaning**: Process raw data by dropping unnecessary columns, combining text fields, and removing duplicates.
- **Easy Verification**: View the shape and columns of the cleaned data set for quick verification.

## 📁 File Structure

- 📄 `final.py`: The main application logic, including news retrieval, data storage, and data cleaning processes.
- 📜 `data.json`: The initial JSON file containing raw news articles.
- 📜 `data_file.csv`: CSV representation of the raw news data.
- 📜 `clean_data_file.csv`: Processed and cleaned CSV data.

## 🔧 Setup & Execution

1. Install the required Python libraries:
   ```bash
   pip install pandas newsapi requests
   ```
2. Execute the Python script:
   ```bash
   python final.py
   ```
3. Navigate to the project directory to view the generated JSON and CSV files.

## 🧠 Technical Details

- **Data Source**: News data is sourced from Bloomberg using the NewsAPI.
- **Data Storage**: Extracted news articles are initially stored as JSON and then converted to CSV for further processing.
- **Data Cleaning**: The application employs pandas for data cleaning, ensuring a refined dataset free of unnecessary columns and duplicates.
- 

## 🧪 Testing

1. Run the application using the steps provided above.
2. Inspect the generated `data.json`, `data_file.csv`, and `clean_data_file.csv` files to verify the extraction, conversion, and cleaning processes.
3. Modify the company or domain in the `final.py` script if you wish to test the extraction for other sources or companies.
