<img width="1329" height="782" alt="org example GtkImageViewer-779" src="https://github.com/user-attachments/assets/f73342f7-8b12-49e3-92ec-732855a76ea7" />

# swwv

Hey there! 👋

Welcome to **swwv**, a simple and chill GTK4 image viewer that also hooks up with `swww` to set your wallpapers on Wayfire.  

If you just want to quickly peek at some images and maybe set one as your background without fuss, this is your buddy.

---

## What’s this all about?

I got tired of juggling between apps just to view images and change wallpapers on Wayfire using `swww`. So I slapped together a tiny GTK4 viewer that:

- Opens your images smoothly  
- Lets you right-click to set that image as your wallpaper via `swww`  
- Has a simple header menu with next/previous and wallpaper options  
- Handles PNG, JPEG, and whatever common formats you throw at it  

No fluff. No crazy features. Just easy.

---

## How to use it

Just run it with one or more image paths:

`swwv mypic.png another.jpg`

You can flick through images with the menu or right-click on the image to set it as your wallpaper instantly.

---

## Handy extra

If you want, you can copy an image to a specific path when launching:

`swwv mypic.png --copy-to ~/.config/waypanel/fav.jpg`

This copies `mypic.png` to your `fav.jpg` and then opens the viewer. Great for quick wallpaper changes.

---

## Installation

If you’re on Arch, I got a PKGBUILD for you, just clone the repo and build it:

`git clone https://github.com/killown/swwwv.git`  
`cd swwwv`  
`makepkg -si`

---

## License

This project is licensed under the MIT License, check it out [here](https://github.com/killown/swwwv/blob/main/LICENSE).

---

## What’s next?

Honestly, I’m happy with the basics now. But if you wanna pitch in with features or fixes, open an issue or pull request, I’m all ears.

---

Thanks for checking out swwv. Hopefully it makes your Wayfire wallpaper game a little easier!

Cheers,  
The swwv guy


