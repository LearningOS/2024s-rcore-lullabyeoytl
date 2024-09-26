我真傻真的

想了半天错在那里，test5/7,发现syscall是忘记增加计数了。。。(os/src/mod.rs)

第一个lab还是比较直白的，建一个taskinfo 跟踪任务状态，每次run task&系统调用时更新taskinfo