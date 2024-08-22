# GitHub Commit Tracker

This repository contains a Python script to fetch commit history from GitHub, visualize it using a heatmap, and track the commit frequency for the past year for a given GitHub user.

## Features

- Fetches repository information and commit history for a specified GitHub user using the GitHub API.
- Counts commits made by the user for each day over the past year.
- Visualizes commit frequency in the form of a GitHub-style heatmap using `matplotlib` and `seaborn`.
- Supports authenticated API requests to avoid rate-limiting issues.

## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/github-commit-tracker.git
cd github-commit-tracker
```

2. **Install the required dependencies:**

```bash
pip install requests matplotlib seaborn pandas numpy
```

3. set up your GitHub Personal Acceess token:
- Go to GitHub Personal Access Token and generate a new token.
- Replace the placeholder token = ```enter_your_token_here``` with your generated token in the code.

## Usage
1. Update GitHub Username:
Modify the username variable in the script to the GitHub username you want to track.

```bash
username = "your-username"
```

2. Run the script:
```bash
python script_name.py
```

3. Visualize commit activity:
The script will generate a heatmap of commit activity for the past year, which will be displayed using `matplotlib`.


