## First we should create ssh-key

# ssh-keygen -t ed25519 -C "your-email"

# USE PARAPHRASE WHEN IT ASKS

## Then we should activate ssh.agent.service with command:

# exec ssh-agent fish

## Then we add our generated key

# ssh-add "location-of-ssh-key"

## Then we open "Settings" in Github and add ssh key (you can do it without help, sorry)
## Then in "Description" we add ssh-key public part data

## Ready!
