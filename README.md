
<h1>Multilingual Handwriting Recognition and Translation</h1>
To create a model that recognises written text from an image file uploaded by the user and translates the recognised text into the languages provided.


## Table of Contents
- [Table of Contents](#table-of-contents)
- [Objectives](#objectives)
- [Objectives completed](#objectives-completed)
- [Usage](#usage)
  - [Installation](#installation)
  - [Navigation](#navigation)
- [Team](#team)
  - [Mentors:](#mentors)
  - [Members:](#members)

## Objectives
* To accurately recognise the text contained in the image uploaded.
* To provide accurate translations for both target languages.
* To provide appropriate translation, with respect to using region specific and colloquial words in the translations.
* To have a flexible dataset which can be altered to suit any use case by appending or deleting words/sentences provided in the dataset for translation.
* To make our project applicable to many real-life based use cases (see Objectives - pt. 4).

## Objectives completed 
  1. Accuracy achieved:
      * Translation to French: 93.76%
      * Translation to Spanish: 96.86%

  2. Since the datasets are stored in .txt file format, they can be infinitely edited to suit multiple use cases such as:
        * A program that translates ancient texts or manuscripts.
        * Travel-based translator to help people communicate when they are abroad.
        * Digitisation of documents in several languages in order to go paperless.
        * A system which converts handwritten text into digital format and translates it into audio for visually impaired individuals, enabling them to access and understand written content.


## Usage

### Installation

<details>
    <summary><b>Installation Steps</b></summary>
  
    1. Clone the Repository: 
          - Open the GitHub repository of the project. 
          - Click on the "Code" button and copy the repository URL. 
          - Open your terminal or command prompt. 
          - Navigate to the directory where you want to clone the repository. 
          - Run the following command to clone the repository:
                git clone <repository_url>

    2. Setting up the Environment: 
          - Make sure Python is installed on your system. If not, download and install Python from the official website (https://www.python.org). 
          - Create a virtual environment (optional but recommended) to isolate the project dependencies using the following command:
                python -m venv env

          - Activate the virtual environment:
                -- For Windows: Run the command: env\Scripts\activate
                -- For macOS/Linux: Run the command: source env/bin/activate. 
                -- Install the required dependencies by running the following command:
                    pip install -r requirements.txt

    3. Saving Files to Drive: 
          - Make sure you have a Google account and access to Google Drive. 
          - Follow the instructions in the documentation or code to integrate the project with Google Drive. 
          - Authenticate the project with your Google account and grant the necessary permissions to access Google Drive. 
          - Modify the code to specify the Google Drive directory path where you want to save the files.

    4. Google Colab Integration: 
          - Upload the project files (or the entire cloned repository folder) to your Google Drive. 
          - Open Google Colab in your web browser.
          - Mount your Google Drive in Colab by running the following code snippet:
                from google.colab import drive
                drive.mount('/content/drive')

          - Navigate to the project folder using the file navigation panel in Google Colab.
          - Open the project notebook (.ipynb file) and start working with it.

    5. PyCharm Integration: 
          - Open PyCharm and create a new project. 
          - Set the project interpreter to the virtual environment you created earlier. 
          - Add the project files (or the entire cloned repository folder) to your PyCharm project. 
          - Open the project notebook (.ipynb file) and start working with it.
</details>

### Navigation

<details>
    <summary><b>Show instructions</b></summary><br>
  
    1. Accessing the website: 
        - Open your web browser and navigate to the URL of the hosted website.
        - The main page of the website will be displayed.

    2. Uploading the handwritten text image: 
        - On the page, locate the "Choose file" button.
        - Click on the "Choose file" button to open the file selection window. 
        - Browse your computer to find the handwritten text image file that you want to process. 
        - Select the file and click "Open" to initiate the upload process. 

    3. Performing handwriting recognition: 
        - Locate the "Predict" button on the main page. 
        - Click on the "Predict" button to initiate the handwriting recognition process. 
        - Wait for the system to process the uploaded image and recognize the handwritten text. 
        - Once the recognition process is completed, the recognized text will be displayed on the screen.

    4. Translating the recognized text: 
        - Locate the "Translate to French/Spanish" button on the main page. 
        - Click on the "Translate to French/Spanish" button to initiate the translation process. 
        - The system will use the selected translation language to translate the recognized text. 
        - Once the translation process is completed, the translated text will be displayed on the screen.
  
    Note:
        - The Choose file button opens up a window for the user to select an image file from their device.
        - The Predict button gives the user the text contained within the image as an output.
        - Translate to French / Translate to Spanish buttons invoke the translation models in the program and show the translated output.

</details>


## Team

### Mentors:
Irfan Siddavatam ( irfansiddavatam@somaiya.edu )<br>
Ashwini Dalvi ( ashwinidalvi@somaiya.edu )

### Members:
| Sr No. | Name | e-mail | git-profile |
| ------ | ------------- | ------------------------- | -------------- |
| 1. | Vedant Hire | vedant.hire@somaiya.edu | vedanthire14 |
| 2. | Pranav Mahulkar | pranav.mahulkar@somaiya.edu | Pranav-Mahulkar |
| 3. | Chinmay Maitre | chinmay.maitre@somaiya.edu | Chinmay-Maitre08 |
| 4. | Hiral Patel | hiral.patel2@somaiya.edu | hiral25p |
