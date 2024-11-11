
This project is used to create slides using the reveal-md project.

## Usage

1. Clone the repository,
2. Create slides in reveal.js markdown format in `md-files` folder. Use the files in `samples` folder as starting point examples.
3. Update `_site/site.webmanifest` as needed.
4. Run the following commands.

```sh
pnpm install
pnpm generate
```

This would create the static html version in `_site` folder which you can then host using gh-pages or otherwise.

**Additional Steps:**

* Add elements to generated html as needed, like the Google Tags etc.

## Resources

### Repositories

- [reveal-md](https://github.com/webpro/reveal-md.git)
- rajgoel/[reveal.js-plugins](https://github.com/rajgoel/reveal.js-plugins)
- rajgoel/[reveal.js-demos](https://github.com/rajgoel/reveal.js-demos)
	- demo page for [rajgoel.github.io/reveal.js-demos](https://rajgoel.github.io/reveal.js-demos "https://rajgoel.github.io/reveal.js-demos")
- hakimel/[reveal.js](https://github.com/hakimel/reveal.js)

- highlightjs code highlighting
	- [highlightjs demo](https://highlightjs.org/demo)
	- zenburn.css code
		- highlightjs [zenburn.css code](https://github.com/highlightjs/highlight.js/blob/main/src/styles/base16/zenburn.css)
		- reveal.js [zenburn.css](https://github.com/hakimel/reveal.js/blob/master/plugin/highlight/zenburn.css)
		-

- revealjs [plugins docs](https://revealjs.com/plugins/)
- [reveal.js-mermaid-plugin](https://zjffun.github.io/reveal.js-mermaid-plugin)
- revealjs [themes](https://revealjs.com/themes/)
	- [list of exposed variables](https://github.com/hakimel/reveal.js/blob/master/css/theme/template/exposer.scss)
	- [creating a theme](https://github.com/hakimel/reveal.js/blob/master/css/theme/README.md)
- mermaid
	- charts and [mindmaps](https://mermaid.js.org/syntax/mindmap.html)
	- Mermaid chart [visual editor](https://www.mermaidchart.com/play#pako:eNp1U-9r2zAQ_VeuLhkp1CPN2rH5w1h-N2XpPiwbDPxFts6xFkcKkpzUhP7vO8l2YlZmiNBJ77073bucglRxDKIgK9QxzZm2sJ7GsteDZzo3sQT6Rv04yFgSZSysVGnLBOGHJShqWJSCYxzc1MDxW-CKbRHmrfgZKe--nkCkSkbgKNEGd3FwC3tl3EHi9nkEw_vXGj7xwk43UWobqj1K-IZMS1gpfck_PcXBT4NgcwTkwiodB42CHPZXTFZgcrZHc0PZ_S4CjgWrGtCsXyepQfBLmJIVMPNKTYr5uZI0x4NWMiz3MOIcJPULhASrVJEwfa5pcSGo3Q6lDbmyBkZLoI5cGvJ4hjGt1TEsMLPw3b2TkCRrqM9A9PLMWHaE6W6NLxe1p_4brXW1JzdQ75jgYCpp2QuBvdUzvkEgLySmVihpIEF7REotOzMAYfgFxn6d-FXewTuY0k8Om-7TMYxLUXBgksMUjdhID535dd6BOZfoYe544dfHzmVb5R_jr2rYU1PsUnJxENwZ41tubFUIuXkPa1154w-1a7X_rR2Q0R6ZETSzDeOqzugipApTVSgdXc_9dwuZKIroejQaDFxkrFZbbOMucfEvsYUOBpNPDx9aoTrqEpf_Iw4_fxxeKqij5u2_VQkpk8D8vFka0aOwOdijoj9NLw7Addy4cWFAxl8Fr38BbsswyQ)
	- [live editor](https://mermaid.live/edit)
	- articles: [From Chaos to Clarity: Exploring Mind Maps with MermaidJS](https://www.mermaidchart.com/blog/posts/from-chaos-to-clarity-exploring-mind-maps-with-mermaidjs)


### Articles

- [Create your own auto-publishing slides with reveal-md and Travis CI](https://ericmjl.github.io/blog/2020/1/18/create-your-own-auto-publishing-slides-with-reveal-md-and-travis-ci/)
- [How can I fix the reveal-md rendering of this two-column slide (code+image)?](https://stackoverflow.com/questions/63236806/how-can-i-fix-the-reveal-md-rendering-of-this-two-column-slide-codeimage)

#### Youtube Videos

- Reveal JS — HTML Presentation Framework [playlist](https://www.youtube.com/playlist?list=PLoqZcxvpWzzf_C8QgHC9XbA-bn18qJ-QV)
	- [Reveal JS — HTML Presentation Framework (4 of 6, Custom CSS and slide transitions)](https://www.youtube.com/watch?v=cJIfrqgOhho)

### Plugins

[reveal.js-plugins](https://github.com/rajgoel/reveal.js-plugins/) [(Demos)](https://rajgoel.github.io/reveal.js-demos) : a collection of plugins including:

- [Animate](https://github.com/rajgoel/reveal.js-plugins/tree/master/animate): A plugin for animations using SVG.js.
- [Anything](https://github.com/rajgoel/reveal.js-plugins/tree/master/anything): A plugin for adding plots, charts, animated SVGs,or anything else inside an HTML object using a JSON string and a javascript function.
- [Audio slideshow](https://github.com/rajgoel/reveal.js-plugins/tree/master/audio-slideshow): A plugin for audio playback and recording.
- [Chalkboard](https://github.com/rajgoel/reveal.js-plugins/tree/master/chalkboard): A plugin adding a chalkboard and slide annotation.
- [Chart](https://github.com/rajgoel/reveal.js-plugins/tree/master/chart): A plugin for using Chart.js.
- [Custom controls](https://github.com/rajgoel/reveal.js-plugins/tree/master/customcontrols): A plugin for customization of controls.
- [Fullscreen](https://github.com/rajgoel/reveal.js-plugins/tree/master/fullscreen): A simple plugin allowing to use fullscreen slides.
- [Load content](https://github.com/rajgoel/reveal.js-plugins/tree/master/loadcontent): A plugin allowing to load external content into the body of HTML-elements.
- [Seminar](https://github.com/rajgoel/reveal.js-plugins/tree/master/seminar): a plugin providing interaction capabilities with other hosts and participants (e.g. slide events, chalkboard drawings, Q&A, polls).
- [Poll](https://github.com/rajgoel/reveal.js-plugins/tree/master/poll): a plugin providing online polls (based on the `seminar` plugin).
- [Questions](https://github.com/rajgoel/reveal.js-plugins/tree/master/questions): a plugin adding Q&As to slide decks (based on the `seminar` plugin).
