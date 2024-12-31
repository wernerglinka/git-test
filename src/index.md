---
layout: 'sections.njk'
draft: false
navLabel: 'Home'
bodyClasses: 'home-page'
access:
  noIndex: false
  noFollow: false
seo:
  title: 'Metalsmith First starter'
  description: 'Metalsmith First starter to build a static site with structured content'
  socialImage: 'path to social image'
  canonicalOverwrite: ''
sections:
  - container: 'section'
    name: 'text'
    containerFields:
      isDisabled: false
      isAnimated: false
      containerId: ''
      containerClass: ''
      inContainer: true
      isNarrow: true
      background:
        color: ''
        image: ''
        isDark: false
    text:
      prefix: ''
      title: 'Metalsmith First'
      header: 'h1'
      subtitle: "The only starter you'll need"
      prose: |-
        Hey there! So, you stumbled upon the Metalsmith First Starter. It is pretty opinionated, reflecting all the choices made over the time I've worked with Metalsmith. 

        ![](/assets/images/questions.jpg)
        _Image by Gerd Altmann from Pixabay_

        Wondering what you get?

        - A clean folder setup. `src` holds the pages, and `lib` has assets, styles, scripts, layouts, and metadata.
        - A `package.json` with the usual stuff I like for a site. Delete what you don't want.
        - A ready-to-go `metalsmith.js` with my favorite plugins.
        - Some basic layouts and snippets to kick things off.
        - A template framework to build pages with sections.
        - A simple script to build the site and watch for changes.
        - Swup for cool page transitions and faster loads.
        - Even a smooth scroll back to the top if you click the arrow up in the footer.

        ### Getting Started
        Clone the repository, do an `npm install`, then, hit `npm start` to fire up a dev server. It'll open a browser at `http://localhost:3000`. If you're reading this, you've probably got that covered.

        There is a simple menu in the header. Note the page transitions when you click on a link. It's Swup doing its thing.

        There are three pages so you can get started quickly. The home page, which you are reading right now, a second and third page. Check them out in the `src` folder. Change them to your liking or just delete them and build your own. The `home` and `second` page are frontmatter only structures, no contents. If you're scratching your head, go see [Metalsmith Components](https://metalsmith-components.netlify.app/). Told ya, this starter's got attitude.

        **But to be on the safe side, I have also included a `third` page with some "traditional" content.**

        ### The Techy Bits
        Here's what’s inside this box:

        - Nunjucks for templates.
        - Basic layouts and snippets.
        - A template framework to build pages with sections.
        - Some starter styles (FYI, no SCSS just modern CSS and PostCSS.)
        - Basic scripts and metadata.
        - Swup for cool page transitions and faster loads.

        ### Oh, and One More Thing

        ![](/assets/images/start.jpg)
        _Image by e_stamm from Pixabay_

        There's this tool I made called [Metalsmith Start](https://github.com/wernerglinka/ms-start/). It's a CLI utility that helps set up your frontmatter - gives you a head start. If you want to learn more about the sections that are available, check out the [MS-Start Documentation](https://ms-start-docs.netlify.app/) site.

        But if you're not into that, no worries. Just make a new page in `src` and slap on the frontmatter you need.
---
