
# 🛡️ Guia Prático de Segurança Digital - CMEI Araras

![Status](https://img.shields.io/badge/Status-Concluído-success)
![License](https://img.shields.io/badge/License-MIT-blue)
![LaTeX](https://img.shields.io/badge/Typeset-LaTeX-008080?logo=latex)

Projeto de **Atividade Extensionista I** do curso de Ciência da Computação (UFBRA), desenvolvido para combater a vulnerabilidade digital em comunidades escolares da periferia.

## 🎯 Sobre o Projeto
Este repositório contém o código-fonte em LaTeX do e-book **"Guia Prático de Segurança Digital: Protegendo sua Família e seu Bolso"**. 
O material foi criado como material de apoio (Takeaway) após uma oficina presencial com as servidoras e a comunidade do **CMEI Araras** (Palmas/TO).

O foco deste projeto é o letramento digital empoderador, transformando jargões técnicos de cibersegurança em hábitos simples do dia a dia, com forte alinhamento aos Objetivos de Desenvolvimento Sustentável da ONU:
- **ODS 5:** Igualdade de Gênero (Capacitação de um corpo docente majoritariamente feminino).
- **ODS 10:** Redução das Desigualdades (Prevenção contra fraudes e golpes financeiros na periferia).

## 🛠️ Tecnologias Abordadas no Guia
O manual instrui o público leigo a configurar um "Ecossistema de Defesa Pessoal" mobile:
* **Brave Browser:** Navegação limpa e bloqueio de rastreadores (Anti-fingerprinting).
* **Bitwarden:** Cofre digital de senhas utilizando criptografia e biometria.
* **AdGuard DNS:** Filtro em nível de rede para controle parental e bloqueio de conteúdo adulto.
* **Cartões Virtuais & NFC:** Blindagem de ativos financeiros contra o golpe da maquininha e fraudes online.
* **DuckDuckGo Email Protection:** Mascaramento de identidade digital.

## 🚀 Como compilar este E-book
Este documento foi tipografado utilizando a linguagem LaTeX para garantir estabilidade e qualidade editorial profissional.

### Pré-requisitos
* Distribuição TeX (Recomendado: [MiKTeX](https://miktex.org/))
* Um editor LaTeX (Recomendado: [TeXstudio](https://www.texstudio.org/))

### 📂 Estrutura de Diretórios
```text
g### 📂 Estrutura de Diretórios
```text
guia-seguranca-cmei-araras/
│
├── main.tex                 # Arquivo principal de compilação
├── referencias.bib          # Arquivo de referências (BibTeX)
│
├── imagens/                 # Ativos visuais (PNGs, logos e capturas de tela)
│   ├── ...
│
└── capitulos/               # Seções modulares do E-book
    ├── 00_capa.tex
    ├── 01_prefacio.tex
    ├── 02_brave.tex
    ├── 03_bitwarden.tex
    ├── 04_adguard.tex
    ├── 05_cartoes_e_golpes.tex
    ├── 06_duckduckgo.tex
    └── 06_conclusao_final.tex
```

### Passos para compilação
1. Clone este repositório:
   ```bash
   git clone https://github.com/naygNo/guia-seguranca-cmei-araras.git
   ```
2. Abra o arquivo `main.tex` no seu editor.
3. Certifique-se de que a compilação de pacotes automáticos (*on-the-fly*) está ativada.
4. Compile usando **PdfLaTeX**.

## 👨‍💻 Autor
**Naygno Barbosa Noia**  
Acadêmico de Ciência da Computação - UFBRA  
[Acesse meu perfil no GitHub](https://github.com/naygno)

## 📄 Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes. O compartilhamento deste material para fins educacionais é fortemente encorajado.



