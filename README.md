# How to create a remote repository using bash
curl -u ZiedMB https://api.github.com/user/repos -d "{\"name\":\"howto\"}"
git remote add howto https://github.com/ZiedMB/howto.git
git push -u howto master
