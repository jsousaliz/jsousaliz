# Ajustes do GitHub — etapa 6

## Diagnóstico atual

- Ainda não existe o repositório especial `jsousaliz/jsousaliz`; sem ele, o perfil não exibe um README de apresentação.
- A bio pública está desatualizada: informa “13+ years” e termina com “Currently learning Python and exploring AI-assisted developme”, inclusive com a última palavra truncada.
- O campo de website está vazio, apesar de o portfólio estar publicado.
- Os cinco repositórios exibidos atualmente são Delphi AMQP Core, DesafioTecnico, Daikit, portfólio e Deskprompter.
- `DesafioTecnico` é um exercício antigo e compete visualmente com projetos atuais mais fortes.
- Os quatro repositórios principais estão sem tópicos; isso reduz contexto, descoberta e leitura rápida.
- As descrições atuais de Delphi AMQP Core e Deskprompter são longas e aparecem truncadas nos cartões do perfil.
- Os campos de homepage dos quatro repositórios principais estão vazios.

## 1. Criar o README do perfil

1. Criar um repositório público chamado exatamente `jsousaliz`.
2. Marcar a opção para iniciar com `README.md`.
3. Copiar para esse arquivo o conteúdo de `6-github-readme.md`.
4. Não adicionar licença ao repositório do perfil; ele contém apenas apresentação pessoal.

O diferencial do README é organizar cada projeto como **problema → solução → evidência**, evitando mural de badges e frases genéricas.

## 2. Atualizar os dados públicos

### Bio recomendada

> Senior Delphi Developer | Integrations, APIs, messaging and legacy modernization | Open source: AMQP, AI and Windows applications

Motivo: é curta, pesquisável, internacional e coerente com currículo, LinkedIn e projetos. Remover “Currently learning Python”; Python é conhecimento complementar, não posicionamento principal.

### Campos

- **Name:** Jean Sousa Liz
- **Location:** Lages, SC, Brasil
- **Website:** `https://jsousaliz.github.io/`
- **Social account:** manter LinkedIn `jsousaliz`
- **Company:** deixar vazio enquanto não houver vínculo atual a apresentar

## 3. Repositórios fixados

Manter somente estes quatro, nesta ordem:

1. `delphi-amqp-core` — maior profundidade de protocolo, concorrência e testes;
2. `daikit` — integração de Delphi com APIs atuais de IA;
3. `deskprompter` — aplicação Windows completa e distribuível;
4. `jsousaliz.github.io` — amplitude complementar em web, testes e CI.

Remover `DesafioTecnico` dos fixados. O repositório pode continuar público como registro histórico, mas não deve disputar atenção com o trabalho atual. Se não tiver utilidade externa, arquivá-lo é melhor do que apagá-lo.

## 4. Descrições, homepages e tópicos

### Delphi AMQP Core

**Descrição:**

> Cliente AMQP 0-9-1 nativo para Delphi e RabbitMQ, com publish/consume assíncrono, ack/nack/reject, observabilidade e testes.

**Homepage:** deixar vazio até existir documentação ou demonstração externa melhor que o próprio README.

**Tópicos:** `delphi`, `object-pascal`, `amqp`, `rabbitmq`, `messaging`, `winsock`, `async`, `testing`

### Daikit

**Descrição:**

> Componentes Delphi para OpenAI, Anthropic e Gemini por uma API única, com execução assíncrona, histórico, testes e instalador.

**Homepage:** playlist do Daikit no YouTube:  
`https://www.youtube.com/watch?v=PG1d8enP1F0&list=PLJQiqZc-swOI`

**Tópicos:** `delphi`, `object-pascal`, `openai`, `anthropic`, `gemini`, `artificial-intelligence`, `components`, `dunitx`

### Deskprompter

**Descrição:**

> Teleprompter Windows em Delphi/VCL e SQLite, com arquitetura em camadas, testes, instalador e releases.

**Homepage:**  
`https://github.com/jsousaliz/deskprompter/releases/latest`

**Tópicos:** `delphi`, `object-pascal`, `vcl`, `sqlite`, `windows`, `teleprompter`, `dunitx`, `inno-setup`

### Portfólio

**Descrição:**

> Portfólio profissional em Astro, React e TypeScript, com testes, CI e publicação no GitHub Pages.

**Homepage:**  
`https://jsousaliz.github.io/`

**Tópicos:** `astro`, `typescript`, `react`, `css`, `portfolio`, `github-pages`, `vitest`

## 5. Estatísticas de linguagens

Fonte: endpoint `/languages` da API pública do GitHub, que retorna bytes classificados pelo Linguist.

Escopo usado: `delphi-amqp-core`, `daikit`, `deskprompter` e `jsousaliz.github.io`.

| Linguagem | Bytes | Participação |
|---|---:|---:|
| Pascal | 944.888 | 86,13% |
| Astro | 70.987 | 6,47% |
| CSS | 33.822 | 3,08% |
| TypeScript | 31.465 | 2,87% |
| PowerShell | 13.872 | 1,26% |
| Inno Setup | 1.463 | 0,13% |
| JavaScript | 479 | 0,04% |
| HTML | 54 | <0,01% |
| **Total** | **1.097.030** | **100%** |

Esses percentuais são um retrato de 14/08/2026. Atualizar quando houver mudança relevante nos projetos; não usar widgets externos de disponibilidade incerta nem apresentar os números como proficiência.

## 6. Ajustes posteriores nos repositórios

- Manter screenshots ou GIFs curtos próximos ao início dos READMEs de Daikit e Deskprompter.
- Manter instruções de execução, testes, arquitetura, licença e releases dentro de cada projeto, não no README do perfil.
- No Daikit, continuar relacionando o README à playlist do YouTube.
- Explicitar licença em Daikit e Deskprompter conforme a intenção de uso: open source com licença reconhecida ou código público com direitos reservados. Não deixar o leitor inferir permissão de uso.
- Atualizar a tabela de linguagens somente quando a composição mudar de forma perceptível.

## 7. Ordem de execução recomendada

1. Atualizar bio, localização e website.
2. Ajustar descrições, homepages e tópicos dos quatro repositórios.
3. Remover `DesafioTecnico` dos fixados e ordenar os quatro projetos principais.
4. Criar `jsousaliz/jsousaliz` e publicar o README aprovado.
5. Conferir o perfil público em desktop e celular.

Nenhuma alteração foi publicada no GitHub nesta etapa. A publicação exige autorização específica após aprovação dos dois arquivos.
