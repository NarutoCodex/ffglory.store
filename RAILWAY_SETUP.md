# Railway Setup - Database Permanent Rakhne Ke Liye

## Yeh karo ek baar:

### Step 1: PostgreSQL Add Karo Railway Mein
1. Railway dashboard mein jao
2. "New" click karo
3. "Database" → "PostgreSQL" select karo
4. Same project mein add karo

### Step 2: DATABASE_URL Connect Karo
1. PostgreSQL service pe click karo
2. "Variables" tab mein jao
3. `DATABASE_URL` copy karo
4. Apni web service ke "Variables" mein jao
5. `DATABASE_URL` paste karo (Railway ye automatically bhi kar deta hai)

### Step 3: Deploy karo
- Ab deploy karo - data hamesha rehega, reset nahi hoga

## Note:
- Pehli baar deploy hone pe tables automatically ban jaayenge
- Admin account bhi automatically ban jaayega: naruto@clanboost.com / narrutocodex
- Baad ke sab deploys mein data same rehega
