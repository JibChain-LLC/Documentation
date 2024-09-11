# Data Flow

Understanding the data flow within the JibChain PoC project is key to grasping how articles are processed, analyzed, and categorized for risk. 

## Detailed Workflow

### 1. **Article Retrieval**
   - **Process**: The system initiates the retrieval of articles from external sources via API calls.
   - **Technical Details**:
     - **API Requests**: The Article API Service sends HTTP GET requests to retrieve articles.
     - **Response Handling**: The service parses the JSON responses, extracting relevant article content for further processing.

### 2. **Data Preparation**
   - **Process**: Prepares the article text for analysis by cleaning and formatting the content.
   - **Technical Details**:
     - **Normalization**: Converts all articles into a standardized format, ensuring consistency in analysis.
     - **Error Checking**: Validates the data to catch and correct any errors before analysis.

### 3. **Risk Analysis**
   - **Process**: Sends the prepared article text to IBM Watson’s NLU for analysis.
   - **Technical Details**:
     - **Tokenization**: Watson’s NLU breaks down the text into tokens for detailed analysis.
     - **Entity Recognition**: Identifies key entities within the text, such as people, organizations, and locations.
     - **Sentiment and Tone Analysis**: Evaluates the sentiment and tone of the article to assess its risk profile.

### 4. **Categorization**
   - **Process**: Categorizes the articles based on the risk factors identified by Watson.
   - **Technical Details**:
     - **Risk Mapping**: Maps Watson’s analysis results to predefined risk categories.
     - **Decision Logic**: Uses decision algorithms to assign articles to specific risk categories based on the analysis.

### 5. **Storage and Reporting**
   - **Process**: Stores the categorized articles and generates reports.
   - **Technical Details**:
     - **Database Storage**: Articles and their risk categorizations are stored in a database for easy retrieval and analysis.
     - **Data Visualization**: Generates reports and visualizations to present the analysis results clearly and effectively.

This structured data flow ensures that the process from article retrieval to risk categorization is efficient, reliable, and scalable.
