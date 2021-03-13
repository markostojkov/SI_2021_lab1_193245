git add -A
git commit -m "Add numbers from 1-5"
git add -A
git commit -m "Add numbers from 6-9"
git add -A
git commit -m "Add some words"
git reset --hard 1a2ae7a639b6bedd3656416cf4ec4d4d31d82f1e
git branch branch1
git branch branch2
git checkout branch1
git add -A
git commit -m "Add 5 words"
git add -A
git commit -m "Add 6 words"
git push -u origin branch1
git checkout branch2
git add -A
git commit -m "Add numbers from 10-15"
