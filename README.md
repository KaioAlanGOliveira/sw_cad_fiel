# Sistema de Cadastro de Fiéis

Aplicação desktop desenvolvida em Java Swing com JPA/Hibernate para gerenciamento de fiéis e registro de dízimos.

## Funcionalidades

- Cadastro completo de fiéis (CPF, Nome, Telefone e Email)
- Listagem de fiéis com filtro por nome e CPF
- Interface gráfica amigável com botões de Incluir, Alterar, Excluir e Pesquisar
- Gerenciamento de pagamentos de dízimos
- Persistência com JPA (Hibernate)

## Tecnologias Utilizadas

- Linguagem: Java
- Interface Gráfica: Swing
- Persistência: JPA + Hibernate
- Banco de Dados: MySQL
- IDE recomendada: Eclipse ou IntelliJ IDEA

## Estrutura do Projeto

- `br.com.kaio.cadswingfiel.domain` → Entidades (Fiel e Pagamento)
- `br.com.kaio.cadswing.dao` → DAOs (FielDao e PagamentoDao)
- `br.com.kaio.cadswingfiel.ui` → Telas (UiPrincipal, UiFielLst, UiFielFrm)
- `persistence.xml` → Configuração do banco de dados

## Configuração do Banco de Dados

1. Crie o banco de dados `dizimistas`
2. Configure as credenciais no arquivo `persistence.xml`
3. A propriedade `hibernate.hbm2ddl.auto` está definida como `update` (cria/atualiza tabelas automaticamente)

## Como Executar

1. Clone o repositório
2. Importe o projeto como Java Project na sua IDE
3. Adicione as bibliotecas (JARs) necessárias (Hibernate, MySQL Connector, etc.)
4. Execute a classe `CadSwingFiel.java`

## Observações

- Projeto desenvolvido com Java Swing (desktop)
- Utiliza máscara de formatação para CPF e Telefone
- Sistema em fase de desenvolvimento

Repositório: https://github.com/KaioAlanGOliveira/sw_cad_fiel.git
