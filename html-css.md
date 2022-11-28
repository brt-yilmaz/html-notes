# From MDN

The `<head>` element. This element acts as a container for everything you want to include on the HTML page, that isn't the content the page will show to viewers.  

The `<title>` element. This sets the title of the page, which is the title that appears in the browser tab the page is loaded in.  

To write an HTML comment, wrap it in the special markers `<!-- and -->` For example:  

Many `<meta>` elements include `name` and `content` attributes:

```html
<meta name="author" content="Chris Mills" />
<meta
  name="description"
  content="The MDN Web Docs Learning Area aims to provide
complete beginners to the Web with all they need to know to get
started with developing web sites and applications." />
```

A favicon can be added to your page by:

`<link rel="icon" href="favicon.ico" type="image/x-icon" />`  

Applying CSS and JavaScript to HTML

<link rel="stylesheet" href="my-css-file.css" />

The `<script>` element should also go into the head, and should include a src attribute containing the path to the JavaScript you want to load, and `defer`, which basically instructs the browser to load the JavaScript after the page has finished parsing the HTML.  

`<script src="my-js-file.js" defer></script>`  

You can also set subsections of your document to be recognized as different languages. For example, we could set our Japanese language section to be recognized as Japanese, like so:

`<p>Japanese example: <span lang="ja">ご飯が熱い。</span>.</p>`  

In HTML we use the `<em>` (emphasis) element to mark up such instances. Browsers style this as italic by default, but you shouldn't use this tag purely to get italic styling. To do that, you'd use a `<span>` element and some CSS, or perhaps an `<i>` element (see below).  

`<p>I am <em>glad</em> you weren't <em>late</em>.</p>`  

In HTML we use the `<strong>` (strong importance) element to mark up such instances

```html
<p>This liquid is <strong>highly toxic</strong>.</p>

<p>I am counting on you. <strong>Do not</strong> be late!</p>
```

Here's the best rule you can remember: It's only appropriate to use `<b>`, `<i>`, or `<u>` to convey a meaning traditionally conveyed with bold, italics, or underline when there isn't a more suitable element; and there usually is. Consider whether `<strong>`, `<em>`, `<mark>`, or `<span>` might be more appropriate.  

`<i>` is used to convey a meaning traditionally conveyed by italic: foreign words, taxonomic designation, technical terms, a thought…

`<b>` is used to convey a meaning traditionally conveyed by bold: keywords, product names, lead sentence…

`<u>` is used to convey a meaning traditionally conveyed by underline: proper name, misspelling…


