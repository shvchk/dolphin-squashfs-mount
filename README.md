## Dolphin service menu: SquashFS mounter / unmounter

- Mount SquashFS file using "Mount SquashFS". No root required.
  - After mounting it opens created mount point in your file manager.  
    It creates a mount point in `/tmp` using the name of the file being mounted + first 8 characters of file path's `sha256` hash.
- Unmount previously mounted file using "Unmount SquashFS".

This project uses `squashfuse`. Please, make sure `squashfuse` package is installed.

![Screenshot](screenshot.png)

![Screenshot](screenshot-2.png)
