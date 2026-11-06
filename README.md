# Sahinur

Full-stack software engineer building web, mobile and developer tooling, and contributing to open source.

[Website](https://www.sahinur.dev) · [X](https://x.com/SahinurDev) · [LinkedIn](https://www.linkedin.com/in/sahinur/) · [Email](mailto:infosahinur@gmail.com)

I build web apps with React and Next.js, mobile apps with React Native, and the Node.js / TypeScript services and APIs behind them, increasingly with agentic AI workflows. I also maintain small, well-tested open-source tools: a fake-data library and an AWS CLI published on npm, and a Chrome extension on the Web Store. When something breaks in a library I depend on, I send the fix upstream.

## Selected work

**[ForgeData](https://github.com/SahinurDEV/ForgeData)**: a zero-dependency, tree-shakable fake-data generator for TypeScript and JavaScript, built as a modern alternative to Faker.js. It ships 100+ generators across 16 modules, 9 locales, seedable output for deterministic tests, Zod-schema generation, React hooks and a CLI.<br>
<sub>TypeScript · ESM + CJS · Vitest · [Docs](https://sahinurdev.github.io/ForgeData/) · [npm](https://www.npmjs.com/package/forgedatajs)</sub>

**[aws-ec2-check](https://github.com/SahinurDEV/aws-ec2-check)**: a CLI that checks EC2 instance health, status checks and metadata from the terminal, so you don't have to open the AWS Console. It has filterable instance tables, `--json` output and clear exit codes for CI, and a documented least-privilege IAM policy.<br>
<sub>TypeScript · AWS SDK v3 · Node.js · [npm](https://www.npmjs.com/package/aws-ec2-check)</sub>

**[ALLtvLive](https://github.com/SahinurDEV/ALLtvLive)**: a web app for watching 10,000+ free live TV channels in one place, with HLS playback, fuzzy search, country detection, filters by country, category and language, and favorites.<br>
<sub>Next.js · TypeScript · Tailwind CSS · HLS.js · [Live](https://livetv.sahinur.dev)</sub>

**[LeadSnipe](https://github.com/SahinurDEV/LeadSnipe)**: a Chrome extension that extracts emails from any webpage, separates business from personal addresses, and exports to CSV or TXT. All processing happens locally in the browser.<br>
<sub>JavaScript · Chrome Extension (Manifest V3) · [Chrome Web Store](https://chromewebstore.google.com/detail/leadsnipe-email-extractor/ndfbblpccbhadnbnfhegjhpefocmilag) · [Website](https://leadsnipe.netlify.app)</sub>

**[Meet Attendance Tracker](https://github.com/SahinurDEV/Meet-Attendance-Tracker)**: a Chrome extension that takes Google Meet attendance automatically, with join and leave times, speaking time, class rosters (present, late or absent), analytics and CSV, Excel or PDF reports. Everything stays on the user's device.<br>
<sub>JavaScript · Chrome Extension (Manifest V3) · Playwright · GitHub Actions · [Chrome Web Store](https://chromewebstore.google.com/detail/meet-attendance-tracker/knhhplmldjejlbhpnhgcbcbnglghoblm) · [Website](https://sahinurdev.github.io/Meet-Attendance-Tracker/)</sub>

**[easy-quick-form](https://github.com/SahinurDEV/easy-quick-form)**: a full-stack form builder with a drag-and-drop editor, response tracking, and JWT authentication with refresh-token rotation and reuse detection.<br>
<sub>React · Express · MongoDB · TypeScript · Vitest · [Live](https://easy-quick-form.vercel.app)</sub>

## Open source

- **[rea](https://github.com/morluto/rea)** (437k+ stars): stopped native Objective-C class, category and protocol records from being dropped when an adopted-protocol list was unreadable, keeping the owner and any readable protocol names with a partial decode status [#8958](https://github.com/morluto/rea/pull/8958), and stopped a valid ZIP Zstandard entry whose decompression window exceeded the 128 MiB cap from being reported as a format error, classifying it as a memory resource limit instead [#8625](https://github.com/morluto/rea/pull/8625). Both merged.
- **[VS Code](https://github.com/microsoft/vscode)** (194k+ stars): made "Debug Extension Host" turn on the inspector on the running extension host instead of asking for a restart, matching how profiling already worked. [#343437](https://github.com/microsoft/vscode/pull/343437), merged.
- **[Tailwind CSS](https://github.com/tailwindlabs/tailwindcss)** (97k+ stars): stopped class canonicalization from collapsing exponentially when a utility sets many properties. [#20558](https://github.com/tailwindlabs/tailwindcss/pull/20558), merged.
- **[Qwik](https://github.com/QwikDev/qwik)** (22k+ stars): fixed an SSR `ReferenceError` in the TypeScript optimizer by keeping outer loop items in scope for handlers inside nested loops. [#9231](https://github.com/QwikDev/qwik/pull/9231), merged.
- **[Plate](https://github.com/udecode/plate)** (16k+ stars): made the markdown deserializer parse autolinks when used with `remark-mdx`. [#5159](https://github.com/udecode/plate/pull/5159), merged.
- **[ApexCharts](https://github.com/apexcharts/apexcharts.js)** (15k+ stars): stopped streaming line and area segments after a `null` gap from replaying their entry animation on every update [#5351](https://github.com/apexcharts/apexcharts.js/pull/5351), and stopped zero-value stacked columns from being expanded by the series stroke width [#5352](https://github.com/apexcharts/apexcharts.js/pull/5352). Both merged.
- **[PapaParse](https://github.com/mholt/PapaParse)** (13k+ stars): fixed a crash in `Papa.unparse` on null or undefined single-cell rows when `skipEmptyLines` is set. [#1164](https://github.com/mholt/PapaParse/pull/1164), merged.
- **[Kubernetes](https://github.com/kubernetes/website)** (5.4k+ stars): fixed the CronJob docs so missed schedules and unsuspend without a starting deadline say the controller starts only the most recent missed Job, after recording a `TooManyMissedTimes` warning. [#58496](https://github.com/kubernetes/website/pull/58496), merged.
- **[Tabularis](https://github.com/TabularisDB/tabularis)** (5k+ stars): made column masking and grid interaction settings persist across sessions. [#911](https://github.com/TabularisDB/tabularis/pull/911), merged.
- **[AlaSQL](https://github.com/AlaSQL/alasql)** (7k+ stars): fixed `WITH` queries (CTEs) that read from an async source such as `CSV()`, which previously threw an uncaught error. [#2571](https://github.com/AlaSQL/alasql/pull/2571), merged.
- **[Style Dictionary](https://github.com/style-dictionary/style-dictionary)** (4.8k+ stars): stopped `outputReferences` from raising false warnings for tokens removed by a filter, by sorting the filtered set while resolving references from the full set. [#1763](https://github.com/style-dictionary/style-dictionary/pull/1763), merged.
- **[Two.js](https://github.com/jonobr1/two.js)** (8.6k+ stars): fixed `dom.unbind` calling a nonexistent `removeEventListeners` method, so DOM event listeners are now actually removed. [#868](https://github.com/jonobr1/two.js/pull/868), merged.
- **[Allotment](https://github.com/johnwalley/allotment)** (1.2k+ stars): fixed sash double-click calling a stale `onReset` instead of the latest callback. [#904](https://github.com/johnwalley/allotment/pull/904), merged.
- **[eslint-plugin-better-tailwindcss](https://github.com/schoero/eslint-plugin-better-tailwindcss)** (850+ stars): bumped synckit to 0.12 so Tailwind worker rules recover after worker timeouts instead of hanging. [#418](https://github.com/schoero/eslint-plugin-better-tailwindcss/pull/418), merged.
- **[wavesurfer-react](https://github.com/katspaugh/wavesurfer-react)**: deep-flattened nested options so `useWavesurfer` no longer recreates the player on every render when options like `fetchParams` are written inline. [#15](https://github.com/katspaugh/wavesurfer-react/pull/15), merged.

## Stack

**Languages:** TypeScript, JavaScript, Python<br>
**Backend:** Node.js, Express, MongoDB, Redis, PostgreSQL, REST, WebSockets<br>
**Frontend:** React, Next.js, Tailwind CSS<br>
**Mobile:** React Native, Expo<br>
**Infra:** AWS (EC2, S3), Docker, GitHub Actions, Vercel, Netlify<br>
**AI and agentic workflows:** Claude Code, OpenAI Codex / ChatGPT, Google Antigravity, OpenCode

---

Open to freelance and full-time roles. The fastest way to reach me is [email](mailto:infosahinur@gmail.com).
