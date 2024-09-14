README xnotes v1

## logs

1. create on github a void repo
2. create in local RStudio, a Quarto Project blog with 

> quarto create blog mixnotes
- with output_dir: docs in _quarto.yml

3. OK or create a new repository on the command line

echo "# mixnotes" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/fischerpj/xnotes.git
git push origin master
