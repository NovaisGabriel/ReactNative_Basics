# reactNative_basics
1. Instalar Java

============================================================

sudo apt update

sudo apt install default-jdk

============================================================



2. Instalar Node & NPM

============================================================

sudo apt-get update

sudo apt-get install curl

curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -

sudo apt-get install -y nodejs

============================================================



3. Instalar Android Studio

============================================================

1- Baixar Android Studio em: https://developer.android.com/studio

2- Descompactar e jogar a pasta 'android-studio' na home.

3- Terminal -> cd android-studio -> cd bin -> ./studio.sh

4- Custom Installation -> Selecionar Tema -> Marcar Android Virtual Device

5- Android Studio -> Configure -> AVD Manager ( Verificar se o Dispositivo Padrão foi criado )

OBS: Instalar qualquer item do SDK Tools para aceitar as licenças.

=============================================================

3.1 Caso erro /dev/kvm device: permission denied

=============================================================

sudo apt install qemu-kvm

sudo adduser cod3r kvm

sudo chown cod3r /dev/kvm

=============================================================



4. Variaveis de Ambiente (.bashrc)

=============================================================

export JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64

export ANDROID_HOME=$HOME/Android/Sdk

export PATH=$PATH:$ANDROID_HOME/emulator

export PATH=$PATH:$ANDROID_HOME/tools

export PATH=$PATH:$ANDROID_HOME/tools/bin

export PATH=$PATH:$ANDROID_HOME/platform-tools

=============================================================



5. React Native & Projeto

=============================================================

sudo npm i -g react-native-cli

react-native init exercicios

react-native start

react-native run-android