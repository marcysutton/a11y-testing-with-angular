# Accessibility and Performance

A presentation on performance and accessibility, including browser rendering quirks and best practices for universal JavaScript apps.

By Marcy Sutton, Senior Front-end Engineer at Deque Systems

##Presenting at:
- Fronteers Spring Thing
- Seattle JS
- Generate NYC

Slide URL: [http://marcysutton.github.io/a11y-perf](http://marcysutton.github.io/a11y-perf)

## Installation

### Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the repository
   ```sh
   $ git clone https://github.com/marcysutton/a11y-perf.git
   ```

5. Navigate to the project folder
   ```sh
   $ cd reveal.js
   ```

6. Install dependencies
   ```sh
   $ npm install
   ```

7. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

8. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.

## License

MIT licensed

Copyright (C) 2016 Marcy Sutton, http://marcysutton.com
