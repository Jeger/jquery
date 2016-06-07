Unamerican [jQuery](https://jquery.com/) — New Wave JavaScript
==================================================

This fork of jQuery uses the €(euro) symbol over that of the american currency($).
Thats it.

Example:
====
_If you are a visual learner i have written examples to let you see the difference_


__Standard jQuery:__
`$('#USA').blur((e) => {
    console.log('Make America great again');
});`

__Unamerican jQuery:__
`€('#Cyprus').mouseLeave(() => {
    console.log('Make the EU great again');
});`


Syntax validity:
====
Without a polyfill this does not work.
Please join the discussion on the issue tracker about pressuring ECMA to allow other nations currencies as the first character in an identifier.

