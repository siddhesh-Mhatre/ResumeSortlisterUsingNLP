Certainly! Below is a basic `README.md` file for your Streamlit JD Matcher App:

```markdown
# JD Matcher App using Streamlit

## Overview

This Streamlit web application is designed to match job descriptions (JDs) with a collection of resumes. It utilizes Doc2Vec for similarity computation between JDs and resumes.

## Dependencies

Ensure you have the required Python libraries installed. You can install them using the following:

```bash
pip install streamlit PyPDF2 gensim numpy pandas
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

2. Run the application:

```bash
streamlit run your_app.py
```

3. Open the app in your browser.

4. Paste your JD into the provided text area.

5. Adjust the similarity threshold using the slider.

6. Select the input and output folders from the sidebar.

7. Click the "Match and Move Resumes" button.

## Note

- Make sure to replace `'D:/InfogenLabs/Resume TEst/GUI/GUI strimer/model/cv_job_maching.model'` with the correct path to your Doc2Vec model.
- Ensure that the input and output folders contain valid PDF resumes.

## Acknowledgments

- This app uses Streamlit for the web interface.
- Doc2Vec is employed for similarity calculations.
- PyPDF2 is used for extracting text from PDF resumes.

Feel free to customize and improve the app based on your requirements.
```

Make sure to replace placeholders like `'your-username'` and `'your-repo'` with your actual GitHub username and repository name. Also, update the path to your Doc2Vec model as mentioned in the note.
