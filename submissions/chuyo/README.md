# 荒原工场培训第二课作业

**提交人**：chuyo (L1uH40yang)

## 1. 本地 Linux 环境实践记录

在本次作业中，我使用 Ubuntu 虚拟机完成了 Git 的基础配置与仓库操作：
- 完成了基本目录查看 (`pwd`) 与测试文件创建；
- 成功克隆了目标仓库 `Wild-Works`；
- 配置了 Git 用户信息并完成了本地代码提交 (`git commit`)。

## 2. 遇到问题与解决心得

在尝试将本地分支推送到远端仓库 (`git push`) 时，遇到了 GitHub 的 Token 身份验证问题（`Invalid username or token`）。

**心得总结**：
1. **身份验证机制**：GitHub 目前已不再支持直接使用账号密码进行命令行 Push 操作，必须配置 Personal Access Token (PAT) 凭证。
2. **灵活应变**：在虚拟机本地推送遇到网络/验证限制时，通过 Fork 仓库并利用 GitHub 网页端与 Pull Request 机制，依然能高效完成开源协同与作业提交流程。
<img width="1972" height="1210" alt="IMG_20261117_173155" src="https://github.com/user-attachments/assets/77dfabb8-92ff-40d2-98c8-eeb087d955ff" />
<img width="2300" height="1406" alt="IMG_20261117_174445" src="https://github.com/user-attachments/assets/f3a87da7-5276-4ced-a118-5655d8595f55" />
<img width="2048" height="1240" alt="IMG_20261117_182148" src="https://github.com/user-attachments/assets/96a38ff9-95fd-46fa-9bb0-81a88d4533e1" />


