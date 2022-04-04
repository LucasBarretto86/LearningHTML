# Learning HTML

- [Learning HTML](#learning-html)
  - [Uncommon tags](#uncommon-tags)
    - [Ruby tag](#ruby-tag)
    - [wbr tag](#wbr-tag)
    - [map tag](#map-tag)
    - [Design Mode](#design-mode)

## Uncommon tags

### Ruby tag

```html
<h1>The ruby and rt elements</h1>

<ruby>
 漢 <rt> ㄏㄢˋ </rt>
</ruby>
```

### wbr tag

```html
<p>Try to shrink the browser window, to view how the very long word in 
the paragraph below will break:</p>

<p>This is a veryveryveryveryveryveryveryveryveryveryveryveryveryveryveryveryveryvery<wbr>longwordthatwillbreakatspecific<wbr>placeswhenthebrowserwindowisresized.</p>
```

### map tag

```html
<h1>The map and area elements</h1>

<p>Click on the computer, the phone, or the cup of coffee to go to a new page and read more about the topic:</p>

<img src="workplace.jpg" alt="Workplace" usemap="#workmap" width="400" height="379">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="coffee.htm">
</map>
```

### Design Mode

```html
<h1>The Document Object</h1>
<h2>The designMode Property</h2>


<p>This document is editable. The designMode is set to "on".</p>

<p>Try editing any text inside this document.</p>

<script>
document.designMode = "on";
</script>
```
