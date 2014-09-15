bootstrap-intro
===============

组内分享bootstrap的示例库以及PPT

1. 使用两个版本的bootstrap进行演示， bootstrapv2 docs可以直接在本地打开， bootstrapv3 docs 依赖于jekyll

Running documentation locally

If necessary, install Jekyll (requires v2.3.x).
Windows users: Read this unofficial guide to get Jekyll up and running without problems.
Install the Ruby-based syntax highlighter, Rouge, with gem install rouge.
From the root /bootstrap directory, run jekyll serve in the command line.
Open http://localhost:9001 in your browser, and voilà.
Learn more about using Jekyll by reading its documentation.

如果是本地下载的是bootstrap-v3.1.1 需要修改_config.xml 才能在本地正确的跑起来， 需要把pygments: true 这一行 改成 highlighter: rouge

2. 基于bootstrap3 给老家创业的朋友花俩小时写一个打印单程序， 参考着玩吧， 没做性能优化， 莫吐槽： http://sqyh.github.io/
