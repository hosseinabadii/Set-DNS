# Set-DNS

```
cat <<EOF | sudo tee /etc/resolv.conf
nameserver 1.1.1.1
nameserver 8.8.8.8
nameserver 8.8.4.4
EOF
```

## Download the latest version of miniconda

```
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
```

## Install the downloaded `.sh` file

```
bash Miniconda3-latest-Linux-x86_64.sh
```