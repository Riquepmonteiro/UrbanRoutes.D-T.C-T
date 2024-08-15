# Urban Routes 🌆

## Descrição do Projeto

**Urban Routes** é um site inovador projetado para facilitar o planejamento de rotas urbanas e melhorar a experiência de navegação pela cidade. Este repositório se concentra no trabalho de **Quality Assurance (QA)** realizado no projeto, com destaque para o design de testes, a escrita de casos de teste e o planejamento de testes para o formulário "Adicionar Carteira de Motorista".

## Design de Teste 🛠️

O design de teste foi cuidadosamente elaborado para garantir a robustez e a confiabilidade do formulário "Adicionar Carteira de Motorista". Foram considerados vários cenários de uso e validada a integridade dos dados inseridos pelos usuários.

### Casos de Teste 📋

Foram escritos diversos casos de teste para cobrir todas as funcionalidades do formulário, incluindo:

1. **Validação de Campos Obrigatórios**: Certifica-se de que os campos obrigatórios não podem ser deixados em branco.
2. **Verificação de Formato de Dados**: Testa se os dados inseridos estão no formato esperado (e.g., nome, sobrenome, e data de nascimento).
3. **Testes de Limite**: Verifica como o sistema reage ao inserir dados no limite máximo ou mínimo permitido.

### Classes de Equivalência e Valores-Limites 📐

Para assegurar a validade dos dados, foram definidas classes de equivalência e valores-limites para os campos "Nome", "Sobrenome" e "Data de Nascimento":

- **Nome e Sobrenome**:
  - **Classes de Equivalência**: 
    - Nomes válidos: letras de A a Z, sem números ou caracteres especiais.
    - Nomes inválidos: números, caracteres especiais, letras não latinas, campo vazio.
  - **Valores-Limites**:
    - Limite inferior: 2 caractere.
    - Limite superior: 14 caracteres.
  
- **Data de Nascimento**:
  - **Classes de Equivalência**:
    - Datas válidas: data no formato "dd/mm/aaaa" dentro de um intervalo lógico para idade.
    - Datas inválidas: datas no futuro, formatos inválidos.
  - **Valores-Limites (Ano)**:
    - Limite inferior: xx/xx/1880.
    - Limite superior: xx/xx/2006.
  - **Valores-Limites (Mês)**:
    - Limite inferior: xx/01/xxxx.
    - Limite superior: xx/12/xxxx.
  - **Valores-Limites (Dia)**:
    - Limite inferior: 01/xx/xxxx.
    - Limite superior: 28,29,30,31/xx/xxxx.

## Implementação dos Testes 🧪

Os testes foram projetados para garantir que o formulário funcione corretamente em diversos cenários, considerando tanto entradas válidas quanto inválidas. Isso assegura que apenas dados corretos sejam aceitos, prevenindo problemas posteriores no sistema.

## Contribuição

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões para melhorias, fique à vontade para abrir uma issue ou enviar um pull request.

**Henrique Monteiro**
QA Analyst
"Qualidade não é um ato, é um hábito." - Aristóteles

### Explicação

- **Design de Teste:** Uma visão detalhada do planejamento dos testes com foco em como eles foram criados para garantir a qualidade do formulário.
- **Casos de Teste e Classes de Equivalência:** Informações sobre como os testes foram pensados para cobrir diversos cenários e validar as entradas do usuário.
- **Contribuição:** Um convite para que outros contribuam com o projeto.
