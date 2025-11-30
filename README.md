🌐 AULAS HARD – Introdução às Redes e Internet + Git
📘 Resumo completo das aulas | Professor: Kenji Taniguchi & Felipe Ozias

✨ Visão Geral

Este README reúne resumos claros, didáticos e organizados de todas as aulas HARD do curso Introdução às Redes e à Internet e Git.
Cada tópico possui explicações simples, curtas e ideais para consulta rápida.
Perfeito para estudos, revisões e provas.

📚 AULA HARD #1 – Protocolos de Comunicação em Redes
🧩 Matéria: Introdução às Redes e à Internet

🔹 Topologia utilizada pelos backbones

Backbones usam topologia em malha (mesh) para garantir alta redundância e rotas alternativas caso um enlace falhe.

🔹 Semiótica na rede de computadores

Estuda como mensagens e sinais são interpretados na comunicação — essencial para entender protocolos.

🔹 Internet x Intranet x Extranet

🌍 Internet: rede global pública.

🏢 Intranet: rede privada interna.

🔗 Extranet: parte da intranet acessível a parceiros externos.

🔹 AJAX

Permite atualizar partes da página sem recarregar tudo, usando JavaScript + HTTP.

🔹 Ferramentas UI/UX

Figma, Adobe XD e Sketch ajudam a planejar telas intuitivas e funcionais.

🔹 IA x Machine Learning

🤖 IA: máquinas que imitam inteligência.

📈 ML: técnica dentro da IA que aprende com dados.

📚 AULA HARD #2 – Endereçamento IP, Sub-redes e Portas

🔹 NAT

Traduz IPs privados → públicos para economizar IPv4.
Problemas: quebra de ponta a ponta, dificulta P2P e geolocalização.

🔹 TCP x UDP

TCP: confiável, com confirmação.

UDP: rápido, sem garantia.
A web usa TCP por confiabilidade.

🔹 TLS

Criptografa e autentica comunicações. Impede espionagem, adulteração e fraudes.

🔹 Contratos Inteligentes

Programas que executam regras automaticamente em blockchains.

📚 AULA HARD #3 – Serviços e Aplicações na Internet

🔹 Confiabilidade

Erros podem vir de falha de rede, perda de pacotes ou aplicações mal projetadas.

🔹 IPv4 → IPv6

IPv6 resolve o esgotamento de endereços e melhora a eficiência.

🔹 Unicast / Multicast / Broadcast

👤 Unicast: um para um

👥 Multicast: um para grupo

📢 Broadcast: um para todos

🔹 Bloqueio de portas

Provedores bloqueiam por segurança; solução: VPN, portas alternativas ou tunelamento.

🔹 QoS

Controla prioridade e qualidade do tráfego.

🔹 VPN

Cria um túnel seguro criptografado entre cliente e servidor.

📚 AULA HARD #4 – Serviços e Aplicações

🔹 API RESTful

Interface que usa HTTP para troca de dados de forma padronizada.

🔹 Arquitetura em 3 camadas

Apresentação

Lógica

Dados

🔹 JSON x XML

JSON: leve, moderno, usado na web.

XML: mais verboso, porém flexível.

🔹 Protobuf

Formato binário, muito mais rápido e compacto que JSON.

🔹 YAML

Formato simples para configurações (Docker, Kubernetes, CI/CD).

🔹 Microsserviços

Arquitetura onde cada serviço é independente, escalável e distribuído.

🔹 OAuth

Permite autenticação usando terceiros (Google, Facebook).

🔹 DDoS

Ataques que sobrecarregam servidores. Soluções: WAF, rate limiting, CDN.

📚 AULA HARD #5 – DNS

🔹 Envenenamento de Cache

Engana resolvers com IPs falsos.
Evita-se com DNSSEC e validação.

🔹 NS Lookup

Ferramenta para consultar registros DNS.

🔹 Registro PTR

Aponta IP → domínio; difícil pela necessidade de permissões do provedor.

🔹 DNS Dinâmico

Atualiza registros automaticamente quando o IP muda.

🔹 Migração de Domínio

Requer cuidado para evitar indisponibilidade e perda de e-mails.

🔹 Registro de Domínio

Feito por entidades como Registro.br, com regras e prazos de renovação.

📚 AULA HARD #6 – Arquitetura da Internet

🔹 Ataques DDoS

Saturam um servidor com tráfego falso.
Mitigação:

blackholing

rate limiting

Firewalls/Cloudflare

🔹 Roteamento Unicast/Multicast

Define como pacotes são enviados individualmente ou para grupos.

📚 AULA HARD #7 – Redes de Computadores

🔹 Latência

Tempo de resposta da rede. Influenciada por distância, saltos e congestionamento.

🔹 Insider Threat

Ameaça interna causada por funcionários. Prevenção: controle de acesso e monitoramento.

🔹 LAN, WAN, MAN, PAN

LAN: local

WAN: longa distância

MAN: metropolitana

PAN: pessoal

🔹 Ethernet x Token Ring

Token Ring usa passagem de token e evita colisões — muito eficiente, porém obsoleto.

📚 AULA HARD #8 – Segurança de Redes

🔹 Ameaças

Phishing, ransomware, MITM, DDoS.
IA aumenta o poder da engenharia social.

🔹 CIA (Disponibilidade, Integridade, Confidencialidade)

