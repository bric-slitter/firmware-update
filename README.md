# iMata camera firmware

Firmware releases for the iMata ESP32-CAM timelapse camera. The iMata app checks this repository for updates
(WiFi & firmware → Check for updates) and installs the newest `imata-firmware-<version>.bin` on the camera over WiFi.

The releases are built by the camera project's "Firmware release" workflow, with the template settings: a camera
updated from the app keeps its own WiFi name and settings.

To install one by hand: download the `.bin` to your phone and choose it in the app under
WiFi & firmware → Or choose a firmware file. A first install needs a USB cable (`pio run --target upload`).
