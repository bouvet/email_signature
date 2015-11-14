# Bouvet Email Signature

Clone or copy the code. The `signature inline logo.html` file seems to work
nicely on most email clients, but not on Outlook. For that you can use the
`signature.html` file; it simply links to the
logo file that is at http://home.bouvet.no/bouvet/logo.gif.

Make sure that you edit all the `{TOKENS-IN-BRACKETS}` with the appropriate
values. Don't forget the ones that are HTML in attributes, e.g. URLs.

You'll also want to amend the address and phone number to your own office. Keep the non-breaking-space characters (`&nbsp;`) between words, which prevent email clients from screwing up the layout.

For the `{GOOGLE-MAPS-MARKER-COORDINATES}` token, do this:

1. On Google Maps, search for your own coordinates, e.g. `54°26′55″S 3°20′20″E`
2. You'll get a result that will include, as part of the URL, a string like
   this: `…/@-54.448608,3.3366949,17z/…`
3. Take **just the two numbers** from the string above (e.g. `-54.448608,3.3366949`)
4. Replace the token with those numbers.

(Yeah I know; there's a way to convert minutes and seconds to decimal degrees…)

## Email client setup

### OS X Apple Mail

http://matt.coneybeare.me/how-to-make-an-html-signature-in-apple-mail-for-el-capitan-os-x-10-dot-11/

### Microsoft Outlook

https://support.office.com/en-us/article/Add-a-signature-to-messages-8ee5d4f4-68fd-464a-a1c1-0e1c80bb27f2

### Mozilla Thunderbird

https://support.mozilla.org/no/kb/signatures

Pull requests welcome!
