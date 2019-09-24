# UNIX fortune Archive

*WARNING:* These fortune files are being archived for historical purposes.  Some of the content has always been offensive, and other parts have only become offensive as culture has progressed in recent years.

Collection of [UNIX fortune](https://en.wikipedia.org/wiki/Fortune_(Unix)) wisdom databases amassed back in 2012 to feed content to my Twitter botnet experiment.

(note: my Twitter bots were benign and friendly, created just for fun and NLP research back when I worked at [Klout](https://jaytaylor.com/klout/spotify.html).).

# What is Fortune?

Fortune is a UNIX program which displays a pseudorandom message from a database of quotes.

```bash
$ fortune

Ken Thompson has an automobile which he helped design.  Unlike most
automobiles, it has neither speedometer, nor gas gage, nor any of the
numerous idiot lights which plague the modern driver.  Rather, if the
driver makes any mistake, a giant "?" lights up in the center of the
dashboard.  "The experienced driver", he says, "will usually know
what's wrong."
```

Fortune databases are plaintext files where each quote is delimited by a line containing only a quote.

For example:

```
quote content #1
%
quote content #2
%
quote content #N
%
...
```

It may seem obvious, but it recently occurred to me the origin of the term "fortune" in this context is likely a reference to _fortune cookies_.  UNIX fortune files are des a *NIX neckbeard slant).

# See Also

* [ruanyf/fortunes](https://github.com/ruanyf/fortunes) is an impressively large archive of UNIX fortune quotes files
* [icy/fortune-vn](https://github.com/icy/fortune-vn) is an archive of vietnamese fortune content
* [Distrotech/fortune-mod](https://github.com/Distrotech/fortune-mod) contains fortune-mod 9708, similar to `fortune-mod` released in October 1995
* [fortune.c](https://github.com/eunuchs/unix-archive/blob/master/PDP-11/Trees/2.11BSD/usr/src/games/fortune/fortune.c) for PDP-11

