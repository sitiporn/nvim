## On Container of Remote Server

### Update nodejs  

### Update Neovim

- To fix ‘add-apt-repository command not found’

```bash
apt-get install software-properties-common
```

- To update neovim
```bash
add-apt-repository ppa:neovim-ppa/stable 
apt-get update
apt-get install neovim
```

- To update Nodejs
```bash
npm cache clean -f
npm install -g n
n stable
```

*remark - if run on local just add sudo at the the front of command 
