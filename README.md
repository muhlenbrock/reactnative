# Tutorial react-native, Ubuntu
### Configurando ambiente de desarrollo Ubuntu 20.04

## Instalando [Node.js](https://nodejs.org/).

  - Primero abriremos la terminal e instalaremos nvm.

```sh
# install nvm (Node Version Manager)
$ wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
```
  - Luego reiniciamos la terminal e instalamos node.

```sh
$ nvm install --lts
```
  - Podemos comprobar la versión.

```sh
$ node --version
```
## Instalando Java Development Kit (JDK)

```sh
$ sudo apt install -y openjdk-8-jdk-headless openjdk-8-jre
```

## Instalando [Homebrew](https://docs.brew.sh/Homebrew-on-Linux) en Ubuntu
```sh
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

## Instalando Watchman
```sh
brew install --HEAD watchman
```
## Instalando [Android Studio](https://developer.android.com/studio)
