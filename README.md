# Print Bench

An iPad app for getting OBJ and STL models ready to 3D print: resize and orient them, sculpt with Apple Pencil, repair holes and flipped faces, cut a flat base, check the fit on your printer, and export STL.

Open it at **https://zahra-hasan.github.io/print-bench/**

## Install on iPad

1. Open the link above in **Safari**.
2. Tap the **Share** button, then **Add to Home Screen**.
3. Open **Print Bench** from the Home Screen. It runs full screen and works offline.

## Your models

- Every model you open or change saves automatically on the iPad. Tap **Models** to open, rename, copy or delete saved models.
- Models stay on the device and are never uploaded. Deleting the app from the Home Screen deletes its saved models, so export anything you want to keep.
- **Export → STL** opens the share sheet: Save to Files, AirDrop, or send it to a slicer app.

## Updating

All files are static. After changing any of them, bump `VERSION` in `sw.js` so installed copies pick up the new files.
