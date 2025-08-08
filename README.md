## Task
Create a GitHub account (if you don’t already have one).
Create a new repository and name it appropriately.
Create a readme.md file which will contain information regarding this project
Scrape a publicly available website of your choice using any method you're comfortable with (e.g., requests, BeautifulSoup, Selenium).
Choose a website you're personally interested in, preferably one that could be useful for a future machine learning project.
Ensure that the website allows web scraping — do not scrape websites with strict scraping restrictions or paywalls. This is important for ethical usage.
Push your code and scraped data to the GitHub repository you created.
Ensure the repo is publicly accessible

```sh
# Initialize Git repository
git init

# Add all files
git add .

# Make initial commit
git commit -m "Initial commit with web scraper"

# Add remote repository (replace with your repo URL)
git remote add origin git@github.com:yourusername/your-repo-name.git

# Push to GitHub
git push -u origin main

# Check current remote URL
git remote -v

# Change to SSH URL
git remote set-url origin git@github.com:yourusername/your-repo-name.git

# Check status
git status

# Add specific file
git add filename.py

# Commit changes
git commit -m "Your commit message"

# Push changes
git push

# Pull latest changes
git pull

```