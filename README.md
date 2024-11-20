## Paypal Standard demo Microfrontend
### fastapi and vanilla javascript for custom element

TLDR;

1. Sign up for a paypal developer account
2. Create a sandbox app and get your client id and client secret
3. Put client id and client secret in a .env file in the same folder as the README.md file

```
PAYPAL_CLIENT_ID=<from developer account>
PAYPAL_CLIENT_SECRET=<from developer account>
```

When you have the .env file correct, you can start the app and surf to the provided url and see the markdown file with the code in it.

```bash
pip install -r requirements.txt
fastapi dev app.py
```

You can see microfrontend docs by adding markdown files and refering to them in the `index.html`. You can see api docs by surfing to `/docs`. This is my response to Martin Fowler's [excellent article about micro frontends](https://martinfowler.com/articles/micro-frontends.html). You will notice that this article is from 2019. Unfortunately the promise of microfrontends and continuous delivery by autonomous teams still seems a little underdeveloped. I would like to develop it a little more!
