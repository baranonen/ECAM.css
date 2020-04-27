# ECAM.css
[![Repo Size](https://img.shields.io/github/repo-size/baranonen/ECAM.css?style=plastic "Repo Size")](https://img.shields.io/github/repo-size/baranonen/ECAM.css?style=plastic "Repo Size") [![License](https://img.shields.io/github/license/baranonen/ECAM.css?style=plastic "License")](https://img.shields.io/github/license/baranonen/ECAM.css?style=plastic "License") [![Version](https://img.shields.io/npm/v/ecam.css?style=plastic "Version")](https://img.shields.io/npm/v/ecam.css?style=plastic "Version")
</br>
Airbus ECAM Style CSS Framework

### Installing
To install ECAM.css, run `npm i ecam.css`.  
Put `<link rel="stylesheet" href="node_modules/ecam.css/ecam.css">` to the `<head>` section of the HTML to import it.

### Fonts
No fonts are included with this package but usage of [Source Code Pro](https://fonts.google.com/specimen/Source+Code+Pro "Source Code Pro") is recommended.

# Components

## IMPORTANT
Most of the components found below do not have layout or width/height styles. You need to add them yourself according to your needs.

#### Question Form
````html
<div class="questiondiv">
    <div>
        <p class="questionmark">?</p>
        <p class="questiontext">A350/A380 Style Question ?</p>
    </div>
    <form class="a350form" action="#">
        <input type="radio" name="form">
        <label class="a350formlabel" for="yes">Yes</label>
        <input type="radio" name="form">
        <label class="a350formlabel" for="no">No</label>
    </form>
</div>
````

### Text Styles
###### Use the `alert` class to add borders to the text
##### Red Text
```html
<p class="text alert red">ERROR</p>
<p class="text red">ERROR</p>
```
##### Amber Text
```html
<p class="text alert amber">WARNING</p>
<p class="text amber">WARNING</p>
```
##### Green Text
```html
<p class="text alert green">INFO</p>
<p class="text green">INFO</p>
```
##### Azure Text
```html
<p class="text action">ACTION</p>
```
##### Basic Text
```html
<p class="text">TEXT</p>
```
### Buttons
##### Non Hoverable
```html
<a class="button" href="#">BUTTON</a>
```
##### Hoverable
```html
<a class="button hoverable" href="#">HOVERABLE</a>
```
### Dropdowns
##### Gray Background
```html
<div class="dropdown">
    <button class="button dropdownbutton"><a class="text dropdowntext">DROPDOWN</a><i class="fa fa-sort-desc"></i></button>
    <div class="button dropdown-content">
        <a href="#">Option 1</a>
        <a href="#">Option 2</a>
        <a href="#">Option 3</a>
    </div>
</div>
```
##### Black Background
```html
<div class="dropdown">
    <button class="button dropdownbutton"><a class="text dropdowntext darkdropdown">DROPDOWN 2</a><i class="dropdownicon fa fa-sort-desc"></i></button>
    <div class="button dropdown-content">
        <a href="#">Option 1</a>
        <a href="#">Option 2</a>
        <a href="#">Option 3</a>
    </div>
</div>
```
##### Gray Background (Hoverable)
```html
<div class="dropdown ">
    <button class="button dropdownbutton hoverable"><a class="text dropdowntext">HOVERABLE</a><i class="fa fa-sort-desc"></i></button>
    <div class="button dropdown-content">
        <a href="#">Option 1</a>
        <a href="#">Option 2</a>
        <a href="#">Option 3</a>
    </div>
</div>
```
##### Black Background (Hoverable)
```html
<div class="dropdown">
    <button class="button dropdownbutton hoverable"><a class="text dropdowntext darkdropdown">HOVERABLE</a><i class="dropdownicon fa fa-sort-desc"></i></button>
    <div class="button dropdown-content">
        <a href="#">Option 1</a>
        <a href="#">Option 2</a>
        <a href="#">Option 3</a>
    </div>
</div>
```
### Radio Buttons
##### Gray
```html
<div class="radiodiv">
    <label class="container">ONE
                    <input type="radio" checked="checked" name="radio">
                    <span class="checkmark"></span>
                </label>
    <label class="container">TWO
                    <input type="radio" name="radio">
                    <span class="checkmark"></span>
                </label>
</div>
```
##### Green
```html
<div class="radiodiv">
    <label class="container green">ONE
                    <input type="radio" checked="checked" name="radiogreen">
                    <span class="checkmark checkmarkgreen"></span>
                </label>
    <label class="container green">TWO
                    <input type="radio" name="radiogreen">
                    <span class="checkmark checkmarkgreen"></span>
                </label>
</div>
```
### Text Inputs
##### Non-hoverable
```html
<input class="textinput" type="text" name="Input" id="Input" placeholder="INPUT">
```
##### Hoverable
```html
<input class="textinput hoverable" type="text" name="Input" id="Input" placeholder="HOVERABLE INPUT">
```
### Popup
```html
<div class="popup">
    <h3 class="text popuptext">THIS IS A POPUP</h3>
    <div class="popupbuttondiv">
        <a class="button popupbutton left hoverable" href="#">YES</a>
        <a class="button popupbutton right hoverable" href="#">NO</a>
    </div>
</div>
```