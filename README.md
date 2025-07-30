# soundness-codes

discord link: https://discord.gg/JYFZWwKG9p

Run each command **one by one**:  

```sh
sudo apt update && sudo apt upgrade -y
```

```sh
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```

```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
```

```sh
source ~/.bashrc
```

```sh
soundnessup install
```

```sh
soundnessup update
```

you need to import your old wallet by import mnemonic seed phrase 
If you saved your mnemonic previously, you can import it to key_store.json by using following command:
```sh
soundness-cli import-key --name my-key --mnemonic "<your‑mnemonic‑words>"

```
if you lost old  mnemonic seed phrase then can create new and replace in discord soundness-cockpit channel
```
soundness-cli generate-key --name my-key

```
you can export your key 
```
soundness-cli export-key --name my-key

```


If it was successful you'll get:

✅ Imported key pair 'my-key'
🔑 Public key:


To view all stored key pairs:
```sh
soundness-cli list-keys

```
