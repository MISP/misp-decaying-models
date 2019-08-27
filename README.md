# MISP Decaying Models

Starting from MISP 2.4.114, a decaying feature is available to apply decaying on attributes in your MISP instance. MISP comes with a set of default decaying models which
can be customised by the users. This repository contains all the default models.

## Models

- [nids-simple-model](./models/nids-simple-model.json) - Simple decaying model for Network Intrusion Detection System (NIDS).
- [phishing-model](./models/phishing-model.json) - Simple model to rapidly decay phishing website.

## How to contribute your decaying model?

It's very easy. Fork the repository, create a new JSON file with your model and make a pull-request.

## License

The MISP decaying models are [dual-licensed](./LICENSE.md) under CC-0 and a simple 2-clause BSD license.
