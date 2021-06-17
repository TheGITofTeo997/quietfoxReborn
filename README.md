## Some Notes ℹ️
We are a group of two people that loved Quietfox. Unluckily Firefox updates have broken it over time, so our goal is to fix it and restore the old look as much as possible, that's why we have this fork. 

We will keep supporting this project through the upcoming Firefox updates.

Most of the credits go to the original ![creator](https://github.com/coekuss)

![quietfox](https://github.com/TheGITofTeo997/quietfoxReborn/blob/master/logo.png)
![](https://github.com/TheGITofTeo997/quietfoxReborn/blob/master/clean2.PNG)

## The Goal ℹ️
This userChrome mod was created by the original creator to make the Firefox UI cleaner and more modern without sacrificing any of its original features. You can pretty much forget that you have a mod installed, it works *quietly* in the background. Here are some of the notable features:


## Customizable values 
Simply open userChrome.css in a text editor and change the values at the top of the file. Restart Firefox to see changes.

💡 Please note this is still in Beta and we had to "force" some values to prevent breakage, so you might *not* be able to tweak all.

### Toolbar Customizations ℹ️

```CSS
/* -------------------- 🎨 Customization 🎨 -------------------- */
    --tab-corner-rounding: 7px;
    /* --menu-corner-rounding: 10px; */
    /* --menu-item-height: 30px;     */
    --button-corner-rounding: 20px;
    --animation-speed: 0.4s;
```
![](https://coekuss.com/quietfox/quietfox70/fluid2.gif)

<br>

```CSS
/* -------------------- 🎨 Customization 🎨 -------------------- */
    --tab-corner-rounding: 0px;
    /* --menu-corner-rounding: 10px; */
    /* --menu-item-height: 30px;     */
    --button-corner-rounding: 0px;
    --animation-speed: 0.0s;
```
![](https://coekuss.com/quietfox/quietfox70/snappy2.gif)

### Menu Customizations ℹ️
```CSS
/* -------------------- 🎨 Customization 🎨 -------------------- */
    /* --tab-corner-rounding: 7px;     */
    --menu-corner-rounding: 10px;
    --menu-item-height: 30px;
    /* --button-corner-rounding: 20px; */
    /* --animation-speed: 0.4s;        */
```

<p align="center">
    <img src="https://coekuss.com/quietfox/tall_rounded.png">
</p>

<br>

```CSS
/* -------------------- 🎨 Customization 🎨 -------------------- */
    /* --tab-corner-rounding: 7px;     */
    --menu-corner-rounding: 0px;
    --menu-item-height: 25px;
    /* --button-corner-rounding: 20px; */
    /* --animation-speed: 0.4s;        */
```
<p align="center">
    <img src="https://coekuss.com/quietfox/short_sharp.png">
</p>


## Theme-adapted menus ℹ️
💡 Please note that we can consider this feature *disabled* (or broken/deprecated) for now. This theme has just been tested and will *JUST* be used with the [Nord Polar Dark](https://addons.mozilla.org/it/firefox/addon/nord-polar-night-theme/) theme. Other Firefox themes *MIGHT* work, but things have been set up on to work best with it, so expect glitches and bugs if you are not going to use that theme.

However, we might be able to restore that behaviour in the future.

## Address bar buttons appear when needed ℹ️
![](https://coekuss.com/quietfox/urlbar_buttons.gif)



## How to install ℹ️
1. Download and unzip (from Repo or from [Releases](https://github.com/TheGITofTeo997/quietfoxReborn/releases))
2. Go to `about:support` in Firefox and open your Profile Folder
3. Drop your unzipped "chrome" folder into the folder that appears
4. Go to `about:config` in your Firefox and set the value of `toolkit.legacyUserProfileCustomizations.stylesheets` to `true` (this enables the loading of userChrome mods)
5. Restart Firefox


✔️ Tested on Firefox 89.0.1, Nord Polar Dark Theme on Windows 10 


### Older version ℹ️
If you need Quietfox for an older version of Firefox, [see the original version releases page.](https://github.com/coekuss/quietfox/releases)


## P.S. ℹ️

We have put so much effort into this project to enhanche your Firefox experience and to make it always up to date, if you want, consider a small donation 💖

<img align="top" width="25px" src="https://coekuss.com/quietfox/bitcoin.png"> Bitcoin: 3QAFBtp2r8L2Ea6Ty2nbkC6pBAqE2LQCMR

---

*Support for the original creator will also be appreciated for sure*

This mod is the product of many late nights of zen laser focus. If it enhances your web experience, consider donating a small sum to show your support ❤

<img align="top" width="25px" src="https://coekuss.com/quietfox/bitcoin.png"> Bitcoin: 1Lc5r26FTwWSLNH46fE5WH3mvFjNUcHGzi

<img align="top" width="20px" src="https://coekuss.com/quietfox/paypal.png"> PayPal: [paypal.me/coekuss](https://paypal.me/coekuss)
