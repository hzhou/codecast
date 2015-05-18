I got my inspiration from these two pages:

    * http://codepen.io/jakealbaugh/full/PwLXXP/
    * http://strml.net/

Both pages are very cool -- I never realized nowadays browser are so capable (and fun). However, both pages are essentially just deomonstrating some CSS techniques. I am not a great front end developer and so nothing I can show in that deartment. But the coolness got me thinking as a programmer -- maybe we can develop a the browser as a virtual machine then run  live code demo through it or even run prenstentation through it. This project is the test of this idea.

### Basic flow

#### js_codecast.def

Javascript to build a virtual machine, reads in from a JSON action list, and perform content injection, css animation or what ever javascript is capable of.

#### code_cast.def

An offline Perl engine transcribe presentation text/code into JSON action list, perform markup like translation as well syntax highlighting. The output is a static webpage that runs the presentation.

### To Run

    $ mydef_make
    $ make
    $ perl out/live.pl
        [output live.html]
