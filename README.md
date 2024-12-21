# Layout switcher

Allows windows to switch layouts by pressing left and right shifts. It could sound wild. But this keybinding won't conflict with any other possible keybinding; it's very comfortable just using 2 pinkies⚡ (no need to move your hand by far). The only downside is this can't be performed by one hand ☹️.

## Why?

I could not find any way to do it with internal or external windows tools.

## How?

Desktop app that does not display window. Running in the background, capturing all key presses. When both LShift and RShift are pressed, a CHANGELAYOUT event is sent. In code, present some hacks 🧐.

This is a personal project, thus it contains some hardcoded stuff 😵, nor installator 💿, nor prebuilt executable 📄.
