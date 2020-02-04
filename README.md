# Coding Lessons w/Riz


## Useful links
Whilst you're learning how to code in HTML, I strongly recommend the following resources:

### Text editors

There are loads of different text editors to choose from (even Notepad is ok!), but you should strongly consider choosing one of the following (in order):

* Visual Studio Code (VSCode)
  - Download here: https://code.visualstudio.com/
  - I strongly recommend using VSCode! I've used (and still use) all of these text editors, but in my experience VSCode is the best and fastest.
* Atom
  - Download here: https://atom.io/
  - Atom is a great text editor, and functions very similarly to VSCode. Atom will hold your hand less than VSCode, but will still provide you with a good experience.
* Notepad ++
  - Download here: https://notepad-plus-plus.org/downloads/
  - This is more or less Notepad with colours and guidelines.

### Learning resources

Whilst you're learing, check out the following links (but try to stay on target with learning HTML. It's very easy to get side-tracked, and it's important to learn the basics first):

* W3 Schools
  - Link: https://www.w3schools.com/html/
* MDN Web Docs
  - Link: https://developer.mozilla.org/en-US/docs/Web/HTML

## Lesson 1

### A standard website structure is as follows:
```
<!DOCTYPE html>
<html>
<head>
    <title>Document</title>
</head>
<body>
</body>
</html>
```
### 'Big' tags explained:

```<!DOCTYPE html>```
This statement declares that the document type (```DOCTYPE```) is html (Hyper Text Markup Language).

```<html>```
This statement declares that everything within these tags is html code.

```<head>```
This ```<head>``` tag is used to reference further files or call-able references (this will be explored in a further lesson). In the ```<head>``` tag you should expect to see tags such as ```<meta />```, ```<link />``` and ```<script />```.

```<title>```
This tag declares the website or page name that will be displayed in the tab of the user's internet browser (Chrome, Firefox, Safari, etc.).

```<body>```
This tag declares the page/website content that will be displayed in the user's internet browser.

### 'Smaller' tags explained:

```<h1>```
This tag represents a 'Heading 1'. It is important to note that all headings should be used in ascending order with none being missed out. From 'Heading 1' (```<h1>```), to 'Heading 2' (```<h2>```), to 'Heading 3' (```<h3>```), all the way up to 'Heading 6' (```<h6>```). 

```<p>```
This tag represents a 'paragraph'. Though it is labelled as 'paragraph', this can contain as little or as much text as you'd like.

```<li>```
This tag represents a 'list', and can be either 'unordered' (```<ul>```), or ordered (```<ol>```).

It is really important to note that listed content should be 'nested'. Please see the below as examples:

```
    <ul>
      <li>Cats</li>
      <li>Dogs</li>
      <li>Hamsters</li>
    </ul>
    
    <ol>
      <li>Cats</li>
      <li>Dogs</li>
      <li>Hamsters</li>
    </ol>
```
From the above example, you can see that the ```<li>``` content sits inside the ```<ul>``` tags. This is considered to be 'nested'. If you look at the 'standard website structure' displayed previously, you will be able to see that the ```<title>``` tag is nested inside the ```<head>``` tag.
