 Sistema de Gestão de Cadeia de Hotéis  
 Projeto de Bases de Dados — Oracle | PL/SQL | APEX

Este projeto consiste no desenvolvimento completo de um **Sistema de Gestão de uma Cadeia de Hotéis**, abrangendo modelação da base de dados, implementação SQL, desenvolvimento de lógica de negócio em **PL/SQL**, criação de **triggers**, **procedures**, **cursores**, vistas e integração com **Oracle APEX**.

O trabalho foi realizado em grupo no âmbito da unidade curricular de **Bases de Dados**, e cada membro contribuiu para diferentes partes do sistema.  
Este repositório representa **a minha participação direta**, bem como a documentação final do projeto.

---

 Funcionalidades Principais

 Gestão de entidades:
- Hotéis  
- Quartos  
- Clientes  
- Reservas  
- Funcionários  
- Pagamentos  
- Manutenções  
- Avaliações  
- Fornecedores e serviços

Lógica de negócio desenvolvida:
- Cálculo de estatísticas de avaliações  
- Quartos acima/abaixo da média de preços  
- Funcionários com salário acima da média  
- Histórico de reservas por cliente  
- Gestão de pagamentos por reserva  
- Relatórios dinâmicos (CLOB + HTP.P)  
- Verificação automática de idades e restrições  
- Geração de relatórios HTML via PL/SQL

 Programação PL/SQL utilizada:
- **Cursores**  
- **Triggers (BEFORE / AFTER)**  
- **Procedures**  
- **Funções**  
- **Blocos anónimos**  
- **Tratamento de exceções**  
- **VARRAY e RECORD types**  
- **CLOB e HTP.P para output HTML**

---

  Modelação da Base de Dados

O projeto inclui:
- Modelo Entidade-Relação (ERD)  
- Modelo Relacional  
- Normalização  
- Definição de chaves primárias e estrangeiras  
- Regras de integridade referencial  

---

Tecnologias Utilizadas

| Tecnologia | Uso |
|-----------|-----|
| **Oracle Database** | Base de dados principal |
| **PL/SQL** | Procedures, triggers, lógica de negócio |
| **Oracle APEX** | Interface web e visualização |
| **SQL** | Criação e manipulação de dados |
| **CLOB / HTP.P** | Geração de relatórios dinâmicos |

---

 A minha contribuição principal

- Criação de **procedures PL/SQL complexas**  
- Desenvolvimento de **triggers** para validação e histórico  
- Implementação de **cursores** e manipulação de dados  
- Desenvolvimento de relatórios com **CLOB/HTML (HTP.P)**  
- Participação na **modelação relacional**  
- Implementação de parte do CRUD (clientes | reservas | funcionários)

---

 Documentação do Projeto

O relatório completo pode ser encontrado aqui:

 **`/docs/GestãoCadeiaHotéis.pdf`**  
*(faz upload do PDF para a pasta `/docs`)*
  
Este documento contém:
- Modelo ER  
- Modelo Relacional  
- Listagem completa das procedures  
- Triggers  
- Testes e resultados  
- Diagramas e explicações

---

 Como executar

 1. Importar o esquema da BD  
Carregar os ficheiros SQL no Oracle SQL Developer ou outra ferramenta Oracle.

 2. Criar as tabelas  
Executar os scripts de criação.

 3. Executar as procedures e triggers  
Correr cada bloco PL/SQL no ambiente Oracle.

 4. APEX (Opcional)  
Importar as páginas no Oracle APEX e associar ao esquema criado.

---

 Licença
Projeto desenvolvido para fins académicos.  
É permitida a visualização e reutilização parcial para estudo.

---

 Autores
Projeto realizado em grupo no âmbito da unidade curricular de Bases de Dados — IPB.

---

