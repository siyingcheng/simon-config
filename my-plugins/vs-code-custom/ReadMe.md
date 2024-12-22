# Create Your Own VSCode Theme with CSS

> I followed this tutorial https://www.youtube.com/watch?v=DSxUlhIN2lk

The file `custom.css` is the one that you need to create. You can customize the colors, fonts, and other styles to your liking.
The file `avatar.png` is the image that will be displayed in the sidebar. You can replace it with your own image.

To apply the custom theme:

1. Install `Dracula Theme Official` from the VSCode marketplace.
2. Install `Custom CSS and JS Loader` from the VSCode marketplace.
3. Open the `settings.json` file and add the following code:
    ```json
    "vscode_custom_css.imports": [
        "file:///{path_to_your_custom.css_file}"
    ]
    ```
    And update the `avatar.png` file path in the `custom.css` file.
4. `View -> Command Palette` and type `Enable Custom CSS and JS` to apply the changes.
5. Restart VSCode.