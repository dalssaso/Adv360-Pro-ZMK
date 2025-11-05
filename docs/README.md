# Advantage 360 Pro - Keymap Documentation

This document describes the custom keymap configuration for the Kinesis Advantage 360 Pro keyboard.

## Overview

The keymap consists of 4 layers:
- **Layer 0**: Default (QWERTY base layer)
- **Layer 1**: Keypad/Symbols
- **Layer 2**: Function Keys & Window Management
- **Layer 3**: Modifier (Bluetooth, RGB, Backlight controls)

## Layer Activation

- **MO(n)**: Momentary layer activation (active while held)
- **TO(n)**: Toggle layer (stays on until toggled off)
- **LT(n, key)**: Layer-tap (tap for key, hold for layer)

---

## Layer 0: Default Layer

### Left Half
```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ ESC │  1  │  2  │  3  │  4  │  5  │ TO1 │
├─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ TAB │  Q  │  W  │  E  │  R  │  T  │     │
├─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│LCTRL│  A  │  S  │  D  │  F  │  G  │     │
├─────┼─────┼─────┼─────┼─────┼─────┤LCMD │
│LSHFT│  Z  │  X  │  C  │  V  │  B  │     │
└─────┴─────┴─────┴─────┴─────┴─────┤LCTRL│
      │ MO1 │  `  │ MO2 │ LALT│LCMD │     │
      └─────┴─────┴─────┴─────┴─────┴─────┘
             │ SPC │ DEL │ END │
             └─────┴─────┴─────┘
```

### Right Half
```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ MO3 │  6  │  7  │  8  │  9  │  0  │  -  │
├─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│     │  Y  │  U  │  I  │  O  │  P  │  \  │
├─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│     │  H  │  J  │  K  │  L  │LT(1;)│ '  │
│RCMD ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │  N  │  M  │  ,  │  .  │  /  │RSHFT│
│RALT ├─────┴─────┴─────┴─────┴─────┴─────┘
│     │RCMD │RALT │  [  │  ]  │ MO2 │
└─────┴─────┴─────┴─────┴─────┴─────┘
      │PG_DN│ENTER│BSPC │
      └─────┴─────┴─────┘
```

**Key Features:**
- Standard QWERTY layout
- Home row mods support (defined in behaviors)
- Left thumb: Space, Delete, End
- Right thumb: Page Down, Enter, Backspace
- Layer access via MO1, MO2, MO3

---

## Layer 1: Keypad/Symbols Layer

### Left Half
```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│     │  1  │  2  │  3  │  4  │  5  │     │
├─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│     │  =  │  @  │  {  │  }  │  |  │     │
├─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│     │  +  │  $  │  (  │  )  │  `  │     │
├─────┼─────┼─────┼─────┼─────┼─────┤LCMD │
│LSHFT│  %  │  ^  │  [  │  ]  │  ~  │     │
└─────┴─────┴─────┴─────┴─────┴─────┤LCTRL│
      │     │  `  │ MO2 │ LALT│LCMD │     │
      └─────┴─────┴─────┴─────┴─────┴─────┘
             │ SPC │ DEL │ END │
             └─────┴─────┴─────┘
```

### Right Half
```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ MO3 │  6  │ NUM │  =  │  /  │  *  │  -  │
├─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│     │  Y  │ KP7 │ KP8 │ KP9 │ KP- │  \  │
├─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│     │ LFT │ DN  │ UP  │ RGT │ KP+ │  '  │
│RCMD ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │  N  │ KP1 │ KP2 │ KP3 │KP_EN│RSHFT│
│RALT ├─────┴─────┴─────┴─────┴─────┴─────┘
│     │RCMD │RALT │KP_. │  ]  │ MO2 │
└─────┴─────┴─────┴─────┴─────┴─────┘
      │PG_DN│ENTER│ KP0 │
      └─────┴─────┴─────┘
