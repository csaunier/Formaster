Formaster
=========

Form / inputs markup to define dominant element and other which will share lasting space

**[try demo here](http://jsfiddle.net/dahfazz/Mwpbu/15/)**

Line
----

```html
<div class="line"></div>
```

Lines permits create new horizontal section. Default behavior considers left element as Master.

To define right element as Master, use this markup :

```html
<div class="line rightMaster"></div>
```

Master
------

Being Master means that element will suffer no width restriction

```html
<div class="master"></div>
```

Other
-----

Around Master, you'll find Other elements.

They will share the lasting width, left by Master

```html
<div class="other"></div>
```

Nested
------

For complex template, you can recreate a Master / Others relation inside a Master or Other section

```html 
<div class="master"></div>
<div class="other"></div>
<div class="other">
  <div class="master"></div>
  <div class="other"></div>
  <div class="other"></div>
</div>
```

> Nested Others will share left space by their Master, inside the containing Other width scope