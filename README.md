### 📎 It looks like you're trying to look at my Github profile

I'm moving to [Source Hut](https://git.sr.ht/~shabbyrobe), but it'll take me a
while. Nearly everything interesting's there now.

Some of my favourite things I made that live on my SourceHut:

- **[bmp2cpp](https://git.sr.ht/~shabbyrobe/bmp2cpp)**: Convert an image into source code representing the bitmap and palette. I.e. the source code actually _looks_ like the image. Mostly silly fun, but extremely useful for very specific tasks.
- **[musefuse](https://git.sr.ht/~shabbyrobe/musefuse)**: Point it at a messy folder full of audio files, get a read-only, mountable FUSE filesystem organised by tag values. Surprisingly useful.
- **[termimg](https://git.sr.ht/~shabbyrobe/termimg)**: Go port of Stefan Haustein's TerminalImageViewer algorithm, with significant performance improvements. This is more than your standard unicode half-block renderer, it wrings a bit more resolution out of your terminal than you might expect. Not as much as [sixel](https://www.arewesixelyet.com/) though.
- **[cmdy](https://git.sr.ht/~shabbyrobe/cmdy)**: Tasteful, flexible Go library for implementing CLI programs. There are more popular tools out there, but I miss `cmdy` terribly every time I'm forced to use cobra.
- **[wu2quant](https://git.sr.ht/~shabbyrobe/wu2quant)**: Performant, garbage-collector friendly Go port of Xiaolin Wu's Color Quantizer. Want to make a paletted version of your true colour image? Probably not? Well, just in case you do, this one works well.
- **[sortnet](https://git.sr.ht/~shabbyrobe/sortnet)**: Code generator for sorting networks in Go. These are optimised to sort small groups of values faster than anything else around, takes 15-35% of the time the stdlib takes up to about 16 elements.
- **[bumpy](https://git.sr.ht/~shabbyrobe/bumpy)**: Experiments with BMP, the most underrated image format in the world. Seriously.
