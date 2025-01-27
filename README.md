# org.freedownloadmanager.Manager

## Not work

### Browser Integration

FDM app receive data from installed browser's FDM extension via native messaging, which doesn't supported by flatpak currently. Flatpak doesn't let flatpak apps interact with each other directly, but can be done via portal. There is ongoing [native messaging implementation on flatpak](https://github.com/flatpak/xdg-desktop-portal/pull/705) so this problem can be solved.
