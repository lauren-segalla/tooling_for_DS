# Uber Pickups in NYC Streamlit App

This Streamlit app analyzes Uber pickups in New York City. It provides various interactive visualizations and tools to explore the dataset.

## Features

- **Number of Pickups by Hour**: Visualize the number of Uber pickups for each hour of the day using a bar chart.

- **Filter by Hour**: Use the slider to filter pickups for a specific hour.

- **Map of Pickups**: View the geographic locations of Uber pickups on a map for the selected hour.

- **Raw Data Display**: Toggle to display the raw dataset.

## Data Source

The dataset used in this app is sourced from the following location:

- [Uber Raw Data (September 2014)](https://s3-us-west-2.amazonaws.com/streamlit-demo-data/uber-raw-data-sep14.csv.gz)

## Getting Started

1. Clone the GitHub repository:

```bash
git clone https://github.com/lauren-segalla/tooling_for_DS.git .
```

2. Navigate to the project directory:
   
```bash
cd tooling_for_DS
```

3. Create a virtual environment (optional but recommended):
   
  ```bash
python -m venv .venv
source .venv/bin/activate  # On Windows, use .venv\Scripts\activate
```

4. Install the required dependencies:
   
  ```bash
pip install -r requirements.txt
```

5. Run the Streamlit app:
   
  ```bash
streamlit run uber_pickups.py
```

6. Open your web browser and navigate to the URL provided by Streamlit

## Docker Support

If you prefer to run the app in a Docker container, a Dockerfile is included. To build and run the Docker container, follow these steps:

1. Build the Docker image:

```bash
docker build -t uber-pickups-app .
```
2. Run the Docker container:

```bash
docker run -p 8501:8501 uber-pickups-app
```
3. Access the app in your web browser at [http://localhost:8501](http://localhost:8501)

## License

This project is licensed under the MIT License. 
