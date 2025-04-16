# bioactivity_drug_prediction
1. Introduction
Drug discovery is a multifaceted and resource-intensive endeavor, often taking years to bring a new therapeutic to market. In recent years, computational approaches such as bioactivity prediction have revolutionized early-stage drug development by significantly accelerating the identification of promising candidates. This project is focused on predicting the likelihood that a compound can inhibit the Acetylcholinesterase (AChE) enzyme — a key target in the treatment of neurodegenerative diseases such as Alzheimer's.

2. What is Bioactivity Prediction?
Bioactivity prediction leverages advanced machine learning techniques to estimate the probability that a small molecule will interact with a specific biological target. By predicting the bioactivity of compounds, researchers can efficiently prioritize the most promising candidates for further testing, ultimately speeding up the drug discovery process.

3. Reproducing the Web App
To replicate this web app on your own machine, follow these straightforward steps:

Download the Project Files: Obtain the complete project by downloading the ZIP file.
Set Up the Development Environment:
Open the project folder in Visual Studio Code.
Install the necessary libraries by running the following command:
pip install -r requirements.txt
Run the App: Start the web app by executing:
streamlit run app.py
The app should now be live in your browser.

4. Generating the PKL File
To utilize the machine learning model within this web app, the model must first be trained and saved. This is done by running the provided Jupyter notebook bioactivity_prediction_app.ipynb. Once all the code cells are executed successfully, the trained model will be saved as a pickled file, acetylcholinesterase_model.pkl, which is essential for making predictions in the app.

5. Database Used
The database used for this project is the comprehensive ChEMBL database hosted by the European Bioinformatics Institute (EBI). You can access it at https://www.ebi.ac.uk/chembl/. ChEMBL provides extensive data on bioactive molecules, including detailed information on their biological activities, making it an invaluable resource for bioactivity prediction and drug discovery.

