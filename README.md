# Kapture Bank — website prototype

Retail banking website prototype for Kapture Bank, built in Kapture's brand
colours and type. Eight pages, all reachable from the header nav:

- Home
- Accounts & Deposits
- Loans
- Cards
- Insurance (motor, health, term life, home & travel)
- Support / Help centre
- About
- Contact
- Log in

The Kapture Assist widget sits bottom-right on every page. It opens a chat
panel and can switch to a voice-call state.

## Running it

`index.html` is a single self-contained file. Open it in any browser, or serve
the folder:

```
python3 -m http.server
```

No build step, no dependencies.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Bundled, standalone site — this is the one to open or deploy |
| `Kapture Bank.dc.html` | Editable source (template + logic) |
| `support.js` | Runtime the source file loads |

Edit `Kapture Bank.dc.html` and re-bundle to regenerate `index.html`.

## Notes

All figures — interest rates, premiums, branch counts, the CIN and the IRDAI
registration number — are placeholders for demonstration. Replace them before
this is shown as anything other than a prototype.
