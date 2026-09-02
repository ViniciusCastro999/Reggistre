# Reggistre

Aplicativo móvel para **controle financeiro pessoal**, desenvolvido em Flutter como
Trabalho de Conclusão de Curso (TCC).

O objetivo do projeto é oferecer uma ferramenta simples para registrar receitas e
despesas, acompanhar o saldo e visualizar para onde o dinheiro está indo ao longo
do tempo.

> Status: projeto em fase inicial. A base do app já está criada (estrutura Flutter
> padrão) e as funcionalidades de controle financeiro estão em desenvolvimento.

## Tecnologias

- [Flutter](https://flutter.dev/) (canal `stable`)
- [Dart](https://dart.dev/) SDK `>=2.7.0 <3.0.0`
- `cupertino_icons` para ícones no estilo iOS

## Pré-requisitos

- Flutter SDK instalado ([guia de instalação](https://docs.flutter.dev/get-started/install))
- Android Studio / Xcode configurados para rodar em emulador ou dispositivo físico
- Verifique o ambiente com:

  ```bash
  flutter doctor
  ```

## Como executar

```bash
# 1. Clone o repositório
git clone <url-do-repositorio>
cd Reggistre

# 2. Instale as dependências
flutter pub get

# 3. Rode o app (com um emulador aberto ou dispositivo conectado)
flutter run
```

## Como testar

```bash
flutter test
```

## Build de produção

```bash
# Android (APK)
flutter build apk --release

# iOS
flutter build ios --release
```

## Estrutura do projeto

```
lib/
  main.dart          # Ponto de entrada do aplicativo
test/
  widget_test.dart   # Testes de widget
android/             # Projeto Android nativo
ios/                 # Projeto iOS nativo
pubspec.yaml         # Dependências e configuração do Flutter
```

## Roadmap

- [ ] Cadastro de receitas e despesas
- [ ] Categorias de transações
- [ ] Cálculo e exibição de saldo
- [ ] Relatórios e gráficos por período
- [ ] Persistência local dos dados
- [ ] Autenticação de usuário

## Licença

Distribuído sob a **Boost Software License 1.0**. Veja o arquivo [LICENSE](LICENSE)
para mais detalhes.
