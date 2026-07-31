# Supabase

The `supabase` folder contains incremental migrations used by the current database.

Run migrations only if the corresponding upgrade has not already been applied:

- `03_V13_ADDITIONAL_FIELDS.sql`
- `04_V14_INTEGRATED_UPGRADE.sql`
- `05_V15_CLINICAL_INCIDENT_DOCUMENTS.sql`
- `06_V17_ALERTS_NOTIFICATIONS.sql`
- `07_V21_CLINICAL_DOCUMENTS.sql`

The optional notification sender is under `supabase/functions/send-notifications/`. Automatic WhatsApp/SMS sending requires provider credentials configured as Supabase Edge Function secrets.
