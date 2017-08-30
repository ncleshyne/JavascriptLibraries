<h1 align="center">Javascript Libraries</h1>

---

## Definition:
A JavaScript library is a library of pre-written JavaScript which allows for easier development of JavaScript-based applications, especially for AJAX and other web-centric technologies.
<br>
One must not confuse the word "library" with "framework." The difference is quite simple: javascript frameworks provide structure to your code while libraries are generic sets of tools that aid in various tasks.
<br>

## jQuery
<h1 align="center"><a href="https://jqueryui.com" target="_blank"><img width="350" height="80" alt="Nicole Shayne" src="https://upload.wikimedia.org/wikipedia/en/9/9e/JQuery_logo.svg"></a></h1>
<br>

> jQuery is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event 
> handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of browsers. With a combination of 
> versatility and extensibility, jQuery has changed the way that millions of people write JavaScript.

jQuery is a widely-used Javascript library that helps you code faster. Its purpose is to make it much easier to use JavaScript on your website. It takes a few lines in jQuery to accomplish many lines of Javascript code making it a "write less, do more" kind of JavaScript library.

```
  JQUERY                         IE9+
    
  $(el).fadeIn();                function fadeIn(el) {
                                    el.style.opacity = 0;
                                    var last = +new Date();
                                    var tick = function() {
                                     el.style.opacity = +el.style.opacity + (new Date() - last) / 400;
                                     last = +new Date();

                                     if (+el.style.opacity < 1) {
                                       (window.requestAnimationFrame && requestAnimationFrame(tick)) || setTimeout(tick, 16);
                                     }
                                   };

                                   tick();
                                 }

                                 fadeIn(el);
```
