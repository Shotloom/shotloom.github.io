# Shotloom — branding

**shot** (inquadrature) + **loom** (telaio): più camere intrecciate in un montaggio.

## Palette

| Ruolo | Hex | Uso |
|-------|-----|-----|
| Accent primary | `#ff5b45` | coral CTA / thread |
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
