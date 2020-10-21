# EIPs [![Discord](https://img.shields.io/discord/758045775493333042.svg?color=768AD4&label=discord&logo=https%3A%2F%2Fdiscordapp.com%2Fassets%2F8c9701b98ad4372b58f13fd9f65f966e.svg)](https://discord.com/channels/758045775493333042/) 
<!-- [![Telegram](https://img.shields.io/badge/chat-on%20Telegram-blue.svg)](https://t.me/earnbasefinance) [![Twitter Follow](https://img.shields.io/twitter/follow/earnbasefinance.svg?label=earnbasefinance&style=social)](https://twitter.com/earnbasefinance) -->

Earnbase Improvement Proposals (EIPs) describe standards for the Earnbase platform, including core protocol specifications, client APIs, and contract standards.

## Contributing

 1. Review [EIP-0](EIPS/EIP-0.md).
 2. Fork the repository by clicking "Fork" in the top right.
 3. Add your EIP to your fork of the repository. There is a [template EIP here](EIP-X.md).
 4. Submit a Pull Request to Earnbase's [EIPs repository](https://github.com/earnbasefinance/EIPS/).

Your first PR should be a first draft of the final EIP. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new EIP and assign it a number before merging it. Make sure you include a `discussions-to` header with the URL to a new thread on [gov.earnbase.org](https://gov.earnbase.org/) where people can discuss the EIP as a whole.

If your EIP requires images, the image files should be included in a subdirectory of the `assets` folder for that EIP as follow: `assets/EIP-X` (for EIP **X**). When linking to an image in the EIP, use relative links such as `../assets/EIP-X/image.png`.

When you believe your EIP is mature and ready to progress past the WIP phase, you should ask to have your issue added to the next governance call where it can be discussed for inclusion in a future platform upgrade. If the community agrees to include it, the EIP editors will update the state of your EIP to 'Approved'.

## EIP Statuses

* **WIP** - a EIP that is still being developed.
* **Proposed** - a EIP that is ready to be reviewed in a governance call.
* **Approved** - a EIP that has been accepted for implementation by the Earnbase community.
* **Implemented** - a EIP that has been released to mainnet.
* **Rejected** - a EIP that has been rejected.
* **Withdrawn** - a EIP that has been withdrawn by the author(s).
* **Deferred** - a EIP that is pending another EIP/some other change that should be bundled with it together.
* **Moribund** - a EIP that was implemented but is now obsolete and requires no explicit replacement.

## Validation

EIPs must pass some validation tests.  The EIP repository ensures this by running tests using [html-proofer](https://rubygems.org/gems/html-proofer) and [YIP_validator](https://rubygems.org/gems/YIP_validator).

It is possible to run the YIP validator locally:
```
gem install YIP_validator
YIP_validator <INPUT_FILES>
```

## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).