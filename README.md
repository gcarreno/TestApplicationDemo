# Application Config Demo

A boiler plate on how to do Application config the "Lazarus Way (tm)".

It includes:

- Setting up what properties to save on `TForm.SessionProperties`
- `TINIPropStorage` for `TForm.SessionProperties` property storage
- `TFileExit` action with different shortcuts for Windows and Linux
- The use of `GetAppConfigFile()` to get the app's default file customised for Linux/Windows
- A way to have different short cuts for exit in Linux(CTRL+Q) and Windows(ALT+X)
