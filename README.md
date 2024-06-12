
# Git Large File

Git Large File Storage (LFS) replaces large files such as audio samples, videos, datasets, and graphics with text pointers inside Git, while storing the file contents on a remote server like GitHub.com or GitHub Enterprise.




## Installation & Use

- Step 1 Create A repository
- Step 2 Clone repository
- Step 3 Open in VS Studio
- Step 4 Copy & Paste *largefile in that repository
- Step 5 Open Terminal and paste this

```bash
  git lfs install
```
- Step 6 Then use this code
In each Git repository where you want to use Git LFS, select the file types you'd like Git LFS to manage (or directly edit your .gitattributes). You can configure additional file extensions at anytime. 

```bash
git lfs track "*.largefiles"
```
It will create a file name **.gitattributes**
> You must add all largefiles using these code


![redme](https://github.com/FBS-OJT-031/Git-Large-Files-Commit/assets/58065866/e62e8ac2-fb8b-4cf0-91fa-5548ca822c21)


- Then just push 
```bash
git add .
git commit -m "largefiles"
git push -u origin main
```
- link:https://git-lfs.com/




    
