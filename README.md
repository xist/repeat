# repeat

![](https://badgen.net/npm/v/repeat?color=grey)
![](https://badgen.net/npm/dw/repeat)
![](https://badgen.net/packagephobia/install/repeat?color=055ff3)
![](https://badgen.net/badge/code%20style/prettier/ff51bc)

> **Looking for Repeat.js?:**  
> This new take on repeat will soon be isomorphic in addition to supporting the same scheduling features as before. However if you are dependent on the old version you can get it here: `npm install repeat@0.0.6`

### install

`npm install repeat`

### example

The following loop will run all tasks once, in place.

```javascript
repeat()
  .do(() => console.log("how are you?"))
  .do(() => console.log("good"))
  .once();
```

### methods

These methods are available.

| Method            | Description               |
| :---------------- | :------------------------ |
| `once(?async)`    | Run the tasks once.       |
| `forever(?async)` | Run the tasks infinitely. |
| `cancel()`        | Stop execution of tasks.  |

### contribute

Pull requests are encouraged.
