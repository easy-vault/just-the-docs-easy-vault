---
layout: default
title: Home
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

# Inject secrets directly into containers .
{: .fs-9 }

Easy vault is an agent which fetch secrets from KMS vaults and inject those secrets into Docker Container
{: .fs-6 .fw-300 }

[Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } 

---

**New: version `{: .version}` has just been released! See [the Image](https://github.com/orgs/easy-vault/packages/container/package/easy-vault) for a detailed breakdown!**

## Getting started

### Dependencies

Just the Docs is built for [EasyVault](https://github.com/easy-vault), a secret vault injector. View the [Secrets  into Spring boot Example](https://github.com/easy-vault/easy-vault-example) for more information. 
EasyVault provides a docker image which can be used in any custom docker image ([refer](https://github.com/easy-vault/easy-vault-example/blob/master/Dockerfile)) using `FROM` keyword .
Primary responsibility of Easy-vault is to fetch secrets from KMS Vault and expose those secrets into containers environment variable. 