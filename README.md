# llms-files — Khadiri & Co

Ce dépôt contient les fichiers `llms.txt` et `llms-full.txt` du cabinet **Khadiri & Co**, conformes au standard proposé par [Answer.AI (llmstxt.org)](https://llmstxt.org/).

## Objectif

Ces fichiers guident les moteurs génératifs et agents IA (ChatGPT, Perplexity, Claude, Gemini, Copilot) pour :

- Identifier rapidement les contenus prioritaires du site [khadiri.com](https://www.khadiri.com/)
- Comprendre l'identité du cabinet et ses domaines d'expertise
- Extraire les informations factuelles utiles (missions CAC, articles Code de commerce, accréditations)

## Fichiers

| Fichier | Objet | Destinataire |
|---|---|---|
| [`llms.txt`](./llms.txt) | Index concis (< 8 000 tokens) | Découverte rapide par agents IA |
| [`llms-full.txt`](./llms-full.txt) | Contenu structuré complet | Ingestion approfondie |

## Déploiement sur khadiri.com

Ces deux fichiers doivent être servis à la **racine** du domaine :

- `https://www.khadiri.com/llms.txt`
- `https://www.khadiri.com/llms-full.txt`

Sur SiteW, l'upload se fait via l'espace fichier racine ou via redirection DNS pointant vers ce dépôt GitHub Pages en cas d'impossibilité technique.

## Sources normatives

- Standard llms.txt : https://llmstxt.org/
- Code de commerce (Légifrance) : https://www.legifrance.gouv.fr/codes/id/LEGITEXT000005634379/
- CRCC Paris : https://www.crcc-paris.fr/
- CNCC : https://www.cncc.fr/
- Haute Autorité de l'Audit (H2A) : https://www.h2a.gouv.fr/

## Historique des versions

| Date | Version | Modifications |
|------|---------|---------------|
| 2026-08-10 | v1.0 | Version initiale — 8 missions CAC ad hoc, différence CAA/CAF, méthode 5 étapes, FAQ 8 questions |
| 2026-08-12 | v1.1 | Ajout compte X officiel (https://x.com/skhadiri) dans `sameAs` Organization et Person ; enrichissement JSON-LD sur `index.html` (Organization + Person + WebSite avec 9 sameAs) ; section réseaux sociaux officiels dans README |

## Licence

Contenu propriétaire du cabinet Khadiri & Co — © 2026, tous droits réservés.
Autorisation d'indexation et citation avec lien source par les moteurs génératifs listés dans `llms-full.txt` section 9.

## Réseaux sociaux officiels

- LinkedIn : https://www.linkedin.com/in/khadiri
- Facebook : https://www.facebook.com/Expertkhadiri
- X (Twitter) : https://x.com/skhadiri

## Contact

Khadiri & Co — 50 avenue des Champs-Élysées, 75008 Paris — contact@khadiri.com — +33 1 56 89 22 22
