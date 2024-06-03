Running multiple graphical user interfaces (GUIs) on Ubuntu allows you to switch between different desktop environments (DEs) or window managers (WMs) on the same system. This can be useful if you want to try out different interfaces or use different environments for different tasks. Here's how you can install and switch between multiple GUIs on Ubuntu:

## 1: Install Additional Desktop Environments
> ### GNOME (Default on Ubuntu)
```
sudo apt install gnome
```

> ### KDE Plasma
```
sudo apt install kde-plasma-desktop
```

> ### XFCE
```
sudo apt install xubuntu-desktop
```

> ### LXDE
```
sudo apt install lubuntu-desktop
```
> ### MATE
```
sudo apt install ubuntu-mate-desktop
```

> ### Cinnamon
```
sudo apt install cinnamon-desktop-environment
```

## 2: Select Desktop Environment at Login
After installing additional desktop environments, you can select which one to use at the login screen:

> 1-Log out of your current session.
> 2-At the login screen, click on the user name.
> 3-Before entering the password, look for a gear icon or a session menu. This is usually located near the password field or the bottom right corner of the screen.
> 4-Click the gear icon or session menu and select the desktop environment you want to use.
> 5-Enter your password and log in.

## 3: Switch Desktop Environments
> [!NOTE]
> To switch desktop environments, simply log out and repeat the steps above to select a different environment.

## 4: Remove a Desktop Environment (if needed)
> [!NOTE]
> If you decide you no longer need a particular desktop environment, you can remove it. For example, to remove KDE Plasma:
```
sudo apt remove kde-plasma-desktop
```
```
sudo apt autoremove
```


