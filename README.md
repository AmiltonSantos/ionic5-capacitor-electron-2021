           _____          .__.__   __                    _________              __                
          /  _  \   _____ |__|  |_/  |_  ____   ____    /   _____/____    _____/  |_  ____  ______
         /  /_\  \ /     \|  |  |\   __\/  _ \ /    \   \_____  \\__  \  /    \   __\/  _ \/  ___/
        /    |    \  Y Y  \  |  |_|  | (  <_> )   |  \  /        \/ __ \|   |  \  | (  <_> )___ \ 
        \____|__  /__|_|  /__|____/__|  \____/|___|  / /_______  (____  /___|  /__|  \____/____  >
                \/      \/                         \/          \/     \/     \/                \/ 

# ionic5-capacitor-electron-2021
Iniciando meus estudos com Ionic5 + Angular + Capacitor + Electronjs - Desktop -- Fevereiro de 2021


### Instalar o NodeJs:
-Instalar o NODEJS [https://nodejs.org/en/](https://nodejs.org/en/) 

### Instalar o Ionic:
```bash
$ sudo npm install -g ionic
```

### Clone o repositório:
```bash
$ git clone https://github.com/AmiltonSantos/nubank-com-ionic5.git
$ cd nubank-com-ionic5
```

### Install node modules:
```bash
$ npm install
```

### Instalação do Electon
```bash
$ npm install ngx-electron electron
$ npm install electron-packager --save-dev
```

### Atualizar o Angular pra uma versão mas recente
```bash
$ sudo npm install -g @angular/cli
$ ng update @angular/cli @angular/core --allow-dirty
```

### Iniciar projeto Ionic + Electron
```bash
$ ionic build
$ npx cap add electron
$ npx cap open electron
```

### Quando for mundando o codigo e precisar buildar novamente
```bash
$ ionic build && npx cap copy
$ npx cap open electron
```

- Verificar se tem o ponto no arquivo src / index.html
- Na linha ----->  "< base href="./" / >"

