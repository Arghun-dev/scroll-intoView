# scroll-intoView

to scroll into specific point in our browser:

I want to scroll to comments section when I click a specific element.

```js
<span onCLick={() => document.querySelector('#comments').scrollIntoView({ behavior: 'smooth' })}>go to comments</span>


<div id='comments'>
  <Comments />
</div>
```
