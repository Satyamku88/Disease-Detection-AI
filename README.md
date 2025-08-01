
# RuralCare AI - AI-Powered Healthcare for Rural Communities

This is a web application designed to provide AI-powered healthcare solutions, particularly for rural communities. The application features an AI-based symptom checker that suggests possible medical conditions based on user-provided symptoms.

## Description

RuralCare AI is a user-friendly platform that aims to bridge the gap in healthcare accessibility. The core feature is the **AI Symptom Checker**, which leverages a powerful AI model to analyze symptoms and provide instant, preliminary feedback on potential health issues. This tool is designed to be a first point of contact, offering guidance and information while always recommending consultation with a qualified medical professional for an accurate diagnosis.

## Features

  * **AI Symptom Checker**: Enter your symptoms and get an AI-generated suggestion of the possible medical condition.
  * **Emergency SOS**: A prominent SOS button to quickly call for help in emergencies.
  * **Medical Resource Locator**: An integrated map to find nearby medical facilities.
  * **Teleconsultation**: A feature to connect with doctors for remote consultations.
  * **Health Education**: A carousel with health tips on various topics, including maternal care.
  * **Voice Command Interface**: A button for voice commands to interact with the application.

## Screenshot
<img width="1908" height="914" alt="Screenshot 2025-08-01 112805" src="https://github.com/user-attachments/assets/3a0b0b10-1bb1-4772-b9b5-ae8dd506a5a9" />

## Live Demo

You can find a live demo of the application here: [***Your Live Demo Link Here***]

## Technologies Used

  * **HTML5**
  * **CSS3**
  * **Bootstrap 5**
  * **JavaScript (ES6)**
  * **OpenRouter AI API** (for the symptom checker)
  * **Google Maps API** (for the medical resource locator)

## How to Use

To set up this project locally, follow these steps:

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/disease-detection-ai.git
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd disease-detection-ai
    ```

3.  **Get your API Keys:**

      * You will need an API key from [OpenRouter](https://openrouter.ai/) for the AI symptom checker to work.
      * You will also need a Google Maps API key for the medical resource locator.

4.  **Add your API keys to the code:**

      * Open the `index.html` file.
      * Find the following line in the JavaScript section and replace `"Bearer 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"` with your OpenRouter API key:
        ```javascript
        "Authorization": "Bearer YOUR_OPENROUTER_API_KEY",
        ```
      * You will also need to add your Google Maps API key where it is required in the project.

5.  **Open the `index.html` file in your browser.**

    You can do this by double-clicking the file or right-clicking and selecting "Open with" your preferred browser.

## Disclaimer

The AI-powered suggestions provided by this application are for informational purposes only and do not constitute a medical diagnosis. Always consult with a qualified healthcare professional for any health concerns.
