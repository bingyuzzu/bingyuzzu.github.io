---
layout: page
titles: color
---

常用附加格式：
对齐
```
{:.alignleft} 
左对齐，可应用于文本或者图像

{:.alignright} 
右对齐，同上

{:.aligncenter}
居中，同上

{:.text-center}
文本居中
```

<main class="col-md-9 col-xl-8 py-md-3 pl-md-5 bd-content" role="main">
          <h1 class="bd-title" id="content">Colors</h1>
          <p class="bd-lead">Convey meaning through color with a handful of color utility classes. Includes support for styling links with hover states, too.</p>

          <h2 id="color"><span class="bd-content-title">Color<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="#" href="#color" style="padding-left: 0.375em;"></a></span></h2>

<div class="bd-example">

<p class="text-primary">.text-primary</p>
<p class="text-secondary">.text-secondary</p>
<p class="text-success">.text-success</p>
<p class="text-danger">.text-danger</p>
<p class="text-warning">.text-warning</p>
<p class="text-info">.text-info</p>
<p class="text-light bg-dark">.text-light</p>
<p class="text-dark">.text-dark</p>
<p class="text-body">.text-body</p>
<p class="text-muted">.text-muted</p>
<p class="text-white bg-dark">.text-white</p>
<p class="text-black-50">.text-black-50</p>
<p class="text-white-50 bg-dark">.text-white-50</p>
</div>
code:

```
{:.text-primary}

{:.text-secondary}

{:.text-success}

{:.text-danger}

{:.text-warning}

{:.text-info}

{:.text-light.bg-dark}

{:.text-dark}

{:.text-body}

{:.text-muted}

{:.text-white.bg-dark}

{:.text-black-50}

{:.text-white-50.bg-dark} #.bg-dark指背景为dark
```


<h2 id="background-color"><span class="bd-content-title">Background color<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="#" href="#background-color" style="padding-left: 0.375em;"></a></span></h2>

<p>Similar to the contextual text color classes, easily set the background of an element to any contextual class. Anchor components will darken on hover, just like the text classes. Background utilities <strong>do not set <code class="highlighter-rouge">color</code></strong>, so in some cases you’ll want to use <code class="highlighter-rouge">.text-*</code> utilities.</p>

<div class="bd-example">

<div class="p-3 mb-2 bg-primary text-white">.bg-primary</div>
<div class="p-3 mb-2 bg-secondary text-white">.bg-secondary</div>
<div class="p-3 mb-2 bg-success text-white">.bg-success</div>
<div class="p-3 mb-2 bg-danger text-white">.bg-danger</div>
<div class="p-3 mb-2 bg-warning text-dark">.bg-warning</div>
<div class="p-3 mb-2 bg-info text-white">.bg-info</div>
<div class="p-3 mb-2 bg-light text-dark">.bg-light</div>
<div class="p-3 mb-2 bg-dark text-white">.bg-dark</div>
<div class="p-3 mb-2 bg-white text-dark">.bg-white</div>
<div class="p-3 mb-2 bg-transparent text-dark">.bg-transparent</div>
</div>
code:

```
{:.bg-primary}
{:.bg-secondary}
{:.bg-success}
{:.bg-danger}
{:.bg-warning}
{:.bg-info}
{:.bg-light}
{:.bg-dark}
{:.bg-white}
{:.bg-transparent}
```

        </main>