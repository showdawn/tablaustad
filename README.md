# A static site built with [HUGO](https://gohugo.io/getting-started/quick-start/)

https://tablaustad.com/

### Build status
[![pages-build-deployment](https://github.com/showdawn/tablaustad/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/showdawn/tablaustad/actions/workflows/pages/pages-build-deployment)

### Download Source Code

```git clone --recurse-submodules https://github.com/showdawn/tablaustad```

_If it fails, use this again_
```git submodule update --force --recursive --init --remote```

### Local Build
Install hugo if not installed already

```brew install hugo```

### Run the site locally 

```hugo serve```

### Steps to add a new post

1. Create a section under content/blog
2. Add this code and update the video url and photo
```yaml
---
title: "Raag Chandrakauns"
date: 2021-07-29
featureImage: images/allpost/raag-chandrakauns.jpg
videoURL: https://www.youtube.com/embed/Ad7GB5ycpuI
---
Raag Chandrakauns. Watch and Enjoy...
```
3. Right click on YouTube video and copy the embed code.
4. For image use Photoshop. Base image is in  /dev/hugo/images

### Build Changes for publish

```hugo```


