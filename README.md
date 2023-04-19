# A guide to customization

## How to install:

### Enable `toolkit.legacyUserProfileCustomizations.stylesheets`
1. Go to `about:config`
2. Click on *„Accept the Risk and Continue”*
3. Doubleclick on `toolkit.legacyUserProfileCustomizations.stylesheets` if it isn't already enabled

### Copy the CSS in your profiles chrome folder
4. Go to `about:profiles`
5. Find your profile  --  ( *„This is the profile in use and it cannot be deleted.”* )
6. Open the profiles root directory
7. Create a folder called `chrome`
8. Copy the preferred `userChrome.css` and `userContent.css` there

### Restart Firefox
1. Click on the X button
2. Doubleclick on the firefox icon

***

## Help with finding the right css for you

### userChrome.css  --  Changes how the browser looks

#### Full theme  --  (Most buttons are visible)

 Windows style titlebar buttons

#### - <a href="https://raw.githubusercontent.com/Bali10050/FirefoxCSS/main/FirefoxCSS/Full/Win11/userChrome.css" download="">For Windows 11</a>
#### - [For Linux](./FirefoxCSS/Full/Linux/Win/)

![Win11 screenshot](./Screenshots/W11.webp)

***

 Macos style titlebar buttons

#### - [For Macos/Linux](./FirefoxCSS/Full/Linux/Mac/)

![MacosStyle screenshot](./Screenshots/MacStyle.webp)

***

#### Minimal theme  --  (Only a few buttons)

#### - [For Linux](./FirefoxCSS/Minimal/)

![Linux screenshot](./Screenshots/Linux.webp)

***

### userContent.css  --  Changes how the pages look

#### All themes  --  (No custom colors)

#### - [For all](./FirefoxCSS/userContent/All/)

#### Dark themes  --  (Custom grey color scheme)

#### - [For me](./FirefoxCSS/userContent/Dark/)
