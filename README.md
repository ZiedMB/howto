# My HowTOs
## How to create a remote repository using bash
```
curl -u ZiedMB https://api.github.com/user/repos -d "{\"name\":\"howto\"}"
git remote add howto https://github.com/ZiedMB/howto.git
git push -u howto master
```

## How to python egg
 - read file from egg 
```
unzip -p /var/lib/waagent/WALinuxAgent-2.2.22/bin/WALinuxAgent-2.2.22-py2.7.egg azurelinuxagent/ga/env.py
```
- creat an egg from repo 
```
python setup.py  bdist_egg
```


