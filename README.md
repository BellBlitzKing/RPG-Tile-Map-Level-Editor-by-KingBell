<h1 align="center">TilemapEditor</h1>

try it online at https://blurymind.github.io/tilemap-editor/

The online demo is an installable pwa, which has as a goal to demonstrate integration of the editor in other projects.
You can use the pwa as a way of sharing a demo of tilesets and tilemaps you have created!

As an example this url:
https://blurymind.github.io/tilemap-editor/?imgur=SjjsjTm
the imgur=ID at the end tells tilemap-editor to use as tilesets an imgur uploads gallery with the same id in its url:
https://imgur.com/a/SjjsjTm

In the same way you can also store your tilemaps in github gists!
as an example this url:
https://blurymind.github.io/tilemap-editor/?gist=e81f38830a67444c54adfb4f69c6538d
the gist=ID at the end tells tilemap-editor to load the timap data (which also has the tilesets in it) from a gist at github with the same id in its url:
https://gist.github.com/blurymind/e81f38830a67444c54adfb4f69c6538d

To store a tilemap in a gist, export it with file>downloadjson file, open the file and copy its contents, then paste them into a gist. Or alternatively just upload the file to a gist. Finally copy the gist's ID and then append the gist=yourGistId to the tilemap-editor url.

I plan to make this a simpler process in the future if there is enough interest.

---

<h3 align="center">
  <a href="#information_source-about">About</a>&nbsp;|
  <a href="#information_source-features">Features</a>&nbsp;|
  <a href="#interrobang-reason">Reason</a>&nbsp;|
  <a href="#link-getting-started">Getting started</a>&nbsp;|
  <a href="#link-api">Api use</a>&nbsp;|
  <a href="#link-how-to-contribute">How to Contribute</a>&nbsp;|
</h3>

---

## :space_invader: About

TileMap Editor is a fat-free tile map editor with zero dependencies and a scalable, mobile-friendly interface.

## :gift: features

- Multiple tileset support
- Multiple tilemap support
- Multi-tile selection and painting (drag select multiple tiles from the tileset)
- Tileset meta-data editing (Assign tags to tiles, automatic assignment of symbols to tiles)
- Animated tiles support
- Flipped tiles support
- Tilemap layers (as many as you like) with opacity and visibility
- Export boilerplate code for kaboomjs https://kaboomjs.com/ (wip)
- Customizable export data
- Resizable tilemap - non destructive too
- Paint tool, Pan tool, eraser tool, Bucket fill tool, Random tile tool, Pick tile tool
- Undo/redo system
- Responsive interface (scales down to portrait mode on mobile)
- Tiny footprint 
- Easy I/O api that lets you transform and save data with ease
