---
title: "我的第一个项目"
date: 2025-07-02
image: /assets/images/projectA.png
layout: default
---

<section class="wrapper py-16">
  <h1 class="text-3xl font-semibold mb-4">{{ page.title }}</h1>
  <img src="{{ page.image }}" alt="{{ page.title }}" class="mb-6 rounded-lg shadow" />
  <p>这是我的第一个使用 Vue3 + Tailwind CSS 构建的项目。</p>
  <ul class="list-disc ml-6 mt-4">
    <li>功能：列表展示、路由导航、接口调用</li>
    <li>技术栈：Vue3, TypeScript, Vite, Tailwind CSS</li>
    <li>仓库：[GitHub 链接](https://github.com/DragonTAT/projectA)</li>
  </ul>
  <a href="/" class="inline-block mt-8 text-blue-600 hover:underline">← 返回首页</a>
</section>