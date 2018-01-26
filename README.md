# XECommand 支持复制文本到剪贴板、打印...

XECommand 是一个原生js实现函数的支持复制文本到剪贴板，部分版本较低的浏览器的不支持，任何使用ES6模块编程的项目都能使用。

### 通过NPM安装最新版本
``` shell
npm install xe-command --save
```

### 按需引入
``` shell
import { copy, print } from 'xe-command'

copy('复制该内容到剪贴板')
print()
```

### 引入所有
``` shell
import XECommand from 'xe-command'

XECommand.copy('复制该内容到剪贴板')
XECommand.print()
```

## API :
#### copy (content) 复制文本到剪贴板
```shell
import { copy } from 'xe-command'

copy('复制该内容到剪贴板')
```

#### print () 打印页面
```shell
import { print } from 'xe-command'

print()
```

## License
Copyright (c) 2017-present, Xu Liangzhan