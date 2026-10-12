# Program row schema

File: [`data/programs.yaml`](data/programs.yaml), top-level `programs:` list.

| Field | Required | Notes |
|---|---|---|
| `name` | yes | Public program name |
| `company` | yes | Company / org running it |
| `category` | yes | `AI lab`, `AI tool`, or `dev tool` |
| `apply_url` | yes | Official apply form or page |
| `program_url` | yes | Official info page (may equal `apply_url`) |
| `perks` | no | From the official page only; `""` if unknown |
| `eligibility` | no | Region / student / usage requirements; `""` if unknown |
| `deadline` | no | `YYYY-MM-DD`, `rolling`, or `""` if unknown |
| `status` | yes | `live` (page + apply path verified) or `closed` |
| `last_checked` | yes | `YYYY-MM-DD`, quoted |
