# macbookpro-xorg.conf.d

## Synaptic Workaround

https://bugs.launchpad.net/ubuntu/+source/xserver-xorg-input-synaptics/+bug/1026046

Switching our the xserver-input-synaptics (1.7.x) for xserver-input-mtrack 0.3.0 led to the following,

### Super annoying problem #1

Thumb detection on lower pad - increase BottomEdge

(now a feature of synaptics 1.8.x)

### Super annoying problem #2

Seemingly random right-click trigger while doing something else, like multi-line selection - reconfigure ClickFinger1

More tweaks may follow.

## Don't Zap - No

http://osdir.com/ml/fedora-devel-list/2009-03/msg02131.html

Re-enables the removed functionality permitting those "in the know" how to kill their xserver whenever they wanted to with Ctrl-Alt-Backspace.

