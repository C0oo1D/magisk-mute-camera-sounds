## Mute Camera Sounds v1
Was created because existing solutions stopped working after updating xiaomi.eu firmware to android 11 (MIUI 12.5).
It turned out that sounds taken from `product` root directory, not `system`, as it was before.
But for greater reliability, sounds was replaced in all found places.

## Overrided files:
- `camera_click.ogg`
- `camera_focus.ogg`
- `VideoRecord.ogg`
- `VideoStop.ogg`

## Target paths:
- `/system/media/audio/ui`
- `/product/media/audio/ui` (through `/system/product` symbolic link)

## Precautions
Use this software on your own risk, and don't use it in countries, where disabling sounds from the above files is forbidden.