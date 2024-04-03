```sh
ssh-keygen -t ed25519 -C "your_email@datawaybr.com"
eval "$(ssh-agent -s)"
cat ~/.ssh/id_ed25519.pub
```