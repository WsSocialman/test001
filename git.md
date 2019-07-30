# git + github

## 配置， 一次就好

- 配置用户名和邮箱， 随意搞
    + git config --global user.name "名字"
    + git config --global user.email "邮箱"

- 生成ssh公钥
    + ssh keygen -t ras -C ["邮箱"]
    + 打开在 c://user/用户/.ssh/ras_pub 公钥， 复制

- github配置公钥
    + 设置-ssh-添加ssh

- 检测有没有配置成功 
    + ssh -T git@github.com // 成功显示github用户名 successfully!

## 克隆远端项目

- git clone github仓库clone处生成的ssh地址 => 这样就建立了与远端同名的本地仓库

- 如果在远端修改了仓库内容， 使用 git pull 同步到本地仓库

## 