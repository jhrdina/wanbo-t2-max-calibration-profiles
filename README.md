# Wanbo T2 MAX Calibration Profiles
Calibration profiles for Wanbo T2 Max projector. Should help significantly with projector's color rendition, especially in skin-tones.

## 📦 Installation
* Download the [ZIP with profiles](https://github.com/jhrdina/wanbo-t2-max-calibration-profiles/archive/refs/heads/main.zip).
* Unpack the ZIP archive.
* Go to folder with a desired profile
* Double click on the ICC profile and install it into your system.
* The colors should look significantly better.

## 👉 Recommended profile
The latest one: [2021-12-22 20-20 2.2 VF-S XYZLUT+MTX](https://github.com/jhrdina/wanbo-t2-max-calibration-profiles/tree/main/2021-12-22%2020-20%202.2%20VF-S%20XYZLUT%2BMTX)

It uses the native whitepoint to preserve the projector's maximum brightness

### Settings for the profile:

Please adjust the settings of the projector so that it matches those I used when creating the profile. They help to recover details in shadows and highlights and give overall better starting point.

1. Go to HDMI mode (Main screen -> Settings -> Input source -> HDMI)
2. Press *menu* button on your remote
3. *Picture mode*
4. Set the following settings:
    - Picture Mode: User
    - Brightness: **47**
    - Contrast: **46**
    - Saturation: 50
    - Gamma: Middle
    - Color temperature: Standard
    - Advanced Video: Defaults
    - Color Tuner: Defaults
    - 11 point white balance Correction:
      - Gain: 10 percent
      - Red: **60**
      - Green: **40**
      - Blue: **40**

## ☀️ The D6500 Profiles
In the profiles that have D6500 in their name, I've set the target color temperature to standard 6500K (much warmer than native).

To achieve this, the Blue and Green channels brightness gets lowered significantly and therefore the overall projector brightness decreases. It was too low for my taste (so I ended up using the native temperature profile), but maybe its what you're looking for.
