# Getting Started


Setting up GPG & SSH key for Github repo
https://github.com/settings/keys


### Add the file to repo
```
echo "# test00001" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:presci/test00001.git
git push -u origin main
```

Create your folder & start adding the file
