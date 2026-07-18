# RC Course Alert

ラジコン・ミニ四駆コース営業/大会通知

## Repository

Recommended repository name: `rc-course-alert`

## Domain candidates

First candidate: `rccoursealert.jp`

Other candidates:

- `rccoursealert.jp`
- `rccourse.jp`
- `miniyonalert.jp`
- `hobbycourse.jp`

## Concept

コース営業、大会、路面状況、パーツ入荷を通知し、施設送客とパーツECへつなげる。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 施設送客
- パーツEC
- 大会告知
- スポンサー
- 遠征宿

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
