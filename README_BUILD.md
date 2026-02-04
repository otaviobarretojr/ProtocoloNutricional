# Protocolo Nutricional (Android)

Este projeto empacota o seu HTML (assets/index.html) dentro de um app Android via WebView.

## Como gerar o APK (jeito mais fácil)
1) Instale o Android Studio
2) Abra o projeto: File > Open > selecione a pasta `ProtocoloNutricional`
3) Espere sincronizar o Gradle
4) Build > Build Bundle(s) / APK(s) > Build APK(s)
5) O APK sai em: app/build/outputs/apk/debug/app-debug.apk

## Persistência (dados não somem)
- Seus dados ficam salvos via `localStorage` no armazenamento interno do app.
- Só perde se você desinstalar o app ou limpar dados manualmente.
