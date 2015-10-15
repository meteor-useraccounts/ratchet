[![Meteor Icon](http://icon.meteor.com/package/useraccounts:ratchet)](https://atmospherejs.com/useraccounts/ratchet)
[![Build Status](https://travis-ci.org/meteor-useraccounts/ratchet.svg?branch=master)](https://travis-ci.org/meteor-useraccounts/ratchet)

useraccounts:ratchet
========================

Meteor sign up and sign in templates styled for Ratchet

This package depends on [useraccounts:core](https://atmospherejs.com/useraccounts/core)

Learn more [here](http://useraccounts.meteor.com) or have a look at the full [documentation](https://github.com/meteor-useraccounts/core).


**Note:** At the moment Ratchet does not support form validation.
So it is mandatory to configure UserAccounts with, at least,

```javascript
AccountsTemplates.configure({
    negativeValidation: false,
    negativeFeedback: false,
    positiveValidation: false,
    positiveFeedback: false,
});
```

## Bring Your Own Ratchet

Adding this package with `meteor add useraccounts:ratchet` does not add any other packages providing Ratchet. This is to let you choose the flavour you prefer, being it compiled, less, sass, or from CDN!

At the moment it is up to date with Ratchet 2.0.2.


## Contributing

Anyone is welcome to contribute. Fork, make your changes, and then submit a pull request.

Thanks to all those who have contributed code changes to [this package](https://github.com/meteor-useraccounts/ratchet/graphs/contributors) as well as to the [core package](https://github.com/meteor-useraccounts/core/graphs/contributors) and all who have helped by submitting bug reports and feature ideas.
