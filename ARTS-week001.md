# ARTS-week001

> 每周至少做一个leetcode算法题、阅读并点评至少一篇英文技术文章、学习至少一个技术技巧、分型一篇有观点和思考的技术文章。简称ARTS打卡计划。

## Algorithm

#### [1. 两数之和](https://leetcode-cn.com/problems/two-sum/)

#### [2. 两数相加](https://leetcode-cn.com/problems/add-two-numbers/)

#### [9. 回文数](https://leetcode-cn.com/problems/palindrome-number)

## Review

[The Mistakes I Made As a Beginner Programmer](<https://medium.com/edge-coders/the-mistakes-i-made-as-a-beginner-programmer-ac8b3e54c312>)



## Tip

Mac上使用git克隆GitHub项目（创建可直接使用souretree创建并配置）

1. 检查git是否已安装

   ```shell
   git --version
   ```

2. 到`~/.ssh/`目录下检查ssh公钥私钥是否已存在。如果多个平台会有不同的账号，则在该目录下会存在多对秘钥。

3. 如果没有github的秘钥对存在，则创建

   ```
   命令行 或者 sourcetree
   ```

4. 在`~/.ssh/`目录下创建 config 文件，在其中配置 对不同域名使用不同 秘钥对的配置

5. 将github的公钥 pub文件 添加到github的pub配置中

6. 测试能否连接成功

   ```shell
   ssh -T git@github.com
   ```

7. 使用

   ```
   git clone <url>
   或直接使用sourcetree克隆项目即可
   ```



## Share

[Hibernate Multi Tenancy with Spring](http://www.ticnfae.co.uk/blog/2014/07/16/hibernate-multi-tenancy-with-spring/)

多租户实现方案