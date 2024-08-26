# **About EclipsedOS:**


EclipsedOS is a linux distro made to run on low end devices (chrome devices should run this operating system well).

    (If there is a link there are no new releases but if there is a question mark then a new release is being compiled).
    (if there is a question mark in front of a known issue then it has not been confirmed yet).
    (Chromebook support is not guarenteed).

If you want to test the latest version please feel free to download the image file here (Currently EclipsedOS 3.0a1):

http://eclipsedosproject.sytes.net/eclipsedosproject/download/93/?tmstv=1724635796

If you want the latest stable version you can get it here (currently EclipsedOS 2.1):

https://drive.google.com/file/d/1538cb6LGc_beHcSay6I_Bo18AYudkQcC/view

# Known issues:

- .bashrc does not show correct command for installing apps.
- Hidden files are shown by default.

# Changelog

    #EclipsedOS 2.1 -> 3.0a1

    - Updated ".bashrc" (Terminal app).
     - "Install <app>" is now "install-app <app>" to avoid issues with the install comand on linux.
     - "remove <app> is now remove-app <app>"
     - "remove" has been kept as a legacy commands so you can still use it.
    - Updated the path bar of thunar app to match the installer's path bar.
    - Updated kernel to version 6.8.
    - Updated firefox.
    - Updated the panel to have a slight spacing between the Whisker menu icon and the app pinned app icons.
    - Updated wallpaper.

    #EclipsedOS 2.0 -> 2.1
    
    -Updated ".bashrc" (teminal app).
    -Restored the default wallpaper.
    
    #EclipsedOS 2.0b3 -> 2.0
    
    -Updated ".bashrc" (teminal app).
    -Fixed all bugs
    
    #EclipsedOS 2.0b2 -> 2.0b3

    -Updated ".bashrc".
    -cleaned up useless files.

    #EclipsedOS 2.0b1 -> 2.0b2

    -Fixed usb 2.0 poor performance though usb 3.0 is reccomended.
    -Updated installer.
    -Changed Desktop Background.
    -Updated ".bashrc".
    -cleaned up useless files.

    #EclipsedOS 2.0a2 -> 2.0b1
    
    -Fixed Themes and icons in installer.
    -Added .bashrc.

    #EclipsedOS 2.0 prv1 -> 2.0a2

    -Skipped 2.0a1 because why not and also it was buggier.
    -Fixed icons.

    #EclipsedOS 1.2 -> 2.0 prv1
    
    -Now 11GB of storage recommended.
    -Increased iso filesize to 2.04GB due to new base being so bad on storage.
    -The long lived bug of the themes and icons or background missing(from 1.0 alpha 6 -> 1.2) is now fixed just go to settings in case of any problems.
    -Updated base to ubuntu 22.04.
    -Retained firefox deb version(no snap)
    -New desktop background and commands.
    -Updated .bashrc(terminal)
    
    #EclipsedOS 1.2b03 -> EclipsedOS1.2
    
    -re-added community wallpapers.
    -Will probably fix the wallpaper issues in 1.3
    
    #EclipsedOS 3122 -> EclipsedOS 1.2b03
        
    -Updated taskmanager.
    -Updated .bashrc.
    -forgot what else exactly bc thank you to exam season.
    
    #EclipsedOS 1.1 -> EclipsedOS 3122
    
    -Added experimental AMD support
    -Changed the color to orange because of halloween.
    
    #EclipsedOS 1.1b03 -> EclipsedOS 1.1
    
    -Updated some xfce configs.
    -1.1 is now out of beta.
    -Nothing much other than bug fixes.
    -Have a nice day. :)
    
    #EclipsedOS 1.1b02 -> EclipsedOS 1.1b03
    
    -Updated keyboard layout to GB chromebook.
    
    #EclipsedOS 1.1b01 -> EclipsedOS 1.1b02
    
    -Updated the default keyboard layout to english GB.
    -Updated the default screen resolution to 1360 x 768.
    
    #EclipsedOS 1.0 -> EclipsedOS 1.1b01
    
    -Changed the Background locations.
    -Updated the .bashrc file (terminal).
    -All languages now show the slideshow for installation in english.
    -Updated the xfce configs to need slightly less vram.

    #EclipsedOS 1.0 beta rc1 -> EclipsedOS 1.0
    
    -Changed some images on the installer.

    #EclipsedOS 1.0 beta 0.2.1 -> EclipsedOS 1.0 rc1
    
    -Added "cleansys" command to do a sudo apt autoremove(removes unneccessary packages).
    -Added "searchapp <program name>" command to see if a program is available for installation.
    
    #EclipsedOS 1.0 beta 0.2.0 -> EclipsedOS 1.0 beta 0.2.1
    
    -Fixed file manager icon.
    -Updated wallpaper.
    -Made some icons in the applications menu bigger.
    
    #EclipsedOS 1.0 beta 0.1.9 -> EclipsedOS 1.0 beta 0.2.0
    
    -Removed ubuntu software updater.
    -Removed notes.
    -Removed unneeded packages but running a sudo apt autoremove after install is still reccomended.
    
    #EclipsedOS 1.0 beta 0.1.8 -> EclipsedOS 1.0 beta 0.1.9
    
    -Fixed the critical bug to do with the Package manager not working.
    
    #EclipsedOS 1.0 beta 0.1.7 -> EclipsedOS 1.0 beta 0.1.8
    
    -Updated Ubiquity info so that it shows the EclipsedOS info.
    
    #EclipsedOS 1.0 beta 0.1.2 -> EclipsedOS 1.0 beta 0.1.7
    
    -Updated thunar icon(for whatever reason the file manager does not have updated icon despite being the same app).
    -Updated info on ubiquity (installer).
    -It is now reccomended to install without internet to and then connect to internet to not have any extra space taken up.
    -Final install size(offline) is now 4.8GB
    -Unfortunately while upgrading every packages the iso filesize is now 1.52GB
    -Updated grub config files.
    -Updated preseed.
    -Updated all packages hence the larger iso filesize.
    -Updated boot screen on installer.
    -Fixed the boot screen is has the wrong logo on installer.
    -fixed the themes that don't apply correctly on installer when using a legacy bios.
    -Updated Kernel from 5.13 -5.15 and brasewell chromebooks are now fully supported.(?)
    -Added codename Lunar.
    -Updated the Thunar icon.

    #EclipsedOS 1.0 beta 0.1.1 -> EclipsedOS 1.0 beta 0.1.2
    
    -Fixed translucent effects.
    -Added an alternative to sudo apt "install/remove/purge/autoremove".
    -Added command "Install [program name]" to install programs.
    -Added commands "uninstall [program name]" and "remove [program name]" to remove programs.

    #EclipsedOS 1.0 beta 0.1.0 -> EclipsedOS 1.0 beta 0.1.1
    
    -Shrunk the iso size from 1.29GB -> 1.28GB.
  
    #EclipsedOS 1.0 alpha 0.0.9 -> EclipsedOS 1.0 beta 0.1.0
    
    -Shrunk the final install from 5.3GB -> 5.1GB.
    -Updated desktop background.
    -Improved overall stability.
    -Added 2 workspaces and workspace switcher to panel by default.
    -The trackpad and audio can be buggy on some chromebook models
     (only brasewell chromebooks are properly supported (?)).
    
    #EclipsedOS 1.0 alpha 0.0.8 -> EclipsedOS 1.0 alpha 0.0.9
    
    -Shrunk the iso down from 1.35GB -> 1.29GB.
    -Shrunk the final install from 5.7GB -> 5.3GB.
    -Removed Thunderbird.
    -Updated "Terminal" app.
    -Improved overall stability.
    
    #EclipsedOS 1.0 alpha 0.0.7 -> EclipsedOS 1.0 alpha 0.0.8
    
    -Made the OS stable enough for daily use again
    -Fixed all icons.(?)
    -Final install size is now 5.8 GB and 5.7GB after applying updates.
    
    #EclipsedOS 1.0 alpha 0.0.6 -> EclipsedOS 1.0 alpha 0.0.7
    
    -Fixed almost every bug from EclipsedOS 1.0 alpha 0.0.6 and made the system stable.
    -Changed the theme of the login screen.
    -Fixed the installer resolution.
    
    #EclipsedOS 1.0 alpha 0.0.5 -> EclipsedOS 1.0 alpha 0.0.6
    
    -Shunk the final instal size from 5.5GB -> Unknown
    -Shrunk the iso file from 1.37GB -> 1.35GB
    -Updated the grub menu to show EclipsedOS
    
    #EclipsedOS 1.0 alpha 0.0.4 -> EclipsedOS 1.0 alpha 0.0.5
    
    -Shunk the final instal size from 5.6GB -> 5.5GB.
    -Fixed The translucent elements.
    -Fixed the Applications menu icon.
    
    #EclipsedOS 1.0 alpha 0.0.1 -> EclipsedOS 1.0 alpha 0.0.4
    
    -Shrunk the iso down from 1.6GB -> 1.38GB.
    -Fixed The translucent elements.
    -Shunk the final instal size from 6.5GB -> 5.6GB
    -Fixed the "Icons".(?)
    -Fixed preinstalled apps not working
    -Skipped Alpha 0.0.2 and 0.0.3 as they are both far too unstable to use.
