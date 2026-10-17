```
 ╭─────────────────────────────────────╮
 │ PROCESSOUT                    ))))  │
 │  ┌───┐                              │
 │  │▓▓▓│                              │
 │  └───┘                              │
 │  4242  4242  4242  4242             │
 │  JEAN-BAPTISTE         VALID 12/99  │
 ╰─────────────────────────────────────╯
  $ curl -X POST /payments -d @coffee.json
  < HTTP/1.1 200 OK
  { "status": "authorized", "3ds": "ok" }
```

### hi, I'm Jean-Baptiste 👋

Senior Software Engineer 1 · Data Team @ **ProcessOut** (Checkout.com) — 📍 Paris

```
  [card] ──▶ [processout] ──▶ [acquirer] ──▶ [scheme] ──▶ [issuer]
                                                              │
  [card] ◀─────────────────── 200 OK ◀────────────────────────┘

  auth rate    ███████████████████▒  97.4%
  p95 latency  ██████▒░░░░░░░░░░░░░  180ms
  coffee       ████████████████████  ∞
```

<p>
  <img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
</p>
