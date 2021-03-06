#pidgin-im-gnome-shell-extension

Make Pidgin IM conversations appear in the Gnome Shell message tray

###Issues
- Messages appear unseen in Pidgin after expanding notification in message tray. Don't know how to set unseen state in Pidgin
- No notifications on locked screen even if notification settings allow it. Because Gnome Shell disables all extensions on screen lock
- No notifications for conversation after right-click on conversation in the message tray. Left-click on conversation icon in the message tray to fix.

###Features
- Supports Chats and IMs for now (i.e. no file transfers or attentions)
- User icons
- User status as secondary icon
- Sends typing state
- Shows unread messages count
- Tries to restore unread messages count after screen lock/unlock
- Search provider for buddys from connected accounts (can be disabled from extension preferences)

Supported Gnome Shell 3.10, 3.12, 3.14, 3.16, 3.18, 3.20

#Installation
###Manual
    mkdir -p $HOME/.local/share/gnome-shell/extensions
    cd $HOME/.local/share/gnome-shell/extensions
    git clone git://github.com/muffinmad/pidgin-im-gnome-shell-extension.git pidgin@muffinmad
Restart GNOME Shell and enable "Pidgin IM integration" extension
###Arch Linux
https://aur.archlinux.org/packages/pidgin-im-gnome-shell-extension/
###GNOME Shell Extensions
https://extensions.gnome.org/extension/782/pidgin-im-integration/