# EclipsedOS 3.0a1

http://eclipsedosproject.sytes.net/eclipsedosproject/download/93/?tmstv=1724635796

# Known issues:

- .bashrc does not show correct command for installing apps.
- Hidden files are shown by default.


# EclipsedOS 2.1

https://drive.google.com/file/d/1538cb6LGc_beHcSay6I_Bo18AYudkQcC/view

# EclipsedOS 2.0

https://drive.google.com/file/d/1z_SUnBSqE-CbTVgKf2vQCWVuyuXAKMoP/view?usp=sharing

# Known issues:

    -None the desktop background will be temporarilly removed for 2.0 on final install only. This doesn't mean you can't still use it as the files are there. I will revert this change in the 2.1 release.

# EclipsedOS 2.0b3

https://drive.google.com/file/d/1WWTNWj6mrsOQ-BvboIv4ldzYhbPkQHRi/view

# Known issues:

    -Missing icons for "default apps" as they are not defned.

# EclipsedOS 2.0b2

https://drive.google.com/file/d/1MXeCXJUxPU2K2SaeifjzrBdNFk6YpZcT/view

# Known issues:

    -Missing icons for "default apps" as they are not defned.

# EclipsedOS 2.0b1

https://drive.google.com/file/d/1KY4tfc0EUo_CM1QsTiuHtJ98fFMRcqh3/view

