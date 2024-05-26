# Sobre esse repositóio

Esse repositório consiste em um repo onde irei guardar meus dotfiles, sinta-se livre para usa-los como bem entender

## Como usar

Esse repositório gira em torno da ferramenta __GNU STOW__, onde podemos criar symlinks, onde podemos apontar para a localização desejada dos nossos arquivos baseado no filesystem desse repositório

### Instalação do GNU STOW

Linux

```shell
sudo apt install stow -y
```

Aqui você pode usar o repositório da sua distro favorita, no meu caso estou usando apt pois eu uso debian based distros


Mac
```shell
brew install stow
```

Use esse comando utilizando o package manager __brew__ caso você use o MacOS

### Finalmente

Basta você usar o comando

```shell
stow .
```

assim, você automaticamente criará __symlinks__ de forma baseada no filesystem desse repositório no seu sistema