# **Módulo 1: Introdução a Blockchain**

## **Aula 1: Carteiras (Wallets)**

- **Objetivo**: Explicar o funcionamento das carteiras digitais e sua importância no ecossistema blockchain.
- **Tópicos**:
  - O que são carteiras (hot wallets vs cold wallets)
  - Como as carteiras armazenam chaves privadas e públicas
  - Exemplos de carteiras populares (MetaMask, Ledger, Trezor)
  - Interagindo com carteiras via DApps
- **Atividade Prática**:
  - Criar e configurar uma carteira Ethereum usando MetaMask.

## **Aula 2: Transações**

- **Objetivo**: Compreender como as transações funcionam na blockchain Ethereum.
- **Tópicos**:
  - Componentes de uma transação: endereço, nonce, valor, dados
  - Taxas de gas e como elas afetam as transações
  - Transações assíncronas e tempos de confirmação
  - Ferramentas de visualização de transações (Etherscan)
- **Atividade Prática**:
  - Enviar uma transação na rede de teste Goerli usando MetaMask.

## **Aula 3: Blocos e Mineração**

- **Objetivo**: Entender o conceito de blocos e como eles são validados.
- **Tópicos**:
  - Estrutura de blocos: transações, cabeçalho, hash anterior
  - Como blocos são minerados (Proof of Work) e validados (Proof of Stake)
  - Diferença entre blocos e transações pendentes
- **Atividade Prática**:
  - Explorar blocos no Etherscan e visualizar as transações em um bloco específico.

## **Aula 4: Consenso**

- **Objetivo**: Explicar os principais mecanismos de consenso na blockchain.
- **Tópicos**:
  - Proof of Work (PoW) vs Proof of Stake (PoS)
  - Como o consenso é alcançado em redes distribuídas
  - Staking e validação na Ethereum 2.0
- **Atividade Prática**:
  - Simular o processo de consenso via uma plataforma educacional (e.g., PoW vs PoS game).

---

# **Módulo 2: Introdução à EVM e Frameworks**

## **Aula 5: Máquinas Virtuais: EVM e Wasm**

- **Objetivo**: Compreender o papel das máquinas virtuais no processamento de contratos inteligentes.
- **Tópicos**:
  - O que é a EVM (Ethereum Virtual Machine)
  - Execução de contratos inteligentes na EVM
  - WebAssembly (Wasm) como uma alternativa emergente
- **Atividade Prática**:
  - Executar um contrato simples na EVM usando Remix.

## **Aula 6: Frameworks de Desenvolvimento: Foundry, Hardhat, ApeWorx**

- **Objetivo**: Explorar diferentes frameworks de desenvolvimento para contratos inteligentes.
- **Tópicos**:
  - Introdução ao Foundry, Hardhat, e ApeWorx
  - Diferenças entre os frameworks e quando usá-los
  - Criação de ambientes de teste e simulações
- **Atividade Prática**:
  - Configurar um projeto Hardhat e implementar um contrato básico.

## **Aula 7: Redes Ethereum e L2 (Layer 2)**

- **Objetivo**: Explicar as diferentes redes e suas camadas.
- **Tópicos**:
  - Rede Ethereum e suas alternativas: Arbitrum, Optimism, Polygon
  - Layer 2: Soluções de escalabilidade e Rollups
  - Diferenças entre redes mainnet, testnet e sidechains
- **Atividade Prática**:
  - Conectar o Hardhat a uma testnet de uma L2 como Arbitrum ou Optimism.

---

# **Módulo 3: Solidity Básico**

## **Aula 8: Variáveis: public, private, internal, constant, immutables**

- **Objetivo**: Aprender a declarar e usar variáveis no Solidity.
- **Tópicos**:
  - Diferença entre `public`, `private`, e `internal`
  - Constantes e variáveis imutáveis (`constant`, `immutable`)
  - Como e quando usar essas variáveis
- **Atividade Prática**:
  - Criar um contrato que usa variáveis `public`, `private`, `constant`, e `immutable`.

## **Aula 9: Expressões Matemáticas e Lógicas**

- **Objetivo**: Explorar operações matemáticas e lógicas em Solidity.
- **Tópicos**:
  - Operações matemáticas básicas (`+`, `-`, `*`, `/`)
  - Operadores lógicos (`&&`, `||`, `!`)
  - Prioridade de operadores e agrupamento
- **Atividade Prática**:
  - Criar um contrato que calcula valores baseados em expressões matemáticas e condições lógicas.

## **Aula 10: Tipos I: bool, int, bytes, address, string**

