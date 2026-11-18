# Digital Photobooth

Give your favorite moments a date, a name, and a place on your wall. This free online photobooth lets you turn snapshots or uploads into custom photo strips. Pick a filter and layout, add your own date and event name, then save a PNG to share or a PDF to print.

[Open the live photobooth](https://suvan4001.github.io/digital-photobooth/digital%20photobooth.html)

## Run locally

From the folder containing `digital photobooth.html`, start a local server with Python 3:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Open [the photobooth](http://localhost:8000/digital%20photobooth.html) and allow camera access when prompted. After taking your photos, use **Save PNG** or **Save PDF** to download your strip.

The booth runs in the browser. Google Fonts supplies the typefaces, and PDF export uses jsPDF from cdnjs, so keep an internet connection for those features.
