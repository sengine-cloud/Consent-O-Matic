# sengine branch

Rules this fork carries until upstream ships them. Consent-O-Matic loads
`sengine-rules-list.json` from this branch as a second rule list, next to
upstream's `rules-list.json`:

    https://raw.githubusercontent.com/sengine-cloud/Consent-O-Matic/sengine/sengine-rules-list.json

Each rule here also has an upstream pull request. Once upstream merges it, its
line leaves `sengine-rules-list.json`.

| Rule | Upstream |
| --- | --- |
| `rules/frisco.pl.json` | pending |

Consent-O-Matic caches a rule list for 22 to 48 hours, so a change here reaches
browsers within two days.
