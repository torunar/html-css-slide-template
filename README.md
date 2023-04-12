# Presentation slides in HTML + CSS
Presentation as a code: no Microsoft Powerpoint, no Google Slides, just plain old HTML.

# How to

1. Copy `<section>` from the `<template>` section of [index.html](/index.html) — this will be your slide.
1. Paste as much of slides as you need.
1. For each slide:
    1. Replace `Number` with the number of a slide.
    1. Replace `Title` with the title of a slide.
    1. Replace `Text` with the text of a slide.
    1. Replace `Prev` and `Next` with the numbers of previous and next slides, accordingly.
    
Resulting document body should look like this:
```html
<section id="s1">
  <header>Title #1</header>
  <article>
      <p>Text #1</p>
  </article>
  <nav>
      <a href="#s1"></a>
      <i></i>
      <a href="#s2"></a>
  </nav>
</section>

<section id="s2">
  <header>Title #2</header>
  <article>
      <p>Text #2</p>
  </article>
  <nav>
      <a href="#s1"></a>
      <i></i>
      <a href="#s3"></a>
  </nav>
</section>

<section id="s3">
  <header>Title #3</header>
  <article>
      <p>Text #3</p>
  </article>
  <nav>
      <a href="#s2"></a>
      <i></i>
      <a href="#s3"></a>
  </nav>
</section>
```
 
