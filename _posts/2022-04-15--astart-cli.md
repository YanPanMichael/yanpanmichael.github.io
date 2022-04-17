---
layout: post
title: astart-cli
subtitle: A beautiful tool to build an integrated process which includes commit, build, change log, push and publish.
gh-repo: astart-cli
gh-badge: [star, fork, follow]
tags: [release]
comments: true
---

This is a beautiful tool to help you to post release process with one command. I strongly encourage you to [take 1 minutes to learn how to use qk-release](https://github.com/YanPanMichael/qk-release) - it'll teach you how to install and config into your app.

## Feature

- One common and quick tool for quick release
- interacion UI with CLI
- Combine with version update, tag commit, building(optional), change log(optional), pushing to git, publishing(optional) etc.

<!-- Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One | -->


<!-- How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :} -->

## install

**Here's a code chunk:**

First, install qk-release in your node_modules folder:

~~~
npm i -D qk-release # OR yarn add -D qk-release
~~~

And here is the same config with release script highlighting:

```javascript
  "scripts": {
    "release": "qkrelease <--skipBuild | --skipLog | --skipPublish>"
  },
```

Finally, start the build and package process:

~~~
npm run release # OR yarn release
~~~

<!-- And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %} -->

### Notification

{: .box-note}
**Note:** 😉😘 If it is helpful to you, please add <b>⭐️<a href="https://github.com/YanPanMichael/qk-release">Star</a></b> Thanks~

<!-- ### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box. -->