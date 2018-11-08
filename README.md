# Hybrid Social App


Hybrid Social App includes authenication, google map api,live chat, profile setting,.... 

One of the big advances in Ionic was moving from a rigid route-based navigation
system to a flexible push/pop navigation system modeled off common native SDKs.
We've embraced this pattern to provide a set of reusable pages that can be
navigated to anywhere in the app. Take a look at the [Settings
page](https://github.com/ionic-team/starters/blob/master/ionic-angular/official/super/src/pages/settings/settings.html)
for a cool example of a page navigating to itself to provide a different UI
without duplicating code.

## How to Install
git clone project git url
npm install
ionic serve

### Adding Languages

To add new languages, add new files to the `src/assets/i18n` directory,
following the pattern of LANGCODE.json where LANGCODE is the language/locale
code (ex: en/gb/de/es/etc.).

### Changing the Language

To change the language of the app, edit `src/app/app.component.ts` and modify
`translate.use('en')` to use the LANGCODE from `src/assets/i18n/`
