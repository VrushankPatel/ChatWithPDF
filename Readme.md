# ChatWithPDF

## Setup Instructions

1. **Obtain Google Gemini API Key**  
   - Get your API key and set it as an environment variable:  
     ```sh
     export GOOGLE_API_KEY="your_api_key_here"
     ```

2. **Add PDFs to the Data Directory**  
   - Place all relevant PDFs containing the context inside the `data/` directory at the project root.

3. **Populate the Database**  
   - Run the following command to process the PDFs:  
     ```sh
     python3 populate_database.py
     ```

4. **Query the Data**  
   - Ask questions based on the PDF context:  
     ```sh
     python3 query_data.py "YOUR_QUESTION_HERE"
     ```
