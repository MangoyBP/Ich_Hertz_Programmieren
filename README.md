# Ich_Hertz_Programmieren

Meine Fullstack-App zum Thema **„Ich liebe Programmieren“**. Sie zeigt eine
Programmier-Checkliste mit Demo-Einträgen. Die Oberfläche verwendet Preact,
TypeScript und Tailwind CSS; die API läuft mit Hono.

## Lokal starten

Voraussetzung: Node.js 22 oder neuer.

```powershell
npm install
npm run dev
```

Das Frontend ist unter <http://localhost:5173> erreichbar, die Demo-API unter
<http://localhost:3000/api/items>.

## Prüfen

```powershell
npm run typecheck
npm test
npm run build
```

Weitere Informationen zur Projektstruktur und den folgenden Modulumsetzungen
stehen in [AGENTS.md](./AGENTS.md).
