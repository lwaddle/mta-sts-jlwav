# MTA-STS Policy for jlwav.com

This repository hosts the MTA-STS (Mail Transfer Agent Strict Transport Security) policy file for the domain `jlwav.com`.

## Purpose

MTA-STS improves email security by requiring sending mail servers to:
- Use STARTTLS to encrypt messages in transit
- Only deliver mail to authorized MX hosts for this domain

## Hosted URL

The policy is served at: https://mta-sts.jlwav.com/.well-known/mta-sts.txt

## MX Host

mx: jlwav-com.mail.protection.outlook.com

## Mode

Currently set to `testing`. Will move to `enforce` after validation.

## Resources

- [RFC 8461 - SMTP MTA Strict Transport Security (MTA-STS)](https://tools.ietf.org/html/rfc8461)
- [Cloudflare Pages](https://pages.cloudflare.com/)
