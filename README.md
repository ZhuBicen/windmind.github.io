## When first initializing or clone this repo, please download all the submodules

```
  git submodule init
  git submodule update
  // 也有可能 sumbodule 可能会包含其他的 git repo, 所以可以使用一下的命令
  git submodule update --init --recursive
```

otherwise you can meet following error:

```
found no layout file for "HTML" for kind "home"
```

## all submodules are needed don't delete it

## need hugo installed

## How to start a new article

```
1. hugo new content posts/xxx.md
2. edit the md
3. After done change the draft status to False

```
