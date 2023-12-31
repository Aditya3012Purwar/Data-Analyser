# Data-Analyser

This repository contains a Streamlit-based Data Analyser Bot that leverages time series forecasting techniques such as ARIMA and SARIMA for understanding trends and predicting future sales data. Additionally, it incorporates LangChain, utilizing Large Language Models (LLMs) from OpenAI for question-answering capabilities on the DataFrame.

## Features

1. **Time Series Analysis:**
   - Utilizes ARIMA and SARIMA models to analyze historical sales data and predict future trends.

2. **Data Visualization:**
   - Generates interactive line charts using Streamlit to visualize the original sales data and forecasted values.

3. **LangChain Integration:**
   - Implements LangChain, a language model framework, for understanding and answering questions about the sales data DataFrame.

4. **Question-Answering:**
   - Employs the OpenAI LLM to comprehend and answer user queries related to the sales data.

## Usage

1. Install the required packages:
   ```bash
   pip install streamlit pandas statsmodels langchain
   ```

2. Set the OpenAI API key and SerpAPI key as environment variables:
   ```bash
   export OPENAI_API_KEY="your_openai_api_key"
   export SERPAPI_API_KEY="your_serpapi_api_key"
   ```

3. Run the Streamlit app:
   ```bash
   !streamlit run app.py & npx localtunnel --port 8501
   ```

4. Upload a CSV file containing the sales data when prompted.

5. Visualize the historical sales data and forecasted values.

6. Ask questions about the DataFrame using the provided input box, and the bot will utilize LangChain and the OpenAI LLM to provide answers.

## Dependencies

- Streamlit
- Pandas
- Statsmodels
- LangChain

## Results
![image](https://github.com/Aditya3012Purwar/Data-Analyser/assets/103439955/76f48d59-3443-4637-98fe-24484b268828)

## Acknowledgments

- [OpenAI](https://www.openai.com/) for providing powerful language models.
- [Streamlit](https://streamlit.io/) for creating interactive and user-friendly web applications.
- [LangChain](https://www.langchain.com) for the language model framework.

Feel free to explore, modify, and contribute to enhance the functionality of the Data Analyser Bot!


