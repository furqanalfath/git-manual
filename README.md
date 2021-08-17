# git-manual
Tutorial Git Upload to Github

## On Laptop
1. Install and Download Git ([GitHub Download](https://git-scm.com/downloads)) 
2. Create new folder and type 
`git init`
3. Create new blank file `touch index.html`
4. Add to git `git add index.html` or `git add --all` for all files in folder
5. Commit to git `git commit -m "Your Comment!"`

## Open github.com
1. Create new repository (example : zxc)

## On Laptop
1. `git remote add origin https://github.com/furqanalfath/zxc.git`
2. `git branch -M main`
3. `git push -u origin main` (browser asked to login to github.com)

Finish, your index.html should be at github.com zxc repository.

---

## Remove Remote
1. `git remote -v`
2. `git remote rm origin/upstream`

## Remove directory from git but NOT local
<!-- https://stackoverflow.com/questions/6313126/how-to-remove-a-directory-from-git-repository*/ -->

`git rm -r --cached myFolder`
`git commit -m "your comment"`
`git push -u origin main`

## Clone
1. `git clone https://github.com/twbs/bootstrap`

