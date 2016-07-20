
Yii-wechat 
==========
原项目地址：[https://github.com/callmez/yii2-wechat]
**由于原项目已停止更新，且composer上的代码还是2014年的，故fork到此，制作目前版本的composer包**

安装步骤如下(2种方式)：

1. 通过composer.json文件安装
   2. `cd 项目目录 && composer require raysoft/yii2-wechat`

   或者

   - 项目目录下的composer.json
   - 添加`"raysoft/yii2-wechat": "dev-master"`内容,然后执行`composer update` (模块中使用了angular的bower源,请确定使用[composer-asset-plugin] **大于** `beta4`的版本)
  \`\`\`
  "require": \{
  '' ...
  '' "raysoft/yii2-wechat": "*",
  '' ...
  }
  \`\`\`
