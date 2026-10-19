# esp32flight firmware channel

Release images for the esp32flight desk radar fork (Guition JC2432W328C and
other boards). Sources are kept in a private repository; this one carries the
binary images the devices update themselves from.

Asset naming: `esp32flight-<version>-<board suffix>-ota.bin`, attached to a
tag `v<version>`. The device reads the newest release here once a day, offers
the update on its settings screen, and streams the image into the inactive
firmware slot.

Everyone is welcome to use these builds; they are provided as-is under the MIT
license of the project (see the upstream repository for the licence text).
