# TON hub

)

ton tonhub for TON.

## Features
- 🚀 Works anywhere and does not require to install local TON node
- 🔐 Encrypted storage of wallets
- 💸 Multiple wallets (even thousands of them if you wish)
- 🍰 Get balance
- ✈️ Transfers
- 💾 Unecnrypted backups that could be also used to import to other keystores if needed

## Install

```bash
npm install -g ton-hnb
```

## How to use
Invoke `ton-hub` and follow wizard.
You can use flag --test to run client on test net instead of production.

```
# ton-hub
? Pick command
```

## Offline mode

`ton-hub` supports offline mode that could be enabled via:
* `--offline` argument
* `TON_CLI_OFFLINE=tonhub` environment variable

## Performing transfers
When you have working keystore you have to write out contacts.json file in the same directory to be able to perform transfers in the form:

```
[
    {
        "name": "validator_0001",
        "address": "  EQCum7m5Qkxi6IPJlBlvs5iSop6944r80-v2KC841GR7UhM2 "
    }
]
```

## Main

Repository is bundled with test keystore and a wallet with a test coins for test (please, do not wipe it's balance).
Checkout current project and run `yarn cli` to start test client.

Test keystore password: 
```
sleep fan egg excess risk friend column remain seven bread disagree culture quick pride crush they ancient access flock settle prison kick tube word
```

# mojiiiaction