- **Objetivo**: Conhecer os tipos de dados primitivos usados no Solidity.
- **Tópicos**:
  - Tipos numéricos (`int`, `uint`)
  - Tipos booleanos e bytes (`bool`, `bytes`)
  - Endereços (`address`) e strings
- **Atividade Prática**:
  - Criar um contrato que usa e manipula esses tipos de dados.

## **Aula 11: Controle de Fluxo I: ifelse, for, while**

- **Objetivo**: Aprender os principais comandos de controle de fluxo.
- **Tópicos**:
  - Estruturas condicionais: `if`, `else if`, `else`
  - Estruturas de repetição: `for`, `while`
  - Diferenças de performance entre loops e condicionais
- **Atividade Prática**:
  - Criar um contrato que usa controle de fluxo para processar uma lista de valores.

---

# **Módulo 4: Solidity Avançado**

## **Aula 12: Funções: public, private, external, internal, view, pure**

- **Objetivo**: Compreender os tipos de funções e seus modificadores.
- **Tópicos**:
  - Diferença entre `public`, `private`, `external`, `internal`
  - Funções `view` e `pure`: Quando usar e suas restrições
- **Atividade Prática**:
  - Implementar um contrato com funções que retornam valores e alteram o estado.

## **Aula 13: Controle de Fluxo II: modifier, revert, error, event**

- **Objetivo**: Aprender a usar modificadores de função e tratamento de erros.
- **Tópicos**:
  - Uso de `modifier` para alterar o comportamento de funções
  - Tratamento de erros com `revert`, `require`, `assert`
  - Emitindo `event` para monitorar transações
- **Atividade Prática**:
  - Criar um contrato que inclui tratamento de erros e eventos customizados.

## **Aula 14: Variáveis e Tipos II: enum, array, struct, mapping**

- **Objetivo**: Entender tipos mais avançados no Solidity.
- **Tópicos**:
  - Usando `enum` para variáveis limitadas
  - Arrays fixos e dinâmicos
  - Estruturas (`struct`) e mapeamentos (`mapping`)
- **Atividade Prática**:
  - Criar um contrato que gerencia dados complexos com `struct`, `array`, e `mapping`.

## **Aula 15: Armazenamento de Dados: calldata, memory, storage**

- **Objetivo**: Explicar como o Solidity lida com diferentes tipos de armazenamento.
- **Tópicos**:
  - Diferença entre `calldata`, `memory`, e `storage`
  - Onde e quando cada um deve ser usado
- **Atividade Prática**:
  - Criar um contrato que manipula dados entre as diferentes regiões de armazenamento.

## **Aula 16: Contratos e Construtores**

- **Objetivo**: Compreender a inicialização de contratos usando construtores.
- **Tópicos**:
  - O que são construtores (`constructor`) e como inicializam contratos
  - Passagem de parâmetros ao contrato
  - Interações entre contratos
- **Atividade Prática**:
  - Criar um contrato com um `constructor` que define valores iniciais e interage com outro contrato.

## **Aula 17: Contratos e OO**

---

# **Módulo 5: Introdução ao ENS**

## **Aula 17: Funcionamento do ENS**

- **Objetivo**: Introduzir o conceito de ENS e suas funcionalidades.
- **Tópicos**:
  - O que é o ENS e sua utilidade na rede Ethereum
  - Mapeamento de endereços para nomes
  - Registradores, resolvers, e controle de domínio
- **Atividade Prática**:
  - Registrar um nome ENS na testnet e associá-lo a um endereço Ethereum.

## **Aula 18: Resolvers e Integração ENS**

- **Objetivo**: Compreender como
  Aqui está a versão detalhada da sua grade para o **Bootcamp ENS**, seguindo o padrão que você solicitou. Cada seção está organizada com tópicos claros e objetivos, mantendo um equilíbrio entre teoria e prática.

---

# **Módulo 1: Introdução a Blockchain**

## **Aula 1: Carteiras (Wallets)**

- **Objetivo**: Explicar o funcionamento das carteiras digitais e sua importância no ecossistema blockchain.
- **Tópicos**:
  - O que são carteiras (hot wallets vs cold wallets)
  - Como as carteiras armazenam chaves privadas e públicas
  - Exemplos de carteiras populares (MetaMask, Ledger, Trezor)
  - Interagindo com carteiras via DApps
- **Atividade Prática**:
  - Criar e configurar uma carteira Ethereum usando MetaMask.

## **Aula 2: Transações**

