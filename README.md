### publish Github Pages

1. use shell

```shell
git checkout --orphan gh-pages
git rm -rf .
cp -r public/* .
git add .
git commit -m "publish GitHub Pages"
git push origin gh-pages --force
```
