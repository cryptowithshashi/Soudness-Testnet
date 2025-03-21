
# SOUNDNESS TESTNET REGISTRATION FULL GUIDE

Soundness Labs is a Web3 infrastructure project focused on advancing zero-knowledge proof (ZKP) technology to create a scalable, decentralized, and efficient verification layer for blockchain ecosystems.
![Image](https://github.com/user-attachments/assets/e9ced0ad-c3b2-467b-87af-92af607eddc6)



## STEPS TO REGISTER SOUNDESS TESTNET

 - Head to the website -- [CLICK HERE](https://soundness.xyz)
 - Sign up with your email
 - Generate public key and phrase using the code below
 - You can run the code on github codespace
 - Copy the public key and head to discord channel
 - Go to testnet access server and enter your public key
 - Join discord server -- [CLICK HERE](https://discord.gg/CY4BgwsF)
 - For video guide check out our telegram channel -- [CLICK HERE](https://t.me/crypto_with_shashi)
 


## INSTALLATION PROCESS

Update and Upgrade System

```bash
  sudo apt update && sudo apt upgrade -y
```
Install Rust (rustup)
```bash
  curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

```
Load Rust Environment Variables
```bash
  source $HOME/.cargo/env
```
Verify Rust and Cargo Versions
```bash
  rustc --version
  cargo --version
```
Persist Rust Environment Variables in Bash
```bash
  echo 'source $HOME/.cargo/env' >> ~/.bashrc
```
Refresh Bash Environment
```bash
  source ~/.bashrc
```
Install Soundnessup
```bash
  curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```
Refresh Bash Environment Again
```bash
  source ~/.bashrc
```
Install and Update Soundnessup
```bash
  soundnessup install
  soundnessup update
```
Generate Your Key
```bash
  soundness-cli generate-key --name my-key
```
## CONCLUSION

You're all set! You've successfully set up your environment and generated your key for the testnet. If you encounter any issues or have questions, please feel free to reach out on our Discord channel.

- Our Telegram channel -- [CLICK HERE](https://t.me/crypto_with_shashi)
