# Dokumentacja Wewnętrzna Firmy

Repozytorium zawiera pełną dokumentację wewnętrzną firmy, obejmującą:

## Struktura dokumentacji

### 📊 Sprzedaż
- **Strategia sprzedaży** - Kompleksowa strategia sprzedażowa firmy
- **Procesy sprzedaży** - Szczegółowe procesy i procedury sprzedażowe
- **Materiały sprzedażowe** - Zasoby i narzędzia wspierające sprzedaż

### 📢 Marketing
- **Strategia marketingowa** - Kompleksowa strategia marketingowa
- **Kampanie marketingowe** - Planowanie i realizacja kampanii
- **Content marketing** - Strategia i plan publikacji contentu

### 👥 HR
- **Wdrożenie pracownika** - Kompleksowy proces onboardingu

### 🎧 Obsługa Klienta
- **Procesy obsługi klienta** - Standardy i procedury obsługi

## Podgląd lokalny

Aby zobaczyć dokumentację lokalnie, zainstaluj [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm i -g mint
```

Następnie uruchom w katalogu głównym:

```bash
mint dev
```

Dokumentacja będzie dostępna pod adresem `http://localhost:3000`.

## Deployment

Dokumentacja jest automatycznie deployowana na Mintlify po każdym pushu do brancha `main`.

## Aktualizacja dokumentacji

1. Edytuj pliki `.mdx` w odpowiednich katalogach
2. Commituj zmiany
3. Push do repozytorium
4. Zmiany pojawią się automatycznie na stronie

## Struktura plików

```
docs/
├── docs.json              # Konfiguracja nawigacji
├── index.mdx             # Strona główna
├── sprzedaz/             # Dokumentacja sprzedaży
│   ├── strategia.mdx
│   ├── procesy.mdx
│   └── materialy.mdx
├── marketing/            # Dokumentacja marketingu
│   ├── strategia.mdx
│   ├── kampanie.mdx
│   └── content.mdx
├── hr/                   # Dokumentacja HR
│   └── wdrozenie.mdx
└── obsluga-klienta/      # Dokumentacja obsługi klienta
    └── procesy.mdx
```

## Wsparcie

W razie pytań dotyczących dokumentacji, skontaktuj się z działem IT lub HR.

## Publishing changes

Install our GitHub app from your [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
