# Open_Source_Contribution_Steps

1) **Find the issue** you want to work on (on the repo's issues page or create one if it doesn't exist).
2) **Fork the repository** to your own GitHub account.
3) **Clone the forked repo** to your local machine using `git clone <your_forked_repo_url>`.
4) **Check the requirements** (e.g., any documentation or setup guides).
5) **Create a virtual environment** (`python3 -m venv venv`).
6) **Activate the virtual environment** (e.g., `source venv/bin/activate` on macOS/Linux or `venv\Scripts\activate` on Windows).
7) **Install all the requirements** for the project (often using `pip install -r requirements.txt` or a similar command).
8) **Sync your fork** with the original repo (to make sure your fork is up to date with the upstream changes) – `git remote add upstream <original_repo_url>` and `git fetch upstream` followed by `git merge upstream/main` (or master).
9) **Create a new branch** for your changes (e.g., `git checkout -b fix-issue-name`).
10) **Fix the issue** by making necessary changes.
11) **Test your changes** to make sure everything works as expected.
12) **Add the changes** to staging (`git add .`).
13) **Commit your changes** with a clear message (`git commit -m "Fix issue with ..."`).
14) **Push** your changes to your forked repo (`git push origin <branch-name>`).
15) **Open a pull request** to the original repository.
16) **Compare and create the pull request**, adding a detailed description of what you’ve done and any context necessary for the maintainers to understand your changes.
