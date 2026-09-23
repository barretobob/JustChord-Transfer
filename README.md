# JustChord Transfer

[Português](#português) • [English](#english)

---

## Português

**JustChord Transfer** adiciona cifras do **Cifra Club** e **Banana Cifras** diretamente à biblioteca do **JustChords** no macOS.

### Como funciona

1. Instale a extensão **JustChord Transfer** no Firefox.
2. Instale o **JustChord Transfer Helper** no macOS.
3. Abra uma cifra no Cifra Club ou Banana Cifras.
4. Clique em **Add to JustChord**.
5. A música é adicionada ao `library.json` do JustChords, com backup automático antes de cada alteração.

A extensão reconhece duplicatas e oferece **Substituir**, **Manter atual** ou **Duplicar**.

### Requisitos

- macOS
- Firefox Desktop 140 ou superior
- JustChords com a biblioteca disponível no iCloud Drive
- **Node.js instalado** no Mac (requisito do Helper v1.0)

### Instalação no macOS

#### 1. Extensão do Firefox

Instale o arquivo `.xpi` assinado da versão correspondente do JustChord Transfer.

#### 2. Helper

Baixe diretamente:

[**Download do Helper para macOS v1.0.0**](https://github.com/barretobob/JustChord-Transfer/releases/download/v1.0.0/JustChord-Transfer-Helper-macOS-v1.0.0.pkg)

ou pela página de **Releases**:

`JustChord-Transfer-Helper-macOS-v1.0.0.pkg`

Abra o `.pkg` e conclua a instalação. O instalador registra automaticamente o Native Messaging Host usado pelo Firefox.

Se o macOS avisar que o pacote vem de um desenvolvedor não identificado, isso acontece porque esta primeira versão do Helper ainda não está assinada/notarizada com um certificado Apple Developer ID.

#### 3. Reinicie o Firefox

Feche completamente o Firefox com `⌘Q` e abra novamente.

### Biblioteca do JustChords

O Helper tenta localizar automaticamente o arquivo `library.json` nos locais padrão do JustChords no iCloud Drive.

Antes de qualquer gravação, ele cria um backup local em:

`~/Library/Application Support/CifraClubJustChord/backups/`

### Privacidade

O conteúdo da cifra é enviado apenas do Firefox para o Helper local usando **Native Messaging**.

O projeto não envia cifras, biblioteca ou dados pessoais para servidores próprios ou serviços de terceiros.

### Sites suportados

- Cifra Club
- Banana Cifras

### Versão

**1.0.0**

### Windows

O JustChords atualmente é disponibilizado para plataformas Apple. Esta versão do Helper é somente para macOS.

---

## English

**JustChord Transfer** adds chord sheets from **Cifra Club** and **Banana Cifras** directly to the **JustChords** library on macOS.

### How it works

1. Install the **JustChord Transfer** Firefox extension.
2. Install the **JustChord Transfer Helper** on macOS.
3. Open a song on Cifra Club or Banana Cifras.
4. Click **Add to JustChord**.
5. The song is added to the JustChords `library.json` file, with an automatic backup created before every change.

The extension detects duplicates and offers **Replace**, **Keep current**, or **Duplicate**.

### Requirements

- macOS
- Firefox Desktop 140 or later
- JustChords with its library available in iCloud Drive
- **Node.js installed** on the Mac (required by Helper v1.0)

### macOS installation

#### 1. Firefox extension

Install the signed `.xpi` file for the corresponding JustChord Transfer version.

#### 2. Helper

Download directly:

[**Download Helper for macOS v1.0.0**](https://github.com/barretobob/JustChord-Transfer/releases/download/v1.0.0/JustChord-Transfer-Helper-macOS-v1.0.0.pkg)

or from the **Releases** page:

`JustChord-Transfer-Helper-macOS-v1.0.0.pkg`

Open the `.pkg` file and complete the installation. The installer automatically registers the Native Messaging Host used by Firefox.

If macOS warns that the package comes from an unidentified developer, this is because the current Helper package has not yet been signed/notarized with an Apple Developer ID certificate.

#### 3. Restart Firefox

Quit Firefox completely with `⌘Q`, then open it again.

### JustChords library

The Helper automatically tries to locate the `library.json` file in the standard JustChords iCloud Drive locations.

Before writing any changes, it creates a local backup in:

`~/Library/Application Support/CifraClubJustChord/backups/`

### Privacy

Chord-sheet content is sent only from Firefox to the local Helper through **Native Messaging**.

The project does not send chord sheets, library data, or personal data to its own servers or third-party services.

### Supported websites

- Cifra Club
- Banana Cifras

### Version

**1.0.0**

### Windows

JustChords is currently available on Apple platforms. This version of the Helper is for macOS only.
