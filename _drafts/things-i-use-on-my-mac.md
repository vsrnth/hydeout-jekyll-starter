---
layout: post
title: Things I use on my mac
excerpt: ''
date: 
last_modified_at: 
categories: []
tags: []
comments: false

---
\--- title: Setting up my mac date: "2019-10-11T23:46:37.121Z" layout: post draft: false path: "/posts/setting-up-my-mac/" category: "Development" tags:   - "OS X"   - "Development"   - "Setup" description: "Apps and command-line utilities I use on a daily basis in my workflow." --- 


\### Below are the utilities which are a part of my daily workflow.

\***

\### Apps
\- \[iTerm2 Config\](#iterm2)
\- \[Fantastical\](#fantastical)
\- \[Vanilla\](#vanilla)
\- \[Amphetamine\](#amphetamine)
\- \[Hocus Focus\](#hocus-focus)

\### \[Command-line utilities\](#command-line-utilities)
\- \[Homebrew\](#homebrew)
\- \[Ripgrep\](#ripgrep)
\- \[Tig\](#tig)
\- \[Icdiff\](#icdiff)


\#### <a name='iterm2'></a> iTerm2
\- OS X's terminal is fine, but personally find it lacking.
\- OS X's stock terminal not maximizing is one of my biggest pet peeves.
\- So that's where \[iTerm2\]([https://www.iterm2.com/](https://www.iterm2.com/ "https://www.iterm2.com/"))  comes into the picture.

Couple of tricks to make iTerm2 even better.

To jump between words and start/end of lines in iTerm2 follow these steps:

iTerm2 -> Preferences (⌘ + ,)
Open the “Keys” tab

Add the following Global Shortcut Keys

\`\`\`
Move cursor one word left
Keyboard Combination: \`⌥ + ←\`
Action: Send Hex Code
Code: 0x1b 0x62

Move cursor one word right
Keyboard Combination: \`⌥ + →\`
Action: Send Hex Code
Code: \`0x1b 0x66\`

Move cursor to beginning of line
Keyboard Combination: ⌘ + ←
Action: Send Hex Code
Code: \`0x01\`

Move cursor to end of line
Keyboard Combination: ⌘ + →
Action: Send Hex Code
Code: \`0x05\`

Delete word
Keyboard Combination: ⌥ + ←Delete
Action: Send Hex Code
Code: 0x1b 0x08

Delete line
Keyboard Combination: ⌘ + ←Delete
Action: Send Hex Code
Code: 0x15

Undo
Keyboard Combination: ⌘ + z
Action: Send Hex Code
Code: 0x1f
\`\`\`
Don't forget to remove the previous bindings:

Open the “Profiles” tab
Click the sub-tab ”Keys”
Remove the mappings for key combinations ⌥ + ← and ⌥ + →

\#### <a name=fantastical></a> Fantastical
\- \[Fantastical\]([https://flexibits.com/fantastical](https://flexibits.com/fantastical "https://flexibits.com/fantastical")) It's a third party calendar manager which is excellent at it's job.
\- I could go into detail as to what's good about it, but since it has 21 day trial take it for a whirl.


\#### <a name=vanilla></a> Vanilla
\- \[Vaniila\]([https://matthewpalmer.net/vanilla/](https://matthewpalmer.net/vanilla/ "https://matthewpalmer.net/vanilla/")) hides stuff in your menu bar.
\- It was so good I bought it 😊.

\#### <a name='amphetamine'/></a> Amphetamine
\- To prevent the machine from dozing off
\- It can be configured in a multitude of ways so check out the preferences to tweak it to your liking.

\#### <a name='hocus-focus'></a>Hocus Focus
\- This app hides any inactive windows.
\- [http://hocusfoc.us/](http://hocusfoc.us/ "http://hocusfoc.us/")


\### <a name='command-line-utilities'></a> Command-line Utilities

\#### <a name='homebrew'></a> Homebrew
\- You probably have this installed on your macbook, if not please go ahead and install it.
\- Homebrew is more or less essential to installing any utility on your mac and it does so in a jiffy.
  - You could install stuff without homebrew, but why would you want to do so when homebrew does it for you easily.
\- [https://brew.sh/](https://brew.sh/ "https://brew.sh/")

\#### <a name='ripgrep'></a> RipGrep
\- Lightning fast search, according to it's author faster than anything you've used.
  - I've not tested this but the author has benchmarks in the git repo.
\- Link: [https://github.com/BurntSushi/ripgrep](https://github.com/BurntSushi/ripgrep "https://github.com/BurntSushi/ripgrep")

\#### <a name='autojump'></a> Autojump
\- Absolutely adore this nifty utiility.
\- [https://github.com/wting/autojump](https://github.com/wting/autojump "https://github.com/wting/autojump")


\#### <a name='tig'></a> Tig
\- This is an excellent visual command line git utility.
\- You can pretty much do everything you want and more using this.
\- [https://github.com/jonas/tig](https://github.com/jonas/tig "https://github.com/jonas/tig")

\#### <a name='icdiff'></a> Icdiff
\- Gives a whole new meaning to the command \`git diff\`
\- [https://github.com/jeffkaufman/icdiff](https://github.com/jeffkaufman/icdiff "https://github.com/jeffkaufman/icdiff")



\---
This post is a work in progress, I'll keep adding stuff as and when I see something shiny.