## 安装步骤

```

git clone https://yldevsvm.faw.com/zbbi/EngWeb      // 把模板下载到本地
//下载不动在控制面板修改凭据
cd  EngWeb     // 进入模板目录
cnpm install       //用cnpm 安装
npm run dev
// 执行构建命令，生成的dist文件夹放在服务器下即可访问
npm run test
npm run build
```

git config格式
```
[core]
	repositoryformatversion = 0
	filemode = false
	bare = false
	logallrefupdates = true
	symlinks = false
	ignorecase = true
[remote "origin"]
	url = https://账号:"密码"@yldevsvm.faw.com/zbbi/EngWeb.git
	fetch = +refs/heads/*:refs/remotes/origin/*
[branch "master"]
	remote = origin
	merge = refs/heads/master

```

开源项目本体
https://github.com/lin-xin/vue-manage-system# vue3