```

**Key Features:**
- Symbol layer with brackets, operators, and special characters
- Right side includes full numpad (KP7-9, KP1-3, KP0)
- Arrow keys on right side (J/K/L/;)
- Math operators for numpad

---

## Layer 2: Function Keys & Window Management

### Left Half
```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ F1  │ F2  │ F3  │ F4  │ F5  │ F6  │ TO1 │
├─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │     │     │     │     │     │
├─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │     │     │     │A-C-E│     │
├─────┼─────┼─────┼─────┼─────┼─────┤     │
│     │     │     │     │A-C-C│     │     │
└─────┴─────┴─────┴─────┴─────┴─────┤     │
      │     │     │     │     │     │     │
      └─────┴─────┴─────┴─────┴─────┴─────┘
             │     │     │     │
             └─────┴─────┴─────┘
```

### Right Half
```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ MO3 │ F7  │ F8  │ F9  │ F10 │ F11 │ F12 │
├─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│     │A-C-U│     │     │A-C-I│A-C-S│     │
├─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│     │A-C-←│A-C-↓│A-C-↑│A-C-→│A-C-G│     │
│     ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │A-C-J│     │     │A-C-K│     │     │
│     ├─────┴─────┴─────┴─────┴─────┴─────┘
│     │     │     │     │     │     │
└─────┴─────┴─────┴─────┴─────┴─────┘
      │     │     │     │
      └─────┴─────┴─────┘
```

**Key Features:**
- Function keys F1-F12
- Window management shortcuts (Alt-Ctrl combinations):
  - **A-C-U**: Window action U
  - **A-C-I**: Window action I
  - **A-C-←/↓/↑/→**: Window navigation/resize
  - **A-C-J**: Window action J
  - **A-C-K**: Window action K
  - **A-C-C**: Window action C
  - **A-C-ENTER**: Window action Enter
  - **A-C-S-→**: Window action Shift-Right (appears to be A-C-LG-RIGHT)
  - **A-C-S-←**: Window action Shift-Left (appears to be A-C-LG-LEFT)

---

## Layer 3: Modifier Layer (Bluetooth & Settings)

### Left Half
```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│     │ BT0 │ BT1 │ BT2 │ BT3 │ BT4 │     │
├─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │     │     │     │     │BTLDR│
├─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │     │     │     │     │RGB5 │
├─────┼─────┼─────┼─────┼─────┼─────┤     │
│     │     │     │     │     │     │BTCLR│
└─────┴─────┴─────┴─────┴─────┴─────┤     │
      │     │     │     │     │     │     │
      └─────┴─────┴─────┴─────┴─────┴─────┘
             │BL_INC│BL_DEC│     │
             └──────┴──────┴─────┘
```

### Right Half
```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│     │     │     │     │     │     │     │
├─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│BTLDR│     │     │     │     │     │     │
├─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│RGB5 │     │     │     │     │     │     │
│BTCLR├─────┼─────┼─────┼─────┼─────┼─────┤
│BTCLR│     │     │     │     │     │     │
│     ├─────┴─────┴─────┴─────┴─────┴─────┘
│     │BLTOG│RGBTG│BL_INC│BL_DEC│     │
└─────┴─────┴─────┴──────┴──────┴─────┘
      │BLTOG│     │     │
      └─────┴─────┴─────┘
```

**Key Features:**
- **Bluetooth Controls**:
  - BT0-BT4: Select Bluetooth profile 0-4
  - BT_CLR: Clear Bluetooth bond
  - BTLDR: Enter bootloader mode
- **Backlight Controls**:
  - BL_INC: Increase backlight
  - BL_DEC: Decrease backlight
  - BL_TOG: Toggle backlight
- **RGB Controls**:
  - RGB_TOG: Toggle RGB lighting
  - RGB_MEFS_CMD 5: RGB effect 5

---

## Custom Behaviors

### Homerow Mods
```c
hm: homerow_mods {
    compatible = "zmk,behavior-hold-tap";
    tapping-term-ms = <200>;
    quick_tap_ms = <175>;
    flavor = "tap-preferred";
}
```

- **Tapping term**: 200ms
- **Quick tap**: 175ms
- **Flavor**: tap-preferred (prioritizes tap over hold)

---

## Notes

- The left and right keymap files (`adv360_left.keymap` and `adv360_right.keymap`) both include the main `adv360.keymap` file
- Layer 2 contains window management shortcuts that appear to be configured for a tiling window manager or similar tool
- The keyboard supports up to 5 Bluetooth profiles
- Custom macros may be defined in the included `macros.dtsi` file (not shown)
