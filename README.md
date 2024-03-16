# Veometry

> [!NOTE]
> This README will be updated as the project progresses

Thank you for showing interest in this project. The project can be made successful only using your valuable inputs.

**Veometry** is an web application used for analysing and visualising scientific (or even normal statistical) data. I have came up with this idea after not being able to find any functional and beautiful app for this purpose, let alone free of cost. The development roadmap for this project is provided below.

### Roadmap

[ ] Implement the basic UI for the project
[ ] Use various python libraries to implement a graph plotting application which allows users to manually create a database or upload a .csv/.txt file to import data
[ ] Implement a data storage system and user login system. Users should be able to store upto 200 MB of data in the server.

> [!IMPORTANT]
> You should not change anything in the `LICENSE` file. Doing so will result in rejection of your Pull Request straight away.

### Installation

1. Fork the repo
2. Use `git clone` to download the repository locally
3. Download Docker. You can also continue without docker if you have the appropriate python packages installed.
4. `cd` into the appropriate directory and run `docker-compose up`
5. Your container should be now running.

Alternate from step 3
3. Create a python virtual environment `python3 -m venv .` or `python -m venv .` (for Windows)
4. Run `pip3 install -r requirements.txt` to install all dependencies.
5. Run `python3 manage.py runserver` or `python manage.py runserver` (for Windows).
6. The web app shall now be running.

#### Extra files
If you want to use a database in your project to test the app `cd` into the root directory of the project and create a new file called `db.sqlite3`. This file will be ignored while staging. You are also expected to not include this file in your contribution / pull request.

### Contributing

If you would like to contribute to this project, kindly follow the above installation steps first. Then, try to understand the codebase before you modify anything. Once you've got a good grasp of the part of the project you'd like to contribute to, create a separate branch named `USERNAME/contribution` where `USERNAME` is your github username. This branch naming format is set to sharply distinguish your branch from all the other contributing branches. It will also prevent name clashes with branches created by the project maintainers to implement various features. At the time of writing this, no tests have been written so far. But testing shall soon be implemented in the project and you should preferrably also write a test to test your code. (You can leave the testing part for now as the project is still very small). Before creating a pull request, make sure you follow the above instructions.


