# some-sign-in
glados 每日自动签到

## run
* `cp env.dev.toml env.local.toml`
* 将你的 cookie 信息放入这个配置文件中，运行程序即可。

## ref
* toml 序列化 https://www.perfcode.com/rust-serde/serde-toml.html
* Making HTTP requests in Rust with Reqwest https://blog.logrocket.com/making-http-requests-rust-reqwest/
* 可选的 cron schedule
    * https://github.com/BlackDex/job_scheduler
    * https://github.com/mvniekerk/tokio-cron-scheduler
    * 轻量的 cron https://github.com/kurtbuilds/tokio-cron

