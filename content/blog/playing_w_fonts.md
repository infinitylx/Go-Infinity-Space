+++
title = "Playing with Fonts and Selfhosting"
tags = ["alpha-century"]
author = "Vladyslav Merezhko"
date = 2019-05-03
summary = "."
+++

Finally I got some time to make my space 100% self hosted. Last thing to move in was custom fonts. But as it turns out this is no more difficult then hosting css or js files. Every free font is already have prepared css to use. 

You can ask why keep everything in one place? Because if someone hack thirdparty cdn or master repo I will don't give a fuck about it. The only place to watch for is my hosting. That way it's more secure. 

And by entering my space no third party requests are made. So no g\*\*\*\*\*\* or f\*\*\*b\*\*\* are watching you.

In case of apocalypse my space will go on ;-)

I choose [Inter][inter], as main font and [Fira Code][fcode], as monospace font, mostly for code.

For different code highlight - [highlight.js][hjs].

Here is a few useful things I found during this update:

* [Fira Code][fcode] - is fantastic monospace font with legatures for code reading.
* [Inter][inter] - is awesome font which I start to use in my space. "Inter is a typeface carefully crafted & designed for computer screens."
* [Here][here] is a list carefully gathered by people for the people on github.
* And one more thing: "[Nerd Fonts][nfonts] is a project that patches developer targeted fonts with a high number of glyphs (icons). Specifically to add a high number of extra glyphs from popular ‘iconic fonts’ such as Font Awesome, Devicons, Octicons, and others."

[fcode]: https://github.com/tonsky/FiraCode
[inter]: https://rsms.me/inter/
[here]: https://github.com/chrissimpkins/codeface
[nfonts]: https://nerdfonts.com
[hjs]: https://highlightjs.org