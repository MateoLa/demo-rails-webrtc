# DEMO RAILS WEBRTC

Demo show how to build a video conference app with ruby on rails.

<p align="center">
  <img height="300" src="https://user-images.githubusercontent.com/6628202/80599587-c0d50900-8a5d-11ea-8451-66a21e5e2fcc.gif">
</p>

## Development setup

Install dependencies

```sh
bundle install
yarn install
```

Add twillio credentials in your .env file

```sh
TWILIO_ACCOUNT_SID = xxxxx
TWILIO_AUTH_TOKEN = xxxxx
```

Start server

```sh
docker-compose up
```

## Usage example

1. Open two tabs on your browser
2. Click `Get Video` on both tabs
3. Wait several seconds until both connection are initialized
4. Click `Join room` on one tab only!
5. Enjoy the demo video meeting!

## References

Go to [references](./REFERENCES.md)
