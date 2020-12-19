# Python_clawer

## Question4

Your job is to design and create a CLI application that will parser www.alexa.com data. The application signature
should look like the following:

```shell=
$ ./clawer <action> <arg1> [<arg2>...]
```

The application must be able to accept these actions as param and perform the corresponding tasks:

1. top <number> : show top <number> sites URL on www.alexa.com
2. country <country> : show top 20 sites URL on www.alexa.com by country
   e.g.

```shell=
$ ./clawer top <number>
$ ./clawer country <country>
```

The application needs to have an extensible interface where adding a new action is just a matter of adding more files
and should not require any modifications to the existing code base.
ps. If anything is unclear, you may set a reasonable assumption and state it at the beginning of the situation.

### 使用方式

- 安裝 python 套件
  安裝 python 套件後使用
  安裝：requests、BeautifulSoup、fire
  範例：

  ```shell=
  pip install requests
  ```

- CLI 命令
  ```shell=
  clawer top <number>
  clawer country <country>
  ```
