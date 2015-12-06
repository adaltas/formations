# Adaltas' Big Data formations

Every presentation uses either [reveal.js](https://github.com/hakimel/reveal.js/) or [impress.js](https://github.com/impress/impress.js)

## Export presentations to PDF

Use [decktape](https://github.com/astefanutti/decktape)

```
git clone --depth 1 https://github.com/astefanutti/decktape.git
cd decktape
curl -L http://astefanutti.github.io/decktape/downloads/phantomjs-[platform] -o bin/phantomjs
chmod +x bin/phantomjs
./bin/phantomjs decktape.js generic --keycode=Space file://pth/to/prez.html /path/to/dest.pdf
```