# dunstrc

This configuration file for `dunst`, a lightweight and customizable notification daemon, integrates with the color scheme used in my `dwm` window manager setup. Key highlights of this configuration include:

- **Global Settings**:
  - Notifications follow the mouse pointer and are displayed on the primary monitor.
  - Notification window geometry and padding are carefully set for a clean look.
  - Frame width is set to 3 pixels, with the frame color matching the `dwm` border color.
  - Transparency is set to 0 for an opaque background.

- **Text and Display**:
  - Notifications use the `JetBrains Mono Medium 10` font for clarity and readability.
  - Text alignment is centered, and word wrapping is enabled for better text presentation.
  - Notifications display the age of messages older than 60 seconds and ellipsize long lines in the middle.

- **Icons and History**:
  - Icons are displayed on the left side, with a maximum size of 32 pixels. NOTE: change your path to icons!
  - Notification history is enabled, keeping up to 20 notifications.

- **Urgency Levels**:
  - Low and normal urgency notifications share a background color matching the `dwm` background color (`#444444`) and a foreground color matching the `dwm` foreground color (`#E6E6E6`).
  - Critical notifications feature a distinct red frame color (`#FF0000`) and a brighter background to draw attention.

- **Custom Shortcuts**:
  - Various keyboard shortcuts are defined for interacting with notifications, such as closing notifications and accessing the notification history.

This setup ensures a cohesive visual experience across the desktop environment, aligning the notification appearance with my `dwm` window manager’s color scheme.
