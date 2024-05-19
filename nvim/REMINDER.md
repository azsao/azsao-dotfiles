remember that u need to install npm & nodejs both locally & through mason by pressing ``I``
^ this is needed for none-ls

paste these commands to make it easier 4 you:

mkdir -p ~/.npm-global
npm config set prefix '~/.npm-global'
export PATH=~/.npm-global/bin:$PATH
cd ~/.npm-global
source ~/.bashrc (or ~/.zshrc)
npm install -g eslint_d


*will add more if the plugins begin to update & screw stuff up*
