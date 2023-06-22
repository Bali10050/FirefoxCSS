> **Warning**
> # Updating README.md in progress

# How to install:

### Enable `toolkit.legacyUserProfileCustomizations.stylesheets`
1. Go to `about:config`
2. Click on *„Accept the Risk and Continue”*
3. Doubleclick on `toolkit.legacyUserProfileCustomizations.stylesheets` if it isn't already enabled

### Copy the CSS in your profiles chrome folder
1. Go to `about:profiles`
2. Find your profile  --  ( *„This is the profile in use and it cannot be deleted.”* )
3. Open the profiles root directory
4. Create a folder called `chrome`
5. Copy the preferred `userChrome.css` and `userContent.css` there

### Restart Firefox
1. Click on the X button
2. Doubleclick on the firefox icon

***
# Configuration (Optional)

> **Warning**
> 
> If you are on linux remove `line 1` from `userChrome.css` !

> **Note**
>
> These configurations need to be done in `userChrome.css` unless said otherwise

## Hiding buttons

> Reload/stop button

Remove the `/*  ` from the beginning of `line 4`

> Forward/back button

Remove the `/*  ` from the beginning of `line 6`

> X-button from the tabs

Remove the `/*  ` from the beginning of `line 8`

> Newtab button

Remove the `/*  ` from the beginning of `line 10`

## Navbar width
You can set the navbar width on `line 16`

## Tabs border radius
You can set a custom border radius for the tabs on `line 15`

## Changing the background image:
> General background

Add your image to the chrome folder and name it `Background.png`

> Background only for newtab

Add your image to the chrome folder and name it `NewtabBackground.png`

> Background only for navbar

Add your image to the chrome folder and name it `NavbarBackground.png`

***

# Downloads:
## userChrome.css  --  Changes how the browser looks

#### [More buttons](https://github.com/Bali10050/FirefoxCSS/releases/download/userChrome(B)/userChrome.css)

![Win11 screenshot](https://github.com/Bali10050/FirefoxCSS/assets/110120798/6a6bce9c-cd1a-4d04-9ce9-1c5c0ec18027)

#### [Less buttons](https://github.com/Bali10050/FirefoxCSS/releases/download/userChrome(A)/userChrome.css)

![Linux screenshot](https://github.com/Bali10050/FirefoxCSS/assets/110120798/3daff38f-2a5c-4842-b8d4-391720b7009a)



## [userContent.css ](https://github.com/Bali10050/FirefoxCSS/releases/download/userContent/userContent.css)  --  Changes how the pages / devtools look

![New devtools screenshot](https://github.com/Bali10050/FirefoxCSS/assets/110120798/8c0ca262-dda8-41bb-8cde-7d0208dcb979)

