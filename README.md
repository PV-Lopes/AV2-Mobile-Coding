# AV2-Mobile-Coding

# 👟 BlueShoes App

Um aplicativo Android moderno desenvolvido em **Kotlin**, simulando uma loja virtual de calçados. Este projeto serve como base educacional e técnica para demonstrar **boas práticas de arquitetura, navegação, design e modularidade** em aplicativos móveis nativos.

---

## ✨ Visão Geral

O BlueShoes é um app fictício que permite aos usuários:

- Navegar por um catálogo de calçados.
- Gerenciar configurações de perfil.
- Cadastrar cartões de crédito e endereços de entrega.
- Acessar políticas e seções institucionais via menu lateral.

Embora não se conecte a um backend real, simula uma estrutura robusta de dados e funcionalidades offline com dados mockados.

---

## 📲 Funcionalidades

- ✅ Tela de login e recuperação de senha.
- ✅ Cadastro de novos usuários.
- ✅ Menu lateral com navegação entre telas.
- ✅ Gerenciamento de configurações pessoais.
- ✅ Registro de cartões de crédito.
- ✅ Cadastro e edição de endereços.
- ✅ Design baseado no Material Design.

---

## ⚙️ Tecnologias Utilizadas

| Tecnologia          | Finalidade                                 |
|---------------------|---------------------------------------------|
| **Kotlin**          | Linguagem principal                         |
| **AndroidX**        | Componentes de UI modernos                  |
| **Material Design** | Layouts bonitos e responsivos               |
| **Fragments**       | Navegação modular                           |
| **Adapters**        | Listagem de dados em RecyclerViews          |
| **Mock Database**   | Dados simulados com Kotlin puro             |
| **Custom Extensions** | Funções reutilizáveis para melhorar o código |

---

## 🧩 Estrutura do Projeto

```
app/
├── java/thiengo/com/br/blueshoes/
│   ├── data/              → Dados mockados (Shoes, User, etc)
│   ├── domain/            → Modelos de entidades (Price, Rate, Shoes, etc)
│   ├── util/              → Funções utilitárias e classes auxiliares
│   └── view/              → Activities e Fragments da interface
│       └── config/        → Telas de configurações do usuário
│           ├── creditcard/
│           ├── deliveryaddress/
│           └── connectiondata/
├── res/
│   ├── layout/            → Arquivos XML de UI
│   ├── drawable/          → Ícones e formas
│   └── values/            → Strings, cores e dimensões

```
---

## 🚀 Como Executar o Projeto

### 🔧 Pré-requisitos

- Android Studio **Hedgehog 2023.1.1** ou superior  
- SDK mínimo: **API 21** (Android 5.0)  
- Gradle: **8.6**

### 🛠️ Passo a Passo

1. Clone este repositório:

   ```bash
   git clone https://github.com/seuusuario/blueshoes-kotlin-android.git

2. Abra o projeto no Android Studio.
3. Aguarde o sincronismo do Gradle.
4. Execute em um dispositivo físico ou emulador com Android 5.0+.


### 🧭 Fluxo de Navegação

    ```bash
    [LoginActivity]
      ↓
    [MainActivity (Menu Lateral)]
        ├── Lista de Produtos
        ├── Configurações
        │   ├── Cartões de Crédito
        │   ├── Endereços
        │   ├── Dados de Conexão
        ├── Sobre
        └── Política de Privacidade

---

## 👤 Autor
Desenvolvido originalmente por Vinícius Thiengo. Ultilisado com propósitos educacionais, análise e documentação por [Pedro Vitor].

## 🔗 Link:
https://github.com/viniciusthiengo/blueshoes-kotlin-android

## ❗ Aviso:
Por ser baseado em um projeto antigo algumas bibliotecas estão desatualizadas ou não existem mais, por esse motivo as funcionalidades não estão 100% funcionais. Agradeço a atenção e compreensão de todos.
