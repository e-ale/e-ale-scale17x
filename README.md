# SCaLE17x

Checkout the bottom of this README for any packages you may need to install to build this.

Generally you can try these out with:

* git clone https://github.com/e-ale/e-ale-common.git
* git clone https://github.com/e-ale/e-ale-scale17x.git
* cd e-ale-scale17x
* make slides
* evince e-ale-scale17x-SLIDES.pdf

However to make your own set of slides do the following:

* git clone https://github.com/e-ale/e-ale-common.git
* git clone https://github.com/e-ale/e-ale-scale17x.git
* mv e-ale-scale17x my-talk
* cd my-talk
* mv e-ale-scale17x.tex my-talk.tex
* sed -i 's/e-ale-scale17x/my-talk/g' my-talk.tex
* make veryclean slides
* evince my-talk-SLIDES.pdf

There is a document <a href="https://cm.c-ale.org/Docs/C-ALE_talkware.pdf">here</a>
which explains how to use the latex language used here.

You will want to replace the example chapters in this slide
deck with your own material.

You will also need some packages installed to be able to
build your slide deck.

On CentOS, Fedora or RHEL

* sudo dnf install make texlive

On Debian or Ubuntu:

* sudo apt install make texlive

On openSUSE

* sudo zypper install make texlive

