# Set-DNS

```
cat <<EOF | sudo tee /etc/resolv.conf
nameserver 1.1.1.1
nameserver 8.8.8.8
nameserver 8.8.4.4
EOF
```