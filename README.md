# Nexus-Prover
![image](https://github.com/user-attachments/assets/cc2288ab-958c-4c0c-ac81-9daa116318df)

[Nexus raises $25M in Series A funding to bring zero-knowledge proofs to Internet scale.](https://blog.nexus.xyz/series-a/)

## Install dependencies
```console
sudo apt update && sudo apt upgrade -y
```
```console
# Install packages
sudo apt install curl iptables screen build-essential git wget lz4 jq make gcc nano automake autoconf tmux htop nvme-cli pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev protobuf-compiler  -y
```
```console
# Install Rust
sudo curl https://sh.rustup.rs -sSf | sh
```
```console
# Add Rust to path
source $HOME/.cargo/env
export PATH="$HOME/.cargo/bin:$PATH"
```
```console
rustup update

rustc --version
```
## Run prover
```console
screen -S nexus
```
```console
sudo curl https://cli.nexus.xyz/install.sh | sh
```
* You'll be asked to accept the terms and conditions. Press y and enter.
* The next step is to provide your prover-id. Go to [nexus](beta.nexus.xyz) and click on profile then add and verify email.
* Copy the prover-id once you've verfied your email and paste in the terminal (make sure you save your prover-id).
## Note
* `ctrl A + D` to detach from screen
* `screen -r nexus` to reattach to screen
* Your prover-id will be saved to `/root/.nexus` you can view with `cat /root/.nexus/prover-id`

