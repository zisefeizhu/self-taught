## git的常规操作
 1、 git clone --bare giturl        
 2、 git push --mirror newgit     
 3、
 ··· 
git clone -b feature/k8s-developer git@gitlab.corp.realibox.com:paas/account-server.git
cd account-server
git status
git branch -m  feature/k8s-developer master
git status
git remote rename origin od_origin
git remote add origin git@gitlab.st.realibox.com:root/account-server.git
git push -u origin master
···