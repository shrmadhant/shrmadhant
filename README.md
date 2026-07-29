# Mercer | Arquitetura de Sistemas & Engenharia de Software

Desenvolvedor orientado a performance, sistemas distribuídos e engenharia quantitativa. Não me dedico a colecionar linguagens ou acumular utilitários superficiais; meu foco é a construção de arquiteturas enxutas, determinísticas e resilientes, cobrindo da infraestrutura de baixo nível à camada de aplicação.

---

## ─── Pilares de Engenharia ───

### 1. Engenharia Quantitativa & Algoritmos de Trading
* **Sistemas de Execução:** Desenvolvimento de indicadores e robôs de negociação de alta precisão em **MQL5** e **Pine Script** (Metatrader 5 / TradingView).
* **Gestão de Risco & Volatilidade:** Implementação de algoritmos baseados em divergência de delta, estruturas de volatilidade e execução controlada.
* **Automação Financeira:** Integração de Webhooks e pontes de sinal para roteamento de ordens e alertas operacionais em tempo real.

### 2. Infraestrutura, Cibersegurança & Ambientes Unix
* **Hardening & Defesa de Servidores:** Configuração de ambientes Linux enxutos, aplicação de regras severas de firewall (`nftables`/`iptables`), privilégios mínimos e auditoria de logs.
* **Virtualização & Kernel:** Ambientes customizados em **Arch Linux**, orquestração de máquinas virtuais com **KVM / QEMU** e isolamento de processos por contêineres e sandboxes.
* **Sistemas Operacionais:** Domínio de rotinas Unix, automação via Shell Scripting, otimização de uso de memória e gerenciamento de processos.

### 3. Automação de Software, Bots & Backend
* **Engenharia de Bots:** Desenvolvimento de ecossistemas de automação para **Telegram**, **Discord** e **WhatsApp** (com e sem integração com modelos de IA/LLMs).
* **APIs & Serviços:** Backend orientado a concorrência, baixa latência e consumo consciente de recursos de hardware.
* **Sistemas Integrados:** Soluções de ponta a ponta conectando captação de eventos de mercado, processamento backend e distribuição de mensagens instantâneas.

---

## ─── Filosofia de Engenharia ───

> *"Complexidade desnecessária é o primeiro passo para a falha do sistema. Código de alta performance é enxuto, previsível e auditável."*

* **Resolução na Causa-Raiz:** Não aplico paliativos na camada de aplicação para problemas originados na infraestrutura ou no design de dados.
* **Pragmatismo Brutal:** Prefiro uma solução monolítica bem projetada e de altíssima performance a um emaranhado de microserviços inflados por modismo.
* **Segurança por Design:** Hardening, isolamento e controle de superfície de ataque integrados desde a concepção do código.

---

## ─── Stack & Ecossistema de Trabalho ───

| Domínio | Tecnologias & Ferramentas |
| :--- | :--- |
| **Quant & Linguagens** | MQL5, Pine Script, Python, C/C++, Bash/Shell Scripting |
| **Infra, Sec & Unix** | Arch Linux, KVM / QEMU, nftables, Docker, Systemd, Linux Hardening |
| **Backend & Mensageria** | APIs RESTful, WebSockets, Telegram API, WhatsApp Engine, Discord SDK |
| **Ambiente & Ferramental** | Git, Neovim/Vim, QEMU, Wireshark, Ferramentas de Análise de Tráfego |

---

## ─── Arquitetura de Projetos em Destaque ───

* **`quant-execution-bridge`**: Ponte de execução entre estratégia customizada (PineScript/MQL5) e serviço backend desacoplado com roteamento de alertas para Telegram.
* **`unix-hardened-environment`**: Conjunto de scripts e configurações declarativas para deploy de VPS Linux otimizada, isolada e com regras restritivas de acesso.
* **`multiplatform-bot-core`**: Core reutilizável para construção de bots multicanais com gerenciamento de estado e integrações modulares.

---

## ─── Contato & Links ───

- **GitHub:** [shrmadhant](https://github.com/shrmadhant)
- **Portfólio:** [Mercer](https://mercer-5bm.pages.dev)
