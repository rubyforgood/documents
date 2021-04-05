# Authentication

## [Google Firebase Authentication](https://firebase.google.com/docs/auth)

To avoid hassle of storing and managing user credentials, authentications and related UX and UI
we recommend [Google Firebase Authentication](https://firebase.google.com/docs/auth) (in future GFA)

What it gives your project:
- UI for all major platforms and/or frameworks (web, ios, andriod)
- Customizable UI or manual/custom UI if you'd like
- UX for password reset
- UX for MFA
- UX for merging authentications using federated identities (i.e. Email/Passowrd, passwordless Email, passwordless Phone number, Google, Facebook, Apple, and many more)
- Email/Push/SMS/etc. messaging done for you (included in UX flows above)
- Storage for accounts
- JWT and a taste of OAuth2+ token culture

Everything above is provided by major vendor, well tested and considered trusted platform.

### [Usage Limits](https://firebase.google.com/docs/auth/limits) 

Please, be aware of [Usage Limits](https://firebase.google.com/docs/auth/limits) which do not seem limiting any of RfG projects

## Logical Limits

- GFA does **not** provide any means of Authorization or Account storage.
- You will need to have "users table" in you project's storage and manage authorization anything account settings related.
- You **should not** use provided `uid` as a key between entities in project's storage, use it for "users table" identification only

## TODO

### Enablement

POC of custom backed validation token, using [reference docs](https://firebase.google.com/docs/auth/admin/verify-id-tokens) and very generic [jwt gem](https://github.com/jwt/ruby-jwt)
to simplify project's adoption
