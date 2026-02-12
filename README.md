# QP280 Change Management Application

Single-page web application implementing:

- KPI dashboard (total/open/closed/cancelled, overdue approvals, escalations)
- Workflow approvals with escalation levels
- Auto-numbered CR creation
- Record lifecycle: create, update/modify, archive
- Creator/modifier audit data
- Role-based access control (creator, modifier, coordinator, approver, admin)
- Complete CR field set requested
- Seeded historical rows from the provided table snapshot

## Run

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Demo users

- admin / admin
- creator1 / creator1
- modifier1 / modifier1
- coord1 / coord1
- approver1 / approver1

Data persists in browser localStorage (`qp280-db`).
