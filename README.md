# MDR_LEAUDIO

This is a modified version of Sony Headphone Connect Android Application V10 that allows activation of LE Audio functionality for Linkbuds S and WF-1000XM5 regardless of device used. 

## Technical Detail

Sony checks if an Android device supports LE Audio by searching Qualcomm's proprietary `vendor.somc.qti_lea.support` attribute in system properties. This makes it impossible for non-Qualcomm devices users (e.g. Pixel) to enable LE Audio for their Sony earbuds. This modified version disables Sony's LE Audio capability detection.

## Credits

This project is inspired by and derived from a modified and recompiled version of Headphone Connect app provided by https://github.com/lzghzr/MDR_Proxy.
