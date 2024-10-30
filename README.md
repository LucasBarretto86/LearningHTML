# Learning HTML

- [Learning HTML](#learning-html)
  - [Uncommon tags](#uncommon-tags)
    - [Ruby tag](#ruby-tag)
    - [wbr tag](#wbr-tag)
    - [map tag](#map-tag)
    - [Design Mode](#design-mode)
    - [Base tag](#base-tag)
    - [Cite tag](#cite-tag)
    - [Abbr tag](#abbr-tag)
    - [Address Tag](#address-tag)
    - [kbd Tag](#kbd-tag)
    - [Samp Tag](#samp-tag)
    - [q Tag](#q-tag)
    - [params Tag](#params-tag)
    - [Meter Tag](#meter-tag)
    - [Progress Tag](#progress-tag)

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

<img src="workplace.jpg" alt="Workplace" usemap="#work-map" width="400" height="379">

<map name="work-map">
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

### Base tag

defines a base url which every src or href will inherit from

```html
<head>
  <base href="https://www.w3schools.com/" target="_blank">
</head>

<body>
<img src="images/stickman.gif" width="24" height="39" alt="Stickman">
<a href="tags/tag_base.asp">HTML base Tag</a>
</body>
```

### Cite tag

used to create a citation

```html
<p><cite>The Scream</cite> by Edward Munch. Painted in 1893.</p>
```

### Abbr tag

Abbreviations, renders the abbreviation and display tooltip with it's meaning

```html
The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.
```

### Address Tag

Used specifically for address, however it might have some appearance which might not be appealing in some browsers

```html
<address>
Written by <a href="mailto:webmaster@example.com">Jon Doe</a>.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
```

### kbd Tag

Used to display keyboard keys, doesn't have appearance but it might help styling

```html
<p>Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy text (Windows).</p>

<p>Press <kbd>Cmd</kbd> + <kbd>C</kbd> to copy text (Mac OS).</p>
```

### Samp Tag

Define some text as sample output from a computer program in a document:

```html
<p>Message from my computer:</p>

<p><samp>File not found.<br>Press F1 to continue</samp></p>
```

### q Tag

Simple quote marks, perhaps good for styling something

```html
<p>WWF's goal is to:
<q>Build a future where people live in harmony with nature.</q>
We hope they succeed.</p>
```

### params Tag

Set the "autoplay" parameter to "true", so the sound will start playing as soon as the page loads:

```html
<object data="horse.wav">
  <param name="autoplay" value="true">
</object> 

```

### Meter Tag

Used to represent gauges

```html
<label for="disk_c">Disk usage C:</label>
<meter id="disk_c" value="2" min="0" max="10">2 out of 10</meter><br>

<label for="disk_d">Disk usage D:</label>
<meter id="disk_d" value="0.6">60%</meter>
```

### Progress Tag

Used to progress or loading

```html
<label for="file">Downloading progress:</label>
<progress id="file" value="32" max="100"> 32% </progress>
```
