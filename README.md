# [How do you pronounce `07-1191`?](http://pghpw.org/ppw2010/talk/3029)

Material for my 20-minute talk at the [Pittsburgh Perl Workshop 2010](http://pghpw.org/ppw2010/), given on Saturday, October 9, 2010.

## Abstract

One part of the [TalkBank project at Carnegie Mellon University](http://talkbank.org/) is the parsing of text [transcripts from Supreme Court oral arguments](http://www.supremecourt.gov/oral_arguments/oral_arguments.aspx) and conversion into the CHAT format (http://childes.psy.cmu.edu/manuals/chat.pdf) for linking utterances to the audio of the oral arguments, and further processing and analysis.

Since the CHAT format represents what is spoken, we were faced with the task of converting a variety of written forms such as `07-1191` and `2nd` and `19.2-187` into pronounceable forms such as `oh seven eleven one ninety-one` and `second` and `nineteen point two one eighty-seven`.

This talk will outline the design of the converter and a natural implementation in [Perl](http://www.perl.org/).
