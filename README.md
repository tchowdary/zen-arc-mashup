# zen-arc-mashup

Move URL bar to Nav Bar

Inspired by 
- https://github.com/neurokitti/Arc_Zen_Theme/tree/main
- https://www.reddit.com/r/zen_browser/comments/1gr2118/im_in_love_with_zen_finally_i_can_switch_from_fkn/

<img width="1662" alt="image" src="https://github.com/user-attachments/assets/9c6ceee3-ef93-492e-9358-09dc46ac89f1">

 # Bookmarks

- about:config
- browser.toolbars.bookmarks.visibility --> always
- move bookmarks toolbar items to navbar
- set browser.toolbars.bookmarks.visibility --> never {back}
- create userChrome.css file in "chrome" folder
- paste css code in userChrome.css

# Download button at the top

```css
 /* Navigation Buttons */
    #downloads-button, #back-button, #forward-button, #stop-reload-button, #unified-extensions-button {
      position: fixed;
      top: var(--zen-element-separation);
      z-index: 1;
      pointer-events: auto !important;
    }
    #downloads-button{
      left:90px;
    }
```
