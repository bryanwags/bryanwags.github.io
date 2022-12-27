1. Start with `git pull` to refresh my local git repo
1. Create post by creating a new file (example.md) in content
1. Test file `zola serve` then click on the hyperlink
1. If looks ok - build it to docs folder `zola build -o docs`
1. This will update the docs folder
1. Then check changes `git status` - wil show a list of all untracked changes 
1. Then track all pending changes `git add .` 
1. Check all have been tracked with `git status` should all now be in green
1. Then commit with `git commit -m "Message"` This adds in the code to the local git repo
1. Finally `git push` to push the code out to the online git repo