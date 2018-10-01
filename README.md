<img src="https://braimlab.com/midias/braim-logo_final.svg" alt="Logo Braim" width="auto" height="100">

> Esse repositório automatiza a criação da arquitetura de pastas padrão para o gerenciamento do projeto.


Iniciando
=========


A cada novo projeto, clone este repositório __na pasta do cliente.__

Use o comando: `git clone https://github.com/igorgomesdev/braim-source.git`

Estrutura de pastas
---------

```
OneDrive/Dev-Chimp/Clientes/                                        # → Raiz da pasta
├── cliente1/                                                       # → Nome do Cliente
│   ├── _Site/                                                      # → Arquivos do site
│   │   ├── plugins/                                                # → Plugins específicos daquele site
│   │   ├── public_html/                                            # → Arquivos do Wordpress (betheme > wp-content > ...)
│   │   └── arquivos.html.css                                       # → Outros arquivos usados no site
│   ├── Backup/                                                     
│   │   ├── Betheme - MuffinBuilder/                                # → Backup dos arquivos do Betheme
│   │   ├── Exportador do Wordpress/                                # → Backup do exportador do Wordpress
│   │   ├── Páginas/                                                # → Backup das páginas do site
│   │   └── Site/                                                   # → Backup dos arquivos do site
│   ├── Design/                                                     
│   │   ├── Formas/                                                 # → Formas/Shapes exportados do Photoshop
│   │   ├── Fundos/                                                 # → Imagens de fundo
│   │   ├── Fontes/                                                 # → Fontes personalizadas
│   │   └── Logos/                                                  # → Logos do cliente
│   ├── Outros/                                                     # → Pasta livre
│   ├── Senhas e Licenças/
│   │   ├── catalogo-de-emails.txt                                  # → Senhas e-mails
│   │   ├── cpanel.txt                                              # → Senha cPanel
│   │   └── licença-betheme.txt                                     # → Chave da licença do Betheme
│   ├── SEO/
│   │   ├── Google Search Console/
│   │   │   └── google1a2b3c4d5e6f7g8h9.html                        # → Arquivo de verificação do Google Search Console
│   │   └── palavras-chave.txt                                      # → Palavras chave para SEO
```
