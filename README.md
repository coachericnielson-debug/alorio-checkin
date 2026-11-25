# Alo Rio guest check-in

Phone-first guest registration page. Guests fill it once; the Supabase function `alorio-checkin` sends the data to the FNRH API (Ministério do Turismo). No credentials live in this repo.

URL params: `p` (skydreams|vista|casamaria|casaquerida), `c` (Airbnb code), `in`, `out` (YYYY-MM-DD), `lang`.