# Known issues:

    -Some missing icons.
    -Poor performance on USB 2.0.


# EclipsedOS 2.0a2

https://drive.google.com/file/d/1ceDWzgx6CFv7EH1eCVB_YJOYQ5x-EX2E/view

# Known issues:

    -Themes and icons not applying correctly ON INSTALLER ONLY (All themes resources etc are preinstalled and can be applied).
    -default keyboard layout is now GB no matter your default layout but you can still change it.
    -Poor performance on USB 2.0.

# EclipsedOS 2.0 prv1

https://drive.google.com/file/d/1b2pJnsj-ZLRh4h-4Sdpsvl3HKg90o730/view

# Known issues:

    -Themes and icons not applying correctly(All themes resources etc are preinstalled and can be applied).
    -Default browser not defined.
    -Audio won't work well on chromebooks.
    -default keyboard layout is now GB no matter your default layout but you can still change it.
    -Poor performance on USB 2.0.

# EclipsedOS 1.2

https://drive.google.com/file/d/1SgOwVd2ojbLH4eJe7mKe2BHlKkaVRKWd/view

# Known issues:

    -Audio won't work well on chromebooks.
    -default keyboard layout is now GB no matter your default layout but you can still change it.
    -Poor performance on USB 2.0.

# EclipsedOS 1.2b03

# Known issues:

    -Audio won't work well on chromebooks.
    -default keyboard layout is now GB no matter your default layout but you can still change it.
    -Poor performance on USB 2.0.

https://drive.google.com/file/d/1sdHnN-OQmVwPBx7yIwwgMqdtyGGYaV_R/view

# EclipsedOS 3122

https://drive.google.com/file/d/1_7emiOj-LLB1gpLCPCSZrTTRrwJOLwyG/view

