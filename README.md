<!-- GitHub profile README - abiramcodes/abiramcodes. Commit README.md + assets/ together. -->

<p align="center">
  <img src="./assets/banner.svg" width="100%" alt="Abirama Kannan - Frontend Engineer, Angular, Micro-Frontends, Dev Tools">
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1200&color=DD0031&center=true&vCenter=true&width=640&lines=Frontend+Engineer+-+Angular+and+Micro-Frontends;Building+ng-point+%2B+angular-doctor;Open+Source+%C2%B7+ng-India+Speaker" alt="Frontend Engineer · Building ng-point + angular-doctor · Open Source · ng-India Speaker">
</p>

<p align="center">
  I build performant UIs, ship Angular dev tools to npm, contribute to open source, and care about clean, maintainable code.
</p>

<p align="center">
  <a href="https://www.abikb.xyz/"><img src="https://shieldcn.dev/badge/Portfolio-abikb.xyz-1F6FEB" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/abirama-kannan-baskar"><img src="https://shieldcn.dev/badge/LinkedIn-Abirama%20Kannan-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://x.com/abiramcodes"><img src="https://shieldcn.dev/badge/X-%40abiramcodes-000000?logo=x&logoColor=white" alt="X (Twitter)"></a>
  <a href="mailto:akbhere20@gmail.com"><img src="https://shieldcn.dev/badge/Email-akbhere20%40gmail.com-D14836?logo=gmail&logoColor=white" alt="Email"></a>
</p>

<p align="center">
  <a href="https://github.com/abiramcodes/ng-point"><img src="https://shieldcn.dev/npm/@abiramcodes/ng-point.svg" alt="ng-point on npm"></a>
  <a href="https://github.com/abiramcodes/ng-point/stargazers"><img src="https://shieldcn.dev/github/stars/abiramcodes/ng-point.svg" alt="ng-point stars"></a>
  <a href="https://github.com/abiramcodes/angular-doctor"><img src="https://shieldcn.dev/npm/@abiramcodes/angular-doctor.svg" alt="angular-doctor on npm"></a>
  <a href="https://github.com/abiramcodes/angular-doctor/stargazers"><img src="https://shieldcn.dev/github/stars/abiramcodes/angular-doctor.svg" alt="angular-doctor stars"></a>
</p>

## About

