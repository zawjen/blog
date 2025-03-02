# StencilJs or not to StencilJs at Zawjen

One of our Frontend team volunteers from Brazil, **[Hugo Machado de Almeida](https://linkedin.com/in/hv90-m182)** wrote an excellent suggestion about [StencilJs.com](StencilJs.com). It is a library for building reusable, scalable component libraries. The creator of the library claims that it generates small, blazing fast `Web Components` that run everywhere `React`, `NextJs`, `Angular` and `Vue` or even `Vanilla Html/Js`.

I am interested in [`Storybook`](https://github.com/storybookjs/storybook) and [`StencilJs`](https://github.com/stenciljs/core) because it encapsulates `UX` for a large project like `Zawjen`. Potentially we will be using `NextJs` and may not be using multiple frameworks like `React`, `NextJs`, `Angular` or `Vue`. However, we will be building a large number of websites for internal and external use using `NextJs`.

I see `StencilJs` has a potential to encapsulate UX for all of our websites. StencilJs components can provide a single source of truth for Web Components for all of the websites, or for right now [`web-zawjen`](https://github.com/zawjen/web-zawjen) and [`web-zawjen-admin`](https://github.com/zawjen/web-zawjen-admin).

I can see a promise of `StencilJs` supporting `NextJs` SSR. But this has to be validated by doing a `POC` using `NextJs 15` and `React 19`. We need to understand the bundle size of our website and performance with or without `StencilJs`.

So far, I have noticed that `StencilJs`, does not support `ReactNative`. So, for our `ReactNative` mobile app, [`app-zawjen`](https://github.com/zawjen/app-zawjen), we may need to think of another strategy. Storybook does support ReactNative , which is a good news.

The community of `StencilJs` with **12.7K** Github stars is not as strong as `Storybook` **85K** stars, but it is built by the same team that developed once popular `ionic` library. Also it is backed by a very large `low code` company [OutSystems](https://www.outsystems.com/).

Nonetheless, we would require a careful `POC` to see the results. I discovered a few articles and repos showing how to do just right

-   [stenciljs-with-storybook](https://dev.to/jfgmdev/stenciljs-with-storybook-3027)
-   [stencil-storybook-boilerplate](https://github.com/artursopelnik/stencil-storybook-boilerplate)

I hope `Hugo` can do a POC and share results in a blog post.

May Allah guide us in the right direction. Ameen 🌿🌿🌿