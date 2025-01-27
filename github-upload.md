* To avoid the conflict , you need to create the repo on github and then clone it locally
* go to the path you want to download it , then do the clone command 
* لابد من أن تبدأ من أول السطر ولا تترك مسافات كما هو موضح  
``` bash
git clone https://github.com/abdallahafez/docs-repo.git
git add doc-test.md
git add 11.jpg
git commit -m "adding the github uploade file "
git push -u ssh-origin main
```
* this commands you may need 
  
``` bash
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:abdallahafez/test.git
git push -u origin main
```
* or push an existing repository from the command line
``` bash
git remote add origin git@github.com:abdallahafez/test.git
git branch -M main
git push -u origin main
```