# How to change the appearance of imported models in Fusion 360
### (Starting From Scratch)

This simple guide describes the steps needed to use Fusion 360 to change the appearance (colors) of models for visualization purposes, especially for anyone very new to Fusion 360. This is not intended to explain any of the basics of the user interface, just the steps that always take me some futzing with to get to do what I want.

### Steps

1. Get a suitable CAD file for the design you want to apply color to. STL will *not* work. Ideally, you'd like to have a `.f3d` file (native to Fusion 360), but a `.step` will work fine too. In this example, I'm working with Rolohaun's Rook 2020 design found on [Printables](https://www.printables.com/model/447255-rook-2020/files), a `.step` file.
2. Launch Fusion 360, sign in, install updates, and dismiss a bunch of annoying "help".
3. In the Data panel on the left, choose Upload.

    ![alt text](https://github.com/ruok5/printer-miscellaney/blob/main/fusion360-appearance/images/IMG_001.png?raw=true)

4. Choose the file you downloaded.

    ![alt text](https://github.com/ruok5/printer-miscellaney/blob/main/fusion360-appearance/images/IMG_002.png?raw=true)


5. In the Fusion 360 Upload dialog, choose a location and start the upload.

    ![alt text](https://github.com/ruok5/printer-miscellaney/blob/main/fusion360-appearance/images/IMG_003.png?raw=true)


6. Wait for the file to upload. You can close the dialog and watch for the new entry in the Data panel to finalize. It may take a minute or more.

    ![alt text](https://github.com/ruok5/printer-miscellaney/blob/main/fusion360-appearance/images/IMG_004.png?raw=true)


7. Open your new design by double-clicking or right-clicking.

    ![alt text](https://github.com/ruok5/printer-miscellaney/blob/main/fusion360-appearance/images/IMG_005.png?raw=true)
    ![alt text](https://github.com/ruok5/printer-miscellaney/blob/main/fusion360-appearance/images/IMG_006.png?raw=true)

8. Type a lowercase letter `a` to launch the Appearance command.

    ![alt text](https://github.com/ruok5/printer-miscellaney/blob/main/fusion360-appearance/images/IMG_007.png?raw=true)


9. In the Library section, select the Fusion 360 Appearances tab and find a suitable material. Drag that material to the In This Design section. The preset materials include surface appearance characteristics, which is what we're primarily after. Setting actual *physical material* properties instead of just appearance is beyond the scope of this how-to.

    ![alt text](https://github.com/ruok5/printer-miscellaney/blob/main/fusion360-appearance/images/IMG_008.png?raw=true)


10. Right-click the material you just added to In This Design and select Copy to My Appearances. Switch to the My Appearances tab.

    ![alt text](https://github.com/ruok5/printer-miscellaney/blob/main/fusion360-appearance/images/IMG_009.png?raw=true)


11. Right-click your material and select Edit.

    ![alt text](https://github.com/ruok5/printer-miscellaney/blob/main/fusion360-appearance/images/IMG_012.png?raw=true)


12. In the edit window, find the drop-down menu to the right of Color. From that menu, choose Edit. This will open the color picker, which will be different depending on your platform. Use the color picker to enter the hex or RGB color you'd like. If you need to convert between hex and RGB, FilamentColors.xyz's [Color Match tool](https://filamentcolors.xyz/library/) is useful.

    ![alt text](https://github.com/ruok5/printer-miscellaney/blob/main/fusion360-appearance/images/IMG_013.png?raw=true)


13. Give your new appearance setting a useful name. The reason to add these to My Appearances is so that they will be reusable in all of your designs. Be kind to your future self.
14. Last step: drag the appearance from My Appearances to a solid body on your model. If you really need to do something fancy, you can choose to apply appearances face-by-face, but I find that method error-prone and tedious.

    ![alt text](https://github.com/ruok5/printer-miscellaney/blob/main/fusion360-appearance/images/IMG_015.png?raw=true)


15. Make as many more appearances as you like by right clicking your starting material or your newly created material and choosing Copy to My Appearances as in step 10.
16. When you're done, click Close at the bottom of the Appearance window.
