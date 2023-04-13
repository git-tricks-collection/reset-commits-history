# reset-commits-history
Simple way to reset commits history in a repository (make a bkp before!)

---

Open folder of project/repo and...<br><br>

- Checkout:<br>
    `git checkout --orphan latest_branch`<br>

- Add all the files<br>
    `git add -A`

- Commit the changes<br>
    `git commit -am "commit message"`

- Delete the branch<br>
    `git branch -D main`

- Rename the current branch to main<br>
    `git branch -m main`

- Finally, force update your repository<br>
    `git push -f origin main`
   
<br>

---

credits: [author: Kevin Bryniak](https://github.com/marsnebulasoup) → [stackoverflow discussion](https://stackoverflow.com/a/26000395)
