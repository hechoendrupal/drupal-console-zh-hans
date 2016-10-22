# drupal-console-zh-hans
DrupalConsole Chinese Simplified Language / DrupalConsole 简体中文翻译

# DrupalConsole 简体中文翻译

## 用法

Drupal Console 默认安装的是英文版本

为 Drupal Console 安装简体中文语言，运行命令：

```
$ composer require drupal/console-zh-hans
```

### 安装 Drupal Console


为 Drupal 网站安装 Drupal Console，运行下面的 Composer 命令

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### 安装 Drupal Console launcher

为了避免 Drupal 和 Drupal Console 主版本和小版本的之间的冲突， 我们创建了 Drupal Console launcher。 它便于为每个 Drupal 8 网站导入可用的 Drupal Console 命令。
 
安装命令如下：

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or 
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### 参与贡献

如果你想为该翻译做贡献，请查看以下步骤：

- 点击[此处](https://github.com/hechoendrupal/drupal-console-zh-hans#fork-destination-box) Fork 本代码库
- 克隆你 Fork 得到的代码库到你的本地机器
- 设置 upstream

为了保持你的代码库始终是最新的，你需要建立与本代码库的连接。命令如下：

```
$ git remote add upstream git@github.com:hechoendrupal/drupal-console-zh-hans.git
```

在开始工作前，尽量保持与本代码库的更新，你需要运行以下命令

```
$ git fetch upstream
$ git merge upstream/master
```

注意: 推送你的变化到您 Fork 后的代码库，每天创建PR，避免与其他贡献者的贡献相冲突。

# 英文版本

请访问 [https://github.com/hechoendrupal/drupal-console-en](https://github.com/hechoendrupal/drupal-console-en)