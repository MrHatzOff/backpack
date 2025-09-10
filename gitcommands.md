#COMMON COMMANDS FOR THIS APP

#GITHUB

echo "# backpack" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/MrHatzOff/backpack.git
git push -u origin main

#PYTHON

serve page on port 8000 with python
python -m http.server 8000