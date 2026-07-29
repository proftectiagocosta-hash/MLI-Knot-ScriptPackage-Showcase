# Contributing Guide / Guia de Contribuição

[English](#english) | [Português](#português)

Thank you for your interest in improving the MLI-Knot ScriptPackage Showcase.

Obrigado pelo interesse em melhorar o MLI-Knot ScriptPackage Showcase.

---

## English

### Repository purpose

This repository is a public, sanitized documentation showcase for the ScriptPackage v0.1 concept extracted from the private MLI-Knot Video Forge Lite project.

It is not the private prototype, a production service, a public API contract, a stable industry format, or a channel for publishing real generated packages.

Contributions must preserve this boundary.

### Appropriate contributions

Useful contributions may include:

- corrections to spelling, grammar, translation, formatting, or broken links;
- improvements to conceptual clarity;
- safer or clearer explanations of current limits;
- fictional and sanitized ScriptPackage examples;
- fictional storyboard examples;
- conceptual diagrams that do not reveal private implementation details;
- consistency improvements between JSON, Markdown, and documentation examples;
- corrections related to privacy, security, attribution, or licensing;
- documentation improvements for the public export flow or public boundary.

### Contributions outside this repository's scope

Do not submit:

- private source code from MLI-Knot Video Forge Lite;
- requests or instructions intended to expose or reconstruct the private repository;
- private prompts, system instructions, activation text, hidden templates, internal rules, or unrevised experiments;
- real ScriptPackage exports, manifests, storyboards, scripts, narration, captions, prompts, metadata, or generated outputs from private work;
- personal data, client material, private conversations, account details, local paths, usernames, device names, hostnames, job identifiers, or private URLs;
- credentials, tokens, API keys, cookies, secrets, environment files, or authentication data;
- internal logs, stack traces, analytics, request or response captures, or private development history;
- copyrighted text, images, audio, video, music, course material, brand assets, or other third-party content without publication rights;
- executable payloads, unsafe commands, deceptive links, or hidden instructions presented as examples;
- claims that ScriptPackage v0.1 is an industry standard, stable public API, production format, compatibility guarantee, or official authorization to process third-party content;
- production functionality, backend code, integrations, or implementation details from the private prototype.

This repository does not provide access to the private MLI-Knot Video Forge Lite project.

### Public and private boundary

Before contributing, read:

- [`README.md`](README.md);
- [`SECURITY.md`](SECURITY.md);
- [`docs/public-boundary.md`](docs/public-boundary.md);
- [`LICENSE.md`](LICENSE.md);
- [`NOTICE.md`](NOTICE.md).

A contribution must be:

- public;
- safe to share;
- fictional when needed;
- sanitized;
- useful for explaining ScriptPackage;
- consistent with the documented limits.

If there is uncertainty about whether material is safe for publication, keep it private and do not include it in an issue, Pull Request, review comment, attachment, or screenshot.

### Fictional examples and sanitization

Public examples should preferably be created from scratch using synthetic content rather than adapted from real private exports.

Before submitting JSON, Markdown, storyboard, manifest, export description, diagram, screenshot, or media-related material:

1. replace real names, clients, brands, projects, titles, and identifiers with fictional values;
2. remove private prompts, hidden instructions, implementation-specific fields, and unreleased structures;
3. replace local paths, URLs, usernames, hostnames, timestamps, job IDs, and machine metadata;
4. remove personal, confidential, contractual, or unreleased content;
5. inspect nested metadata, comments, filenames, manifests, and auxiliary files;
6. verify that every referenced asset is fictional, public-safe, or properly licensed;
7. ensure that the contribution cannot be combined with other public information to reconstruct the private prototype or a real production package;
8. label examples clearly as fictional and sanitized.

Redaction alone may be insufficient when structure or context still reveals private information.

### Media, screenshots, and metadata

Images, audio, video, subtitles, PDFs, HTML exports, and storyboards may contain sensitive information outside their visible content.

Review:

- filenames and directory structures;
- author, device, software, location, and creation metadata;
- thumbnails, subtitles, comments, manifests, and alternate streams;
- visible browser tabs, notifications, account menus, local paths, or editing timelines;
- faces, voices, private locations, logos, copyrighted material, and unreleased creative work;
- links to private storage, temporary downloads, protected services, or cloud assets.

Do not attach unreviewed media or screenshots to public issues or Pull Requests.

### Documentation style

Keep contributions clear, factual, and proportional to the public showcase.

When editing documentation:

- preserve the distinction between confirmed behavior, conceptual description, limitation, and future possibility;
- do not convert an experimental concept into a promise or guarantee;
- avoid claims about production readiness, security guarantees, compatibility, performance, or support unless they are explicitly documented and evidenced;
- keep links relative when referring to files inside this repository;
- use descriptive headings and readable Markdown;
- preserve bilingual structure when editing a bilingual document;
- update both language sections when a change affects shared meaning.

### JSON examples

JSON examples must remain valid JSON and must not contain comments, trailing commas, private values, or executable content.

A proposed local validation command is:

```bash
python -m json.tool examples/sanitized-scriptpackage.json
```

Run the equivalent command for the exact JSON file you changed.

Only report a validation as completed when you actually ran it and observed the result.

### Markdown and link review

For Markdown changes:

- preview the rendered document;
- verify headings, lists, code fences, and internal links;
- confirm that links to repository files resolve correctly;
- check that no private URL or local path was introduced;
- review both English and Portuguese sections when applicable.

This repository does not currently claim an automated Markdown or link-checking workflow. Do not describe a check as automated unless such automation actually exists.

### Preparing a Pull Request

Use a focused branch and keep each Pull Request limited to one coherent objective.

A Pull Request should explain:

- what changed;
- why the change is useful for the public showcase;
- the exact files changed;
- how fictionalization and sanitization were reviewed;
- which validations were actually executed;
- which validations were not executed;
- whether third-party material is included and under which license or permission;
- any remaining limitation or uncertainty.

Avoid mixing unrelated documentation, example, licensing, and security changes in the same Pull Request.

### Contributor checklist

```text
[ ] The contribution is appropriate for a public documentation showcase
[ ] No private source code or implementation detail is included
[ ] No private prompt, instruction, export, log, or unrevised material is included
[ ] No personal, client, credential, local-environment, or confidential data is included
[ ] Examples are fictional and explicitly marked as sanitized
[ ] JSON is valid when JSON files are changed
[ ] Markdown and links were reviewed when documentation is changed
[ ] Media and metadata were reviewed when files or screenshots are included
[ ] Rights and licenses for third-party material were confirmed
[ ] ScriptPackage limitations and non-standard status were preserved
[ ] Executed validations are listed accurately
[ ] Non-executed validations are declared honestly
[ ] The Pull Request has one focused objective
```

### Security reports

Do not reproduce sensitive material in a public issue, Pull Request, review comment, discussion, or screenshot.

Follow [`SECURITY.md`](SECURITY.md) and use GitHub private vulnerability reporting when available. If it is unavailable, contact the maintainer through a private channel listed on the maintainer's GitHub profile.

Provide only the minimum information required to locate and investigate the issue safely.

### License and contribution rights

This public documentation showcase is released under CC BY-NC 4.0 unless otherwise stated.

By submitting a contribution, you confirm that:

- you created the submitted material or have the rights required to publish it;
- the contribution may be distributed under the repository's applicable license;
- third-party material is identified with its source, license, and required attribution;
- the contribution does not grant access to, authorization over, or rights in the private MLI-Knot Video Forge Lite project;
- commercial use remains subject to the terms and authorization requirements documented in [`LICENSE.md`](LICENSE.md).

Maintainers may request changes, reject material that does not fit the public boundary, or remove content later found to be unsafe, unauthorized, misleading, or insufficiently sanitized.

---

## Português

### Objetivo do repositório

Este repositório é uma vitrine pública e sanitizada de documentação do conceito ScriptPackage v0.1 extraído do projeto privado MLI-Knot Video Forge Lite.

Ele não é o protótipo privado, um serviço de produção, um contrato de API pública, um formato estável da indústria nem um canal para publicar pacotes reais gerados.

As contribuições devem preservar essa fronteira.

### Contribuições adequadas

Contribuições úteis podem incluir:

- correções de ortografia, gramática, tradução, formatação ou links quebrados;
- melhorias de clareza conceitual;
- explicações mais seguras ou claras das limitações atuais;
- exemplos fictícios e sanitizados de ScriptPackage;
- exemplos fictícios de storyboard;
- diagramas conceituais que não revelem detalhes privados de implementação;
- melhorias de consistência entre exemplos JSON, Markdown e documentação;
- correções relacionadas a privacidade, segurança, atribuição ou licenciamento;
- melhorias documentais do fluxo público de exportação ou da fronteira pública.

### Contribuições fora do escopo deste repositório

Não envie:

- código-fonte privado do MLI-Knot Video Forge Lite;
- solicitações ou instruções destinadas a expor ou reconstruir o repositório privado;
- prompts privados, instruções de sistema, textos de ativação, templates ocultos, regras internas ou experimentos não revisados;
- exports reais de ScriptPackage, manifestos, storyboards, roteiros, narrações, legendas, prompts, metadados ou saídas geradas de trabalhos privados;
- dados pessoais, materiais de clientes, conversas privadas, dados de contas, caminhos locais, nomes de usuário, nomes de dispositivos, hostnames, identificadores de jobs ou URLs privadas;
- credenciais, tokens, chaves de API, cookies, segredos, arquivos de ambiente ou dados de autenticação;
- logs internos, stack traces, analytics, capturas de requisições ou respostas ou histórico privado de desenvolvimento;
- textos, imagens, áudios, vídeos, músicas, materiais de curso, ativos de marca ou outro conteúdo de terceiros protegido sem direitos de publicação;
- cargas executáveis, comandos inseguros, links enganosos ou instruções ocultas apresentados como exemplos;
- alegações de que o ScriptPackage v0.1 é padrão da indústria, API pública estável, formato de produção, garantia de compatibilidade ou autorização oficial para processar conteúdo de terceiros;
- funcionalidades de produção, código de backend, integrações ou detalhes de implementação do protótipo privado.

Este repositório não fornece acesso ao projeto privado MLI-Knot Video Forge Lite.

### Fronteira pública e privada

Antes de contribuir, leia:

- [`README.md`](README.md);
- [`SECURITY.md`](SECURITY.md);
- [`docs/public-boundary.md`](docs/public-boundary.md);
- [`LICENSE.md`](LICENSE.md);
- [`NOTICE.md`](NOTICE.md).

Uma contribuição deve ser:

- pública;
- segura para compartilhamento;
- fictícia quando necessário;
- sanitizada;
- útil para explicar o ScriptPackage;
- coerente com as limitações documentadas.

Quando houver incerteza sobre a segurança de publicação, mantenha o material privado e não o inclua em issue, Pull Request, comentário de revisão, anexo ou captura.

### Exemplos fictícios e sanitização

Exemplos públicos devem preferencialmente ser criados do zero com conteúdo sintético, em vez de adaptados de exports privados reais.

Antes de enviar JSON, Markdown, storyboard, manifesto, descrição de exportação, diagrama, captura ou material relacionado a mídia:

1. substitua nomes, clientes, marcas, projetos, títulos e identificadores reais por valores fictícios;
2. remova prompts privados, instruções ocultas, campos específicos da implementação e estruturas ainda não lançadas;
3. substitua caminhos locais, URLs, nomes de usuário, hostnames, datas, identificadores de jobs e metadados de máquina;
4. remova conteúdo pessoal, confidencial, contratual ou ainda não publicado;
5. inspecione metadados aninhados, comentários, nomes de arquivos, manifestos e arquivos auxiliares;
6. confirme que todos os ativos referenciados sejam fictícios, seguros para publicação ou devidamente licenciados;
7. confirme que a contribuição não possa ser combinada com outras informações públicas para reconstruir o protótipo privado ou um pacote real de produção;
8. identifique claramente os exemplos como fictícios e sanitizados.

A simples ocultação de trechos pode ser insuficiente quando a estrutura ou o contexto ainda revelam informações privadas.

### Mídias, capturas e metadados

Imagens, áudios, vídeos, legendas, PDFs, exports HTML e storyboards podem conter informações sensíveis fora do conteúdo visível.

Revise:

- nomes de arquivos e estruturas de diretórios;
- metadados de autor, dispositivo, software, localização e criação;
- miniaturas, legendas, comentários, manifestos e fluxos alternativos;
- abas do navegador, notificações, menus de conta, caminhos locais ou timelines de edição visíveis;
- rostos, vozes, locais privados, logotipos, material protegido e trabalho criativo ainda não lançado;
- links para armazenamento privado, downloads temporários, serviços protegidos ou ativos em nuvem.

Não anexe mídias ou capturas não revisadas a issues ou Pull Requests públicos.

### Estilo da documentação

Mantenha as contribuições claras, factuais e proporcionais à vitrine pública.

Ao editar documentação:

- preserve a distinção entre comportamento confirmado, descrição conceitual, limitação e possibilidade futura;
- não transforme um conceito experimental em promessa ou garantia;
- evite alegações de prontidão para produção, garantias de segurança, compatibilidade, desempenho ou suporte sem documentação e evidência explícitas;
- utilize links relativos para arquivos do próprio repositório;
- use títulos descritivos e Markdown legível;
- preserve a estrutura bilíngue ao editar documento bilíngue;
- atualize as duas seções de idioma quando a alteração afetar significado compartilhado.

### Exemplos JSON

Exemplos JSON devem permanecer JSON válido e não podem conter comentários, vírgulas finais, valores privados ou conteúdo executável.

Um comando local proposto para validação é:

```bash
python -m json.tool examples/sanitized-scriptpackage.json
```

Execute o comando equivalente para o arquivo JSON exato que foi alterado.

Declare uma validação como concluída somente quando realmente a executar e observar seu resultado.

### Revisão de Markdown e links

Para alterações em Markdown:

- visualize o documento renderizado;
- confira títulos, listas, blocos de código e links internos;
- confirme que links para arquivos do repositório funcionem corretamente;
- verifique que nenhuma URL privada ou caminho local tenha sido introduzido;
- revise as seções em inglês e português quando aplicável.

Este repositório não afirma possuir atualmente workflow automatizado de Markdown ou verificação de links. Não descreva uma verificação como automatizada sem que essa automação exista de fato.

### Preparação de Pull Request

Use uma branch focada e mantenha cada Pull Request limitado a um objetivo coerente.

Um Pull Request deve explicar:

- o que mudou;
- por que a alteração é útil para a vitrine pública;
- os arquivos exatos alterados;
- como a ficcionalização e a sanitização foram revisadas;
- quais validações foram realmente executadas;
- quais validações não foram executadas;
- se há material de terceiros e sob qual licença ou autorização;
- qualquer limitação ou incerteza restante.

Evite misturar alterações documentais, exemplos, licenciamento e segurança sem relação no mesmo Pull Request.

### Checklist do colaborador

```text
[ ] A contribuição é adequada a uma vitrine pública documental
[ ] Nenhum código-fonte privado ou detalhe de implementação foi incluído
[ ] Nenhum prompt, instrução, export, log ou material privado não revisado foi incluído
[ ] Nenhum dado pessoal, de cliente, credencial, ambiente local ou informação confidencial foi incluído
[ ] Exemplos são fictícios e explicitamente marcados como sanitizados
[ ] O JSON é válido quando arquivos JSON são alterados
[ ] Markdown e links foram revisados quando a documentação é alterada
[ ] Mídias e metadados foram revisados quando arquivos ou capturas são incluídos
[ ] Direitos e licenças de materiais de terceiros foram confirmados
[ ] As limitações e o caráter não padronizado do ScriptPackage foram preservados
[ ] As validações executadas estão listadas com precisão
[ ] Validações não executadas foram declaradas honestamente
[ ] O Pull Request possui um único objetivo focado
```

### Relatos de segurança

Não reproduza material sensível em issue, Pull Request, comentário de revisão, discussão ou captura pública.

Siga o [`SECURITY.md`](SECURITY.md) e utilize o relato privado de vulnerabilidade do GitHub quando disponível. Caso não esteja, contate o mantenedor por um canal privado indicado no perfil do mantenedor no GitHub.

Forneça somente o mínimo necessário para localizar e investigar o problema com segurança.

### Licença e direitos da contribuição

Esta vitrine pública de documentação é disponibilizada sob CC BY-NC 4.0, salvo indicação diferente.

Ao enviar uma contribuição, você confirma que:

- criou o material enviado ou possui os direitos necessários para publicá-lo;
- a contribuição pode ser distribuída sob a licença aplicável do repositório;
- materiais de terceiros estão identificados com fonte, licença e atribuição necessária;
- a contribuição não concede acesso, autorização ou direitos sobre o projeto privado MLI-Knot Video Forge Lite;
- o uso comercial continua sujeito aos termos e requisitos de autorização registrados em [`LICENSE.md`](LICENSE.md).

Os mantenedores podem solicitar alterações, rejeitar material que não respeite a fronteira pública ou remover posteriormente conteúdo considerado inseguro, não autorizado, enganoso ou insuficientemente sanitizado.
