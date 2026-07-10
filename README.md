# بطاقتي VIP — bitaqaty.vip
منصة دعوات زفاف رقمية فاخرة (عربي · بادینی · سۆرانی)
ملفات ثابتة — بدون بناء، ترفع مباشرة على GitHub + Vercel

## الروابط
- `/` الرئيسية + القوالب الحية
- `/admin` لوحة التحكم (الرمز من Environment Variables)
- `/edit/CODE?key=KEY` رابط التعديل للزبون
- `/d/CODE` رابط الدعوة للضيوف (يقفل تلقائياً بعد الحفل بيومين)

## متغيرات البيئة في Vercel
- ADMIN_CODE — رمزك السري
- ADMIN_WHATSAPP — رقمك (مثل 9647515193165)
- UPSTASH_REDIS_REST_URL و UPSTASH_REDIS_REST_TOKEN — من upstash.com (مجاني)
