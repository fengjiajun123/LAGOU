#一级标题
##二级标题
###三级标题
-官网"# LAGOU"  
-git init
-git status   查看建立的文件
-git add README.md

-git commit -m "first commit"
-git remote add origin git@github.com:fengjiajun123/LAGOU.git
-git push -u origin master


Git ssh配置
git config --global user.anme"github用户名"
git config --global user.email"github邮箱地址"
ssh-keygen -t rsa -C "github邮箱地址"
.ssh/id_rsa.pub 复制内容到github里面

验证：ssh -T git@github.com