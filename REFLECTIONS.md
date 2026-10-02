# Reflections

## 1. Where does your code live?

Aurora Morales  
After I save the file, my changes are only on my computer. When I use git add, the changes move to the staging area, and after git commit, they are saved in my local Git history. After I git push, my changes are on GitHub. My partner can see my work after I push it to GitHub and they run git pull to get the changes onto their own computer.

Tony Salas 
The files are saved on your working directory at first. After that the git add command moves your files to the staging area but it still lives locally and it is not officially saved yet. After you use the git commit the files are then officially saved but still live locally. Once you git push, the files are then officially uploaded to the cloud on Github. from there your partner can git pull and grab the repo that lives in the remote cloud and store it onto their local repo. 

## 2. Your predictions vs. reality

Aurora Morales  
I had predicted that Tony's push probably was not going to go through because I pushed my changes first. And, that is what actually happened. Git rejected his push because I had already pushed a different commit, so GitHub had changes that Tony didn’t have yet. git pull brought those changes onto Tony's computer and combined them with their changes, so he could push without Git rejecting it again.

Tony Salas 
I predicted that there would be an issue because we were both trying to make changes to the same line. Since I pushed first my partner got an error when she tried to push the same line to the cloud. Git rejected my partners push because it did not want to overwrite changes that I had already pushed to the remote repository. When my partner used the git pull it downloaded my changes and attempted to merge them with hers creating a merge conflict . she then resolved it manually.

## 3. Resolving a conflict

Aurora Morales  
For the title conflict in Round 1, my partner and I had different titles, so when I ran git pull, there was a merge conflict in the title line. We both decided together which title we wanted to keep, I then deleted the conflict markers and kept the title we agree on. Before pushing, I ran python3 main.py to make sure the program worked without an error and that the conflict was resolved. Once everything worked, I committed the resolution and pushed it.

Tony Salas 
We both had a merge conflict with the title being written on the same line. I git pulled and saw the merge conflict had my version on the top and her version on the bottom all divided with <,> and = symbols. I removed those markers after discussing which version to keep and we tested it with python3 main.py.

## 4. Getting unstuck

Aurora Morales  
While working on the story, I got confused about whether my changes had actually made it to GitHub. I checked git status and then used git pull, which gave me “Already up to date.” This helped me understand that there weren’t any new changes to pull and that my repository was caught up.

Tony Salas 
A moment where I was stuck was when I tried to run git add my first line of code but I was in the wrong directory. fatal: not a git repository (or any of the parent directories): .git popped up and i decided to check pwd just to try to see where I was. after a close look I realized I was in the wrong directory and I changed to the correct one using ../.. to go back and cd into the proper one.

## 5. Commit messages for a team

Aurora Morales  
The most useful commit message to me was "add story line" because it clearly tells me what was added. The least useful was "testing" because it doesn't really tell me what was being tested or what was changed. If five people were working in the same repo, clear commit messages would make it easier to keep track of everyone's changes and pulling before starting would definitely help make sure everyone is working with the most recent version of the project.

Tony Salas 
I feel like writing fixed merge conflict (titles) was a good one because we include what bug we fixed to what line. And I feel like "add characters" could be more specific in writing what characters specifically were added.(assuming there were many important characters.) It matters because a clear commit can add clarity to what everyone is doing exactly and pulling before you start in case of merge conflicts occur.