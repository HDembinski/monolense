# monolens

Show part of your screen in 8-bit grayscale.

![](https://user-images.githubusercontent.com/2631586/119804111-57356180-bee0-11eb-9177-9ad46544fbc2.mov)

# Usage

Run `monolens` in a terminal on the screen that you want to look at.

- Drag the lens around by holding a Mouse button down inside the window
- Resize the lens by pressing up, down, left, right
- To refresh the lens press the spacebar (see limitations)
- To quit, press Q

# Limitations

- Pulling the window to another screen is currently not supported. To switch screens,
  you need to run `monolens` from a terminal on that screen. This limitation will
  hopefully be lifted in the future.
- The lens uses a static screenshot which has to be manually updated if the screen
  content changed. Press spacebar to update the lens (which causes it to flicker).
- On OSX, you need to give `monolens` permission to make screenshots, since an ordinary
  App is not allowed to view pixel outside of its window for security reasons.
  `monolens` has no networking code implemented at all, so it is safe to use.
