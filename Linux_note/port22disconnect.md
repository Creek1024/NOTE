## Git port 22 connect timeout
`ssh -T git@github.com`
`ssh -vT git@github.com `

> describe:
>You can use the `ssh -v` command, `-v` Indicates verbose, and a detailed log will be printed

* 修改下面这个文件（Git默认安装目录）

  `C:\Program Files\Git\etc\ssh\ssh_config`
  
  add lines:
  
  ```txt
  Host github.com
  User your uid@email.com
  Hostname ssh.github.com
  PreferredAuthentications publickey
  IdentityFile ~/.ssh/id_rsa
  Port 443
  ```
  
  

