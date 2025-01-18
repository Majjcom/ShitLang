# ShitLang

ShitLang基于[Lua](https://www.lua.org/)创建

以下是修改的关键词：

- function -> fuck
- print -> shit
- end -> bug
- for -> ufo
- math -> budong
- table -> dian
- var -> van
- do -> fly
- string -> beng
- tostring -> tobeng

### 体验

windows用户可以前往[release](https://github.com/Majjcom/ShitLang/releases/latest)页面下载体验

#### 简单运行 (Windows)

将下载的可执行文件放到目录下。

在此目录下启动终端，运行`shitlang-win.exe xxxx.shit`即可。

#### 编辑shit代码

随便使用一个文件编辑器即可，比如windows上的记事本都可以。

在Windows上创建新代码时，保存的时候记得使用GBK (ANSI)避免出现乱码。

### 构建

使用cmake构建

```shell
mkdir build && cd build
cmake -DCMAKE_BUILD_TYPE=Release ..
cmake --build . -t lua
```

### 注意

**windows上使用时请注意自己系统的默认编码，在中文环境下，请将shitlang代码文件以GBK格式保存，避免乱码**
