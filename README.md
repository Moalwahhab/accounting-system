# 🧮 نظام المحاسب الشامل

نظام محاسبي متكامل مطور باستخدام Django و Bootstrap لإدارة الحسابات المالية والمخزون.

## 🌟 الميزات الرئيسية

- ✅ إدارة المبيعات والمشتريات
- ✅ نظام مخزون متقدم
- ✅ إدارة العملاء والموردين  
- ✅ التقارير المالية
- ✅ لوحة تحكم تفاعلية
- ✅ واجهة عربية كاملة
- ✅ متوافق مع الجوال

## 🚀 التثبيت السريع

### 1. استنساخ المشروع
\`\`\`bash
git clone https://github.com/YOUR_USERNAME/accounting-system.git
cd accounting-system
\`\`\`

### 2. إعداد البيئة الافتراضية
\`\`\`bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# أو
venv\Scripts\activate     # Windows
\`\`\`

### 3. تثبيت المتطلبات
\`\`\`bash
pip install -r requirements.txt
\`\`\`

### 4. إعداد قاعدة البيانات
\`\`\`bash
cp .env.example .env
# قم بتعديل .env بالإعدادات الصحيحة
python manage.py migrate
python manage.py createsuperuser
\`\`\`

### 5. تشغيل النظام
\`\`\`bash
python manage.py runserver
\`\`\`

زيارة: http://localhost:8000

## 🐳 التشغيل بـ Docker

\`\`\`bash
docker-compose up -d
\`\`\`

## 📱 استخدام النظام

- **لوحة التحكم**: http://localhost:8000
- **لوحة الإدارة**: http://localhost:8000/admin
- **API**: http://localhost:8000/api

## 🛡️ الأمان

النظام يتضمن طبقات أمان متقدمة:
- حماية CSRF/XSS
- تشفير كلمات المرور
- تسجيل العمليات الحساسة
- نسخ احتياطي تلقائي

## 📊 التقارير

- تقارير المبيعات والمشتريات
- تقرير المخزون
- الأرباح والخسائر
- تقارير العملاء

## 🤝 المساهمة

نرحب بالمساهمات! الرجاء قراءة CONTRIBUTING.md

## 📄 الترخيص

هذا المشروع مرخص تحت رخصة MIT - راجع LICENSE

## 📞 الدعم

- GitHub Issues للأخطاء والاقتراحات
- البريد الإلكتروني: support@accounting-system.com# accounting-system
