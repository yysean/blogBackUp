---
title: Hello World
date: 2015-09-02 20:33:26     
categories: 生活类         
tags: [愤青] 
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` objc
//
//  LHZForgetPassWViewController.m
//  LHZWine
//
//  Created by 八戒科技-Mr_Sen on 15/10/20.
//  Copyright © 2016年 Mr-Yangsen. All rights reserved.
//

#import "LHZLoginViewController.h"
#import "LHZForgetPassWViewController.h"

@interface LHZForgetPassWViewController ()<LHZInputBoxTextChangeDelegate>

@property( nonatomic, strong) UILabel *titleLab;
@property( nonatomic, strong) LHZInputBox *phoneBox;
@property( nonatomic, strong) LHZInputBox *codeBox;
@property( nonatomic, strong) GetCodeButton *getCodeBtn;
@property( nonatomic, strong) LHZInputBox *passwordBox1;
@property( nonatomic, strong) LHZInputBox *passwordBox2;
@property( nonatomic, strong) UIButton *sureBtn;

@end

@implementation LHZForgetPassWViewController

- (void)viewDidLoad {

[super viewDidLoad];
[self initBgViewDismissBtn];
[self initInputBoxAndForgetView];

}

```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)