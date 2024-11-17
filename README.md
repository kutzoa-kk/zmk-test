```
west build --pristine -b nice_nano_v2 -- -DSHIELD=first_ble_kbd -DZMK_CONFIG="/workspaces/zmk-config/config" -DZMK_EXTRA_MODULES="/workspaces/zmk-config"
west build --pristine -b adafruit_feather_nrf52840 -- -DSHIELD=first_ble_kbd -DZMK_CONFIG="/workspaces/zmk-config/config" -DZMK_EXTRA_MODULES="/workspaces/zmk-config"
```

