# MailFaker.js for JavaScript
<p align="center">
  <img src="logo.jpg">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-orange">
  <img src="https://img.shields.io/badge/Platform-JavaScript%20(es5)-orange">
  <img src="https://img.shields.io/badge/Node.js-Any-orange">
  <img src="https://img.shields.io/badge/No%20Dependencies-orange">
</p>

## Installation
Simply include the `mailfaker.js` file in your project or via a `<script>` tag in the browser.

```html
 <script src="mailfaker.js"></script>
```

## Usage

```javascript
// Browser
var mailFaker = new MailFaker();

// Generate random names and emails
mailFaker.firstName();      // => A random first name
mailFaker.lastName();      // => A random last name
mailFaker.fullName();      // => A random full name
mailFaker.localPart();      // => A random local-part of an email
mailFaker.domainPart();    // => A random domain part
mailFaker.fullAddress();     // => A random email address`
```

## Examples

The following code examples provide an overview of what MailFaker.js can do.

_Initialize MailFaker_

```javascript
 var mailFaker = new MailFaker();
// => Uses current browser language (if supported)

var faker = new MailFaker('fr');
// => Explicitly sets the language to "fr"

// Fallback is "en" if the provided language is not supported
```

_Generate first names_

```javascript
mailFaker.firstName('female');   // e.g. Manuela
mailFaker.firstName('male');    // e.g. Benedikt
mailFaker.firstName();          // e.g. Peter

// mailFaker.firstName() is the same as mailFaker.firstName('random')
```

_Generate last names__

```javascript
mailFaker.lastName();   // e.g. Müller
```

_Generate full names_

```javascript
mailFaker.fullName('female');   // e.g. Lisa Müller
mailFaker.fullName('male');     // e.g. Markus Urban
mailFaker.fullName();          // e.g. Sabine Meier

// mailFaker.fullName() is the same as mailFaker.fullName('random')
```

_Generate local parts_

```javascript
mailFaker.localPart('female');    // e.g. reitze_anabel-3377
mailFaker.localPart('male');     // e.g. danneberg.mark_1823
mailFaker.localPart();          // e.g. 3714.patrick-gabius

// mailFaker.localPart() is the same as mailFaker.localPart('random')
```

_Generate domain parts_

```javascript
mailFaker.domainPart();   // e.g. dolor.fr
```

_Generate full email addresses_

```javascript
mailFaker.fullAddress('female');    // e.g. 9792.krippner-nisa@lorem.de
mailFaker.fullAddress('male');     // e.g. tiago_dies-8420@molestiae.americanexpress
mailFaker.fullAddress();          // e.g. 2245.schirmer-michaela@dicta.net

// mailFaker.fullAddress() is the same as mailFaker.fullAddress('random')
```
## Author

[Stephan Ferraro](https://github.com/ferraro) – Aionda GmbH

## License

MailFaker.js is licensed under the MIT License. See [LICENSE.md](LICENSE.md) for more info.
The logo was created using artificial intelligence with MidJourney and is available here: https://www.midjourney.com/jobs/57f3eae8-a2d5-4c59-b131-94b64336c4ac 
