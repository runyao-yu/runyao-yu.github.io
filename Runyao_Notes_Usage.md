If want to debug locally:

Step 0: change the url in the _config.yml

url: "https://runyao-yu.github.io" -> "http://localhost:4000"

Step 1: terminal:
 
cd C:\Users\YuR\Desktop\Personal_Website
bundle exec jekyll serve --watch --livereload --force_polling

open:
http://localhost:4000

Step 2: under "_posts" folder, create .md file to add new publications. 
 
Step 3: in _config.yml, modify under career_events or life_events
 
Step 4: Resume can also be placed in _config.yml

Others: Convert_figures_to_white_black.ipynb converts figures to black and white