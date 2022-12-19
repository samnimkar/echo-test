# echo-test
just to check echo with jenkins 
check by system to say my name is - hostname
and hello world



`use-clipboard-copy` is a **lightweight** (< 1KB) React hook that makes it possible to add a copy-to-clipboard functionality to your React application with very little code! A simple implementation looks like this:

```js
function CopyText() {
  const clipboard = useClipboard();
  return (
    <div>
      <input ref={clipboard.target} />
      <button onClick={clipboard.copy}>Copy</button>
    </div>
  );
}
```
