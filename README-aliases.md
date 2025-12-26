# ⌨️ Notes — ściąga aliasów

Krótka legenda do pracy z notatkami.

---

## 📓 Daily notes

| Alias | Działanie |
|------|----------|
| `note` | Tworzy / otwiera dzienną notatkę `daily/YYYY-MM-DD.md` |

---

## 🗂 Nawigacja

| Alias | Katalog | Opis |
|------|--------|------|
| `nd` | `daily/` | dzienne notatki |
| `ni` | `ideas/` | pomysły |
| `nn` | `nixos/` | NixOS / techniczne |

Każdy alias:
- przechodzi do katalogu
- otwiera `nvim .`

---

## ❄️ NixOS — szablony

| Alias | Typ | Plik |
|-------|---------|--------------------------------|
| `ndd` | debug   | `nixos/debug-YYYY-MM-DD.md`    |
| `ndr` | runbook | `nixos/runbook-YYYY-MM-DD.md`  |
| `ndc` | decyzja | `nixos/decision-YYYY-MM-DD.md` |

Każdy:
- kopiuje odpowiedni TEMPLATE
- otwiera plik w `nvim`

---

## 🔄 Synchronizacja

| Alias | Działanie |
|--------------------------------------------------------|
| `notes-sync` | `git add + commit + push` w `notes-md/` |

---

## 🧭 Typowy workflow

1. `note` — log dnia
2. `ndd` — gdy pojawi się problem
3. `ndr` — gdy procedura się stabilizuje
4. `notes-sync` — backup na GitHub

