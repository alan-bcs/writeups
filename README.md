# CTF Writeups

Repositório contendo relatórios e documentações técnicas (*writeups*) de resolução de desafios e máquinas virtuais das plataformas **TryHackMe** e **HackTheBox**.

---

## 📑 Índice de Writeups

### 🟢 HackTheBox

| Desafio / Máquina | Dificuldade | Relatório (PDF) |
| :--- | :---: | :---: |
| **CCTV** | Fácil | [writeup_cctv.pdf](hackthebox/writeup_cctv.pdf)
| **Connected** | Fácil | [writeup_connected.pdf](hackthebox/writeup_connected.pdf)
| **DevHub** | Média | [writeup_devhub.pdf](hackthebox/writeup_devhub.pdf)
| **Facts** | Média | [writeup_facts.pdf](hackthebox/writeup_facts.pdf)
| **Oopsie** | Fácil | [writeup_oopsie.pdf](hackthebox/writeup_oopsie.pdf)
| **Reactor** | Fácil/Média | [writeup_reactor.pdf](hackthebox/writeup_reactor.pdf)

### 🔴 TryHackMe

| Desafio / Máquina | Dificuldade | Relatório (PDF) |
| :--- | :---: | :---: |
| **Bounty Hacker** | Fácil | [writeup_bountyhacker.pdf](tryhackme/writeup_bountyhacker.pdf)
| **Chocolate Factory** | Fácil | [writeup_chocolate_factory.pdf](tryhackme/writeup_chocolate_factory.pdf)
| **Crack The Hash** | Fácil | [writeup_crackthehash.pdf](tryhackme/writeup_crackthehash.pdf)
| **Pickle Rick** | Fácil | [writeup_picklerick.pdf](tryhackme/writeup_picklerick.pdf)
| **RootMe** | Fácil | [writeup_rootme.pdf](tryhackme/writeup_rootme.pdf)
| **Simple CTF** | Fácil | [writeup_simplectf.pdf](tryhackme/writeup_simplectf.pdf)

---

## 📝 Template e Metodologia

O arquivo [template.tex](template.tex) contém a estrutura padrão em LaTeX adotada para a elaboração dos relatórios, garantindo consistência técnica e visual:

* **Capa e Metadados:** Título, plataforma, data, autor e tabela de informações do desafio.
* **Visão Geral (Sem Spoilers):** Descrição introdutória da superfície de ataque e objetivos sem adiantar credenciais ou respostas de forma prematura.
* **Reconhecimento:** Varredura de portas, serviços e enumeração de rotas (Nmap, Feroxbuster, etc.).
* **Exploração:** Vetor de entrada inicial, obtenção do *foothold* e consolidação do shell.
* **Movimentação Lateral:** Transição entre usuários e captura de credenciais intermediárias (quando aplicável).
* **Escalada de Privilégios:** Abuso de configurações do sistema, SUID, recursos de kernel ou `sudoers` para obtenção de acesso como `root`.
* **Conclusão e Recomendações:** Análise técnica da postura de segurança e medidas de mitigação.
* **Referências:** Links para ferramentas, documentações e base de conhecimento (GTFOBins, CVEs, etc.).
