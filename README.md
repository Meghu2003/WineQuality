This project predicts the wine quality class labels, i.e.,
      {Very Poor, Poor, Average, Good, Very Good, Excellent}

"app.py" is the python file that contains the deployment code using the python library - streamlit
To deploy it in Google Colab, you need to run the below command,
      !streamlit run app.py & npx localtunnel --port 8501

To deploy it in VisualStudio Code, you will need to run the below command in the terminal,
      streamlit app.py

Note: you need to install the library,
      pip install streamlit --quiet
