## week2

Q1: etcd operator应该以什么样的形式部署？

具体问题是：etcd operator在部署的时候是不是只应该运行在master节点上？ 如果master节点有多个，每个master节点都要运行同样的代码吗？



Q2: 在Step1 选出leader,leader运行run方法这一步骤中，leaderelection.RunOrDie() 这一方法的主体是什么，哪些节点在进行选举？



Q3: 如何正确的导包？

这个项目没有go.mod, 只有Gopkg.lock和Gopkg.toml用的是dep命令。网上有两种导包的建议，一种是把Gopkg.lock转成go.mod，另一种是直接用dep命令，两种我都试了下，但都遇到些问题，应该用哪种方式导包容易些呀？