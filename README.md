# Template 

空的模版项目

- cp -r Template <NewProject>
- cd <NewProject>
- rm Template.iml
- sed -i '' 's/Template/<NewProject>/g' `grep Template --include=\*.{md,html,xml} -rl .`
- git remote set-url origin https://github.com/hello-world-example/<NewProject>.git

