# ASP.NET Core API Versioning Task 🚀

مشروع عملي يوضح كيفية إدارة إصدارات الـ Web APIs بطرق احترافية باستخدام **ASP.NET Core API Versioning**.

---

## 📌 الاستراتيجيات المشروحة في التاسك:

### 1. URL Path Versioning (إصدار عبر المسار)
هذه الطريقة تعتبر الأكثر شيوعاً ووضوحاً، حيث يتم تضمين رقم الإصدار مباشرة داخل مسار الـ URL (Endpoint).

* **مثال على الـ Endpoint:**
  `GET /api/v1/products` أو `GET /api/v2/products`

* **معاينة وطريقة التنفيذ والنتيجة:**
  ![URL Path Versioning Output](./screenshots/url-path.png)

---

### 2. Query String Versioning (إصدار عبر المعاملات)
يتم تحديد الإصدار عن طريق إرسال معامل إضافي (Query Parameter) في الـ URL مثل `api-version`.

* **مثال على الـ Endpoint:**
  `GET /api/products?api-version=1.0`

* **معاينة وطريقة التنفيذ والنتيجة:**
  ![Query String Versioning Output](./screenshots/query-string.png)

---

## 💻 طريقة التشغيل:
1. قم بفتح المشروع باستخدام Visual Studio.
2. شغل الـ API وجرب الـ Endpoints عبر Postman أو Swagger.
