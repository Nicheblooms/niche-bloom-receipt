# NICHE BLOOM — Receipt Dashboard

ระบบจัดการใบเสร็จ / ผ่อนชำระ / ทวงถาม พร้อม Login + RBAC และแท็บจัดการลูกค้า-สัญญา

## Deploy

1. Import repo นี้ใน Vercel
2. ตั้ง Environment Variables:
   - `LINE_CHANNEL_SECRET`
   - `LINE_CHANNEL_ACCESS_TOKEN`
   - `SUPABASE_SERVICE_ROLE_KEY`
3. Deploy

## Supabase

- ตาราง: customers, contracts, payment_logs, app_settings
- RBAC: roles, permissions, role_permissions, user_roles
- RPC: my_permissions(), my_roles()

## URL

https://niche-bloom-receipt.vercel.app