- **Objetivo**: Compreender como as transações funcionam na blockchain Ethereum.
- **Tópicos**:
  - Componentes de uma transação: endereço, nonce, valor, dados
  - Taxas de gas e como elas afetam as transações
  - Transações assíncronas e tempos de confirmação
  - Ferramentas de visualização de transações (Etherscan)
- **Atividade Prática**:
  - Enviar uma transação na rede de teste Goerli usando MetaMask.

## **Aula 3: Blocos e Mineração**

- **Objetivo**: Entender o conceito de blocos e como eles são validados.
- **Tópicos**:
  - Estrutura de blocos: transações, cabeçalho, hash anterior
  - Como blocos são minerados (Proof of Work) e validados (Proof of Stake)
  - Diferença entre blocos e transações pendentes
- **Atividade Prática**:
  - Explorar blocos no Etherscan e visualizar as transações em um bloco específico.

## **Aula 4: Consenso**

- **Objetivo**: Explicar os principais mecanismos de consenso na blockchain.
- **Tópicos**:
  - Proof of Work (PoW) vs Proof of Stake (PoS)
  - Como o consenso é alcançado em redes distribuídas
  - Staking e validação na Ethereum 2.0
- **Atividade Prática**:
  - Simular o processo de consenso via uma plataforma educacional (e.g., PoW vs PoS game).

---

# **Módulo 2: Introdução à EVM e Frameworks**

## **Aula 5: Máquinas Virtuais: EVM e Wasm**

- **Objetivo**: Compreender o papel das máquinas virtuais no processamento de contratos inteligentes.
- **Tópicos**:
  - O que é a EVM (Ethereum Virtual Machine)
  - Execução de contratos inteligentes na EVM
  - WebAssembly (Wasm) como uma alternativa emergente
- **Atividade Prática**:
  - Executar um contrato simples na EVM usando Remix.

## **Aula 6: Frameworks de Desenvolvimento: Foundry, Hardhat, ApeWorx**

- **Objetivo**: Explorar diferentes frameworks de desenvolvimento para contratos inteligentes.
- **Tópicos**:
  - Introdução ao Foundry, Hardhat, e ApeWorx
  - Diferenças entre os frameworks e quando usá-los
  - Criação de ambientes de teste e simulações
- **Atividade Prática**:
  - Configurar um projeto Hardhat e implementar um contrato básico.

## **Aula 7: Redes Ethereum e L2 (Layer 2)**

- **Objetivo**: Explicar as diferentes redes e suas camadas.
- **Tópicos**:
  - Rede Ethereum e suas alternativas: Arbitrum, Optimism, Polygon
  - Layer 2: Soluções de escalabilidade e Rollups
  - Diferenças entre redes mainnet, testnet e sidechains
- **Atividade Prática**:
  - Conectar o Hardhat a uma testnet de uma L2 como Arbitrum ou Optimism.

---

# **Módulo 3: Solidity Básico**

## **Aula 8: Variáveis: public, private, internal, constant, immutables**

- **Objetivo**: Aprender a declarar e usar variáveis no Solidity.
- **Tópicos**:
  - Diferença entre `public`, `private`, e `internal`
  - Constantes e variáveis imutáveis (`constant`, `immutable`)
  - Como e quando usar essas variáveis
- **Atividade Prática**:
  - Criar um contrato que usa variáveis `public`, `private`, `constant`, e `immutable`.

## **Aula 9: Expressões Matemáticas e Lógicas**

- **Objetivo**: Explorar operações matemáticas e lógicas em Solidity.
- **Tópicos**:
  - Operações matemáticas básicas (`+`, `-`, `*`, `/`)
  - Operadores lógicos (`&&`, `||`, `!`)
  - Prioridade de operadores e agrupamento
- **Atividade Prática**:
  - Criar um contrato que calcula valores baseados em expressões matemáticas e condições lógicas.

## **Aula 10: Tipos I: bool, int, bytes, address, string**

- **Objetivo**: Conhecer os tipos de dados primitivos usados no Solidity.
- **Tópicos**:
  - Tipos numéricos (`int`, `uint`)
  - Tipos booleanos e bytes (`bool`, `bytes`)
  - Endereços (`address`) e strings
- **Atividade Prática**:
  - Criar um contrato que usa e manipula esses tipos de dados.

## **Aula 11: Controle de Fluxo I: ifelse, for, while**

- **Objetivo**: Aprender os principais comandos de controle de fluxo.
- **Tópicos**:
  - Estruturas condicionais: `if`, `else if`, `else`
  - Estruturas de repetição: `for`, `while`
  - Diferenças de performance entre loops e condicionais
