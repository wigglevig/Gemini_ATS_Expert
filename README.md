# Resume ATS Expert with Google Gemini AI

Welcome to the **Resume ATS Expert** project! This web application leverages Google's Gemini AI to assist job seekers by analyzing their resumes in the context of job descriptions. Built with Python and Streamlit, this app offers various features to enhance resume evaluation and optimization.

## Features

- **Resume Analysis**: Upload your resume (in PDF format) and receive an in-depth review based on the provided job description.
- **Skill Improvement Recommendations**: Get actionable insights on how to enhance your skills to better align with job requirements.
- **Keyword Identification**: Discover missing keywords in your resume that are crucial for passing Applicant Tracking Systems (ATS).
- **Percentage Match**: Evaluate how closely your resume matches the job description, with detailed feedback on areas of improvement.
- **Custom Queries**: Ask specific questions about your resume and receive tailored responses based on Gemini AI’s analysis.

## How It Works

1. **Upload Your Resume**: Use the file uploader to submit your resume in PDF format.
2. **Enter Job Description**: Provide the job description to compare against your resume.
3. **Choose an Option**: Select one of the available actions to analyze your resume, get skill improvement tips, find missing keywords, or get a percentage match.
4. **Receive Feedback**: View the generated analysis, recommendations, or percentage match, and use the insights to enhance your resume.

## Technologies Used

- **Streamlit**: For creating the interactive web application.
- **Google Gemini AI**: For generating content and insights based on resume and job description analysis.
- **PyMuPDF (fitz)**: For extracting text from PDF files.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/resume-ats-expert.git
    ```

2. Navigate to the project directory:

    ```bash
    cd resume-ats-expert
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Create a `.env` file in the project root directory and add your Google API key:

    ```plaintext
    GOOGLE_API_KEY=your_google_api_key_here
    ```

5. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

## Usage

Open the application in your web browser at the address shown in your terminal. Upload your resume, enter the job description, and use the buttons to get feedback on your resume.

## Contributing

Feel free to open issues or submit pull requests to contribute to this project. Your feedback and contributions are highly appreciated!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
