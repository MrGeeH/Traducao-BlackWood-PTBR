# 🇧🇷 BLACKWOOD - TRADUÇÃO PT-BR

Bem-vindo ao repositório da tradução para Português do Brasil (PT-BR) do jogo **Blackwood**. Abaixo você encontra todas as instruções de uso do nosso instalador automatizado.

---

## 📥 Como Instalar

1. Feche o jogo completamente.
2. Execute o arquivo `Blackwood_Traducao_PTBR.exe`.
   > **Nota:** O instalador tentará encontrar a pasta do jogo automaticamente. Se não conseguir, clique em **"Procurar..."** e escolha a pasta onde está localizado o arquivo `Blackwood.exe`.
3. Clique em **"Instalar tradução"**. O processo leva apenas alguns segundos.

## 🔄 Como Atualizar para uma Versão Nova

1. Feche o jogo.
2. Execute o **novo** arquivo `.exe` baixado e clique em **"Reinstalar / Atualizar"**. 
   > A versão anterior da tradução será removida e a nova será instalada automaticamente.

## 🗑️ Como Desinstalar

1. Feche o jogo.
2. Execute o mesmo instalador (`Blackwood_Traducao_PTBR.exe`) e clique em **"Desinstalar tradução"**.
   > Os arquivos do jogo voltarão a ser **idênticos aos originais** (byte a byte).

---

## ⚙️ O Que o Instalador Faz (Detalhes Técnicos)

Para garantir a segurança dos arquivos do seu jogo, o instalador atua da seguinte forma:

* **Verificação de Versão:** Antes de alterar qualquer coisa, ele confere se os arquivos do jogo são exatamente os da versão para a qual a tradução foi feita. Se não forem, ele aborta a operação e não modifica nada.
* **Sistema de Backup:** Guarda um backup automático na pasta `Blackwood_Data\ptbr_backup` (cerca de 90 MB). ⚠️ **Não apague essa pasta** enquanto a tradução estiver instalada, pois ela é necessária para a desinstalação.
* **Arquivos `.assets/levelN`:** Os textos traduzidos são anexados ao final do arquivo; o conteúdo original não é apagado.
* **Bundles da "Internet" (StreamingAssets):** O arquivo é substituído pela versão traduzida, mantendo o mesmo CRC do original.

## ⚠️ Se o Jogo For Atualizado

Uma atualização oficial do jogo pode acabar substituindo os arquivos traduzidos. Caso isso aconteça:
1. Faça a desinstalação padrão (o nosso desinstalador é inteligente e ignora o que a atualização oficial já trocou).
2. Baixe e instale uma **versão nova da tradução**, gerada especificamente para a nova versão do jogo.

---

## 💻 Linha de Comando (CLI)

Para usuários avançados, o instalador suporta argumentos via linha de comando:

**Instalar:**
```cmd
Blackwood_Traducao_PTBR.exe --install "C:\caminho\do\Blackwood" [arquivo_de_log]
```

**Desinstalar:**
```cmd
Blackwood_Traducao_PTBR.exe --uninstall "C:\caminho\do\Blackwood" [arquivo_de_log]
```

---

## 📝 O Que Ficou em Inglês (De Propósito)

Algumas partes do jogo foram mantidas no idioma original para evitar bugs ou por decisões de localização:

* Títulos de filmes, nomes de produtos, roupas, armas, peças, marcas e nomes próprios.
* Nomes internos usados pelo motor do jogo para controles e ícones (*traduzir essas strings quebraria o jogo*).
* Créditos e as dicas das palavras cruzadas (*as respostas da grade obrigatoriamente são em inglês*).
* Alguns textos gerados nativamente pelo próprio código do jogo (ex: *"Borderless"* na lista de modos de tela).
