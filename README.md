# soundness-codes


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

```sh
soundness-cli generate-key --name my-key
```

```sh
soundness-cli export-key --name my-key
```
If you saved your mnemonic previously, you can import it to key_store.json by using following command:
```sh
soundness-cli import-key --name my-key --mnemonic "<your‑mnemonic‑words>"

```
If it was successful you'll get:
```sh
✅ Imported key pair '<imported-key-name>'
🔑 Public key: <base64-encoded-public-key>

```
To view all stored key pairs:
```sh
soundness-cli list-keys

```
