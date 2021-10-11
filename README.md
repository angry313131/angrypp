# angrypp
angrypp
//META{"name":"Wishful Blue","description":"A theme filled with wishes and blue style","author":"Ruben7173","version":"1.0"}*// {}

/* imports urls here */ /* remove the status.css import url if you want default status */
@import url(https://raw.githack.com/Ruben7173/Ruben7173.github.io/master/BetterDiscord-Themes/Modules/status.css);
@import url(https://raw.githack.com/Ruben7173/Ruben7173.github.io/master/BetterDiscord-Themes/Modules/transparency2.css);
@import url(https://raw.githack.com/Ruben7173/Ruben7173.github.io/master/BetterDiscord-Themes/wishful-blue/code.css);

:root {
    /* background URL */
    --background-image: url(
https://media.giphy.com/media/uKWBNet3fFTP9ZDZIg/giphy.gif
) center/cover no-repeat;
    /* Guild and Top bar transparency */
    --transparency-1: linear-gradient(to left, rgba(0,0,0,0.85), rgba(0,0,0,0.85));
    /* transparency for channels and private channels */
    --transparency-2: linear-gradient(to right, rgba(0,0,0,0.85), rgba(0,0,0,0.65));
    /* chat and top area and other secondary pages */
    --transparency-3: linear-gradient(to right, rgba(0,0,0,0.65), rgba(0,0,0,0.55));
    /* member list */
    --transparency-4: linear-gradient(to right, rgba(0,0,0,0.55), rgba(0,0,0,0.65));
    /* transparecy with gradient of top bar */
    --transparency-5: linear-gradient(to right, rgba(0,0,0,0.85), rgba(0,0,0,0.85),rgba(0,0,0,0.65), rgba(0,0,0,0.62), rgba(0,0,0,0.60),rgba(0,0,0,0.55), rgba(0,0,0,0.55));
    
    /* Background color of markdown box */
    --markdown-background-color: rgba(54, 139, 165, 0.15);
    /* Border of markdown text */
    --markdown-border-color: rgba(54, 139, 165, 0.45);
    /* accent color, applies to buttons */
    --accent-color: rgba(54, 139, 165, 0.35);
    /* accent color for the border */
    --accent-color-border: rgba(54, 139, 165, 0.45);
    /* accent color hover state */
    --accent-color-hover: rgba(54, 139, 165, 0.10);
    /* acent color border hover state */
    --accent-color-border-hover: rgba(54, 139, 165, 0.20);
    /* Checker ON/OFF */
    --checker-on: rgba(54, 139, 165, 0.35);
    --checker-off: rgba(11, 39, 45, 0.60);
    /* Sub Menu's background color and hover */
    --submenu-color: rgba(18, 63, 80, 0.85);
    --submenu-hover: rgba(3, 12, 21, 0.25);
}
