# Introducing Muon

Muon, the *Mu*tt theme for Prot*on*—it doesn't get smaller than this.

# What is it?

This custom CSS strips out all of the mouse-driven UI from Proton Mail, making it similar to the command-line email client [Mutt](http://www.mutt.org/).  This means that you navigate it (almost) entirely though keyboard shortcuts.  (Press `?` to see a list of ProtonMail's keyboard commands.)

# "Installation" instructions

Copy the CSS from `muon.css` into the `Custom Theme` box at [mail.protonmail.com/appearance](https://mail.protonmail.com/appearance).

# FAQ

### Wait, really?

Yes

### Should I actually use this?

Probably not.  You have to be a special kind of crazy to want to turn a perfectly good webmail client into an imitation of a CLI app.  If nothing else, you should probably just set up the real mutt and use ProtonMail's IMAP bridge to use the real thing if that's your jam.

### Ok, but do *you* actually use it?

Yep, every day—I'm that special kind of crazy!

### If I *do* use it, how does it work?

Mostly, you just use the ProtonMail's keyboard commands.  As I mentioned up top, press `?` to see a list of the keyboard commands.  Ironically enough, the list of keyboard commands *itself* doesn't support keyboard navigation that well, but you can `<TAB>` though the various options.   That lets you navigate to your inbox or other built-in ProtonMail folders (Spam, Sent, etc.).

Two other commands to remember: `<SHIFT-space>` opens the command pallet, which lets you do a few more things with your keyboard.  And `/` jumps you to the search bar, which will prove useful for more than just searching for emails.

### Should I know anything else about keyboard navigation other than pressing `?`?

Well, you can jump to a specific folder by searching for `in:$FOLDER_NAME`.  For example, I jump to my `promo` folder by pressing `/` and then searching `in:promo`.  No, you can't do `in:p*`.  And no, `in:p<TAB>` doesn't autocomplete.  Yes, I agree it should.  I [opened an issue](https://github.com/ProtonMail/WebClient/issues/144).  Until that's resolved, I recommend short folder names.

### Wait, I just noticed something—you turned off the button for settings!  How do I get to settings?  I can't even turn this blasted thing off!

Of course I turned it off—it was a button, after all!  And what good would something with vim-inspired keybindings be if it weren't at least a *little* hard to quit? 

Fortunatly, ProtonMail follows a sane URL schme for their app, so you can get to any of the settings pages by going to that page directly.  Here's a list of all the urls you might want:

 * [mail.protonmail.com/inbox](https://mail.protonmail.com/inbox)
 * [mail.protonmail.com/contacts](https://mail.protonmail.com/contacts)
 * [mail.protonmail.com/dashboard ](https://mail.protonmail.com/dashboard )
 * [mail.protonmail.com/account](https://mail.protonmail.com/account)
 * [mail.protonmail.com/labels](https://mail.protonmail.com/labels)
 * [mail.protonmail.com/filters](https://mail.protonmail.com/filters)
 * [mail.protonmail.com/autoresponder](https://mail.protonmail.com/autoresponder)
 * [mail.protonmail.com/security](https://mail.protonmail.com/security)
 * [mail.protonmail.com/appearance](https://mail.protonmail.com/appearance)
 * [mail.protonmail.com/members](https://mail.protonmail.com/members)
 * [mail.protonmail.com/domains](https://mail.protonmail.com/domains)
 * [mail.protonmail.com/bridge](https://mail.protonmail.com/bridge)
 * [mail.protonmail.com/pmme](https://mail.protonmail.com/pmme)
 * [mail.protonmail.com/payments](https://mail.protonmail.com/payments)
 * [mail.protonmail.com/keys](https://mail.protonmail.com/keys)
 * [mail.protonmail.com/vpn](https://mail.protonmail.com/vpn)

Specifically, if you want to turn it off, you'll want the `mail.protonmail.com/appearance` URL.   (No promisses that you can use the settings pages without a mouse, though, saddly enough).

### Ok, sounds like I can do a lot.  Is there anything I *can't* do without a mouse?

You can't delete messages from the Trash or empty the Trash (though they're auto-deleted on their own).  You also can't add a custom filter based on an existing email message, though I left the button alone for that so you *can* still get out your mouse like a caveman if you need to.

### Any other bugs I should know about?

This isn't *exctly* a bug with this theme, but you should know that opening a new message results in a new draft being created—even if you close the message without adding any text.  This can clutter up your Drafts folder, especially because keyboard navigation makes it easier to open a new message.  Again, I've [opened an issue](https://github.com/ProtonMail/WebClient/issues/142).

### These questions weren't actually asked frequently, were they?

Nope!  But, then again, neither are the questions in most FAQs.
