# Shotloom — branding

**shot** (inquadrature / camere) + **loom** (telaio): tre viewfinder che si intrecciano in un solo clip timeline.

## Mark

Tre camere stilizzate (corpo + schermo) → steli che convergono → barra timeline con play.
Leggibile a 16–32 px.

## Palette

| Ruolo | Hex | Uso |
|-------|-----|-----|
| Accent primary | `#ff5b45` | coral |
| Accent secondary | `#ff3d8b` | magenta / timeline |
| Accent tertiary | `#ff7a66` | coral light |
| Testo dark bg | `#f3f5fa` | wordmark |
| Testo light bg | `#0b0d12` | wordmark |
| Sfondo favicon | `#0b0d12` | app icon |

## File

| File | Uso |
|------|-----|
| `logo-mark.svg` | Solo simbolo |
| `logo-horizontal-dark.svg` | Lockup sfondi scuri |
| `logo-horizontal-light.svg` | Lockup sfondi chiari |
| `favicon.svg` | Favicon moderna |
| `favicon.ico` / `favicon-32.png` | Fallback browser / Windows |

## Rigenerare

```bash
python scripts/build_shotloom_logos.py
```

## Regole

- Area di rispetto = altezza simbolo su ogni lato
- Non distorcere proporzioni
- Mark minimo: 16 px
