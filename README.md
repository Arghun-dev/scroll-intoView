# scroll-intoView

`https://developer.mozilla.org/en-US/docs/Web/API/Element/scrollIntoView`

to scroll into specific point in our browser:

I want to scroll to comments section when I click a specific element.

```js
<span onCLick={() => document.querySelector('#comments').scrollIntoView({ behavior: 'smooth' })}>go to comments</span>


<div id='comments'>
  <Comments />
</div>
```

### Examples 

```js
var element = document.getElementById("box");

element.scrollIntoView();
element.scrollIntoView(false);
element.scrollIntoView({block: "end"});
element.scrollIntoView({behavior: "smooth", block: "end", inline: "nearest"});
```
