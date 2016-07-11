# Fabricator Forms and Buttons Styling

While this component is designed with the [BuzzingPixel Fabricator Build Process](https://github.com/tjdraper/buzzing-pixel-fabricator) in mind, it can be used anywhere (in theory).

Variables available in this file you can override:

```
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

@coloredButtonBackground: #40EEFF;
@coloredButtonBackgroundHover: darken(@coloredButtonBackground, 5%);
@coloredButtonBackgroundActive: darken(@coloredButtonBackground, 10%);
@coloredButtonColor: false;
@coloredButtonBorderColor: false;

@disabledButtonBackground: lighten(#000, 75%);
@disabledButtonColor: lighten(#000, 45%);
@disabledButtonCursor: not-allowed;
```