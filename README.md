# Knowledge-Graph-Based-Movie-Recommendation-System
This repository contains a comprehensive implementation of a Movie Recommendation System using a Knowledge Graph. The system leverages various algorithms and techniques, providing personalized recommendations based on user preferences and movie attributes.

## Overview
This repository implements a sophisticated Movie Recommendation System using a Knowledge Graph (Neo4j), LangChain, and a Large Language Model (LLM). It provides an interactive interface for users to get personalized movie recommendations and query the system using natural language.

## Approach
The system follows these key steps:

1. **Import Data**: Reads movie data from a CSV file (`imdb_top_1000.csv`) and imports necessary libraries.
2. **Connect to Neo4j**: Establishes a connection to a Neo4j database to store and query movie data efficiently.
3. **Create Database**: Stores movie data, including attributes like title, director, actors, genres, etc., in Neo4j as nodes and relationships.
4. **Generate User Data**: Simulates user demographics and preferences for testing the recommendation system.
5. **Build a QA System**: Leverages LangChain and a large language model (LLama/OpenAI) to answer user queries and generate recommendations by interacting with the Knowledge Graph.
6. **Provide an Interface**: Offers a Gradio-based user interface, enabling users to ask questions and receive recommendations in a user-friendly manner.

## Features
- **Knowledge Graph Integration**: Uses Neo4j to store movie data and build complex relationships.
- **AI-Powered Recommendations**: Employs LLMs to provide intelligent responses and suggestions.
- **User Simulation**: Includes synthetic user data to test and refine the system.
- **Interactive Interface**: Enables users to interact with the recommendation system via Gradio.

## Prerequisites
To run this project, ensure you have the following:
- Python 3.8 or higher
- Neo4j database instance
- CSV file (`imdb_top_1000.csv`) with movie data

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/movie-recommendation-system.git
   cd movie-recommendation-system
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up Neo4j:
   - Install Neo4j Desktop or Community Edition.
   - Create a database and obtain the connection URI, username, and password.

## How to Use
1. **Prepare the Database**:
   - Run the script to populate the Neo4j database with movie data from the CSV file.

2. **Start the System**:
   - Open the Jupyter Notebook (`Movie_recommendation.ipynb`).
   - Execute the cells step by step to:
     - Load data into Neo4j.
     - Generate synthetic user data.
     - Set up the QA and recommendation system.

3. **Launch the Interface**:
   - Use the Gradio interface to ask questions and get movie recommendations.

## File Structure
```
.
├── data/                       # Dataset folder (includes imdb_top_1000.csv)
├── Movie_recommendation.ipynb  # Main Jupyter Notebook for implementation
├── requirements.txt            # Python dependencies
├── README.md                   # Project documentation
```

## Technologies Used
- **Neo4j**: For graph-based storage and querying.
- **LangChain**: For connecting with the LLM and building the QA system.
- **Gradio**: To create a user-friendly interface.
- **Python Libraries**: Pandas, NumPy, Matplotlib, and more for data processing and visualization.

## Future Enhancements
- Expand the dataset to include more movies and genres.
- Enable real-time user feedback to refine recommendations.
- Incorporate multilingual support for user queries.

## Contributing
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact
For any queries or feedback, please contact:
- **Name**: Himadri
- **Email**: himadri.roni@gmail.com
- **GitHub**: [yourusername](https://github.com/Heminoid)
