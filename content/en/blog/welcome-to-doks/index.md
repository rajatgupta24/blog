---
title: "Welcome to Doks 🎉"
description: "This is my first post to myself"
excerpt: ""
date: 2022-09-12T13:01:40+05:30
lastmod: 2022-09-12T13:01:40+05:30
weight: 50
images: [gsoc.png]
categories: [blog, gsoc]
tags: [doks]
contributors: [Rajat Gupta]
pinned: false
homepage: true
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

![image](gsoc.png)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

## Lorem ispum

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

```javascript
const scene = new THREE.Scene();

const camera = new THREE.PerspectiveCamera(45, 500/500);
camera.position.z = 3

scene.add(camera);

const textureLoader = new THREE.TextureLoader()
const texture = textureLoader.load("https://bruno-simon.com/prismic/matcaps/8.png")

const geometry = new THREE.TorusKnotGeometry(.5, .2, 100, 22);
const material = new THREE.MeshMatcapMaterial({
    matcap: texture
});
```

### Lorem ispum

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{{< video ratio="16x9" attributes="controls autoplay muted loop" webm-src="videos/flower.webm" mp4-src="videos/flower.mp4" >}}
