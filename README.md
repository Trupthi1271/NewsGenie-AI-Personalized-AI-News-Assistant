# NewsGenie

NewsGenie is a Django-based news aggregator that fetches articles from various sources, provides summaries, and even offers audio versions of the articles. It includes user authentication, bookmarking, and personalized recommendations.

## Features

*   **User Authentication:** Register, login, and logout functionality for users.
*   **News Aggregation:** Fetches news articles from various sources using a web scraper.
*   **Article Summarization:** Provides concise summaries of news articles.
*   **Text-to-Speech:** Listen to audio versions of the news articles.
*   **Bookmarking:** Save your favorite articles to read later.
*   **Personalized Recommendations:** Get news recommendations based on your reading history.
*   **Search:** Search for articles based on keywords.
*   **Admin Interface:** Admin panel to manage news articles and users.

## Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/NewsGenie.git
    cd NewsGenie
    ```

2.  **Create a virtual environment and activate it:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the dependencies:**
    ```bash
    pip install django djangorestframework django-debug-toolbar beautifulsoup4 requests gTTS
    ```

4.  **Apply the database migrations:**
    ```bash
    python manage.py migrate
    ```

5.  **Create a superuser:**
    ```bash
    python manage.py createsuperuser
    ```

6.  **Run the development server:**
    ```bash
    python manage.py runserver
    ```

    The application will be available at `http://127.0.0.1:8000`.

## Usage

*   Visit `http://127.0.0.1:8000` to view the website.
*   Register for a new account or log in with an existing one.
*   Browse the news articles, read summaries, and listen to the audio versions.
*   Bookmark your favorite articles.
*   Visit the admin panel at `http://127.0.0.1:8000/admin` to manage the news articles and users.

