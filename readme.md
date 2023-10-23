mkdir gitexercise
cd gitexercise
git init
touch readme.md
echo "commit1" >> readme.md
git add readme.md
git commit -m "commit1"
echo "commit2" >> readme.md
git add readme.md
git commit -m "commit2"
echo "commit3" >> readme.md
git add readme.md
git commit -m "commit3"
git tag tag1
git branch branch
git checkout branch
echo "commit4" >> readme.md
git add readme.md
git commit -m "commit4"
echo "commit5" >> readme.md
git add readme.md
git commit -m "commit5"
echo "commit6" >> readme.md
git add readme.md
git commit -m "commit6"
git tag tag2
git checkout main
echo "commit7" >> readme.md
git add readme.md
git commit -m "commit7"
git merge branch
git checkout branch
git push origin branch
git push --tags
