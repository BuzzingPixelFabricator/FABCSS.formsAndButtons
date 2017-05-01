# Fabricator Forms and Buttons Styling

While this component is designed with the [BuzzingPixel Fabricator Build Process](https://github.com/tjdraper/buzzing-pixel-fabricator) in mind, it can be used anywhere (in theory).

## Installing

With Fabricator and NPM, simply require this library into your project and restart the Fabricator Grunt build process.

`npm install fabcss.forms-and-buttons --save`

If you are not using Fabricator, you will need to include into your Less build `src/FABCSS.formsAndButtons.less`.

## Usage

Variables available in this file you can override:

```
@inputOutline: 'no-change';
@inputBackground: #fff;
@inputBackgroundDisabled: lighten(#000, 96%);
@inputColor: lighten(#000, 35%);
@inputColorDisabled: lighten(#000, 45%);
@inputPlaceholderColor: lighten(@inputColor, 40%);
@inputFont: false;
@inputFontSize: false;
@inputBorderColor: lighten(#000, 90%);
@inputBorderColorHover: darken(@inputBorderColor, 10%);
@inputBorderColorFocus: darken(@inputBorderColor, 20%);
@inputBorderWidth: 1px;
@inputRounded: 0;
@inputPaddingHorizontal: 16px;
@inputPaddingVertical: 10px;
@inputMarginBottom: 20px;
@inputCursorDisabled: not-allowed;

@textareaLineHeight: 1.3em;
@textareaMinHeight: 80px;
@textareaPaddingHorizontal: 16px;
@textareaPaddingVertical: 10px;
@textareaResize: vertical; // none, horizontal, vertical, both

@labelFontSize: false;
@labelColor: lighten(#000, 30%);
@labelFontStyle: italic;
@labelFontWeight: normal;
@labelLineHeight: 1.3em;
@labelMarginBottom: 4px;
@labelMarginRight: 10px;

@buttonColor: #fff;
@buttonBackground: lighten(#000, 45%);
@buttonBackgroundHover: darken(@buttonBackground, 5%);
@buttonBackgroundActive: darken(@buttonBackground, 10%);
@buttonBorderColor: false;
@buttonFont: false;
@buttonFontSize: false;
@buttonFontWeight: normal;
@buttonMarginBottom: false;
@buttonPaddingHorizontal: 30px;
@buttonPaddingVertical: 13px;
@buttonRounded: 3px;
@buttonOutlinedBorderWidth: 1px;

@lightButtonColor: #000;
@lightButtonBackground: #fff;
@lightButtonBackgroundHover: darken(@lightButtonBackground, 10%);
@lightButtonBorderColor: false;
@lightButtonBorderColorHover: false;

@coloredButtonBackground: #40EEFF;
@coloredButtonBackgroundHover: darken(@coloredButtonBackground, 5%);
@coloredButtonBackgroundActive: darken(@coloredButtonBackground, 10%);
@coloredButtonColor: false;
@coloredButtonBorderColor: false;

@disabledButtonBackground: lighten(#000, 75%);
@disabledButtonColor: lighten(#000, 45%);
@disabledButtonCursor: not-allowed;
```

## License

Copyright 2017 TJ Draper, BuzzingPixel, LLC

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
