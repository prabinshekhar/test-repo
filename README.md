# test-repo
mkdir test-repo

cd test-repo

git init

echo "Hello" > myfile.txt

git add myfile.txt

git commit -m "Added myfile.txt"

git remote add origin https://github.com/PrabinShekhar/test-repo.git

git remote -v

git branch -M  main

git pull --rebase origin main

git push origin main


