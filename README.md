# go-learning
Golang 学习笔记

众所周知，Go语言最大的特色就是对高并发的良好支持，而网络上的中文教程基本都是在讲基础语法，几乎没有能讲清楚协程的，且大多不成体系。通过一番查找后，发现还是得通过图书来入门并提升Go，推荐以下一些资料

入门书籍
- [《The Way to Go》](https://github.com/unknwon/the-way-to-go_ZH_CN)(《Go 入门指南》)
- [《Go 语言学习笔记》](https://book.douban.com/subject/26832468/)
- [《Go 语言设计与实现》](https://draveness.me/golang/)
- [《Go 程序设计语言》](https://book.douban.com/subject/27044219/) 本书虽然经常被推荐，但我看还是有些吃力

Go 协程理解
- [《 Visualizing Concurrency in Go 》](https://divan.dev/posts/go_concurrency_visualize/) ([中文版本](https://learnku.com/go/t/39490)) 通过可视化的方式理解 goroutine
- [《Google I/O 2012 - Go Concurrency Patterns》](https://www.youtube.com/watch?v=f6kdp27TYZs) 演讲者为 Go 语言核心开发者之一
- [《Go 语言原本》](https://github.com/golang-design/under-the-hood)


在学习go中，有几个问题一直困惑着我：
1. `GOPATH`应该怎么设置？ 有多个go项目，代码都要放到src目录下吗？文件目录应该怎么组织？
2. go依赖文件为什么下载到了src目录下？
3. 协程怎么可以充分利用到我的四核CPU？我想写一个协程的高并发爬虫练手，怎么写呢？


优秀开源库
- 中文的 Go 标准库 https://github.com/astaxie/gopkg
- GORM https://github.com/go-gorm/gorm
- 比原生net/http更快的 HTTP 请求 https://github.com/valyala/fasthttp
- 爬虫框架 https://github.com/gocolly/colly
- Web 框架 https://github.com/gin-gonic/gin
- Go 语言构建 Web 应用 https://github.com/astaxie/build-web-application-with-golang/blob/master/zh/preface.md
- Go 入门指南 https://github.com/unknwon/the-way-to-go_ZH_CN
- 分布式消息平台 https://github.com/nsqio/nsq
- Go语言 Leetcode https://github.com/halfrost/LeetCode-Go
- Redis 客户端 https://github.com/go-redis/redis
- 视频下载 https://github.com/iawia002/annie