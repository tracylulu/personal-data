推送文件到github中：
github:
tracylulu  2627240624lulu

Git config -- local    默认只对某个仓库有效
Git config -- global  对当前用户的所有仓库有效，推荐最常用
git config --local --list

//配置用户名
git config --local user.name  "tracylulu"
//配置邮箱
git config --local user.email "1769517572@qq.com"
//配置代理，不然会连接超时
git config --local http.proxy proxy02.h3c.com:8080


git init
git add README.md
git commit -m "first commit"

git remote add origin https://github.com/tracylulu/kcms.git
git push -u origin master