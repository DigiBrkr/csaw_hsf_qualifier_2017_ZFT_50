# ZFT
50 Points
> What kind of megalomaniac writes a manifesto? What is he even trying to say?
> Note: flag is not in flag{} format

## Solving it

We are given this: ![ZFT.png](ZFT.png)  At first look it looks like total garbage.
Just for fun the first I tried was a [google reverse image search](https://support.google.com/websearch/answer/1325808?hl=en) and that led to belive this was a [fringe glyph](http://fringe.wikia.com/wiki/Glyphs) it had something to do with a J.J Abrams tv show. After poing around on goolge fow a few minutes I found this decoding chart: ![Decryption Key.jpg](Decryption Key.jpg)
Decding the image one character at a time gave me this:
`GUROBLZHFGYVIR`
This may also look like total giberish but, it's not. Now we have to take `GUROBLZHFGYVIR` and run it though a [rot13 decoder](GUROBLZHFGYVIR) and that turns `GUROBLZHFGYVIR` into `THEBOYMUSTLIVE`, however, we are still not done you have to make `THEBOYMUSTLIVE` lowercase and put it in flag syntax.  And that gives us out flag: `flag{the_boy_must_live}`
