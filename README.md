![gitcommands](https://github.com/user-attachments/assets/f4119905-45c4-41eb-b581-fe90b15d83d1)
git push origin main
git branch feature
git checkout feature
git log
touch d.py;git add .;git commit -m "Added d.py";git push origin feature
//origin=repo ; feature=branch
//two branches created
//compare and pull request
merge pull request -> confirm merge
// d.py in main branch is added in remote repo
git checkout main
git pull origin main // now addedd to local repo

git config --global user.name "Varsha" 
git config --global user.email "varshagowdaa2004@gmail.com 
git config --list 
git init 
git status 
touch testFile.py 
ls 
git status 
git add testFile.py (just add content) 
git status 
git commit -m "first version of the file" 
git status 
vi testFile.py   to type i to type,…to save and exit …. Ecs and :wq 
git status 
git add testFile.py (delete the content) 
git commit -m "second version of the file" 
git status 
git show 
vi testFile.py 
git status 
git add testFile.py (add content and for the 4th time add and delete) 
git commit -m "third version of the file" 
git status 
git show 

git show <commitID>  
Going to a particular version 
git checkout <commitID> --*/filename  git checkout master --*/filename 
Correcting the Mistakes 
Edited and saved 
git restore filename 
Edited and added to staging area 
git restore --staged filename 
Edited, addded to Staging area and edited again 
git restore --worktree 
Edited and committed 
Git restore -soft HEAD^ 
Git restore -hard HEAD^ 
Git logging 
Git log -p -2 (last two commit with difference) 
Git log --stat (along with summary of changes) 
Git log --pretty=oneline 
Git log --pretty=format:"%h -%an, %ar:%s 
Git log -S <function_name> 
Grep, since, until, author 

 vim a.py
git add .
git commit -m "Added code"
git log -S printName

sign in to jenkins -> new item -> enter an item name = sample_2 -> ok
build steps -> add build step -> exeute Windows batch command
= mkdir a.txt
echo this is a message > b.txt
save 
build now 
conssole output
sample_2 -> configure -> env

git push origin main 

configure source code management git()
repo url paste
branch specifier = */main 
python a.py in execute
save
build now








