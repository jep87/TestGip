# TestGip
Respository de test

info supplémentaire dans le fichier readme

Copie info
Simple Placeholder
===

Use this if you want to get the `placeholder` attribute to work cross browser and don't want to load
a larger plugin. If you want to get more HTML5 goodness cross browser, I suggest you take a look
at [Modernizr](http://modernizr.com/) or the other great solutions out there.

How to Use
---

Write your HTML as you would normaly:
    
```html
<input type="text" placeholder="Something to be held in place" />
```

Then you simply have to target each types of inputs/textarea you will use:

```javascript
$('textarea[placeholder]').simplePlaceholder();
$('input:text[placeholder]').simplePlaceholder(); // classic input[type=text]
$('input:email[placeholder]').simplePlaceholder(); // email fields input[type=email]
[...] // target other input types you need
```

