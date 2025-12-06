# 🏋️ Fitness Tracker

Aplicativo Android nativo desenvolvido em *Kotlin* focado em saúde e bem-estar. O app permite que o usuário calcule seu *IMC* e *TMB*, mantendo um histórico para acompanhar a sua evolução.

---

## 💡 Funcionalidades

* *Cálculos e Navegação:*
    * Cálculos: Realiza cálculos de *IMC* (Índice de Massa Corporal) e *TMB* (Taxa Metabólica Basal).
    * Navegação: Gerenciamento de fluxo e troca de dados entre diferentes telas (Activities).
* *Histórico com Persistência de Dados:*
    * Salva o resultado de cada cálculo realizado.
    * Utiliza a biblioteca *Room* (camada sobre o SQLite) para persistir os dados no dispositivo.
* *Interface Dinâmica com RecyclerView:*
    * *Menu Principal:* Utiliza RecyclerView para criar um grid de navegação, onde os ícones, textos e cores dos botões são manipulados dinamicamente pelo Adapter.
    * *Histórico:* Reutiliza a estrutura de lista com uma RecyclerView para exibir os registros salvos e permitir a visualização da evolução.

---

## ⬇️ Baixe para Testar!

Você pode baixar o arquivo APK diretamente e instalar no seu celular para testar.

* *Arquivo APK:* [app-debug.apk](https://github.com/fernandes-gustavo/app-fitness-tracker/releases/download/v1.0/app-debug.apk)
* *Instruções de Instalação:* Lembre-se de permitir a instalação de aplicativos de "fontes desconhecidas" nas configurações do seu celular.
