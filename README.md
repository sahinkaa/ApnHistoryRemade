# ApnHistory Remade

<img src="ApnHistoryIcon.png" alt="ApnHistory Remade app icon" width="240">

I've been using ApnHistory since the dawn of time. I couldn't go without it on iOS 26, so I remade it. Thank you to **m156nrkvv** for making the original and giving me a tweak I've kept coming back to for years.

ApnHistory Remade keeps a local history of app notifications, incoming SMS and calls. Browse it by app or in a timeline. Use **Copy notification** from an entry’s menu to put its text on the clipboard.

Keep track of notifications from apps whose alerts you’ve turned off, whenever iOS still posts those notifications as system bulletins. Turning off delivery can prevent a notification from reaching the capture hook.

## What's changed from the original

- Reworked notification capture around the SpringBoard bulletin observation method used by **Vē Enhanced**.
- Rebuilt Settings for light and dark mode and added a color picker and photo backgrounds with optional blur.
- Added **Copy notification** alongside **View raw data** and restored app icons and app launching from history.
- Expanded Auto Protect to an editable list of keywords. Set your own history limit from 1 to 10,000 items. New entries replace the oldest unprotected items as the history fills.
- Added separate controls to delete unprotected items or clear the entire history. Individual entries can be deleted with a swipe.
- Removed Twitter media saving and the Extended Scheme option.

## Compatibility and installation

The package targets **iOS 16.6 through iOS 26 on RootHide**. Tested on **iOS 16.6** and **iOS 26.0.1**. Download the RootHide .deb from [v1.0](https://github.com/sahinkaa/ApnHistoryRemade/releases/tag/v1.0) and open it in Sileo. The Home Screen label is **ApnHistory**.

## Credits

Original **ApnHistory** by **m156nrkvv**. Remade by **sahinkaa**. Credit to **Vē Enhanced** for the notification capture method.
