## Bruno Strapazzon

Estudo Ciência da Computação na FIAP (2026–2029) e construo automações e sistemas com IA que dá para conferir. A IA entra onde ajuda; onde ela poderia errar, entram regras, testes e métricas. E quando o sistema não sabe, ele diz que não sabe.

Trabalho com suporte de TI e redes desde 2023, e é de lá que vêm os problemas que eu automatizo.

### NetDoctor: regras decidem, a IA só explica

**[NetDoctor](https://github.com/brunostrapazzon/NetDoctor)** automatiza a triagem de problemas de internet no Windows: um clique, uns 10 segundos, e ele explica a causa em português simples.

- O diagnóstico vem de regras determinísticas. O modelo de linguagem (Groq, OpenAI ou Ollama local) só reescreve a explicação, nunca decide.
- A resposta da IA é validada. Se sair do formato, demorar ou falhar, o app usa o texto offline sem mostrar erro.
- A IA recebe só uma lista fechada de campos. Nome da rede, IP e MAC nunca saem da máquina, e há testes que quebram se isso mudar.
- 279 testes com saídas reais do Windows em português e inglês. O GitHub Actions testa, gera o `.exe` e publica o release.

[Baixar o NetDoctor.exe](https://github.com/brunostrapazzon/NetDoctor/releases/latest)

### Citizen Assist AI: um assistente que prefere não responder a chutar

**[Citizen Assist AI](https://github.com/brunostrapazzon/CITIZEN-ASSIST-AI)** (FIAP, equipe de 3) orienta o cidadão usando só fontes oficiais, em Python e sem modelo de linguagem: busca com índice invertido e correção de digitação, grafo e Dijkstra para assuntos relacionados.

- Avaliado com 30 perguntas de teste: **86,7% de acerto** e **87,5% de abstenção correta** quando a base não tem a resposta.
- A avaliação pegou a primeira versão respondendo "receita de bolo" com a orientação do CPF. A segunda passou a se abster ou oferecer opções.

[Vídeo de apresentação](https://youtu.be/QpQYXNN09l8)

### Outros projetos (em equipe)

| Projeto | O que faz |
|---|---|
| EV ChargeOps (Enterprise Challenge GoodWe + FIAP) | Divide a conta de recarga de carros elétricos em condomínio. Lê o carregador via Modbus, identifica a unidade por RFID e usa detecção de anomalias (Isolation Forest) para barrar medições suspeitas: nos testes, pegou as 12 sessões com problema sem bloquear nenhuma normal. |
| [Monitoramento ARES-VII](https://github.com/brunostrapazzon/Global-Solution---1-Semestre-) | Telemetria de uma missão simulada em Marte: alertas priorizados com fila e pilha e previsão da reserva de energia com regressão linear feita à mão. |
| [SCIC Aurora Siger](https://github.com/brunostrapazzon/scic-aurora-siger) | Análise de latência, previsão, alertas priorizados com heap e busca por prefixo com trie. |

### Com o que trabalho

- **IA e dados:** APIs de modelos de linguagem (Groq, OpenAI, Ollama), validação de saída, avaliação com métricas, detecção de anomalias
- **Automação:** Python, pytest, Git, GitHub Actions, PyInstaller, automação de comandos do Windows
- **Infraestrutura:** redes TCP/IP, DHCP, DNS, Wi-Fi, Windows, suporte ao usuário

### Contato

Procuro minha primeira vaga remota em automação ou IA aplicada. Veja o [portfólio](https://brunostrapazzon.github.io) ou fale comigo pelo [LinkedIn](https://www.linkedin.com/in/brunostrapazzon).

<sub>In English: Computer Science student at FIAP (Brazil), English B2, IT support since 2023. I build automation and AI systems you can check: deterministic rules where a model could be wrong, tests and metrics to know when it is right. Start with [NetDoctor](https://github.com/brunostrapazzon/NetDoctor) or the [English portfolio](https://brunostrapazzon.github.io/en/).</sub>
