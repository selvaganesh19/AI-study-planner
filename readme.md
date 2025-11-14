# AI Study Planner 🚀

[![GitHub stars](https://img.shields.io/github/stars/selvaganesh19/AI-study-planner?style=social)](https://github.com/selvaganesh19/AI-study-planner)
[![GitHub forks](https://img.shields.io/github/forks/selvaganesh19/AI-study-planner?style=social)](https://github.com/selvaganesh19/AI-study-planner)
[![License](https://img.shields.io/github/license/selvaganesh19/AI-study-planner)](https://github.com/selvaganesh19/AI-study-planner/blob/main/LICENSE)

## Introduction 👋

AI Study Planner is an AI-powered application designed to revolutionize your study habits. ✌️ It helps you create personalized study schedules, suggests optimal study techniques, and keeps you motivated to achieve your academic goals. This project leverages the power of Large Language Models, specifically through the OpenRouter API, to deliver a dynamic and effective study planning experience.  ✨

## Features 💡

*   **Personalized Study Schedules:**  Generate customized study plans based on your courses, deadlines, and preferred learning style. 🗓️
*   **AI-Powered Topic Prioritization:**  The AI intelligently prioritizes topics based on difficulty and exam relevance. 🧠
*   **Study Vibe Generation:** Receive motivational quotes, playlist suggestions, and ambient sound recommendations to create the perfect study atmosphere. 🎶
*   **Flexible and Adjustable Plans:**  Easily modify your schedule to accommodate unexpected events or changes in priorities. 🔄
*   **Simple & Intuitive Interface:** User-friendly frontend designed for ease of access and navigation.💻
*   **OpenRouter Integration:** Utilizes the OpenRouter API to connect to powerful language models.🌐

## Installation 🛠️

Follow these steps to get the AI Study Planner up and running on your local machine:

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/selvaganesh19/AI-study-planner.git
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd AI-study-planner
    ```

3.  **Backend Setup:**
    ```bash
    cd backend
    ```
    Create a `.env` file in the `backend` directory and add your OpenRouter API key:
    ```
    OPENROUTER_API_KEY=your_openrouter_api_key
    OPENROUTER_MODEL=your_openrouter_model  #Optional, defaults to a standard model
    ```
    Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```
    

4.  **Frontend Setup:**
    ```bash
    cd ../frontend
    ```
    No specific setup is required for the frontend, as it's a static HTML page.

## Usage 🚀

1.  **Run the Backend (Flask) server:**

    Navigate to the `backend` directory and execute:

    ```bash
    python app.py
    ```

    This will start the Flask development server, typically on `http://127.0.0.1:5000/`.

2.  **Open the Frontend:**

    Open the `frontend/index.html` file in your web browser.

3.  **Interact with the App:**

    *   Enter your study topics and deadlines.
    *   Click "Get Study Plan" to generate a personalized schedule.
    *   Explore the suggested study vibes to enhance your focus.

   **API Endpoints:**
   * `/plan`: POST request with course details to generate a study plan.
   * `/vibe`: GET request to get a motivational or study vibe suggestion.

## Contributing 🤝

We welcome contributions to the AI Study Planner!  Here's how you can get involved:

1.  **Fork the repository.**
2.  **Create a new branch for your feature or bug fix:**

    ```bash
    git checkout -b feature/your-feature-name
    ```

3.  **Make your changes and commit them:**

    ```bash
    git commit -m "Add your descriptive commit message"
    ```

4.  **Push your branch to your forked repository:**

    ```bash
    git push origin feature/your-feature-name
    ```

5.  **Create a pull request to the main repository.**

Please ensure your code follows our coding style guidelines (to be defined, but generally Python's PEP 8 and clean, readable code).  Include unit tests whenever possible.

## License 📝

This project is licensed under the [MIT License](https://github.com/selvaganesh19/AI-study-planner/blob/main/LICENSE) - see the [LICENSE](https://github.com/selvaganesh19/AI-study-planner/blob/main/LICENSE) file for details.


## License
This project is licensed under the **MIT** License.

---
🔗 GitHub Repo: https://github.com/selvaganesh19/AI-study-planner