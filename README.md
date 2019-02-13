# nerd-reads

#### [React Awesome Toasts](https://bananabobby.github.io/react-awesome-toasts/)
*Notifications, possible replacement for redux-flash-messages, or at least an inspiration*

#### [React DnD (in TypeScript)](https://github.com/react-dnd/react-dnd/)
*React DnD is a set of React higher-order components to help you build complex drag and drop interfaces while keeping your components decoupled.*

#### [UselessPickles/ts-enum-util](https://github.com/UselessPickles/ts-enum-util)
*Strictly typed utilities for working with TypeScript enums*

#### [React events in depth w/ Kent C. Dodds, Ben Alpert, & Dan Abramov](https://www.youtube.com/watch?v=dRo_egw7tBc)
*Based on a recent pull request in the React repo it was suggested that we chat about how events in React work. Ben and Dan were eager to have this conversation with me :)*

#### [facebookincubator/redux-react-hook](https://github.com/facebookincubator/redux-react-hook)
*React Hook for accessing state and dispatch from a Redux store*

#### [Andarist/use-onclickoutside](https://github.com/Andarist/use-onclickoutside)
*React hook for listening for clicks outside of an element*

#### [Defining Component APIs in React](http://jxnblk.com/writing/posts/defining-component-apis-in-react/)  
*Over the years, I’ve noticed patterns in how I tend to approach component APIs and building out applications and libraries. The following is a collection of thoughts, opinions, and advice for defining component APIs that are meant to be more flexible, composable, and easier to understand. None of these are hard-and-fast rules, but they’ve helped guide the way I think about organizing and creating components.*

#### [Trunk Based Development](https://trunkbaseddevelopment.com)  
*A source-control branching model, where developers collaborate on code in a single branch called ‘trunk’, resist any pressure to create other long-lived development branches by employing documented techniques. They therefore avoid merge hell, do not break the build, and live happily ever after.*

#### [Rapid release at massive scale](https://code.fb.com/developer-tools/rapid-release-at-massive-scale/)  
*We decided to move facebook.com to a quasi-continuous “push from master” system in April 2016. (...) After almost exactly a year of planning and development, over the course of three days in April 2017 we enabled 100 percent of our production web servers to run code deployed directly from master.*

## Type systems

#### [What are covariance and contravariance?](https://www.stephanboyer.com/post/132/what-are-covariance-and-contravariance)

#### [TypeScript Design Goals](https://github.com/Microsoft/TypeScript/wiki/TypeScript-Design-Goals)

