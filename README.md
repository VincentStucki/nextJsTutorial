# Next.js – Summary

## Ecosystem

| Name    | Age                              | Usage                                                | Documentation                                                                   | Issue & Bug Fixes                                                         | Migration                                      |
|---------|----------------------------------|-----------------------------------------------------|---------------------------------------------------------------------------------|---------------------------------------------------------------------------|------------------------------------------------|
| Next.js | 7 Jahre (erstmals veröffentlicht 2016) | Weit verbreitet, besonders für React-basierte Webanwendungen | Umfangreich, gut strukturiert und detailliert mit vielen Tutorials und Beispielen | Regelmässige Bugfixes und Updates, grosse Entwickler-Community | Relativ einfach, viele Migrationsleitfäden und Tools |

## Performance

| Name    | Server-Side Rendering | Single Page App                      | Static Generation                     | Serverless Affinity                                                                 |
|---------|-----------------------|--------------------------------------|---------------------------------------|-------------------------------------------------------------------------------------|
| Next.js | Zuerst werden anders als sonst die statischen Dateien geladen, was zu schnelleren Ladezeiten und besserem SEO führt | Sehr gut für SPAs, da diese stabil und schnell sind | Vorgerenderte Seiten bei Next.js immer gegeben, durch vorrendern | Unterstützt Serverless Functions, durch direkte Back-End-Funktionalitäten |

## Business Model Pricing

| Name    | Infrastructure Costs                                              | License Costs    | Biz: Avg (average starter plan cost/mo) | Small App Costs           | Large App Costs          |
|---------|-------------------------------------------------------------------|------------------|----------------------------------------|----------------------------|---------------------------|
| Next.js | Abhängig von der verwendeten IaaS/PaaS (z.B. Vercel bietet kostenlose und kostenpflichtige Pläne) | Kostenlos, MIT-Lizenz | $0 für Starter Plan bei Vercel         | Gering, abhängig vom Provider | Höhere Kosten für mehr Traffic und Funktionen bei grossen Apps |

## Business Needs

### Preismodell des Frameworks:
Next.js ist Open-Source und kostenlos, was bedeutet, dass keine Lizenzkosten anfallen. Die Nutzung von Vercel (der Hauptplattform für das Hosting von Next.js-Anwendungen) bietet jedoch kostenpflichtige Pläne, wenn erweiterte Funktionen oder höhere Performance für grössere Anwendungen benötigt werden. Für dein Projekt hängt die Wahl des Preismodells also davon ab, wie viel Traffic und wie viele Funktionen du benötigst.

### Risikotoleranz in Bezug auf neue Technologien:
Next.js gilt als ein ausgereiftes und stabiles Framework, das weit verbreitet ist. Daher ist das Risiko der Verwendung einer „neuen“ oder „unsicheren“ Technologie relativ gering. Es wird regelmässig gewartet und aktualisiert, was bedeutet, dass es gut unterstützt wird. Für dein Projekt könnte dies bedeuten, dass man Next.js mit geringem Risiko nutzen kann.

### Wichtigkeit der Unabhängigkeit von spezifischen Cloud-Diensten:
Next.js ist nicht an eine bestimmte Cloud-Plattform gebunden. Obwohl es eng mit Vercel integriert ist, kann es auch auf anderen Cloud-Diensten wie AWS, Azure oder Google Cloud bereitgestellt werden. Dein Projekt könnte also frei entscheiden, welchen Cloud-Anbieter du verwenden möchtest, abhängig von deinen geschäftlichen Anforderungen oder bestehenden Infrastrukturen.

## Scalability

| Name    | Horizontal Scaling | Host Provider Headroom                           | Additional Notes                                                                        |
|---------|--------------------|--------------------------------------------------|-----------------------------------------------------------------------------------------|
| Next.js | Unterstützt horizontales Skalieren durch serverlose Architektur | Hoch (insbesondere bei Vercel, AWS und Google Cloud) | Vercel bietet automatische Skalierung; Next.js unterstützt SSR (Server-Side Rendering) und statische Generierung für bessere Performance. |

## Scalability Needs

1. **Hohe Flexibilität**: Unser Projekt benötigt eine Infrastruktur, die sich schnell an wachsende Anforderungen anpassen lässt, insbesondere im Hinblick auf steigenden Traffic und mehr Nutzer.
2. **Individuelle Anpassbarkeit**: Es ist notwendig, bestimmte Funktionen selbst zu entwickeln, um spezifische Anforderungen zu erfüllen, die durch Standardlösungen nicht abgedeckt werden können.
3. **Kontrolle über die Infrastruktur**: Um langfristige Flexibilität zu gewährleisten, brauchen wir die Möglichkeit, das System nach Bedarf anzupassen und zu erweitern, auch wenn dies mehr Aufwand bedeutet.
4. **Skalierbare Plattform**: Trotz des Wunsches nach Kontrolle sollte eine Plattform wie Vercel oder AWS in Betracht gezogen werden, um anfangs weniger Aufwand bei der Infrastrukturverwaltung zu haben, insbesondere für kleinere Apps.

## Takeaways

Next.js hat eine einfache Handhabung und eignet sich gut für kleinere Projekte. Viele Systeme basieren auf Next.js, was zeigt, dass es sich auch für grosse Infrastrukturen, wie z.B. Vercel, lohnt. Das Erstellen von API-Routen ist sehr einfach und die Datenverarbeitung funktioniert direkt ohne separate Infrastruktur. Next.js und Serverless passen also sehr gut zusammen, um moderne, skalierbare Webanwendungen zu erstellen, die sowohl dynamische als auch statische Inhalte effizient handhaben können.

