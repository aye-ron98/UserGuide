# Overview

You are a developer now! As such it is important to know how to navigate and work the many settings of [VS Code](https://code.visualstudio.com/learn).

In this section we will cover:

- [Customizing hotkeys](./settings.md#customizing-hotkeys)
- [Customizing save settings](./settings.md#customizing-save-settings)

## Customizing Hotkeys

VS Code offers a variety of hotkeys to help you save time as you work. In this example we will be setting the hotkey Alt + Z to autoformat text.

1. Open VS Code, from the landing page **click** the manage icon on the bottom of left navbar.

    <figure marksdown>
        <img src="../images/setting0.jpg" alt="VS Code side bar" style="display: block;margin-left: auto;margin-right: auto; max-width: 350px">
    </figure>

2. **Click** key board shortcuts from the popup. A new window will open displaying all hotkeys VS Code offers.

    !!! info "Info"
        This step may be accessed directly using the Ctrl + K, Ctrl + S hotkey.

    <figure markdown>
        <img src="../images/setting1.jpg" alt="VS Code side bar" style="display: block;margin-left: auto;margin-right: auto; max-width: 350px">
    </figure>

    You can manage all the hotkeys on this window, and check the hotkeys for your current OS.

3. Type the following in the search bar:

    ```{.js .annotate}
    Terminal: Toggle size to content width
    ```

    <figure markdown>
        <img src="../images/setting2.jpg" alt="VS Code side bar" style="display: block;margin-left: auto;margin-right: auto; max-width:350px">
    </figure>

    Toggle size to content width helps you autoformat your text to fit your current window size.

4. **Click** the hotkey from the search results. A popup _window_ will appear prompting you to enter your desired hot key.

    <figure markdown>
        <img src="../images/setting3.jpg" alt="VS Code side bar" style="display: block;margin-left: auto;margin-right: auto; max-width:350px">
    </figure>

5. Type your hot key in the popup text box and hit **enter** to save your changes. We recommend Alt + Z.

    !!! info "Info"
        If the hotkey you wish to use is already used by another setting, VS Code with prompt you with a warning before you can save any changes.

    <figure markdown>
        <img src="../images/setting4.jpg" alt="VS Code side bar" style="display: block;margin-left: auto;margin-right: auto; max-width:350px">
    </figure>

## Customizing Save Settings

It is important to always save your work. Nothing is more frustrating than working an a problem for hours only to loose all your progress because you did not save. Luckily, VS Code offers autosave features customizable by time, and user actions.

Here we will demonstrate how to customize your autosave to be preformed after switching to a new tab.

1. Open VS Code, from the landing page **click** the _manage_ icon on the bottom of left navbar. A popup _menu_ will appear as the image below.

    <figure markdown>
        <img src="../images/setting0.jpg" alt="VS Code side bar" style="display: block;margin-left: auto;margin-right; max-width:350px">
    </figure>

2. **Click** settings from the popup menu. A new window will open present with save settings.
    !!! info "info"
        This step may be accessed directly using the  Ctrl + hotkey.

    <figure markdown>
        <img src="../images/setting5.jpg" alt="VS Code side bar" style="display: block;margin-left: auto;margin-right: auto; max-width: 350px">
    </figure>

3. **Click** the _commonly used_ bar located under the user tab.

    !!! info "Info"
        Off is the default option that will disable autosave.

    <figure markdown>
            <img src="../images/setting6.jpg" alt="VS Code side bar" style="display: block;margin-left: auto;margin-right: auto;max-width: 350px">
    </figure>


4. **Click** the dropdown menu under _Files: Autosave_ and choose _OnFocusChange_.

    !!! info "Info" 
        onFocusChange auto-saves files both when you switch windows on your computer and when you switch tabs within VSCode.

    <figure markdown>
        <img src="../images/setting7.jpg" alt="VS Code side bar" style="display: block;margin-left: auto;margin-right: auto;max-width: 350px">
    </figure>
    
## Conclusion

You should now know how to customize save and hotkey settings in VS Code.

In this section we have covered:

- Customizing save settings
- Customizing hotkeys