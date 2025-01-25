# User-Behavior-Analysis-in-Reddit-for-Product-Marketing

This project analyzes Reddit user behavior to segment users and provide tailored marketing recommendations for maximizing engagement and visibility.

## Key Features

- Comments/Post Ratio: Measures subreddit activity through the average number of comments per post, identifying highly interactive subreddits for engagement and feedback.

- Engagement Rate: Highlights user activity relative to subreddit size, helping to target subreddits with active participation for impactful marketing.

- Karma Analysis: Tracks high-karma users (regular and superusers) to identify subreddits with credible and influential participants, ideal for ad placements and community engagement.

- Weighted Sum: Computes a comprehensive score for each subreddit based on a combination of comment/post ratio, engagement rate, regular users count, and superusers count, multiplied by their respective weights for meaningful comparisons.

## Installation

### Prerequisites
- Ensure you have Python 3.7 or above installed on your system. You can check your Python version by running:
  ```bash
  python3 --version
  ```
  If Python is not installed, download and install it from [python.org](https://www.python.org/).

### Download the Project Folder

- Download the project folder
- Extract the contents to your desired location on your system.

### Create the Virtual Environment
- Open your terminal or command prompt.
- Navigate to the extracted project folder.
- Run the following command to create the virtual environment:
   ```bash
   python3 -m venv smdm_project
   ```

### Activate the Virtual Environment
- **For Windows:**
  ```bash
  smdm_project\Scripts\activate
  ```
- **For macOS/Linux:**
  ```bash
  source smdm_project/bin/activate
  ```

Once activated, your terminal will show `(smdm_project)` as a prefix.

### Install Required Packages
- Install the required packages using `pip`:
   ```bash
   pip3 install -r requirements.txt
   ```

### Run the Application
- Open the Jupyter Notebook server by running:
   ```bash
   jupyter notebook
   ```
- In the browser, navigate to the behaviour_analysis.ipynb file within the project folder and open it.
- Execute the cells in the notebook as needed to run the code.

### Deactivate the Virtual Environment
- Once finished, deactivate the virtual environment by running:
   ```bash
   deactivate
   ```

## Authors

- Kirankumar Kanaje
- Haravindan Jain
- Amit Vatyani
- Kusuma Shivaramaiah 
- Atharva Chandras
- Induja Ragava


