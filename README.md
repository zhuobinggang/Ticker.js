## How to use

#### Init a ticker

Require the lib or just include it in the html

`var t = new Tikcer(1000)`

Set the interval to 1000, means to tick per second

#### Add a listener

```js
const greet = () => {
  console.log('Hello!');
}
t.add(greet);
```

Then start it

#### Start ticker

```js
t.start();
```

You can pause it

#### Pause ticker

```js
t.pause();
```

Or clear all listeners then stop it

#### Stop ticker

```js
t.stop()
```

Finally, you can remove a listener

#### Remove listener

```js
t.remove(greet)
```