Known issues:
  
    -Audio won't work well on chromebooks.
    -default keyboard layout is now GB no matter your default layout but you can still change it.
    -Poor performance on USB 2.0.
    -No firefox :(

# EclipsedOS 1.1

https://drive.google.com/file/d/1JyX52PRWBFEhSz50mSJQ9MQi2Z2x8TFA/view

Known issues:
    -Audio won't work well on chromebooks.
    -default keyboard layout is now GB no matter your default layout but you can still change it.
    -Poor performance on USB 2.0.

# EclipsedOS 1.1b03

https://drive.google.com/file/d/139F_5rIZ8AHQiOzzixVuInmsoVBSxRsz/view

Known issues:
    -Audio won't work well on chromebooks.
    -default keyboard layout is now GB no matter your default layout but you can still change it.
    -Poor performance on USB 2.0.

# EclipsedOS 1.1b02

https://drive.google.com/file/d/1EarmHjJCPivVk4TkdarFgXIZq2cy7QzL/view

Known issues:
    -Audio won't work too well.
    -Runs poorly on USB 2.0.

# EclipsedOS 1.1b01

https://drive.google.com/file/d/1laHYx-IvSNPdvPlNJSrARspcqRlS6urV/view

Known issues:
    
    -Audio on chromebooks doesn't work to well.

# EclipsedOS 1.0

https://drive.google.com/file/d/1YI1HPolY_FQyOq5r0fA1uTiayqX_bzmC/view

Known issues:
  
    -(?)

# EclipsedOS 1.0 rc1

https://drive.google.com/file/d/1jZYi1JJO5UsuAL0KvJ3U79Nnh4a8joLt/view

Known issues:
  
    -The "Media Keys"(chromebooks) don't work.(by default)
    -The trackpad and audio can be buggy on some chromebook models but works fine on most.

# EclipsedOS 1.0 beta 0.2.1

https://drive.google.com/file/d/1zc5wvDYJU-zS47LmEm-2zyfGodQ_L2-P/view

Known issues:
  
    -The "Media Keys"(chromebooks) don't work.(by default)
    -The trackpad and audio can be buggy on some chromebook models but works fine on most.

# EclipsedOS 1.0 beta 0.2.0

https://drive.google.com/file/d/1sI1HON3cq_xURb_QZI_D43_YlAgS7MJa/view

Known issues:
  
    -The "Media Keys"(chromebooks) don't work.(by default)
    -For whatever reason the file manager does not have updated icon despite being the same app.
    -The trackpad and audio can be buggy on some chromebook models
     (only brasewell chromebooks are properly supported (?)).

# EclipsedOS 1.0 beta 0.1.9

https://drive.google.com/file/d/1HznZ-Pqflz0aEW0yyN0CsMBShLegTDpA/view

Known issues:
  
    -The "Media Keys"(chromebooks) don't work.(by default)
    -For whatever reason the file manager does not have updated icon despite being the same app.
    -The trackpad and audio can be buggy on some chromebook models
     (only brasewell chromebooks are properly supported (?)).

# EclipsedOS 1.0 beta 0.1.8

https://drive.google.com/file/d/1GPCzFd-V8_AKdos9ASJfASygBZft2yHE/view

Known issues:
  
    -The "Media Keys"(chromebooks) don't work.(by default)
    -The trackpad and audio can be buggy on some chromebook models
     (only brasewell chromebooks are properly supported (?)).
    -For whatever reason the file manager does not have updated icon despite being the same app.
    -Repos do not work.


# EclipsedOS 1.0 beta 0.1.7

https://drive.google.com/file/d/1Sr8DHosUblxRZisHl3SYYQXMPWNKtVbh/view

Known issues:
  
    -The "Media Keys"(chromebooks) don't work.(by default)
    -The trackpad and audio can be buggy on some chromebook models
     (only brasewell chromebooks are properly supported (?)).
    -For whatever reason the file manager does not have updated icon despite being the same app.
    -repos do not work.

# EclipsedOS 1.0 beta 0.1.6

https://drive.google.com/file/d/1TaIE9NJ5pM3PCsrQlOuDNoUOWqLTHGb0/view

# EclipsedOS 1.0 beta 0.1.5 

https://drive.google.com/file/d/1_EKkTPQF5CHeGQ52jE3b7qMNi80rLdPn/view

# EclipsedOS 1.0 beta 0.1.5

https://drive.google.com/file/d/1_EKkTPQF5CHeGQ52jE3b7qMNi80rLdPn/view

# EclipsedOS 1.0 beta 0.1.4 

https://drive.google.com/file/d/1JOLgFD12NMS95Nb23fQ-lqhJ-5-r75GI/view

# EclipsedOS 1.0 beta 0.1.3

https://drive.google.com/file/d/1GCpvXXHwzZ9UCJSPi0iy_PRZSYBgsmvY/view

-updated a few install commands

# EclipsedOS 1.0 beta 0.1.2
    
https://drive.google.com/file/d/1Mh4fGMI4-E14NRsdRp_BPsl2omgD9jwK/view

Known issues:
  
    -The "Media Keys"(chromebooks) don't work.(by default)
    -The boot screen is has the wrong logo(installer only).
    -The themes don't apply correctly on installer when using a legacy bios.
    -The trackpad and audio can be buggy on some chromebook models
     (only brasewell chromebooks are properly supported (?)).

# EclipsedOS 1.0 beta 0.1.1
    
https://drive.google.com/file/d/1dOuYKrqRYDbK0iv9t-ypqlsWFwvOFv24/view

Known issues:
  
    -The "Media Keys"(chromebooks) don't work.(by default)
    -The boot screen is has the wrong logo(installer only).
    -The themes don't apply correctly on installer when using a legacy bios.
    -The trackpad and audio can be buggy on some chromebook models
     (only brasewell chromebooks are properly supported (?)).

# EclipsedOS 1.0 beta 0.1.0
    
https://drive.google.com/file/d/1x_iZ-Fs-QVCZLOENeC6rkEnQeugz-Eny/view

Known issues:
  
    -The "Media Keys"(chromebooks) don't work.(by default)
    -The boot screen is has the wrong logo(installer only).
    -The themes don't apply correctly on installer when using a legacy bios.
    -The trackpad and audio can be buggy on some chromebook models
     (only brasewell chromebooks are properly supported (?)).

# EclipsedOS 1.0 alpha 0.0.9
    
https://drive.google.com/file/d/1DDNAo4hVeef4UEvhv2Ph_VUMkDyAZFg5/view

Known issues:
  
    -The "Media Keys"(chromebooks) don't work.(by default)
    -The boot screen is has the wrong logo(installer only).
    -The themes don't apply correctly on installer when using a legacy bios.

# EclipsedOS 1.0 alpha 0.0.8
    
https://drive.google.com/file/d/1PrdVOpSg1pIpqx2Y5bqRpIrq_TkgFsHj/view

Known issues:
  
    -Restarting the system is extremely buggy.
    -The "Media Keys"(chromebooks) don't work.(by default)
    -The boot screen is has the wrong logo(installer only).
    -The themes don't apply correctly on installer when using a legacy bios.

# EclipsedOS 1.0 alpha 0.0.7
    
https://drive.google.com/file/d/1DDoAwdYhQf6CYBHUcHMyR1dm3PZOoezA/view

Known issues:
  
    -Applications menu icon is bugged again
    -The "Media Keys"(chromebooks) don't work.(by default)
    -The boot screen is has the wrong logo(installer only).
    -The themes don't apply correctly on installer when using a legacy bios.

# EclipsedOS 1.0 alpha 0.0.6
    
https://drive.google.com/file/d/1M-Q1xj7ZRbFVq0wYiO89B1e8odXKjW5z/view

Known issues:
  
    -Is far too unstable to be used in general 
    -The "Media Keys"(chromebooks) don't work.
    -The boot screen is has the wrong logo(installer only).
    -The themes don't apply correctly.(installer)
    -The default resolution is 1400 900 but this shouldn't be a problem on a real display.(?)


# EclipseOS 1.0 alpha 0.0.5

https://drive.google.com/file/d/1ZUFJK_BphttDnycU_Nw3ZfgxXikQ3xC9/view

Known issues:
  
    -The "Media Keys"(chromebooks) don't work.
    -The boot screen is broken(installer only).
    -The themes don't apply correctly.(installer)
    -The default resolution is 1400 900 but this shouldn't be a problem on a real display.(?)


# EclipsedOS 1.0 alpha 0.0.4:
    
https://drive.google.com/file/d/1UOZT5Qs0IdWvnXRrmH0yvtk7ykD4ukqW/view?usp=sharing

Known issues:
  
    -The "Media Keys"(chromebooks) don't work.
    -The boot screen is broken(installer only).
    -The "Applications Menu" has the wrong icon and is not configured correctly when installed.
    -The themes don't apply correctly.(?)
    -The default resolution is 1400 900 but this shouldn't be a problem on a real display.(?)

# EclipsedOS 1.0 alpha 0.0.1:
    
https://drive.google.com/file/d/1DqzQ0QRnn5_DW7pkbJu3_UxM_iSCw8ZT/view

Known issues:

    -Some apps don't launch(firefox is an example)
    -You can't make new accounts.
    -The "Media Keys"(chromebooks) don't work.
    -The boot screen is broken(installer only).
    -The package manager is semi broken.
    -The "Applications Menu" has the wrong icon and is not configured correctly when installed.
    -The themes don't apply correctly.
    -The default resolution is 1400 900 but this shouldn't be a problem on a real display.
    -Transparency effects don't work.
    
