# finnegansways
NaNoGenMo2015 entry

My first NaNoGenMo entry, a Perl script now called `finnegansways`, was initially a mere proof of concept. It only had the `--vico` option below. I've since added a second command-line option, `--poetry`.

People who've read, or even started, the Wake know that the last sentence of the book is broken in half,
and wraps around to become the first sentence, beginning with the word "riverrun".
The entire book is an endless cycle.
Joyce based it partly on the theories of history developed by the 
18th-century Italian philosopher Giambattista Vico.

The `--vico` option takes as input a slightly modified version of the Wake 
called `fwin.txt`. (The modification is that the last two words of the original book are inserted 
at the beginning, before "riverrun", where they belong.) Then the script picks a random line of the 
etext file, and reads until the end. It continues reading from the first line of the etext,
up until but not including the randomly-selected line. It then dumps this rotated version of the 
text to a new file called `fwout.txt`.

The `--poetry` option, based on an algorithm by Robert Amos, as implemented in a script by Charles Cave (which I use as a preprocessor), breaks the lines of the book in poetically appropriate places. That is, it makes the Wake look like poetry even more than it already does.

Of course, you can combine the two options for Wakean poetry in a Viconian cycle, or omit them both for something approximating the original text. These are the four "ways" (at present) of `finnegansways`.

Further fun: start reading from the first line of the "new edition" you generate
and try to suss out where in the plot/cycle of the Wake they are -- how does the Wake feel different,
starting from a new point in the cycle? Also, search for the word "riverrun"
and regard how the end and beginning of the original book join seamlessly into what is "just another"
page in the new edition.

The tenth anniversary meeting of my _Finnegans Wake_ reading group, Allforabit Funferall, occurred the 
day before the NaNoGenMo 2015 deadline. I generated random versions (with the Vico option) 
of the Wake for all eight of us attending.
Those editions are included in this repo.
