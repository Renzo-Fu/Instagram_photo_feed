# Breathe Code Photo Feed

This repository contains the source code for the Breathe Code Photo Feed, a simple web application designed to showcase a collection of photographs.

## Project Structure
/project_root
- styles.css
- index.html
- server.py
/images
  - puppy1.png
  - puppy2.png
  - puppy3.png
  - puppy4.png
- README.md
- README.cn.md
- README.es.md

```bash
$ pip3 install flask && python3 server.py
```

- You can create as many HTML files as you want.
- You can also create CSS files and import them into your website using a `<link>` tag placed between the `<head></head>` tags, like this:

```html
<head>
  ...
  <link rel="stylesheet" type="text/css" href="styles.css">
  ...
</head>
```
In this structure, you would save your images in the /images folder. Then, when you reference these images in your HTML, you would use a path relative to your HTML file. For instance:
```html
<img src="/images/photo1.jpg" alt="Description of Photo">
```

### Contributors

This template was built as part of the [Full Stack Developer course](https://4geeksacademy.com/us/coding-bootcamps/part-time-full-stack-developer) at [4Geeks Academy Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) by [Alejandro Sanchez](https://twitter.com/alesanchezr) and [many other contributors](https://github.com/4GeeksAcademy/html-hello/graphs/contributors).

You can find other templates and resources like this at the [school's GitHub page](https://github.com/4geeksacademy/).
