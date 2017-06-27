# Build Design Documentation Made to Last - slides by Marc Friederich

1. Me
  - Marc Friederich, software designer, Antistatique
  - @Zufrieden on twitter/github
2. Introduction
  - Start to love Documentation
  - Sustainable approach!
  - Design should be documented as well
3. Concepts
  - What is design? I mean really!
    - Design is solving problem
    - Good design is ... thanks to Dieter Rams (https://www.vitsoe.com/us/about/good-design)
  - The Law of Leaky Abstractions
    - Bootstrap developers :-(
  - Technical debt
    - Every decision you make ... you may increase the debt
  - Design systems
    - :-)
  - Progressive enhancement - Joy of Web
   - This means that not everyone will experience the same visual design. This is not a bug. This is a feature of the web.
4. Web all the things!
  - Styleguide first approach
  - Product development, styleguide less-more frontend oriented
  - A11Y!
  - Open!
5. What we've learned from building swiss styleguide, and now Vaud
  - Tell the story ;-)
  - Going faster in the browser
  - Rationalize design (component matrix)
  - Discussion (Accessibility/Ethics/Visual/Technical)
6. Takaways
  - Plan your work acceptation ahead
  - Documentation is fun!
  - Designing your design system is important
  - Reduce technical debt
  - Get your hands dirty, brake abstraction law!

## Sources
- Full of ressources about styleguides by Brad Frost http://styleguides.io/ (exemples, podcasts, books, frameworks)
- Frontend Toolbox - our styleguide tool (new version is out) http://frontend.github.io/toolbox/
- The Law of Leaky Abstractions https://www.joelonsoftware.com/2002/11/11/the-law-of-leaky-abstractions/
- Technical debt https://antistatique.net/fr/nous/bloggons/2015/05/22/la-dette-technique
- Design Styleguide exemple for PEGA https://design.pega.com/
-----

## Installation

Some reveal.js features, like external markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Yarn](http://yarnpkg.com/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone this repository

5. Install dependencies
   ```sh
   $ yarn
   ```

6. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

7. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.


## Attributions

Presentation built with [Reveal.js](https://github.com/hakimel/reveal.js)
