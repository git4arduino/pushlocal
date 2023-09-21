hier entsteht ein großartiges projekt

```
mkdir pushlocal
cd pushlocal/
echo "Hier entsteht ein großartiges Projekt" >> README.md
echo "//code folgt" >> projekt.ino
git init
git add .
git commit -m "project start"
echo "// more code" >> projekt.ino
cat projekt.ino
git add .
git commit -m "2nd commit"
```