- **Atividade Prática**:
  - Criar um contrato que usa controle de fluxo para processar uma lista de valores.

---

# **Módulo 4: Solidity Avançado**

## **Aula 12: Funções: public, private, external, internal, view, pure**

- **Objetivo**: Compreender os tipos de funções e seus modificadores.
- **Tópicos**:
  - Diferença entre `public`, `private`, `external`, `internal`
  - Funções `view` e `pure`: Quando usar e suas restrições
- **Atividade Prática**:
  - Implementar um contrato com funções que retornam valores e alteram o estado.

## **Aula 13: Controle de Fluxo II: modifier, revert, error, event**

- **Objetivo**: Aprender a usar modificadores de função e tratamento de erros.
- **Tópicos**:
  - Uso de `modifier` para alterar o comportamento de funções
  - Tratamento de erros com `revert`, `require`, `assert`
  - Emitindo `event` para monitorar transações
- **Atividade Prática**:
  - Criar um contrato que inclui tratamento de erros e eventos customizados.

## **Aula 14: Variáveis e Tipos II: enum, array, struct, mapping**

- **Objetivo**: Entender tipos mais avançados no Solidity.
- **Tópicos**:
  - Usando `enum` para variáveis limitadas
  - Arrays fixos e dinâmicos
  - Estruturas (`struct`) e mapeamentos (`mapping`)
- **Atividade Prática**:
  - Criar um contrato que gerencia dados complexos com `struct`, `array`, e `mapping`.

## **Aula 15: Armazenamento de Dados: calldata, memory, storage**

- **Objetivo**: Explicar como o Solidity lida com diferentes tipos de armazenamento.
- **Tópicos**:
  - Diferença entre `calldata`, `memory`, e `storage`
  - Onde e quando cada um deve ser usado
- **Atividade Prática**:
  - Criar um contrato que manipula dados entre as diferentes regiões de armazenamento.

## **Aula 16: Contratos e Construtores**

- **Objetivo**: Compreender a inicialização de contratos usando construtores.
- **Tópicos**:
  - O que são construtores (`constructor`) e como inicializam contratos
  - Passagem de parâmetros ao contrato
  - Interações entre contratos
- **Atividade Prática**:
  - Criar um contrato com um `constructor` que define valores iniciais e interage com outro contrato.

---

# **Módulo 5: Introdução ao ENS**

## **Aula 17: Funcionamento do ENS**

- **Objetivo**: Introduzir o conceito de ENS e suas funcionalidades.
- **Tópicos**:
  - O que é o ENS e sua utilidade na rede Ethereum
  - Mapeamento de endereços para nomes
  - Registradores, resolvers, e controle de domínio

## **Aula 18: Resolvers e Integração ENS**

- **Objetivo**: Compreender como os resolvers do ENS funcionam e se integram com contratos.
- **Tópicos**:
  - Como os resolvers convertem nomes em dados (endereços, hashes)
  - Integração ENS com contratos Solidity

## **Aula 19: Hands-on**

- **Objetivo**: Implementar nomes e integrações com o ENS na testnet
- **Atividade Prática**:
  - Registrar um nome ENS na testnet e associá-lo a um endereço Ethereum.
  - Criar um contrato Solidity que utiliza o ENS para resolver nomes e endereços.

---

# **Projetos Práticos**

## **Projeto Prático 1: Construir nossa versão do ENS**

- **Objetivo**: Implementar um sistema básico de mapeamento de nomes.
- **Atividade**:
  - Criar um contrato que registre e resolva nomes simples para endereços.

## **Projeto Prático 2: Construir um Dapp que integre com nosso ENS**

- **Objetivo**: Desenvolver uma interface web para interagir com o ENS.
- **Atividade**:
  - Usar `ethers.js` ou `web3.js` para criar um front-end que permita registrar e consultar nomes.

## **Projeto Prático 3: Construindo um Protocolo que Integre com nosso ENS**

- **Objetivo**: Construir um protocolo mais avançado que utilize ENS para funcionalidades complexas.
- **Atividade**:
  - Criar um protocolo descentralizado que gerencie identidades ou serviços baseados no ENS.

## **Projeto Prático 4: Construindo um Dapp que Integre com ENS (Real)**

- **Objetivo**: Implementar uma aplicação real que utilize o ENS em produção.
- **Atividade**:
  - Lançar um DApp que interaja com o ENS real, utilizando a mainnet e resolvendo nomes para usuários reais.
