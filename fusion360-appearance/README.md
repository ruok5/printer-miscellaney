(Starting From Scratch)

1. Get a suitable CAD file for the design you want to apply color to. STL will *not* work. Ideally, you'd like to have a `.f3d` file (native to Fusion 360), but a `.step` will work fine too. In this example, I'm working with Rolohaun's Rook 2020 design found on [Printables](https://www.printables.com/model/447255-rook-2020/files), a `.step` file.
2. Launch Fusion 360, sign in, install updates, and dismiss a bunch of annoying "help".
3. In the Data panel on the left, choose Upload.
4. Choose the file you downloaded.
5. In the Fusion 360 Upload dialog, choose a location and start the upload.
6. Wait for the file to upload. You can close the dialog and watch for the new entry in the Data panel to finalize. It may take a minute or more.
7. Open your new design by double-clicking or right-clicking.
8. Type a lowercase letter `a` to launch the Appearance command.
9. In the Library section, select the Fusion 360 Appearances tab and find a suitable material. Drag that material to the In This Design section. The preset materials include surface appearance characteristics, which is what we're primarily after. Setting actual *physical material* properties instead of just appearance is beyond the scope of this how-to.
10. Right-click the material you just added to In This Design and select Copy to My Appearances. Switch to the My Appearances tab.
11. Right-click your material and select Edit.
12. In the edit window, find the drop-down menu to the right of Color. From that menu, choose Edit. This will open the color picker, which will be different depending on your platform. Use the color picker to enter the hex or RGB color you'd like. If you need to convert between hex and RGB, FilamentColors.xyz's [Color Match tool](https://filamentcolors.xyz/library/) is useful.
13. Give your new appearance setting a useful name. The reason to add these to My Appearances is so that they will be reusable in all of your designs. Be kind to your future self.
14. Last step: drag the appearance from My Appearances to a solid body on your model. If you really need to do something fancy, you can choose to apply appearances face-by-face, but I find that method error-prone and tedious.
15. Make as many more appearances as you like by right clicking your starting material or your newly created material and choosing Copy to My Appearances as in step 10.
16. When you're done, click Close at the bottom of the Appearance window.
