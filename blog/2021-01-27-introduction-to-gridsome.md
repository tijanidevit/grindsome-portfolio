---
title: My Experience as a Computer Science Student, The Story and The Glory
path: /my-journey-as-a-computer-science-student
date: 2021-01-27
summary: Logical problem solving has always appealed to me and this explains my interests in mathematics, programming and computing in general. The decision to read computer science was therefore a simple one. My desire for solving challenging problems led to my choices of studying computer science.
tags: ['coding']
---

![background](./images/computer-science.jpg)

> Most users see a computer at the front and use the graphical user interfaces. The first time I used a computer, it intrigued me to know how these interfaces work, the theory behind computers and the methodology of how they work.

## Why Computer Science?

Logical problem solving has always appealed to me and this explains my interests in mathematics, programming and computing in general. The decision to read computer science was therefore a simple one. My desire for solving challenging problems led to my choices of studying computer science. Solving these problems motivates me and has been my driving tool. Learning new tools, programming languages and frameworks is also very exciting, that's where I get my spark from!

## The Curves and Edgy Roads

```js
<template>
  <Layout>
    <div class="container-inner mx-auto my-16">
      <h1 class="text-4xl font-bold leading-tight">{{ $page.post.title }}</h1>
      <div class="text-xl text-gray-600 mb-8">{{ $page.post.date }}</div>
      <div class="markdown-body" v-html="$page.post.content" />
    </div>
  </Layout>
</template>
```


### Prerequisites
You should have basic knowledge about HTML, CSS, [Vue.js](https://vuejs.org) and how to use the [Terminal](https://www.linode.com/docs/tools-reference/tools/using-the-terminal/). Knowing how [Vue Single File components](https://vuejs.org/v2/guide/single-file-components.html) & [GraphQL](https://www.graphql.com/) works is a plus, but not required. Gridsome is a great way to learn both.

Gridsome requires **Node.js** and recommends **Yarn**. [How to setup](/docs/prerequisites)

![background](./images/background.jpg)

### 1. Install Gridsome CLI tool

Using yarn:
`yarn global add @gridsome/cli`

Using npm:
`npm install --global @gridsome/cli`

### 2. Create a Gridsome project

1. `gridsome create my-gridsome-site` to create a new project </li>
2. `cd my-gridsome-site` to open folder
3. `gridsome develop` to start local dev server at `http://localhost:8080`
4. Happy coding 🎉🙌

### 3. Next steps

1. Create `.vue` components in the `/pages` directory to create page routes.
2. Use `gridsome build` to generate static files in a `/dist` folder


- [How it works](/docs/how-it-works)
- [How Pages work](/docs/pages)
- [How to deploy](/docs/deployment)
