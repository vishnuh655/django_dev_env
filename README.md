# Python Django Development Container

## Setting up the development container
Follow these steps to open this sample in a container using the VS Code Remote - Containers extension:

1. Please ensure that you have [Docker](https://www.docker.com/) and [docker-compose](https://docs.docker.com/compose/) installed in your system

2. Clone this repository to your local filesystem.

3. Press `F1` and select the Remote-Containers: Open Folder in Container... command.

4. Select the cloned copy of this folder, wait for the container to start.

5. Press `ctrl+shift+P` to open a terminal window.

6. Type `cd drf_learner && poetry run python manage.py runserver 0.0.0.0:8000` to run the app.