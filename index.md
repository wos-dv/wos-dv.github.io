% wos-dv's blog

### Tiling window managers suck & the idiocy of window tiling 

What are tiling window managers you ask? Better yet, what is a window manager?

Window managers (WMs) orchestrate the layout of windows you see on
screen.  They pretty much decide where to draw the application on your screen,
how big the window is, some even add decorations to the window such as a close
button etc. (windows users probably can't image how one would close windows
without a close button in the corner). 

Now, a tiling window manager (TWM) usually brings two things to the table but
only one of them is inherent to TWM. The first thing easy setting of shortcuts
do control applications and windows. The second thing is 'window tiling'.
Tiling of windows or 'window tiling' means that application windows are laid
out in such a manner, that they fill the screen without overlapping.  Usually
this involves a policy to divide the screen space between the currently
rendered windows. This policy could be to divide the screen evenly between the
windows or to have one master window that is larger than the rest, while the
rest chill out on a pile with only the top one visible etc.. There are many
such policies and it doesn't really matter since they all suck. And here is the
reason why.

T[WM]{.smallcaps}s suck because they contradict many of their alleged strengths. 

First of these strengths is 'conserving screen space'. Now if someone would try
to convince me, that filling the screen with inactive windows 'conserves screen
space', then I would marvel at that Orwell level of double-think.  Try to do it
reader and come to your senses! It's a great lie!  The whole notion is just
illogical, I don't even think that the first tiling managers were invented for
this purpose of 'conserving screen space'. If they were, then I amazed how
their inventor could come up with the such an anti-solution to the problem
without actually noticing that it. 'Oh, you retard, you can just maximize the
window you are currently working on, so that the others don\'t bother you. You
are clearly a noob that knows nothing.' if such an argument were to occur in
someones head, I hope, that the explosion caused by the void occupying the
inner regions of their skull fails to hurt anybody when the bone finally gives
in to the negative pressure. Because that is the whole point! You are not
tilling when maximized, you are switching it off, because it's in the way. Just
switch it off for good. And be done with it. Real 'conservation of screen
space' happens only when the windows don't tile but instead they overlap.

Just to touch upon workspaces. Those are utter garbage too and you really
shouldn't be using them. If you do a thing, do a thing and don't leave ten
unrelated things open on a different workspace, that just makes doing the thing
harder. You only need workspaces because of tiling idiocy. If you let windows
overlap, workspaces are superfluous.

At this point I need to explain how people actually use a TWM. The core
philosophy is keyboard oriented so that you don't have to use your mouse to
interact with the window or to move the selection of windows (focus) between
different windows. But tiling windows manages to negate these otherwise big
advantages. The reason why this is the case is very simple. Most of the time
the layout that results from multiple windows being tiled is not a grid so it
is impossible to tell where your next command will shift the focus without
actually thinking about how your WM is organizing your windows. So it's
basically impossible without thinking which most of us don't do, we just try
and if it doesn't work out we try again, wasting key-presses. Even dose that
are able to do it fast are just wasting effort. Some might argue that one can
bind keys to switch to specific windows. I just add to that, that such bindings
work even better if you don't tile your windows.

Some window managers are better than others, since they recognize the poison
that is tiling itself. Take for example AwesomeWM(AWM). AWM makes it possible
to switch the focus between windows reliably even when in floating mode
(floating mode is the equivalent of the layout that MS Windows uses, which
means no-tiling). This alone redeems AWM from the tragic anti-pattern of window
tiling. Other TWM should emulate this and drop the T from TWM as it is the
only workflow that is not crippling to the user. Really AWM is not a TWM as the
name reflects it. It can do what a TWM can, but thankfully, it can also
not-tile which is key. I don't know what the future of WMs is going to be, but
I'm convinced more than ever that it's not going to be the tiling of windows.
