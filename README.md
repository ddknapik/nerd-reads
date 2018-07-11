# nice-to-read-you

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

