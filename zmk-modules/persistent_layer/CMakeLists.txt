# zmk_keymap_* symbols only exist on the central half (ZMK compiles keymap.c
# under the same guard), so only build this module there to avoid undefined
# references when linking the peripheral.
if((NOT CONFIG_ZMK_SPLIT) OR CONFIG_ZMK_SPLIT_ROLE_CENTRAL)
  target_sources(app PRIVATE src/persistent_layer.c)
endif()
