# ead_flutter_alura_criando-um-app

> Projeto referente a [este](https://www.alura.com.br/curso-online-flutter-crie-primeiro-app) curso.

> Não entendi pq o app não atualizou o statefull widget e abandonei o curso

> [Catalogo de widgets](https://docs.flutter.dev/development/ui/widgets/material) [Doc dos widgets](https://api.flutter.dev/flutter/widgets/widgets-library.html#classes)

## Setup Linux

1. Baixe o flutter

```sh
sudo snap install flutter --classic
```

2. Baixe o [Android Studio](https://developer.android.com/studio)
    1. Descompacte
    2. Mova para ~
    3. Instale com `./bin/studio.sh`
    4. Adicione `$HOME/Android/Sdk` ao `PATH`

3. Execute ``flutter doctor`` para verificar pendências da instalação

## Run on physical device

1. Plugar USB
    - Veja se o dispositivo está disponível com ``flutter devices``
2. Execute o app ``flutter run``

## Run on emulator

1. Localize o [emulador](https://developer.android.com/studio/run/managing-avds#createavd) ``flutter emulators``
2. Ative o emulador ``flutter emulators --launch <emulator id>``
3. Execute o app ``flutter run``

## Terminal tips

- `r` para hot reload
