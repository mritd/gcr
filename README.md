# GCR 同步仓库 [![Build Status](https://travis-ci.org/mritd/imgsync.svg?branch=master)](https://travis-ci.org/mritd/imgsync)


> 这是一个 Google contaiber registry 镜像同步仓库，目前由 [Travis CI](https://travis-ci.org/mritd/imgsync) 进行每日自动构建

### 同步工具

同步工具已经开源在 [mritd/gcrsync](https://github.com/mritd/imgsync)，如想要自行同步可直接使用该工具

### Manifests

manifests 目录下为目前已经同步的镜像 manifest 文件，每个 tag 一个文件，每次同步完成后 CI 将更新相关文件。
