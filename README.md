# How to Install
Run the Backend Locally

To run the backend locally, follow these steps:

    Download the "football-live-score-scraper-backend" folder, which contains the backend files.
    Install Docker on your machine if you haven't already.
    Set the timezone in the Dockerfile located inside the folder to match your local timezone. By default, it is set to Asia/Bangkok:

    Dockerfile

# Set TZ environment variable
ENV TZ Asia/Bangkok

Open your command line or terminal and navigate to the "football-live-score-scraper-backend" directory.
Run the following command to create the Docker image and start the container:

bash script.sh

Make sure you are in the "football-live-score-scraper-backend" directory before running the command.
