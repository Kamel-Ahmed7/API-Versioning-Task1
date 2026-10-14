# ASP.NET Core API Versioning Task 🚀

مشروع عملي يوضح كيفية إدارة إصدارات الـ Web APIs بطرق احترافية باستخدام **ASP.NET Core API Versioning**.

---

## 📌 الاستراتيجيات المشروحة في التاسك:

### 1. URL Path Versioning (إصدار عبر المسار)
هذه الطريقة تعتبر الأكثر شيوعاً ووضوحاً، حيث يتم تضمين رقم الإصدار مباشرة داخل مسار الـ URL (Endpoint).

* **مثال على الـ Endpoint:**
  `GET /api/v1/products` أو `GET /api/v2/products`

* **معاينة وطريقة التنفيذ والنتيجة:**
  
<img width="1654" height="691" alt="Query String Versioning" src="https://github.com/user-attachments/assets/afc9266b-9d4d-46d6-93ef-8c49cd49117f" />

---

### 2. Query String Versioning (إصدار عبر المعاملات)
يتم تحديد الإصدار عن طريق إرسال معامل إضافي (Query Parameter) في الـ URL مثل `api-version`.

* **مثال على الـ Endpoint:**
  `GET /api/products?api-version=1.0`

* **معاينة وطريقة التنفيذ والنتيجة:**
 
<img width="1622" height="897" alt="URL Path Versioning" src="https://github.com/user-attachments/assets/20eda121-071b-46e1-bba9-8d050de20f1d" />

---

## 💻 طريقة التشغيل:
1. قم بفتح المشروع باستخدام Visual Studio.
2. شغل الـ API وجرب الـ Endpoints عبر Postman أو Swagger.
