# spine-png-exporter

Because [Nikke-DB Visualiser](https://github.com/Nikke-db/nikke-db-vue)'s WebM exporter sucks. Any lag that occurs is recorded into the export, and the end is often cut off.

This instead exports the Spine animation as a ZIP of PNGs. It doesn't record any lag and doesn't skip any frames.  
The exported frames can then be animated using Ezgif [as a GIF](https://ezgif.com/maker) or [as a WebP](https://ezgif.com/webp-maker). (Discord supports WebP btw.)

See [the original repo](https://github.com/Nikke-db/spine-web-player-template) for more info.

# Credits

Spine web player made by esoteric software, learn more about it at http://esotericsoftware.com/spine-player.  
Template made by Koshirei https://github.com/Koshirei and used for the Nikke-db website https://github.com/Nikke-db/Nikke-db.github.io.

The libraries [JSZip](https://github.com/Stuk/jszip) and [FileSaver](https://github.com/eligrey/FileSaver.js) have also been added in this fork for exporting ZIP folders.