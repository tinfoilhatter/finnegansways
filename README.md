# finnegansways
NaNoGenMo2015 entry

My first NaNoGenMo entry is much less ambitious than I proposed in my entry announcement.
Rather than many interactive ways to view James Joyce's massive 1939 work of fiction, _Finnegans Wake_,
I'm only offering one. It may still be of interest, especially to Wakeans, and I hope to extend it later.

People who've read, or even started, the Wake know that the last sentence of the book is broken in half,
and wraps around to become the first sentence, beginning with the word "riverrun".
The entire book is an endless cycle.
Joyce based it partly on the theories of history developed by the 
18th-century Italian philosopher Giambattista Vico.

I wrote a short Perl script called `vico` that takes as input a slightly modified version of the Wake 
called `fwin.txt`. (The modification is that the last two words of the original book are inserted 
at the beginning, before "riverrun", where they belong.) Then the script picks a random line of the 
etext file, and reads until the end. It continues reading from the first line of the etext,
up until but not including the randomly-selected line. It then dumps this rotated version of the 
text to a new file called `fwout.txt`.

Fun things to do, especially for Wakeheads, are to start reading from the first line of the "new edition"
and try to suss out where in the plot/cycle of the Wake they are -- how does the Wake feel different,
starting from a new point in the cycle? A second fun thing to do is search for the word "riverrun"
and regard how the end and beginning of the original book join seamlessly into what is "just another"
page in the new edition.

The tenth anniversary meeting of my _Finnegans Wake_ reading group, Allforabit Funferall, occurred the 
day before the NaNoGenMo 2015 deadline. I generated random versions of the Wake for all eight of us. Those
editions are included in this repo for people who would rather not run the Perl script.

