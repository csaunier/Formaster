Formaster
=========

Form / inputs markup to define Master element and Slaves which will share lasting space

**[try demo here](http://cssdesk.com/93BFM)**

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

Slave
-----

Around Master, you'll find Slave elements.

They will share the lasting width, left by Master

```html
<div class="slave"></div>
```

Nested
------

For complex template, you can recreate a Master / Slaves relation inside a Master or Slave section

```html 
<div class="master"></div>
<div class="slave"></div>
<div class="slave">
  <div class="master"></div>
  <div class="slave"></div>
  <div class="slave"></div>
</div>
```

> Nested Slaves will share left space by their Master, inside the containing Slave width scope