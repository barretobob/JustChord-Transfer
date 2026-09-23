# JustChord Transfer

**JustChord Transfer** adiciona cifras do **Cifra Club** e **Banana Cifras** diretamente à biblioteca do **JustChords** no macOS.

## Como funciona

1. Instale a extensão **JustChord Transfer** no Firefox.
2. Instale o **JustChord Transfer Helper** no macOS.
3. Abra uma cifra no Cifra Club ou Banana Cifras.
4. Clique em **Add to JustChord**.
5. A música é adicionada ao `library.json` do JustChords, com backup automático antes de cada alteração.

A extensão reconhece duplicatas e oferece **Substituir**, **Manter atual** ou **Duplicar**.

## Requisitos

- macOS
- Firefox Desktop 140 ou superior
- JustChords com a biblioteca disponível no iCloud Drive
- **Node.js instalado** no Mac (requisito do Helper v1.0)

## Instalação no macOS

### 1. Extensão do Firefox

Instale o arquivo `.xpi` assinado da versão correspondente do JustChord Transfer.

### 2. Helper

Baixe em **Releases**:

`JustChord-Transfer-Helper-macOS-v1.0.0.pkg`

Abra o `.pkg` e conclua a instalação. O instalador registra automaticamente o Native Messaging Host usado pelo Firefox.

Se o macOS avisar que o pacote vem de um desenvolvedor não identificado, isso acontece porque esta primeira versão do Helper ainda não está assinada/notarizada com um certificado Apple Developer ID. Uma versão assinada pode ser distribuída futuramente sem esse aviso.

### 3. Reinicie o Firefox

Feche completamente o Firefox com `⌘Q` e abra novamente.

## Biblioteca do JustChords

O Helper tenta localizar automaticamente `library.json` nos locais padrão do JustChords no iCloud Drive. Antes de qualquer gravação, ele cria um backup local em:

`~/Library/Application Support/CifraClubJustChord/backups/`

## Privacidade

O conteúdo da cifra é enviado apenas do Firefox para o Helper local usando **Native Messaging**. O projeto não envia cifras, biblioteca ou dados pessoais para servidores próprios ou serviços de terceiros.

## Sites suportados

- Cifra Club
- Banana Cifras

## Versão

**1.0.0**

## Observação sobre Windows

O JustChords atualmente é disponibilizado para plataformas Apple. Esta versão do Helper é somente para macOS.
