# Versotile

Versotile is an umbrella organisation that hosts open source projects, namely the [Verso browser](https://github.com/versotile-org/verso), the [Fortress](https://github.com/versotile-org/fortress) project, a secure enclave for sensitive data, and soon other exciting projects around a free and open source web.

## [Verso](https://github.com/versotile-org/verso)

A web browser that plays old world blues to build new world hope.

![](https://github.com/pewsheen/verso/assets/460329/7df44c7d-a4c5-4393-8378-a8b7bc438b03)

Verso is a web browser built on top of Servo web engine. It's still under development. We dont' accept any feature request at the moment.
But if you are interested, feel free to help test it.

## [Fortress](https://github.com/versotile-org/fortress)

At a time when cyber threats are rampant and data breaches can have catastrophic consequences,
the focus on robust software security has never been more important.
The need to protect private data is not just a compliance issue, but a fundamental aspect of digital trust.
This application proposes to develop a modular security component library.

**FORTRESS** is a software enclave similar to hardware keys such as yubikey and similar products.
The main idea is to store sensitive data that is not directly accessible to the user. Rather,
any cryptographic operation required, such as signing, encrypting, decrypting, etc.,
takes place inside a so-called vault: a fraction of the system memory that remains highly guarded
and encrypted with the latest state-of-the-art encryption, preferably `xchacha20-poly1305`.

The goal of this project is to build a lightweight system for the secure storage of e.g. identity data.
In this context, we assume that identity data is implemented using public key cryptography such as `DID`.

## Communications

- Zulip: We are reachable at our [![project chat](https://img.shields.io/badge/zulip-57a7ff?style=for-the-badge&labelColor=555555&logo=zulip)](https://versotile.zulipchat.com/)
- Contributions: We are happy for any contributions! Please check the `CONTRIBTUTING.md` for each project.
