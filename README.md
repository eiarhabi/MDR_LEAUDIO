# MDR_LEAUDIO

This is a modified version of Sony Headphone Connect Android Application V10 that allows activation of LE Audio functionality for Linkbuds S and WF-1000XM5 regardless of device used. 

## Warning

This app is not intended for everyday use. Please be advised that an official version is highly recommended for turning earbuds for anything other than LE Audio settings. Proceed at your own risk.

## Technical Detail

Sony checks if an Android device supports LE Audio by looking at Qualcomm's proprietary `vendor.somc.qti_lea.support` attribute in system properties. This makes it impossible for non-Qualcomm devices users (e.g. Pixel) to enable LE Audio for their Sony earbuds. This modified version bypass Sony's detection so that any Android device that suppoorts LE Audio is able to change LE Audio priority setting.

## Acknowledgements 

This project is inspired by and derived from a modified and recompiled version of Headphone Connect app provided by https://github.com/lzghzr/MDR_Proxy.
