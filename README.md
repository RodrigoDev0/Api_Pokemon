Android Pokedex App

Este projeto é uma aplicação móvel desenvolvida para a plataforma Android utilizando Java e Android Studio. A aplicação se integra a um banco de dados local e realiza chamadas à API pública PokeAPI para exibir informações sobre Pokémon.

Funcionalidades
1. Desenvolvimento Android
O projeto foi desenvolvido utilizando o Android Studio e segue as melhores práticas recomendadas para desenvolvimento de aplicativos Android. Ele usa componentes do Android como:

Activities e Fragments para navegação entre telas.
RecyclerView para exibição de listas.
ViewModel e LiveData para gerenciar o ciclo de vida de dados.
2. Conexão com Banco de Dados (SQLite)
A aplicação realiza operações de CRUD (Create, Read, Update, Delete) utilizando o banco de dados SQLite local. As informações dos Pokémon pesquisados são salvas localmente para consulta offline. Funcionalidades incluem:

Armazenamento de dados persistentes.
Atualização e exclusão de registros do banco de dados.
Leitura de dados para exibição.
3. Interface de Usuário
A interface foi desenhada utilizando os princípios de Material Design, garantindo uma experiência de usuário fluida e moderna.

Layouts responsivos que se adaptam a diferentes tamanhos de tela.
Animações e transições suaves entre telas.
Validação de entradas com feedbacks visuais apropriados.
4. Funcionalidades Básicas
A aplicação conta com:

Navegação entre telas por meio de Intents e Fragments.
Persistência de dados locais para uso offline.
Integração com a API PokeAPI para buscar dados em tempo real.
Tratamento de erros, como falhas de rede ou respostas inválidas da API.
Validação de entradas do usuário para evitar crashes e garantir a integridade dos dados.

Pré-requisitos
Android Studio 4.0+
Java 8+
Emulador Android ou dispositivo físico com Android 5.0 (Lollipop) ou superior.

Como Executar o Projeto

Clone este repositório para sua máquina local:
bash
Copiar código
Abra o projeto no Android Studio.
Sincronize as dependências do projeto com Gradle.
Conecte um dispositivo Android ou inicie um emulador.
Execute o aplicativo pressionando Shift + F10 ou clicando em Run > Run 'app'.
