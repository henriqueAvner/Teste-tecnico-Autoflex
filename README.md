
# Teste Técnico Autoflex

## Descrição do Problema

Uma indústria precisa controlar o estoque de insumos (matérias-primas) para a produção dos itens que fabrica. Para isso, será necessário desenvolver um sistema que permita:

- Manter o controle dos **produtos** e das **matérias-primas** utilizadas em cada produto.
- Armazenar para cada produto: **código**, **nome** e **valor**.
- Armazenar para cada matéria-prima: **código**, **nome** e **quantidade em estoque**.
- Associar produtos às matérias-primas que os compõem, incluindo a quantidade de cada matéria-prima necessária para produzir o produto.
- Consultar quais produtos (e quantas unidades) podem ser produzidos com o estoque atual de matérias-primas, e o valor total obtido com a produção sugerida.
- Priorizar a produção dos produtos de **maior valor**, já que uma matéria-prima pode ser usada em mais de um produto.

---

## Requisitos

### Requisitos Não Funcionais

- **RNF001:** O sistema deve ser desenvolvido para plataforma **WEB**, compatível com Chrome, Firefox e Edge.
- **RNF002:** O sistema deve ser construído em arquitetura **API** (back-end separado do front-end).
- **RNF003:** O front-end deve ser **responsivo**.
- **RNF004:** Persistência de dados em SGBD: **Postgres**, **MySQL** ou **Oracle** (preferencialmente Oracle, se disponível).
- **RNF005:** O back-end (API) deve ser desenvolvido com framework como **Spring**, **Quarkus** ou similar (preferencialmente Quarkus).
- **RNF006:** O front-end pode ser desenvolvido com qualquer linguagem/framework, preferencialmente **React** e **Redux**.
- **RNF007:** Toda a codificação (back-end, front-end, tabelas e colunas do banco) deve ser feita em **inglês**.

### Requisitos Funcionais

- **RF001:** CRUD de produtos no back-end.
- **RF002:** CRUD de matérias-primas no back-end.
- **RF003:** CRUD de associação entre produtos e matérias-primas no back-end.
- **RF004:** Consulta dos produtos que podem ser produzidos com o estoque atual de matérias-primas (back-end).
- **RF005:** CRUD de produtos no front-end.
- **RF006:** CRUD de matérias-primas no front-end.
- **RF007:** CRUD de associação entre produtos e matérias-primas no front-end (pode ser integrado à tela de produtos).
- **RF008:** Listagem dos produtos (e quantidades) que podem ser produzidos com o estoque atual de matérias-primas (front-end).

---

## Desejável

- Desenvolvimento de **testes unitários** para back-end e front-end.
- Desenvolvimento de **testes de integração** (preferencialmente com **Cypress**).

---

## Checklist de Implementação

- [ ] CRUD de produtos (back-end)
- [ ] CRUD de matérias-primas (back-end)
- [ ] CRUD de associação produto/matéria-prima (back-end)
- [ ] Consulta de produção possível (back-end)
- [ ] CRUD de produtos (front-end)
- [ ] CRUD de matérias-primas (front-end)
- [ ] CRUD de associação produto/matéria-prima (front-end)
- [ ] Listagem de produção possível (front-end)
- [ ] Testes unitários
- [ ] Testes de integração
