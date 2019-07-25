Hi!
Here you could find the result set of Udemy Advanced CSS and SASS Courses (Second Project, Trillo)
You can find a demo via the next url:
[https://glareone.github.io/Udemy-Advanced-Sass-Second-Portfolio-Project/]

To start project you could do the next:
1. npm install
2. npm run start

To build the production version of this site you have to use the next script:
1. npm run build:css

Also there are several scripts which are used by "build:css" and "start":
1. "watch:sass" - watch changes in sass files and update their css result file. Used for development purposes
2.1. "compile:sass": - creates a sass compile file. Used as a start point of build process.
2.2. "prefix:css": - uses autoprefixer to support different browsers. It works with compiled file from the beginning.
2.3. "compress:css": - compressing the result file and compilation and prefixing