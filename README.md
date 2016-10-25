# React <-> D3 Resources

This is a incomplete list of resources on how to link react & d3.

These approaches mostly differ as to 'who' has control over the dom and does the transitions etc. 
That distinction either requires the user to know more about react or d3, vice versa. Some of the approaches (like react-d3 or react-d3-components) include prebuilt charts, other just provide frameworks to place your charts in.

The following list tries to summarize some of the approaches, hopefully there will be some convergence to a (set of) standard(s), at one point.

Also, I included a short section on react wrappers for other charting libraries, such as highcharts.

This list is **UNSORTED**.

**PLEASE** let me know of any other links that should be included here ... PRs very welcome

##HOWTO/Tutorials/Articles
(find the author's contacts on the respective pages)

[10consulting](http://10consulting.com/2014/02/19/d3-plus-reactjs-for-charting/)

[formidable labs, Colin Megill: d3js for Math, React for rendering](http://formidablelabs.com/blog/2015/05/21/react-d3-layouts/)
--> see below: Victory library

[Video for Victory, at ReactiveConf](https://www.youtube.com/watch?v=n8TwLWsR40Y)

[Nicolas Hery, let d3 do the charting work](http://nicolashery.com/integrating-d3js-visualizations-in-a-react-app/)

[siftblog](http://blog.siftscience.com/blog/2015/4/6/d-threeact-how-sift-science-made-d3-react-besties)

[A.Sharif](http://busypeoples.github.io/post/d3-with-react-js/)

[Shirley Wu Medium Blog post](https://medium.com/@sxywu/on-d3-react-and-a-little-bit-of-flux-88a226f328f3)

[Shirley Wu Dec15 at #wafflejs](http://slides.com/shirleywu/deck#/)

[Oliver Caldwell](http://oli.me.uk/2015/09/09/d3-within-react-the-right-way/)
./.
[source](https://github.com/Olical/react-faux-dom)

[Swizec Teller: d3 Enter & Exit transitions in React](https://github.com/Swizec/react-d3-enter-exit-transitions)

[d4 - Declarative Data-Driven Documents](https://github.com/joelburget/d4)

### Videos
[Benjamin Malley at Midwest JS 2015: Interactive Data Visualization with React and D3](https://www.youtube.com/watch?v=nBwm48eM1iY)

[D3 with React | Andreas Savvides | Reactive 2015](https://www.youtube.com/watch?v=NFTWq10bYcs)

##github sources/libraries and examples

[d3act, motivated by Nicolas' approach, see above](https://github.com/AnSavvides/d3act); this even [...has a youtube motivation](https://www.youtube.com/watch?v=6Pbf0n85HH8)

[Victory, of FormidableLabs](https://github.com/FormidableLabs/victory) again [with video](https://www.youtube.com/watch?v=n8TwLWsR40Y)

[react-d3, library including charts](https://github.com/esbullington/react-d3)

[react-d3-components](https://github.com/codesuki/react-d3-components)

[link highlights using reflux](https://github.com/pbeshai/linked-highlighting-react-d3-reflux)

[react-vis, by Uber](https://github.com/uber/react-vis)

####Concrete implementations of d3 charts as react components

[d3 force implementation for react](https://github.com/uber/react-vis-force)

##Wrappers for other charting libraries

[react-highcharts](https://github.com/kirjs/react-highcharts)

----------

### my own approach

[d3-react-squared, a framework for reusable, linked charts](https://github.com/bgrsquared/d3-react-squared)

[live example](http://bgrsquared.com/dogs/)

[blog post](https://medium.com/@ilikepiecharts/about-using-d3-react-squared-an-example-8cc5e5a6b58e#.lrnxtf7to)

[d3-react-squared-c3-loader, loads c3 charts](https://github.com/bgrsquared/d3-react-squared-c3-loader)

[adding d3-version4 in react, playground](https://medium.com/@ilikepiecharts/playing-with-d3-version-4-react-react-motion-3d04c6eb21c9#.a9v0sze5p)