Pilares da segurança.

🔹 Malwares

Softwares maliciosos que exploram falhas.

🔹 VPN Remota, Site-to-Site e alternativas

Conectam usuários ou redes inteiras por criptografia.

🔹 Container x VM

Containers são leves; VMs isolam mais.

🔹 Patches

Atualizações que corrigem vulnerabilidades.

🔹 ORM

Mapeamento de objetos para bancos de dados — evita SQL Injection.

📚 AULA HARD #9 – Segurança na Web

🔹 HTTPS

Criptografia + integridade + autenticação.

🔹 TLS/SSL

Usa chaves assimétricas no handshake e chave simétrica nos dados.

🔹 Certificados

Emitidos por CAs após validação (HTTP, DNS ou arquivo).

🔹 Validade e renovação

Certificados expiram; sites ficam inseguros e podem ser bloqueados.

🔹 Objetivos da Criptografia

Confidencialidade

Integridade

Autenticidade

🔹 Criptografia ponta a ponta

Só origem/destino leem a mensagem.

📚 AULA HARD #10 – Tendências e Desafios nas Redes Modernas

🔹 IoT

Desafios de segurança, conectividade e protocolos como MQTT, CoAP.

🔹 SDN

Separa o plano de controle do de dados — redes programáveis.

🔹 Blockchain

Estrutura em blocos encadeados + consenso distribuído.

🔹 CDNs

Proteção, caching, performance (Cloudflare, Akamai).

🔹 Cloud vs On-Premise

Nuvem = escalável.
Local = mais controle, porém mais custos.

🔹 Serviços

Cloudflare (WAF, CDN, DNS)
AWS S3 (armazenamento escalável)

📚 AULA HARD Git #1 – Git, VSCode e GitLens

🔹 O que é Git

Git é um sistema de controle de versão que registra todas as mudanças feitas no projeto, permitindo voltar no tempo, criar ramificações (branches) e trabalhar em equipe com segurança.

🔹 O que é VS Code

VS Code (Visual Studio Code) é um editor de código leve, rápido e extensível, usado para programar, editar arquivos, integrar com Git e instalar extensões como o GitLens.

🔹 Configurações

Feitas em:

git config --global …

🔹 Restore x Reset

restore: recupera arquivos
reset: altera histórico

🔹 GitLens

Extensão do VSCode para visualizar histórico, autores e comparar mudanças.

🔹 Boas práticas

Commits pequenos, mensagens claras, branches organizadas.

📚 AULA HARD Git #2 – Branches e Merge

🔹 Branch

Linha separada de desenvolvimento.

🔹 HEAD

Aponta para o commit atual.

🔹 git stash

Guarda mudanças temporariamente.

🔹 Merge

Combina branches; pode gerar conflitos.

📚 AULA HARD Git #3 - Respositório remoto

O que é um repositório remoto?

É uma cópia do seu projeto armazenada na nuvem (como no GitHub).
Ele permite guardar, compartilhar e sincronizar seu código com outras pessoas ou outros computadores.

Pontos importantes
1️⃣ Criar um repositório remoto

Você cria um espaço vazio no GitHub onde o seu projeto será enviado.

2️⃣ Conectar seu projeto ao repositório remoto

Depois de criar o repositório online, você liga o seu projeto local a ele.
A partir daí, seu computador “sabe” para onde deve enviar as atualizações.

3️⃣ Enviar seu projeto para o remoto

Após conectar, você pode mandar todos os arquivos do seu projeto para o GitHub.

4️⃣ Enviar novas alterações

Sempre que fizer mudanças no seu código, você salva localmente e envia para o repositório remoto para manter tudo atualizado.

5️⃣ Baixar alterações do remoto

Caso tenha mudanças no GitHub (seja você ou outra pessoa), você pode baixar essas modificações para o seu computador.

Resumo

O repositório remoto é onde seu projeto mora na internet.
Você envia mudanças e baixa atualizações para manter tudo sincronizado com o GitHub.

📚 AULA HARD Git #4 -

O que é um Pull Request?

É um pedido para revisar e juntar o código de uma branch em outra (normalmente para a principal, a main).
É uma forma organizada de colaborar, revisar e aprovar código antes dele entrar no projeto oficial.

Pontos importantes
1️⃣ Quando usar um Pull Request

Quando você cria uma branch separada para trabalhar em algo específico.

Quando quer revisar o que mudou antes de juntar ao projeto principal.

Quando trabalha em equipe (ou mesmo sozinho, para manter histórico organizado).

2️⃣ Como funciona um PR

Você envia sua branch para o GitHub e abre um Pull Request dizendo:
“Essas são as alterações que quero adicionar ao projeto principal.”

3️⃣ Revisão do PR

Outras pessoas (ou só você mesmo) podem:

Ver todas as alterações

Comentar linha por linha

Discutir ideias

Pedir ajustes

Aprovar a mudança

4️⃣ Fazer o merge

Quando tudo estiver revisado e aprovado, as alterações são integradas à branch principal.

5️⃣ Apagar a branch depois

Após o merge, a branch de trabalho normalmente é removida, porque ela já cumpriu sua função.

Resumo

Pull Request é um processo para revisar, discutir e aprovar mudanças antes de adicioná-las ao projeto.
Ele garante mais organização, controle e qualidade no código.
