# Sahinur

Full-stack software engineer building web, mobile and developer tooling, and contributing to open source.

[Website](https://www.sahinur.dev) · [X](https://x.com/SahinurDev) · [LinkedIn](https://www.linkedin.com/in/sahinur/) · [Email](mailto:infosahinur@gmail.com)

I build web apps with React and Next.js, mobile apps with React Native, and the Node.js / TypeScript services and APIs behind them, increasingly with agentic AI workflows. I also maintain small, well-tested open-source tools: a fake-data library and an AWS CLI published on npm, and a Chrome extension on the Web Store. When something breaks in a library I depend on, I send the fix upstream.

## Selected work

**[ForgeData](https://github.com/SahinurDEV/ForgeData)**: a zero-dependency, tree-shakable fake-data generator for TypeScript and JavaScript, built as a modern alternative to Faker.js. It ships 100+ generators across 16 modules, 9 locales, seedable output for deterministic tests, Zod-schema generation, React hooks and a CLI.<br>
<sub>TypeScript · ESM + CJS · Vitest · [Docs](https://sahinurdev.github.io/ForgeData/) · [npm](https://www.npmjs.com/package/@sahinur/forgedata)</sub>

**[aws-ec2-check](https://github.com/SahinurDEV/aws-ec2-check)**: a CLI that checks EC2 instance health, status checks and metadata from the terminal, so you don't have to open the AWS Console. It has filterable instance tables, `--json` output and clear exit codes for CI, and a documented least-privilege IAM policy.<br>
<sub>TypeScript · AWS SDK v3 · Node.js · [npm](https://www.npmjs.com/package/aws-ec2-check)</sub>

**[ALLtvLive](https://github.com/SahinurDEV/ALLtvLive)**: a web app for watching 10,000+ free live TV channels in one place, with HLS playback, fuzzy search, country detection, filters by country, category and language, and favorites.<br>
<sub>Next.js · TypeScript · Tailwind CSS · HLS.js · [Live](https://livetv.sahinur.dev)</sub>

**[LeadSnipe](https://github.com/SahinurDEV/LeadSnipe)**: a Chrome extension that extracts emails from any webpage, separates business from personal addresses, and exports to CSV or TXT. All processing happens locally in the browser.<br>
<sub>JavaScript · Chrome Extension (Manifest V3) · [Chrome Web Store](https://chromewebstore.google.com/detail/leadsnipe-email-extractor/ndfbblpccbhadnbnfhegjhpefocmilag) · [Website](https://leadsnipe.netlify.app)</sub>

**[Meet Attendance Tracker](https://github.com/SahinurDEV/Meet-Attendance-Tracker)**: a Chrome extension that takes Google Meet attendance automatically, with join and leave times, speaking time, class rosters (present, late or absent), analytics and CSV, Excel or PDF reports. Everything stays on the user's device.<br>
<sub>JavaScript · Chrome Extension (Manifest V3) · Playwright · GitHub Actions · [Website](https://sahinurdev.github.io/Meet-Attendance-Tracker/)</sub>

**[easy-quick-form](https://github.com/SahinurDEV/easy-quick-form)**: a full-stack form builder with a drag-and-drop editor, response tracking, and JWT authentication with refresh-token rotation and reuse detection.<br>
<sub>React · Express · MongoDB · TypeScript · Vitest · [Live](https://easy-quick-form.vercel.app)</sub>

## Open source

- **[PapaParse](https://github.com/mholt/PapaParse)** (13k+ stars): fixed a crash in `Papa.unparse` on null or undefined single-cell rows when `skipEmptyLines` is set. [#1164](https://github.com/mholt/PapaParse/pull/1164), merged.
- **[Tabularis](https://github.com/TabularisDB/tabularis)** (5k+ stars): made column masking and grid interaction settings persist across sessions. [#911](https://github.com/TabularisDB/tabularis/pull/911), merged.
- **[AlaSQL](https://github.com/AlaSQL/alasql)** (7k+ stars): fixed `WITH` queries (CTEs) that read from an async source such as `CSV()`, which previously threw an uncaught error. [#2571](https://github.com/AlaSQL/alasql/pull/2571), merged.
- **[Style Dictionary](https://github.com/style-dictionary/style-dictionary)** (4.8k+ stars): stopped `outputReferences` from raising false warnings for tokens removed by a filter, by sorting the filtered set while resolving references from the full set. [#1763](https://github.com/style-dictionary/style-dictionary/pull/1763), merged.
- **[Two.js](https://github.com/jonobr1/two.js)** (8.6k+ stars): fixed `dom.unbind` calling a nonexistent `removeEventListeners` method, so DOM event listeners are now actually removed. [#868](https://github.com/jonobr1/two.js/pull/868), merged.

## Stack

**Languages:** TypeScript, JavaScript, Python<br>
**Backend:** Node.js, Express, MongoDB, Redis, PostgreSQL, REST, WebSockets<br>
**Frontend:** React, Next.js, Tailwind CSS<br>
**Mobile:** React Native, Expo<br>
**Infra:** AWS (EC2, S3), Docker, GitHub Actions, Vercel, Netlify<br>
**AI and agentic workflows:** Claude Code, OpenAI Codex / ChatGPT, Google Antigravity, OpenCode

---

Open to freelance and full-time roles. The fastest way to reach me is [email](mailto:infosahinur@gmail.com).
