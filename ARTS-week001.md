# ARTS-week001

> 每周至少做一个leetcode算法题、阅读并点评至少一篇英文技术文章、学习至少一个技术技巧、分型一篇有观点和思考的技术文章。简称ARTS打卡计划。

## Algorithm

#### [1. 两数之和](https://leetcode-cn.com/problems/two-sum/)

#### [2. 两数相加](https://leetcode-cn.com/problems/add-two-numbers/)

#### [9. 回文数](https://leetcode-cn.com/problems/palindrome-number)

## Review

[The Mistakes I Made As a Beginner Programmer](<https://medium.com/edge-coders/the-mistakes-i-made-as-a-beginner-programmer-ac8b3e54c312>)

Aware of mistakes that we might be making, spot signs of them, and avoid them.

1. **Writing code without planning**

   Writing quality programs is a process with a flow: **Think. Research. Plan. Write. Validate. Modify**

   The actual writing of lines of code is probably only 10% of the whole process.

   Do not think about programming as writing lines of code. Programming is a logic-based creativity that needs nurturing.

2. **Planning too much before writing code**

   Do not look for a perfact plan. That does not exist in the world of programming.

   Look for a good-enough plan, something that you can use to get started.

   **Waterfall Approach** 瀑布流

3. **Underestimating the importance of code quality**

   Unclear code is trash. It is not even recyclable.

   Never go beyond the 80 character limit, ever.

   Measuring programming progress by lines of code is like mueasuring aircraft building progress by weight.

4. **Picking the first solution**

   

5. **Not quitting**

6. **Not googling**

7. **Not Using Encapsulation**

8. **Planning for the Unknown**

9. **Not Using the Right Data Structures**

10. **Making Existing Code Worse**

11. **Writing Comments About the Obvious Things**

    Most comments can be replaced with better-named elements in your code.

12. **Not Writing Tests**

13. **Assuming That If Things are Working then Things are Right**

    It's not a bug, It's a feature. — someone who forgot a test case.

14. **Not Questioning Existing Code**

15. 



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