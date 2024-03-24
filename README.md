# complete-workflow is just a project to test my workflow as a whole. Here you will find:

- [ ] Git
  - [ ] Set up SSH key
- [ ] Laravel 
- [ ] React 
- [ ] docker
- [ ] CI-CD
- [ ] Unitary and feature tests
- [ ] Design patterns
- [ ] Scripts
- [ ] Stress Tests
- [ ] Backups
- [ ] DB Configs
- [ ] External Services (maybe)
- [ ] LunarVim Configs
- [ ] AWS Config

## Project set up
### Generate SSH key for github repository
```bash
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
eval "$(ssh-agent -s)" && ssh-add ~/.ssh/id_rsa
cat ~/.ssh/id_rsa.pub
```
Paste the copied key into the "Key" field in GitHub settings and then run the command:
```bash
ssh -T git@github.com
```
### Generate SSH key for github repository
