# rust web开发

- rust和go的哪个比较适合web开发

    - 这个没有绝对的答案 但有一个基本的答案 *********选GO*********
    > 如果您时间、精力不允许 看到这里您就不要在看下面的东西了 可以关掉网页或是什么别的

    - go的web开发 已经可以满足99%web开发中的并发要求而且已经形成了成熟的体系环境

    - rust
    >我把go称为工程语言，而rust称为学术编程语言

        - rust只适合于极端环境、极端领域、极端的本人意愿
        - 一门语言可以称之为web语言需要两点
            - 完整的语言生态环境
                > 随着rust2018的发布，已经基本满足
            - 成熟、稳定的web框架社区
                > 无论是iron还是rocket都不能称之为成熟和稳定
- diesel
> 个人感觉比较像rust的orm，但做了很多底层的东西还有些sdl，一堆生成脚本 表面像java的mybatis 但源码充斥着大量宏 下面是项目用到的指令

    - diesel setup
    - diesel migration generate create_books
    - diesel migration run
    - diesel migration redo
    - diesel print-schema > src/schema.rs
