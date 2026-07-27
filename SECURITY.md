# Security Policy / Política de Segurança

[English](#english) | [Português](#português)

---

## English

### Scope

This repository is a public, sanitized showcase of the ScriptPackage v0.1 concept extracted from the private MLI-Knot Video Forge Lite project.

It contains documentation, fictional examples, conceptual package structures, storyboard samples, and public-safe export descriptions. It is not the private prototype, a production service, a public API contract, or a distribution channel for real generated packages.

### Sensitive material that must not be published

Do not publish:

- private source code, internal architecture, unreleased implementation details, or repository history from MLI-Knot Video Forge Lite;
- private prompts, system instructions, activation text, hidden templates, internal generation rules, or unrevised prompt experiments;
- real ScriptPackage exports, manifests, storyboards, scripts, captions, narration, visual prompts, or metadata copied from private work without review;
- personal data, private conversations, client information, account identifiers, contact details, faces, voices, locations, or other identifying material;
- credentials, passwords, tokens, API keys, cookies, secrets, environment files, private URLs, signed links, or authentication data;
- local paths, usernames, device names, hostnames, project directories, cloud identifiers, repository URLs, or service configuration that reveal a private environment;
- internal logs, stack traces, request or response captures, job identifiers, analytics, debug output, or unrevised development notes;
- real audio, video, image, narration, subtitle, voice, music, or generated-media files that have not been approved for public release;
- copyrighted scripts, lyrics, images, audio, video, course material, brand assets, or third-party content without the required publication rights;
- hidden instructions, unsafe commands, executable payloads, or links presented as harmless fictional example content;
- any combination of otherwise small details that could reconstruct a private package, workflow, person, client, or operating environment.

Public examples must use fictional content, synthetic metadata, generic paths, placeholder identifiers, and assets that are safe and authorized for publication.

### ScriptPackage sanitization

Before publishing a JSON, Markdown, storyboard, manifest, export description, or related example:

1. replace real titles, names, clients, projects, brands, and identifiers with fictional values;
2. remove private prompts, internal instructions, and implementation-specific fields;
3. replace local paths, URLs, usernames, hostnames, job IDs, timestamps, and machine metadata;
4. remove personal, confidential, contractual, or unreleased content from scripts, narration, captions, and visual prompts;
5. verify that referenced media is fictional, public-safe, or properly licensed;
6. inspect nested metadata, comments, filenames, manifests, and auxiliary files;
7. confirm that the example cannot be combined with other public material to reconstruct the private prototype or a real production package;
8. mark the example clearly as fictional and sanitized.

Redaction alone may be insufficient when structure or context still reveals private information. Prefer recreating the example from scratch with synthetic content.

### Media and metadata

Audio, video, image, subtitle, PDF, HTML, and storyboard files may contain sensitive information outside their visible content.

Before publication, review:

- filenames and directory structures;
- embedded author, device, software, location, and creation metadata;
- thumbnails, alternate streams, subtitles, comments, and manifests;
- visible browser tabs, notifications, account menus, local paths, or editing timelines;
- voices, faces, private locations, logos, copyrighted material, or unreleased creative work;
- links to private storage, temporary downloads, cloud assets, or protected services.

When possible, recreate public examples using fictional assets instead of modifying real private exports.

### Security-relevant reports

A report is security-relevant when it concerns:

- accidental exposure of private prompts, source code, credentials, personal data, internal logs, or real exports;
- a package, manifest, media file, or example that reveals a private workflow or operating environment;
- repository history that still contains sensitive content removed from the current tree;
- a public link or artifact that grants unintended access to private content;
- a supposedly fictional example that identifies a real person, client, project, or unreleased work;
- executable, deceptive, or unsafe content embedded in an example or referenced resource;
- misuse of the MLI-Knot or Tendoshk identity to falsely claim an official package, service, standard, endorsement, or production API.

Typos, formatting errors, broken links, translation issues, and conceptual disagreements are normally documentation issues rather than security vulnerabilities, unless they expose or direct users to sensitive or unsafe material.

### Reporting a vulnerability or accidental exposure

Do not reproduce sensitive content in a public issue, discussion, pull request, review comment, or screenshot.

Use GitHub private vulnerability reporting when it is available for this repository. If it is unavailable, contact the maintainer through a private channel listed on the maintainer's GitHub profile.

Provide only the minimum information required for safe investigation:

- affected file, path, commit, release, page, or artifact;
- general category of exposed or unsafe content;
- whether the material is still publicly accessible;
- steps needed to locate the issue without repeating the sensitive value;
- potential impact;
- sanitized screenshots, logs, or excerpts when necessary.

Do not send complete tokens, real private prompts, confidential packages, personal documents, unreviewed media, or full copies of proprietary material unless a secure channel and a clear need have been established.

### Incident response

When sensitive or unsafe material is confirmed, the maintainer should evaluate the need to:

1. stop further publication;
2. remove or disable access to the affected file, page, release, or artifact;
3. assess commits, branches, tags, releases, caches, forks, and external mirrors;
4. rotate or revoke exposed credentials, tokens, links, or secrets;
5. notify affected people, clients, services, or rights holders when appropriate;
6. rewrite or purge public history when deletion from the latest commit is insufficient;
7. replace the material with a fictional, sanitized, and authorized example;
8. document the correction without reproducing the exposed content.

Deleting a file from the latest commit does not remove it from earlier Git history, releases, artifacts, forks, or caches.

### Public concept limitation

ScriptPackage v0.1 is a documented project concept. It is not presented here as an industry standard, stable public API, production file format, security boundary, compatibility guarantee, or authorization to process third-party content.

Security guarantees for the private prototype, future services, generated outputs, third-party integrations, or systems inspired by this documentation are outside this repository's public scope.

---

## Português

### Escopo

Este repositório é uma vitrine pública e sanitizada do conceito ScriptPackage v0.1 extraído do projeto privado MLI-Knot Video Forge Lite.

Ele contém documentação, exemplos fictícios, estruturas conceituais de pacote, amostras de storyboard e descrições públicas de exportação. Ele não é o protótipo privado, um serviço de produção, um contrato de API pública ou um canal de distribuição de pacotes reais gerados.

### Material sensível que não deve ser publicado

Não publique:

- código-fonte privado, arquitetura interna, detalhes de implementação ainda não lançados ou histórico do MLI-Knot Video Forge Lite;
- prompts privados, instruções de sistema, textos de ativação, templates ocultos, regras internas de geração ou experimentos de prompt não revisados;
- exports reais de ScriptPackage, manifestos, storyboards, roteiros, legendas, narrações, prompts visuais ou metadados copiados de trabalhos privados sem revisão;
- dados pessoais, conversas privadas, informações de clientes, identificadores de contas, contatos, rostos, vozes, localizações ou outro material identificável;
- credenciais, senhas, tokens, chaves de API, cookies, segredos, arquivos de ambiente, URLs privadas, links assinados ou dados de autenticação;
- caminhos locais, nomes de usuário, nomes de dispositivos, hostnames, diretórios de projetos, identificadores de nuvem, URLs de repositórios ou configurações de serviço que revelem um ambiente privado;
- logs internos, stack traces, capturas de requisições ou respostas, identificadores de jobs, analytics, saídas de debug ou notas de desenvolvimento não revisadas;
- arquivos reais de áudio, vídeo, imagem, narração, legenda, voz, música ou mídia gerada que não tenham sido aprovados para publicação;
- roteiros, letras, imagens, áudios, vídeos, materiais de curso, ativos de marca ou conteúdo de terceiros protegido sem os direitos necessários para publicação;
- instruções ocultas, comandos inseguros, cargas executáveis ou links apresentados como conteúdo fictício inofensivo;
- qualquer combinação de pequenos detalhes que permita reconstruir um pacote privado, fluxo de trabalho, pessoa, cliente ou ambiente operacional.

Exemplos públicos devem usar conteúdo fictício, metadados sintéticos, caminhos genéricos, identificadores placeholder e ativos seguros e autorizados para publicação.

### Sanitização de ScriptPackage

Antes de publicar JSON, Markdown, storyboard, manifesto, descrição de exportação ou exemplo relacionado:

1. substitua títulos, nomes, clientes, projetos, marcas e identificadores reais por valores fictícios;
2. remova prompts privados, instruções internas e campos específicos da implementação;
3. substitua caminhos locais, URLs, nomes de usuário, hostnames, identificadores de jobs, datas e metadados de máquina;
4. remova conteúdo pessoal, confidencial, contratual ou ainda não publicado de roteiros, narrações, legendas e prompts visuais;
5. confirme que as mídias referenciadas sejam fictícias, seguras para publicação ou devidamente licenciadas;
6. inspecione metadados aninhados, comentários, nomes de arquivos, manifestos e arquivos auxiliares;
7. confirme que o exemplo não possa ser combinado com outro material público para reconstruir o protótipo privado ou um pacote real de produção;
8. identifique claramente o exemplo como fictício e sanitizado.

A simples ocultação de trechos pode ser insuficiente quando a estrutura ou o contexto ainda revelam informações privadas. Prefira recriar o exemplo do zero com conteúdo sintético.

### Mídia e metadados

Arquivos de áudio, vídeo, imagem, legenda, PDF, HTML e storyboard podem conter informações sensíveis fora do conteúdo visível.

Antes da publicação, revise:

- nomes de arquivos e estruturas de diretórios;
- metadados incorporados de autor, dispositivo, software, localização e criação;
- miniaturas, fluxos alternativos, legendas, comentários e manifestos;
- abas do navegador, notificações, menus de conta, caminhos locais ou timelines de edição visíveis;
- vozes, rostos, locais privados, logotipos, material protegido ou trabalho criativo ainda não lançado;
- links para armazenamento privado, downloads temporários, ativos em nuvem ou serviços protegidos.

Quando possível, recrie exemplos públicos com ativos fictícios em vez de modificar exports privados reais.

### Relatos relevantes para segurança

Um relato é relevante para segurança quando envolve:

- exposição acidental de prompts privados, código-fonte, credenciais, dados pessoais, logs internos ou exports reais;
- pacote, manifesto, arquivo de mídia ou exemplo que revele um fluxo privado ou ambiente operacional;
- histórico do repositório que ainda contenha material sensível removido da árvore atual;
- link público ou artefato que conceda acesso não intencional a conteúdo privado;
- exemplo supostamente fictício que identifique pessoa, cliente, projeto ou trabalho ainda não lançado;
- conteúdo executável, enganoso ou inseguro incorporado a um exemplo ou recurso referenciado;
- uso indevido da identidade MLI-Knot ou Tendoshk para alegar falsamente pacote, serviço, padrão, endosso ou API de produção oficial.

Erros de digitação, formatação, links quebrados, tradução e divergências conceituais normalmente são problemas de documentação, e não vulnerabilidades, exceto quando expõem ou direcionam para material sensível ou inseguro.

### Como relatar vulnerabilidade ou exposição acidental

Não reproduza conteúdo sensível em issue, discussão, Pull Request, comentário de revisão ou captura pública.

Utilize o relato privado de vulnerabilidade do GitHub quando estiver disponível neste repositório. Caso não esteja, contate o mantenedor por um canal privado indicado no perfil do mantenedor no GitHub.

Forneça somente o mínimo necessário para uma investigação segura:

- arquivo, caminho, commit, release, página ou artefato afetado;
- categoria geral do conteúdo exposto ou inseguro;
- indicação se o material ainda está acessível publicamente;
- passos para localizar o problema sem repetir o valor sensível;
- impacto potencial;
- capturas, logs ou trechos sanitizados quando necessários.

Não envie tokens completos, prompts privados reais, pacotes confidenciais, documentos pessoais, mídias não revisadas ou cópias integrais de material proprietário sem que exista canal seguro e necessidade clara.

### Resposta a incidentes

Quando material sensível ou inseguro for confirmado, o mantenedor deverá avaliar a necessidade de:

1. interromper novas publicações;
2. remover ou desativar o acesso ao arquivo, página, release ou artefato afetado;
3. avaliar commits, branches, tags, releases, caches, forks e espelhos externos;
4. revogar ou substituir credenciais, tokens, links ou segredos expostos;
5. notificar pessoas, clientes, serviços ou titulares de direitos afetados quando apropriado;
6. reescrever ou limpar o histórico público quando a exclusão no commit mais recente for insuficiente;
7. substituir o material por exemplo fictício, sanitizado e autorizado;
8. documentar a correção sem reproduzir o conteúdo exposto.

Excluir um arquivo no commit mais recente não o remove do histórico Git anterior, releases, artefatos, forks ou caches.

### Limitação do conceito público

O ScriptPackage v0.1 é um conceito documentado do projeto. Ele não é apresentado aqui como padrão da indústria, API pública estável, formato de produção, limite de segurança, garantia de compatibilidade ou autorização para processar conteúdo de terceiros.

Garantias de segurança do protótipo privado, serviços futuros, saídas geradas, integrações de terceiros ou sistemas inspirados nesta documentação estão fora do escopo público deste repositório.
