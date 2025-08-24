# 🩺 Cancer Prediction App

This project is a **Machine Learning-powered Cancer Prediction System**
built with **Python**, **Streamlit**, and popular ML libraries\*\*.\
It allows users to input medical data and predicts the likelihood of
cancer using a trained model.

------------------------------------------------------------------------

## 🌐 Live Demo

🚀 Try the app here:
[cancerpredictions.streamlit.app](https://cancerpredictions.streamlit.app)

------------------------------------------------------------------------

## 📂 Project Structure

    cancer_prediction/
    │── app/
    │   ├── main.py          # Streamlit app entry point
    │   ├── utils.py         # Helper functions (if any)
    │── model/
    │   ├── cancer_model.pkl # Saved ML model
    │   ├── scaler.pkl       # Preprocessing scaler (if used)
    │── requirements.txt     # Dependencies
    │── README.md            # Project documentation

------------------------------------------------------------------------

## ⚙️ Features

-   📊 **User Input Form** -- enter medical parameters for prediction\
-   🤖 **ML Model** -- trained classifier for cancer prediction\
-   🌐 **Streamlit Web App** -- interactive, simple, and accessible UI\
-   📦 **Deployed on Streamlit Cloud** -- no local setup required

------------------------------------------------------------------------

## 🚀 Installation (Run Locally)

1.  Clone the repo:

    ``` bash
    git clone https://github.com/daivya4/cancer_prediction.git
    cd cancer_prediction
    ```

2.  Create and activate a virtual environment (recommended):

    ``` bash
    python -m venv venv
    source venv/bin/activate   # Linux/Mac
    venv\Scripts\activate      # Windows
    ```

3.  Install dependencies:

    ``` bash
    pip install -r requirements.txt
    ```

4.  Run the Streamlit app:

    ``` bash
    streamlit run app/main.py
    ```

------------------------------------------------------------------------

## 📦 Deployment

The app is deployed on **Streamlit Cloud** 👉
[cancerpredictions.streamlit.app](https://cancerpredictions.streamlit.app)

To deploy your own: 1. Push code to GitHub\
2. Connect the repo to **Streamlit Cloud**\
3. Set `app/main.py` as the entry point\
4. Done ✅

------------------------------------------------------------------------

## 🧑‍💻 Tech Stack

-   **Frontend/UI**: Streamlit\
-   **Backend/Logic**: Python\
-   **ML Libraries**: Scikit-learn, NumPy, Pandas\
-   **Deployment**: Streamlit Cloud

------------------------------------------------------------------------

## 📜 License

This project is open-source under the **MIT License**.

------------------------------------------------------------------------

## 👨‍💻 Author

Made with ❤️ by **Daivya**
