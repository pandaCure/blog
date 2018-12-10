# pod 版本管理工具.md

pod 版本版本管理工具需要 Ruby 的支持，所以

#### 安装 Ruby 的版本管理工具

- 安装版本工具

`curl -L get.rvm.io | bash -s stable && source ~/.rvm/scripts/rvm`

- 安装 Ruby 版本
  `rvm install 2.5.0`
- 选择 Ruby 版本
  `rvm use 2.5.0`
- 安装 pod 版本
  如果你是 mac 的 10.11 及以上系统，需要使用命令

  `sudo gem install cocoapods -v <Version> -n /usr/local/bin`

  否则的话使用命令

  `sudo gem install cocoapods -v <Version>`

#### 關宇 React Native 需要注意

- `npm i`
- `react-native link`
