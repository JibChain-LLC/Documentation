# API Reference

The JibChain PoC project exposes several API endpoints that allow external applications to interact with its article analysis and risk categorization features.

## Endpoints

### 1. **Fetch Articles**
   - **Endpoint**: `/api/fetch-articles`
   - **Description**: Retrieves article data from external sources through an API.
   - **Input**: None required; fetches the latest articles automatically.
   - **Output**: JSON object containing the article data, ready for analysis.

### 2. **Categorize Risk**
   - **Endpoint**: `/api/categorize-risk`
   - **Description**: Analyzes the provided article text using IBM Watson and categorizes it based on the type of risk.
   - **Input**: JSON object containing the article text to be analyzed.
   - **Output**: JSON object detailing the risk category assigned to the article by Watson's analysis.
