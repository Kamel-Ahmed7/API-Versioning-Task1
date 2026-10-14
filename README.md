<img width="1654" height="691" alt="Query String Versioning" src="https://github.com/user-attachments/assets/2318fdb9-3f21-4808-b857-d5fbfdba1fe0" />
# ASP.NET Core API Versioning Task 🚀

مشروع عملي يوضح كيفية إدارة إصدارات الـ Web APIs بطرق احترافية باستخدام **ASP.NET Core API Versioning**.

---

## 📌 الاستراتيجيات المشروحة في التاسك:

### 1. URL Path Versioning (إصدار عبر المسار)
هذه الطريقة تعتبر الأكثر شيوعاً ووضوحاً، حيث يتم تضمين رقم الإصدار مباشرة داخل مسار الـ URL (Endpoint).

* **مثال على الـ Endpoint:**
  `GET /api/v1/products` أو `GET /api/v2/products`

* **معاينة وطريقة التنفيذ والنتيجة:**
  ![URL Path Versioning Output](![Uploading Query String Versioning.png…]()
)

---

### 2. Query String Versioning (إصدار عبر المعاملات)
يتم تحديد الإصدار عن طريق إرسال معامل إضافي (Query Parameter) في الـ URL مثل `api-version`.

* **مثال على الـ Endpoint:**
  `GET /api/products?api-version=1.0`

* **معاينة وطريقة التنفيذ والنتيجة:**
  ![Query String Versioning Output](<img width="1622" height="897" alt="URL Path Versioning" src="https://github.com/user-attachments/assets/41bdcdc9-10a5-4e96-b243-425857827036" />
)

---

## 💻 طريقة التشغيل:
1. قم بفتح المشروع باستخدام Visual Studio.
2. شغل الـ API وجرب الـ Endpoints عبر Postman أو Swagger.
