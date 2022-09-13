---
author: "Rajat Gupta"
title: "GSOC Community Bonding Period with Jenkins X"
date: "2022-06-06"
description: "I'm sharing my gsoc experiences with Jenkins X"
tags: ["emoji"]
ShowBreadCrumbs: false
draft: true
cover:
    image: images/gsoc.png
---

Sharing my gsoc experiences with Jenkins X during Community Bonding Period

<!--more-->

The [`emojify`](https://gohugo.io/functions/emojify/) function can be called directly in templates or [Inline Shortcodes](https://gohugo.io/templates/shortcode-templates/#inline-shortcodes).

To enable emoji globally, set `enableEmoji` to `true` in your site's [configuration](https://gohugo.io/getting-started/configuration/) and then you can type emoji shorthand codes directly in content files; e.g.

<p><span class="nowrap"><span class="emojify">🙈</span> <code>:see_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙉</span> <code>:hear_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙊</span> <code>:speak_no_evil:</code></span></p>
<br>

The [Emoji cheat sheet](http://www.emoji-cheat-sheet.com/) is a useful reference for emoji shorthand codes.

---

**N.B.** The above steps enable Unicode Standard emoji characters and sequences in Hugo, however the rendering of these glyphs depends on the browser and the platform. To style the emoji you can either use a third party emoji font or a font stack; e.g.

{{< highlight html >}}

.emoji {
    font-family: Apple Color Emoji, Segoe UI Emoji, NotoColorEmoji, Segoe UI Symbol, Android Emoji, EmojiSymbols;
}

{{< /highlight >}}


{{< css.inline >}}

<style>
.emojify {
	font-family: Apple Color Emoji, Segoe UI Emoji, NotoColorEmoji, Segoe UI Symbol, Android Emoji, EmojiSymbols;
	font-size: 2rem;
	vertical-align: middle;
}
@media screen and (max-width:650px) {
  .nowrap {
    display: block;
    margin: 25px 0;
  }
}
</style>

{{< /css.inline >}}


---
title: "GSoC 2022 Community Bonding Period with Jenkins X"
date: 2022-07-12
draft: false
description: >
  Jenkins X GSoC 2022 Community Bonding Period
categories: [blog]
keywords: [Community, gsoc, 2022]
slug: "GSoC2022-Community-Bonding-Period"
aliases: []
author: Rajat Gupta
---

## Introduction

Hello everyone, I am Rajat Gupta, pursuing my bachelor's in Information Technology.
In 2022, I have been selected as a student developer in Google Summer of Code under Jenkins X.
We will be building a new UI for Jenkins X. I got this news on May 20th, as I received an email from google.

## How I started

The technologies needed were **Golang**, **Kubernetes**, and **GitOps**.
I used golang only once before, while linting Jenkins X codebase, I only used Kubernetes once before while setting up a k3s cluster to run Jenkins X pipelines. These tasks were necessary to do for all GSoC participants. Apart from that, I was a total beginner.

## What I learned during Community Bonding Period

So, when I got selected, I had a lot to learn, my mentors gave me a **30 Day plan**.
They also suggested some resources and conference talks which made it simple for me to start.

30 Day plan was: 
- Learn **golang**
- Getting started with **Kubernetes**
- Learn what is a **CRD** and how they are used?
- Complete a tutorial on **Kubebuilder**
- Getting started with **Tekton** pipelines
- Learn **Jenkins X**

We also had some amazing pair programming sessions, where I used to share my screen and my mentor guided me through, which is not common because mentors have a very busy schedule.
But my mentors helped me a lot.
These sessions helped me in working with the massive Jenkins X codebase and learning its complex workflows.

I also learned that testing and documentation are very important as they make it easier for developers to understand these workflows.
Hence testing also became an important part of my learning period. 


We also started the **UI-sig** a week or two after my selection where we work on Jenkins X UI. 
The learning I did in this community bonding period was just amazing, I learned more in 3 weeks than that what I learned in the past 3 months.

## Highlights

I also attended the **kubeCon**, **cdCon**, and **Jenkins X Contributor Summit 2022** during this period.
When I meet other contributors of Jenkins X, people from CD Foundation were very excited about our plans for the future.
I also gave a small introduction to my project.

If you are looking for a project where you can learn about CI/CD, DevOps, Cloud, Golang, Jenkins X is the best place for you.

Thanks to all my mentors [@ankitm123](https://github.com/ankitm123), [@babadofar](https://github.com/babadofar), [@msvticket](https://github.com/msvticket), and [@tomhobson](https://github.com/tomhobson)