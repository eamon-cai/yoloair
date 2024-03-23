git add .
git commit -m 'update'
git push origin main

git config --global --list
git config --global https.proxy
git config --global http.proxy

git config --global --unset http.proxy
git config --global --unset https.proxy



git reset --hard 0a30a916 回退到特定版本

git push -f 远程分支取消