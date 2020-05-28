<h1>React Native Basics</h1>

<p>Repositório destinado ao estudo de conceitos básicos do 
    framework React Native. O conteúdo do repositório foi 
    gerado a partir de curso online.</p>

<h3>Algumas instruções...</h3>

<p><b>1. Instalar Java</b></p>

<p><code>sudo apt update</code></p>

<p><code>sudo apt install default-jdk</code></p>

<p><b>2. Instalar Node & NPM</b></p>

<p><code>sudo apt-get update</code></p>

<p><code>sudo apt-get install curl</code></p>

<p><code>curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -</code></p>

<p><code>sudo apt-get install -y nodejs</code></p>

<p><b>3. Instalar Android Studio</b>(em ordem)</p>

<p>Baixar Android Studio em: https://developer.android.com/studio</p>

<p>Descompactar e jogar a pasta 'android-studio' na home.</p>

<p>Terminal -> cd android-studio -> cd bin -> ./studio.sh</p>

<p>Custom Installation -> Selecionar Tema -> Marcar Android Virtual Device</p>

<p>Android Studio -> Configure -> AVD Manager ( Verificar se o Dispositivo Padrão foi criado )</p>

<p>OBS: Instalar qualquer item do SDK Tools para aceitar as licenças.</p>

<p><b>3.1 Caso erro /dev/kvm device: permission denied</b></p>

<p><code>sudo apt install qemu-kvm</code></p>

<p><code>sudo adduser XXXX kvm</code></p>

<p><code>sudo chown XXXX /dev/kvm</code></p>

<p><b>4. Variaveis de Ambiente (.bashrc)</b></p>

<p><code>export JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64</code></p>

<p><code>export ANDROID_HOME=$HOME/Android/Sdk</code></p>

<p><code>export PATH=$PATH:$ANDROID_HOME/emulator</code></p>

<p><code>export PATH=$PATH:$ANDROID_HOME/tools</code></p>

<p><code>export PATH=$PATH:$ANDROID_HOME/tools/bin</code></p>

<p><code>export PATH=$PATH:$ANDROID_HOME/platform-tools</code></p>

<p><b>5. React Native & Projeto</b></p>

<p><code>sudo npm i -g react-native-cli</code></p>

<p><code>react-native init exercicios</code></p>

<p><code>react-native start</code></p>

<p><code>react-native run-android</code></p>
