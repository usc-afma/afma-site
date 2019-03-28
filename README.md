# AFMA Website Repo

## Introduction
This is the repo of AFMA index webpage

The site is in plain html/css/js.

## Hierachy

- `index.html` is the index html file.
- `contact.html` is the contact page, which is pointed by index html file. Seperating this page is because Fullpage is 
not working with the linked auto scroll fuction. Misscrolling happing all the time with a index more than two sections.
- `404.html` is default 404 request notice page, but not routed (aka not working).
- img: folder for images
    - bg-masthead.jpg: index background img
    - bg-masthead-back.jpg: original index background img
    - bg-signup.jpg: sign up page background img
    - contactbg.png: as the name said
    - learnmore.jpg: second section background img for index
- css: folder for css files
    - afma.css: customized css for AFMA site
    - fullpage.css: css to achieve fullpage feature
    - grayscale.css: original template css, check conflicts if new css added
- js: folder for js files
    - afma.js: customized js for AFMA site
    - fullpage.js: js for fullpage
    - grayscale.js: original js
    - scrolloerflow.js: js to achieve scroll overflow, not working now.
