# Go-Getter
### Stock Market Stats To Look Out For!

## Introduction
A free, lightweight, blazing-fast and dynamically updating page to get stock quotes using the [IEX Cloud][iexc]. Stocks can be grouped into user-defined portfolios. Quotes update every 15 Minutes.

## User Story
Not everyone is investor savvy. Use this app to help you find the latest trends in the stock markets and find the best companies to place your limited investment funds into.

## A Simple Mock-Up Made With [Pencil][pencil]
![Screenshot MockUp][ssmu]

## The [Picnic CSS][picnicss] Framework

For CSS we've decided to use Picnic CSS as it is super light weight, gets out of the way and makes for a stuningly beautiful, yet simple website.

## We use both vanilla [JavaScript][javascript] and [jQuery][jquery].

For added functionality we are using both vanilla JavaScript and some jQuery to keep our codebase light and efficent.

## Team Roles
 - Front-End (HTML/CSS Focused)
   - Alexander Marzullo (@Amarz94)
   - Drew Bridgman (@dbridgman1) 
   - Michael Conway (@Mconway409)
   - David Rodriguez (@davidsaulrodriguez)*
 - Backend (JavaScript & jQuery Focused)
   - David Rodriguez (@davidsaulrodriguez)

\* Interim role and only step in when support is needed.

## Why aren't the market indices available? (S&P 500, DJIA, NASDAQ)

The IEX API only provides free data for stocks, not indices, so the closest thing is to use ETFs that track the major indices. See here for context: https://github.com/iexg/IEX-API/issues/36. Suggested index ETFs:

- S&P 500: `SPY`
- Dow Jones: `DIA`
- NASDAQ: `QQQ`
- Russell 2000: `IWM`

## Browser compatibility

The page uses the [Fetch API][fetch-mdn], which means it does not work with Internet Explorer.

## Bugs and Issues
Found a bug? Review any [open issues][open-issues] or create a [new issues here][new-issue] so we can fix it for you!

## License
This project and all of its source code is released and permissively licensed under the [BSD 2 Clause][license] license.

[javascript]: https://www.javascript.com/
[jquery]: https://jquery.com/
[picnicss]: http://picnicss.com/
[pencil]: http://pencil.evolus.vn/
[ssmu]: screenshots/homepage_mockup.png
[iexc]: https://iexcloud.io/
[fetch-mdn]: https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API
[open-issues]: https://github.com/davidsaulrodriguez/go-getter/issues/
[new-issue]: https://github.com/davidsaulrodriguez/go-getter/issues/new
[license]: LICENSE.md