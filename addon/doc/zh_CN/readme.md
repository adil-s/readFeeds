# Read Feeds-NVDA-RSS阅读插件 #

* 作者: Noelia Ruiz Martínez, Mesar Hameed
* 下载 [稳定版][1]
* 下载 [开发板][2]

此插件提供了一种使用NVDA以Atom或RSS格式读取订阅源的简单方法。 Feed不会自动刷新。下面我们提到feed时，我们指的是RSS和ATOM提要。

## 安装和更新： ##

如果您使用此插件的先前版本，并且个人NVDA配置文件夹中有RSS或personalFeeds文件夹，则在安装当前版本时，会出现一个对话框，询问您是要升级还是安装。选择更新以保留已保存的源，并在新安装的readFeeds版本中继续使用它们。

## 快捷键 ##

### 阅读Feed菜单 ###

您可以从nvda菜单的Tools子菜单访问Read Feeds子菜单，其中有以下菜单选项：

#### 订阅... ####

打开包含以下控件的对话框：

* 过滤条件：用于搜索以前保存的feed的编辑框。
* 已保存的feed列表。
* 文章列表：打开一个对话框，显示当前Feed中的文章列表。选择要阅读的文章，然后按OK按钮在浏览器中打开相应的页面。
* 打开feed：在默认应用程序中打开所选feed。
* 新建：打开带有编辑框的对话框，以输入新Feed的地址。如果地址有效且可以保存Feed，则其名称（基于Feed标题）将显示在Feed列表的底部。
* 重命名：打开一个带有编辑框的对话框，以重命名所选的源。
* 删除：打开确认后删除所选feed的对话框。
* 设置默认值：将选定的Feed设置为默认值，以便可以使用NVDA的快捷键访问其文章。
* 关闭：关闭“源”对话框。

##### 注意 #####

* 如果创建了名为tempFeed的Feed，请将其重命名，因为在需要创建名称已存在的Feed时，可以替换此文件。
* 无法删除作为默认设置的Feed设置。重置配置时，addressFile提要将用作默认值，因此无法删除。

####复制feed文件夹... ####

打开一个对话框，选择一个文件夹，您可以在其中保存Feed的personalFeeds目录。默认情况下，所选文件夹是NVDA的配置目录，该目录将创建personalFeeds目录。

#### 恢复Feed ... ####

打开一个对话框，选择一个替换personalFeeds文件夹中的Feed的文件夹。确保加载包含feed网址的文件夹。

### 快捷键 ###

* Ctrl + Shift + NVDA + Space：宣布当前文章的URL。按两次将打开网页。
* Ctrl + Shift + NVDA + 8：刷新选定的Feed并宣布其最新的标题。
* Ctrl + Shift + NVDA + I：宣布当前的Feed标题和链接。按两次将标题和相关链接复制到剪贴板。
* Ctrl + Shift + NVDA + U：宣布以前的Feed标题。
* Ctrl + Shift + NVDA + O：宣布下一个Feed标题。

## 通知 ##

* 复制标题或URL时。
* 无法连接/刷新Feed时，或者URL与有效Feed不对应。
* 如果无法备份或还原personalFeeds文件夹，NVDA将显示错误消息。
* “文章列表”对话框的标题显示所选的源名称和可用项目数。



## 版本4.0 ##

* 添加了一个按钮，可以从“源”对话框中打开所选的源。

## 版本3.0 ##

* 管理订阅源文件的对话框已被删除。现在，他们的功能包含在“源”对话框中。
* 对话框的可视化表示已得到增强，符合NVDA中显示的对话框的外观。
* 默认配置保存在NVDA的配置中。因此，可以在配置配置文件中设置不同的默认源。
* 需要NVDA 2016.4。


## 版本2.0 ##

* 插件管理器提供了插件帮助。

## 版本1.0 ##

* 发布初始版本

[[!tag dev stable]]

[1]: http://addons.nvda-project.org/files/get.php?file=rf

[2]: http://addons.nvda-project.org/files/get.php?file=rf-dev