## On Container of Remote Server

## To begin 

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
- To install nodejs and npm
```bash
apt-get install nodejs 
apt-get install npm
```

- To update Nodejs
```bash
npm cache clean -f
npm install -g n
n stable
```

### Config

- in .bashrc

```bash
alias vim ='nvim'
export EDITOR = 'nvim'
```
- config in init.vim 

- create nvim folder 
- create init.vim inside nvim folder
- create autoload folder
- install stuff 


curl https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

" create plug.vim
curl https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim -o plug.vim

"check source code 
less plug.vim

5. Go to init.vim








*remark - if run on local just add sudo at the the front of command 
