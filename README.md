# chirpier-starter

`_posts`中是`示例markdown`，可自行删除，但要保留`_posts`文件夹，用于存放自己的markdown文件。

`common/img/posts`中是`示例markdown`中使用的资源，可自行删除。

`common/img/web/avatar.png`替换为自己的头像，`_config.yml`中 `avatar: /common/img/web/avatar.png` 为头像。

`common`文件夹也可以删除，然后自己另行创建文件夹，存放资源。

`assets/img/favicons`替换为自己的图片，图片名保持不变。

`_data/authors.yml`用于配置markdown的作者信息。

`_config.yml`中，注意：
```shell
# Fill in the protocol & hostname for your site.
# E.g. 'https://username.github.io', note that it does not end with a '/'.
url: ""  # github仓库可以不用填写


baseurl: "" # github_username.github.io 仓库 不用填写，保持为 baseurl: "" 就可以
baseurl: "/chirpier-starter"  # 非 github_username.github.io 仓库，需要通过此项指定仓库路径，当前行以“chirpier-starter”仓库为例
```
