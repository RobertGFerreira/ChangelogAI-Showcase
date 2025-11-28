# Política de Segurança e Privacidade

## Arquitetura "Air-Gapped" por Design

O ChangelogAI foi construído com uma filosofia de **Privacidade em Primeiro Lugar**. Entendemos que o histórico de commits e o código-fonte de uma organização são ativos sensíveis e confidenciais.

Por isso, a arquitetura do software garante que:

1.  **Execução 100% Local**: Todo o processamento, desde a leitura do Git até a inferência da Inteligência Artificial, ocorre na máquina do usuário.
2.  **Sem Telemetria de Código**: O software não envia trechos de código, diffs ou mensagens de commit para servidores externos.
3.  **Dependência de IA Local**: O ChangelogAI utiliza o [Ollama](https://ollama.com/) rodando em `localhost`. Isso elimina a necessidade de enviar dados para APIs de terceiros (como OpenAI ou Anthropic), prevenindo vazamentos de propriedade intelectual.

## Relatando Vulnerabilidades

Como este é um software em Beta Fechado, a segurança é monitorada ativamente.

Se você descobrir uma vulnerabilidade de segurança neste repositório de vitrine ou no software ChangelogAI, por favor, **NÃO** abra uma issue pública.

Envie um e-mail diretamente para o mantenedor (endereço disponível na seção de contato do README) com os detalhes da vulnerabilidade. Agradecemos a cooperação para manter o ecossistema seguro.