#### Discussions around soundness of TypeScript:
- [Type-checking unsoundness: standardize treatment of such issues among TypeScript team/community?](https://github.com/Microsoft/TypeScript/issues/9825)
- [Proposal: covariance and contravariance generic type arguments annotations](https://github.com/Microsoft/TypeScript/issues/10717)
- [Flow vs TypeScript discussion on Hacker News](https://news.ycombinator.com/item?id=14471358)
- [TypeScript unsoundness discussion on Hacker News](https://news.ycombinator.com/item?id=14473197)

#### [semantic-release](https://semantic-release.gitbooks.io/semantic-release/content/#highlights)

#### [CSS Stats](https://cssstats.com)  
Analyse CSS on any given website

#### [A Tinder Progressive Web App Performance Case Study by Addy Osmani](https://medium.com/@addyosmani/a-tinder-progressive-web-app-performance-case-study-78919d98ece0)

#### [A Pinterest Progressive Web App Performance Case Study by Addy Osmani](https://medium.com/dev-channel/a-pinterest-progressive-web-app-performance-case-study-3bd6ed2e6154)

#### [A type-safe approach to Redux stores in TypeScript](https://dev.to/resir014/a-type-safe-approach-to-redux-stores-in-typescript--5ajm)

#### [Assign string literals to string enum type - great tip!](https://github.com/Microsoft/TypeScript/issues/17690#issuecomment-361215664)

#### [React/Redux TypeScript starter project](https://github.com/JonJam/react-redux-ts)

#### [New 'unknown' top type](https://github.com/Microsoft/TypeScript/pull/24439)  
*This PR adds a new top type unknown which is the type-safe counterpart of any. Anything is assignable to unknown, but unknown isn't assignable to anything but itself and any without a type assertion or a control flow based narrowing. Likewise, no operations are permitted on an unknown without first asserting or narrowing to a more specific type.*

#### [Array iteration methods summarized](https://gist.github.com/ljharb/58faf1cfcb4e6808f74aae4ef7944cff)
*JavaScript Arrays have lots of built in methods on their prototype. Some of them mutate - ie, they change the underlying array in-place. Luckily, most of them do not - they instead return an entirely distinct array. Since arrays are conceptually a contiguous list of items, it helps code clarity and maintainability a lot to be able to operate on them in a "functional" way.*

#### [So you want to write a package manager - 50 mins read](https://medium.com/@sdboyer/so-you-want-to-write-a-package-manager-4ae9c17d9527)

#### [Getting Ready For HTTP2: A Guide For Web Designers And Developers](https://www.smashingmagazine.com/2016/02/getting-ready-for-http2/)
*A detailed look at the basics of HTTP/2 as they apply to web designers and developers. We’ll look at the key features of the new protocol, browser and server compatibility, and detail the things you might need to think about as we see more adoption of HTTP/2.*

#### [Using TypeScript with Redux](https://brightinventions.pl/blog/using-typescript-with-redux/)

#### [Optimize Website Speed With Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/speed/get-started)
*This tutorial teaches you how to use Chrome DevTools to find ways to make your websites load faster.*

#### [TypeScript at Lyft](https://eng.lyft.com/typescript-at-lyft-64f0702346ea)
*How Lyft chose TypeScript over FlowType*

#### [A CLI dashboard for webpack dev server](https://github.com/FormidableLabs/webpack-dashboard)

#### [If TypeScript is so great, how come all notable ReactJS projects use Babel?](https://discuss.reactjs.org/t/if-typescript-is-so-great-how-come-all-notable-reactjs-projects-use-babel/4887/2)
Nice discussion with insights from FB and MS colaborators.

#### [Brian Vaughn tweeting on React profiler](https://mobile.twitter.com/brian_d_vaughn/status/1005597605219393537?s=12)

#### [npm trends](http://www.npmtrends.com)
*Compare package download counts over time*

#### [You Probably Don't Need Derived State](https://reactjs.org/blog/2018/06/07/you-probably-dont-need-derived-state.html)
*In this post, we will explain some common anti-patterns with derived state and our preferred alternatives.*

#### [Don’t Use My Grid System (or any others) - Miriam Suzanne - btconfDUS2018](https://vimeo.com/268576559)
*When to use floats, CSS Grid, flexbox, custom properties, and other techniques  
How to make grid-math simple, and lose the grid-system  
How to make grid-systems work for you when you need them*

#### [Bundling JavaScript: The Good, the Dead and the Ugly Code](https://events.techcast.com/btd/2018/Garmisch_1130/)
*How do  ES modules make scope-hoisting possible?  
How is tree-shaking actually done in RollupJS?*

#### [Web performance made easy (Google I/O '18) by Addy Osmani](https://www.youtube.com/watch?v=Mv-l3-tJgGk)

#### [JavaScript Start-up Optimization by Addy Osmani](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/javascript-startup-optimization/)

#### [The Tech Behind a Design System That Scales - Monica Lent](https://www.youtube.com/watch?v=nVcjaiTRgSY)
*Most teams who end up implementing a design system do so because they need a more efficient way to propagate design ideas and their implementations across various products and codebases. They want to stop reinventing the wheel and offer a consistent experience to their end-users — but they also want to be able to adapt and adjust without a ton of manual overhead. In this talk, you'll see how SumUp uses React, Emotion, and Storybook to implement a design system that scales: in terms of people, products, and processes.*

#### [Circuit Ui](https://circuit.sumup.com/#/)
Resources, tooling, and design guidelines for building websites with Circuit UI, the web incarnation of the SumUp Circuit Design System.

#### [Decrease Front-end Size](https://developers.google.com/web/fundamentals/performance/webpack/decrease-frontend-size)
*How to use webpack to make your app as small as possible.*

#### [ES modules: A cartoon deep-dive](https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/)
*Many JavaScript developers know that ES modules have been controversial. But few actually understand how ES modules work. Let’s take a look at what problem ES modules solve and how they are different from modules in other module systems.*

#### [7 Practical Tips for Cheating at Design](https://medium.com/refactoring-ui/7-practical-tips-for-cheating-at-design-40c736799886)
*Improving your designs with tactics instead of talent. Every web developer inevitably runs into situations where they need to make visual design decisions, whether they like it or not. It’s easy to throw your hands up and say, “I’ll never be able to make this look good, I’m not an artist!” but it turns out there are a ton of tricks you can use to level up your work that don’t require a background in graphic design.*

#### [RIP CommonsChunkPlugin](https://gist.github.com/sokra/1522d586b8e5c0f5072d7565c2bee693)
*Webpack 4 removes the CommonsChunkPlugin in favor of two new options (optimization.splitChunks and optimization.runtimeChunk). Here is how it works.*

#### [why-did-you-update](https://github.com/maicki/why-did-you-update)
*Puts your console on blast when React is making unnecessary updates.*

#### [Didact Fiber: Incremental reconciliation](https://engineering.hexacta.com/didact-fiber-incremental-reconciliation-b2fe028dcaec)
*We are writing a React clone to understand what React does under the hood. We call it Didact*

#### [The Ultimate Guide to JavaScript SEO](https://www.elephate.com/blog/ultimate-guide-javascript-seo/)
*How to ensure Google(bot) is able to properly render your website.  
How to see your website the same way Google sees it.  
What the most common JavaScript SEO mistakes are.  
Which one is best: Prerendering, SPA or Isomorphic JavaScript?*

#### [Purgecss](https://github.com/FullHuman/purgecss)
*When you are building a website, chances are that you are using a css framework like Bootstrap, Materializecss, Foundation, etc... But you will only use a small set of the framework and a lot of unused css styles will be included.*

*This is where Purgecss comes into play. Purgecss analyzes your content and your css files. Then it matches the selectors used in your files with the one in your content files. It removes unused selectors from your css, resulting in smaller css files.*

#### [How To Speed Up Continuous Integration Build With New NPM CI And package-lock.json](https://hackernoon.com/how-to-speed-up-continuous-integration-build-with-new-npm-ci-and-package-lock-json-7647f91751a)

#### [Building ChatBots with React & AWS](https://tylermcginnis.com/building-chatbots-with-react-aws/)
*In this tutorial, I’ll walk through how to leverage AWS Amplify, AWS Lambda, & Amazon Lex to build a functioning chatbot!*

#### [Building Serverless React GraphQL Applications with AWS AppSync](https://tylermcginnis.com/building-serverless-react-graphql-apps-with-aws-appsync/)
*Even though GraphQL has gained a lot of popularity over the past year, building the backend for a GraphQL API can be a major pain and a source of confusion for developers new to the ecosystem.*

*AWS AppSync allows developers to offload the complexity and time involved with building a GraphQL backend and only worry about building their application, and it does so with real-time and offline capabilities.*

#### [React Fiber resources ](https://github.com/koba04/react-fiber-resources)
*This is a repository of resources for React Fiber.  
React Fiber is a new React reconciler algorithm, which is used from v16.*

#### [Optimize your libraries with webpack](https://github.com/GoogleChromeLabs/webpack-libs-optimizations)
*Using a library in your webpack project? Use these tips to make your bundle smaller!*

#### [INTO THE WEEDS OF CSS LAYOUT](https://vimeo.com/254679499)
*In this talk we’ll take a serious look at the algorithms your browser is using in order to lay things out using Flexbox and Grid. By understanding how these algorithms work, you’ll be in a better position to make good decisions around layout, and fully take advantage of the possible performance gains of new CSS layout.*

#### [Web Performance Optimization with webpack by Addy Osmani](https://developers.google.com/web/fundamentals/performance/webpack/)
*Modern web applications often use a bundling tool to create a production "bundle" of files (scripts, stylesheets, etc.) that is optimized, minified and can be downloaded in less time by your users. In Web Performance Optimization with webpack, we will walk through how to effectively optimize site resources using webpack. This can help users load and interact with your sites more quickly.*

#### [Building your own CDN for Fun and Profit](https://pasztor.at/blog/building-your-own-cdn)

#### [Chiccocoin: Learn what is a Blockchain by creating one in NodeJS](https://developers.caffeina.com/chiccocoin-learn-what-is-a-blockchain-by-creating-one-in-nodejs-12929a89208b?gi=86896add2cda)

#### [An Overview of JavaScript Testing in 2018](https://medium.com/welldone-software/an-overview-of-javascript-testing-in-2018-f68950900bc3)
*This guide is intended to catch you up with the most important reasoning, terms, tools, and approaches to JavaScript testing in 2018.*

#### [Interpreters, JITS, & Compilers (Oh My!)](https://medium.com/fullstack-academy/interpreters-jits-compilers-oh-my-1bec4702995a)
*Contrasting Code Executors & Translators via Concrete Examples*

#### [How To Make A Dynamic Website Become Static Through A Content CDN](https://www.smashingmagazine.com/2018/02/dynamic-website-static-content-cdn/)

#### [Does React keep the order for state updates? - explained by D. Abramov](https://stackoverflow.com/questions/48563650/does-react-keep-the-order-for-state-updates/48610973#48610973)

#### [How we improved webpack build performance by 95%](https://blog.box.com/blog/how-we-improved-webpack-build-performance-95/)
*At Box, we’re modernizing our front-end architecture with frameworks such as react and redux, as well as webpack for the build process. We’ve tackled many performance issues with the new tools and libraries adopted along the way, and would like to share how we were recently able to improve our webapp build time drastically.*

#### [Understanding CORS](https://medium.com/@baphemot/understanding-cors-18ad6b478e2b)

#### [Ultimate React Component Patterns with Typescript 2.8](https://levelup.gitconnected.com/ultimate-react-component-patterns-with-typescript-2-8-82990c516935)
*Stateful, Stateless, Default Props, Render Callbacks, Component Injection, Generic Components, High Order Components, Controlled Components*

#### [react-redux-tests.tsx](https://github.com/DefinitelyTyped/DefinitelyTyped/blob/master/types/react-redux/react-redux-tests.tsx)
*Test cases written in a way to isolate types and variables and verify the output of `connect` to make sure the signature is what is expected*

#### [The complete guide to static typing in "React & Redux" apps using TypeScript](https://github.com/piotrwitek/react-redux-typescript-guide)
*This guide is a living compendium documenting the most important patterns and recipes on how to use React (and it's Ecosystem) in a functional style with TypeScript and to make your code completely type-safe while focusing on a conciseness of type annotations so it's a minimal effort to write and to maintain types in the long run.*

#### [Type System Differences in TypeScript (Structural Type System) VS C# & Java (Nominal Type System)](https://www.triplet.fi/blog/type-system-differences-in-typescript-structural-type-system-vs-c-java-nominal-type-system/)

#### [Workbox: JavaScript libraries for Progressive Web Apps](https://github.com/GoogleChrome/workbox)
*Precaching, runtime caching, request routing, background sync, helpful debugging*

#### [Mathias Bynens - V8 internals for JavaScript developers](https://www.youtube.com/watch?v=m9cTaYI95Zc)
*This presentation demonstrates how learning just a little bit about JavaScript engine internals can help you improve the run-time performance of your JavaScript code — not just in V8 specifically, but across all JavaScript engines!*

### Design systems

#### [Fabric](https://developer.microsoft.com/en-us/fabric#/components)
#### [Lightning](https://lightningdesignsystem.com)
#### [Atomic Design](https://shop.bradfrost.com)


#### [Setting up multi-platform npm packages](http://2ality.com/2017/04/setting-up-multi-platform-packages.html)
*This blog post explains ways of targeting multiple platforms via the same npm package.*

#### How to Create JavaScript Libraries in 2018
[Part 1](https://developers.livechatinc.com/blog/how-to-create-javascript-libraries-in-2018-part-1/)  
[Part 2](https://developers.livechatinc.com/blog/how-to-create-javascript-libraries-in-2018-part-2/)
