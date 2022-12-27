Start with `git pull` to refresh my local git repo
Create post by creating a new file (example.md) in content
Test file `zola serve` then click on the hyperlink
If looks ok - build it to docs folder `zola build -o docs`
This will update the docs folder
Then check changes `git status` - wil show a list of all untracked changes 
Then track all pending changes `git add .` 
Check all have been tracked with `git status` should all now be in green
Then commit with `git commit -m "Message"` This adds i