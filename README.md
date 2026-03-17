# @thereis/baileys-nightly

[![npm](https://img.shields.io/npm/v/@thereis/baileys-nightly)](https://www.npmjs.com/package/@thereis/baileys-nightly)
[![X (Twitter)](https://img.shields.io/badge/X-@dev__reis-000000?logo=x)](https://x.com/dev_reis)
[![GitHub](https://img.shields.io/badge/GitHub-thereis-181717?logo=github)](https://github.com/thereis)

## English

Unofficial nightly mirror of [WhiskeySockets/Baileys](https://github.com/WhiskeySockets/Baileys). Automatically built and published to npm every day at 20:00 UTC when there are new upstream commits.

### What are nightly builds?

Nightly builds are automated snapshots of the latest code from the Baileys repository, built and published daily. They include the most recent changes and fixes that haven't been officially released yet.

> [!WARNING]
> Nightly builds may contain breaking changes. For stable usage, always prefer the official [RC releases](https://github.com/WhiskeySockets/Baileys/releases). Use nightlies at your own risk.

### Drop-in replacement for `baileys`

If you already use `baileys` and want to switch to nightlies without changing any imports, update your `package.json`:

```json
{
  "dependencies": {
    "baileys": "npm:@thereis/baileys-nightly@latest"
  }
}
```

Then run `pnpm install`. All your `import { ... } from 'baileys'` will keep working — npm resolves it to the nightly package.

### Pin a specific version

```bash
pnpm add @thereis/baileys-nightly@7.0.0-rc.9-nightly.20260317.d0779026
```

Version format: `{upstream_version}-nightly.{YYYYMMDD}.{commit_sha}`

For documentation, visit [baileys.wiki](https://baileys.wiki/).

View [recent nightly releases](https://github.com/thereis/baileys-nightly/releases).

---

## Português (BR)

Mirror não-oficial do [WhiskeySockets/Baileys](https://github.com/WhiskeySockets/Baileys) com builds automáticas publicadas no npm todos os dias às 20:00 UTC quando há novos commits.

### O que são builds nightly?

Builds nightly são snapshots automatizados do código mais recente do repositório Baileys, compilados e publicados diariamente. Eles incluem as mudanças e correções mais recentes que ainda não foram oficialmente lançadas.

> [!WARNING]
> Builds nightly podem conter mudanças que quebram compatibilidade. Para uso estável, sempre prefira as [versões RC oficiais](https://github.com/WhiskeySockets/Baileys/releases). Use as nightlies por sua conta e risco.

### Substituição direta do `baileys`

Se você já usa `baileys` e quer trocar para as nightlies sem alterar nenhum import, atualize seu `package.json`:

```json
{
  "dependencies": {
    "baileys": "npm:@thereis/baileys-nightly@latest"
  }
}
```

Depois rode `pnpm install`. Todos os seus `import { ... } from 'baileys'` continuam funcionando — o npm resolve para o pacote nightly.

### Fixar uma versão específica

```bash
pnpm add @thereis/baileys-nightly@7.0.0-rc.9-nightly.20260317.d0779026
```

Formato da versão: `{upstream_version}-nightly.{YYYYMMDD}.{commit_sha}`

Para documentação, acesse [baileys.wiki](https://baileys.wiki/).

Veja as [releases nightly recentes](https://github.com/thereis/baileys-nightly/releases).
