# Oodler

This is a barely tested bookmarklet that could very well break things, but it replaces all the vowels in the page you’re on with “oodle”.

## Usage

Drag the following link to your bookmarks bar. Click it.

<a href="javascript:void%20function(){for(var%20e=document.createTreeWalker(document.body,NodeFilter.SHOW_TEXT);e.nextNode();)e.currentNode.nodeValue=e.currentNode.nodeValue.replace(/[aeiou]/gi,%22oodle%22)}();">Oodler</a>
