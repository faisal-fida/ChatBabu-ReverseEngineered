# ChatBabu Reverse Engineered

## Overview

This project aims to reverse-engineer the ChatBabu website by scraping its data and interacting with its API using Python. The notebook demonstrates how to send requests to ChatBabu's endpoints and process the returned data.

## Complexities

### API Interaction
- **Challenge:** Interacting with the ChatBabu API using appropriate headers and payloads.
- **Solution:** Configured detailed headers and payloads to mimic legitimate requests, ensuring successful API interactions.

### Data Handling
- **Challenge:** Processing multipart form-data for POST requests.
- **Solution:** Utilized Python's `BytesIO` to encode payloads correctly and handle multipart form-data efficiently.

## Challenges and Solutions

### Challenge 1: Request Formatting
- **Problem:** Ensuring the payload and headers are formatted correctly for API requests.
- **Solution:** Carefully constructed the headers and payloads to match the API's requirements.

### Challenge 2: Response Parsing
- **Problem:** Extracting useful information from the complex JSON responses.
- **Solution:** Implemented robust parsing functions to extract and display relevant data from the API responses.

## Getting Started

### Prerequisites
- Python 3.x
- `requests` library (`pip install requests`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/faisal-fida/ChatBabu-ReverseEngineered.git
   cd ChatBabu-ReverseEngineered
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:
   ```bash
   jupyter notebook chatbabu_reverse_engineered.ipynb
   ```

## Usage

- The notebook includes code to interact with the ChatBabu API, send queries, and process the results.
- Modify the query variable to test different inputs and observe the responses.

## Contributing

We welcome contributions from the community. Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
