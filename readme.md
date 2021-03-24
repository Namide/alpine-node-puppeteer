# Alpine Node Puppeteer

Use Pupeeteer with:

```js
puppeteer.launch({
  headless: true,
  executablePath: '/usr/bin/chromium-browser',
  args: [
    '--no-sandbox',
    '--disable-setuid-sandbox'
  ]
})
```
