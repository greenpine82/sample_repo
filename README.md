Create new repository
GitHub -> Dashboard -> New repository

GitHub -> Profile Menu -> Settings -> Developer Settings -> Personal access tokens -> Tokens (classic) -> check repo option -> generate  

git clone <REPO URL>  
echo "# sample_repo" >> README.md  
git add README.md  
git commit -m "first commit"  
git branch -M main  
git push -u origin main  
