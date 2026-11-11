<p align="center">
  <a href="https://contashare.com"><img src="https://contashare.com/images/contashare-avatar.png" width="120" alt="ContaShare"></a>
</p>

<h1 align="center">ContaShare</h1>

<p align="center">Keep your contact details in one place, and choose which companies can see them.</p>

[ContaShare](https://contashare.com) lets people store their address, phone number, name, email and date of birth once, and
decide which companies may read each one. When someone moves or changes their number, they update it once, and every company
they still share it with gets a webhook and fetches the new version through the API.

- **For people:** free. Share only what you tick, and stop sharing any detail at any time.
- **For companies:** "Sign in with ContaShare" (OAuth 2.0), a REST API and signed webhooks. Pay for API calls with prepaid
  credits, with no subscription.

## Packages

| Package | For | Install |
| --- | --- | --- |
| [contashare-socialite](https://github.com/contashare/contashare-socialite) | Laravel (Socialite driver) | [`composer require contashare/socialite`](https://packagist.org/packages/contashare/socialite) |
| [contashare-node](https://github.com/contashare/contashare-node) | Node.js 18+ | [`npm install contashare`](https://www.npmjs.com/package/contashare) |
| [contashare-python](https://github.com/contashare/contashare-python) | Python 3.9+ | `pip install git+https://github.com/contashare/contashare-python` |

Each one signs customers in, reads what they share, and checks webhook signatures. The Python package is on its way to PyPI;
until then, install it from its repo.

## Docs

- [OAuth integration guide](https://contashare.com/help/oauth)
- [Webhooks guide](https://contashare.com/help/webhooks)
- [API reference](https://contashare.com/docs/api)
- [Guide for AI coding assistants](https://contashare.com/llms-full.txt)