- Currently shipping **[ng-point](https://github.com/abiramcodes/ng-point)** + **[angular-doctor](https://github.com/abiramcodes/angular-doctor)** - details below
- Exploring modern Angular (signals, zoneless, standalone, control flow) + AI-assisted workflows
- Frontend Engineer working in Angular / React / Astro
- Spoke at **ng-India Chennai** on Dynamic Components & Forms

## Shipping

### [ng-point](https://github.com/abiramcodes/ng-point) - One Alt+Click. Your agent is already on it.

Alt+Click any element in your running Angular app → an **LLM-ready context block on your clipboard**, at a fraction of the tokens of a screenshot. Paste it straight into Claude Code, Cursor, Copilot, or any coding agent. **Dev-mode only. Redacted at capture. Never in production bundles.**

```text
Component: SubmitButtonComponent
File: src/app/orders/submit-button.component.ts:19
Template: src/app/orders/submit-button.component.ts:16
Element: <button class="btn btn-primary">Approve selected</button>
Parent: OrdersPage (src/app/pages/orders-page.ts:110)
Instruction: disable this while orders are loading
```

**Setup - install + one provider, that's it:**

```bash
npm i -D @abiramcodes/ng-point        # pnpm: pnpm add -D @abiramcodes/ng-point
npx skills add abiramcodes/ng-point   # optional: teach your agent to drive it
```

```ts
// app.config.ts
import { provideNgPoint } from '@abiramcodes/ng-point';

export const appConfig: ApplicationConfig = {
  providers: [provideRouter(routes), provideNgPoint()],
};
```

<kbd>Alt</kbd>+<kbd>Click</kbd> pick · <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>Click</kbd> add (up to 5) · <kbd>Alt</kbd>+<kbd>↑</kbd>/<kbd>↓</kbd> re-target · <kbd>Enter</kbd> copy · <kbd>Esc</kbd> close _(macOS: <kbd>Option ⌥</kbd> = <kbd>Alt</kbd>)_

JWTs, API keys & typed values redacted before copy - mark anything off-limits with `ngPointIgnore` · Angular **21–22** (exact `Template:` line on 22.1.4+) · zone or zoneless · micro-frontends supported · no build plugin

[Docs & live demo](https://abiramcodes.github.io/ng-point/) · [npm](https://www.npmjs.com/package/@abiramcodes/ng-point) · [GitHub](https://github.com/abiramcodes/ng-point) · [Agent skill](https://skills.sh/abiramcodes/ng-point)

### [angular-doctor](https://github.com/abiramcodes/angular-doctor)

Deterministic health scanner for Angular codebases and coding agents. 0–100 score, categorized diagnostics, agent-ready report. One command, zero config.

`npx @abiramcodes/angular-doctor@latest` · [Docs](https://ngdoctor.dev/) · [npm](https://www.npmjs.com/package/@abiramcodes/angular-doctor) · [GitHub](https://github.com/abiramcodes/angular-doctor)

## Stack

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=angular%2Cts%2Crxjs%2Creact%2Castro%2Ctailwind%2Cnestjs%2Cnodejs&theme=dark&perline=8">
    <img src="https://skillicons.dev/icons?i=angular%2Cts%2Crxjs%2Creact%2Castro%2Ctailwind%2Cnestjs%2Cnodejs&theme=light&perline=8" alt="Angular, TypeScript, RxJS, React, Astro, Tailwind CSS, NestJS, Node.js">
  </picture>
</p>

**Also working with:** Micro-frontends (Native/Module Federation), NgRx, TanStack Query, Zod, Angular Material, PrimeNG

**AI tooling:**

![Claude Code](https://shieldcn.dev/badge/Claude%20Code-D97757?logo=anthropic)
![GitHub Copilot](https://shieldcn.dev/badge/Copilot-2088FF?logo=githubcopilot)
![OpenCode](https://shieldcn.dev/badge/OpenCode-000000)
![Cursor CLI](https://shieldcn.dev/badge/Cursor%20CLI-000000?logo=cursor&logoColor=white)
![Antigravity CLI](https://shieldcn.dev/badge/Antigravity%20CLI-4285F4)
![Muse CLI](https://shieldcn.dev/badge/Muse%20CLI-000000)

## Projects

<table>
  <tr>
    <td width="50%"><a href="https://github.com/abiramcodes/ng-point"><picture><source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=abiramcodes&repo=ng-point&theme=github_dark&hide_border=true"><img src="https://github-readme-stats.vercel.app/api/pin/?username=abiramcodes&repo=ng-point&hide_border=true" alt="ng-point - Alt+Click to LLM-ready clipboard context. Angular 21–22." width="100%"></picture></a></td>
    <td width="50%"><a href="https://github.com/abiramcodes/angular-doctor"><picture><source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=abiramcodes&repo=angular-doctor&theme=github_dark&hide_border=true"><img src="https://github-readme-stats.vercel.app/api/pin/?username=abiramcodes&repo=angular-doctor&hide_border=true" alt="angular-doctor - 0–100 codebase health score + agent-ready reports" width="100%"></picture></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://github.com/abiramcodes/dynamic-forms-demo"><b>dynamic-forms-demo</b></a><br>Demo used in my ng-India Chennai 2025 talk on flexible UIs with dynamic components & forms.</td>
    <td width="50%"><a href="https://github.com/abiramcodes/MD-PDF"><b>MD-PDF</b></a><br>Markdown → PDF converter (Angular + NestJS + Puppeteer).</td>
  </tr>
</table>

Also contributing to **[freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp)**, **[carbon-components-angular](https://github.com/carbon-design-system/carbon-components-angular)**, **[spartan-ng](https://github.com/spartan-ng/spartan)** and **[ng-primitives](https://github.com/ng-primitives/ng-primitives)**.

<details>
<summary><b>npm downloads - last 365 days</b></summary>
<br>
<p align="center">
  <a href="https://abiramcodes.github.io/ng-point/" title="ng-point - npm downloads, last 365 days">
    <img src="https://shieldcn.dev/chart/npm/@abiramcodes/ng-point.svg" alt="ng-point npm downloads chart" width="800">
  </a>
</p>
<p align="center">
  <a href="https://ngdoctor.dev/" title="angular-doctor - npm downloads, last 365 days">
    <img src="https://shieldcn.dev/chart/npm/@abiramcodes/angular-doctor.svg" alt="angular-doctor npm downloads chart" width="800">
  </a>
</p>
</details>

## Stats

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=abiramcodes&show_icons=true&theme=github_dark&hide_border=true">
    <img height="165" src="https://github-readme-stats.vercel.app/api?username=abiramcodes&show_icons=true&hide_border=true" alt="Abiram's GitHub stats">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=abiramcodes&theme=github-dark&hide_border=true">
    <img height="165" src="https://streak-stats.demolab.com/?user=abiramcodes&hide_border=true" alt="Abiram's GitHub streak">
  </picture>
</p>
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=abiramcodes&layout=compact&langs_count=8&theme=github_dark&hide_border=true">
    <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abiramcodes&layout=compact&langs_count=8&hide_border=true" alt="Abiram's most used languages">
  </picture>
</p>

<p align="center">
  <img src="./assets/footer.svg" width="100%" alt="Building tools that help Angular developers ship healthier code.">
</p>
