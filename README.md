# phase-0-gps-1 #

```
  692  mkdir guided-pairs
  mkdir : made the directory for our repo to live in
  693  ls
  ls : list all items in current directory
  694  cd guided-pairs
  cd : moves into the specified directory
  695  ls -la
  ls -la : lists items in current directory, including hidden files
  696  pwd
  pwd : print working directory
  697  git clone https://github.com/cclazarou/phase-0-gps-1.git
  git clone : clone specified repo to local machine
  698  ls -la
  699  cd phase-0-gps-1/
  700  ls -la
  701  touch awesome_page.md
  touch : create file
  702  ls -la
  703  git branch
  git branch : check current branch
  704  git add .
  git add . : add all files in current dir (stage)
  705  git status
  git status : check status of files in dir
  706  git commit -m "create awesome_page.md"
  git commit : confirm all staged changes to the dir
  707  git push origin master
  git push origin master : push all committed files to our source (github repo in this case)
  708  git checkout -b "add-command-log"
  git checkout -b : enter new branch with specified name
  709  git branch
  710  git rebase --help
  git --help : check manual for specified command and list description
  711  subl .
  subl . : open current directory in sublime editor
  712  git history
  713  history
  history : list all terminal commands since start
```