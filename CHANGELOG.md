# Changelog

## 2.1.1

- Update SSL/TLS certificates into Docker image

## 2.1.0

- Authorize encryption of already encrypted volumes (key migration)

## 2.0.3

- Adding a security check on KMS alias

## 2.0.2

- Adding option for choosing to restart or not an instance after encryption
- Code refactoring

## 2.0.1

- Fixing code typos
- Fixing KMS bug (given KMS key wasn't used only default AWS KMS key)

## 2.0.0

- Refactoring this projet from Python to Golang. Why ? Just for fun & rampup for me on Golang language.

## 1.2.3

- Again fixing a problem with AWS tags

## 1.2.2

- Fixing a problem with AWS tags (can't copy AWS tags) 

## 1.1.1

- Fixing a problem with BOTO waiters (adding a maximum retry value) 

## 1.1.0

- Upgrade Boto modules
- Changing old-style Python strings to new Python 3.6 fstrings
- Simplifying encryption algorithm (since AWS let create encrypted volume from snapshot directly)
- Fixing a bug on IO1 volume encryption
