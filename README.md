# مشروع تصنيف الصور (كلاب vs قطط) باستخدام Teachable Machine

## 📌 فكرة المشروع
مشروع بسيط للتعرف على الصور باستخدام نموذج تم تدريبه بواسطة [Teachable Machine من Google](https://teachablemachine.withgoogle.com/).  
الموديل يقوم بتمييز ما إذا كانت الصورة تحتوي على *كلب* أو *قطة*.

## 🧠 خطوات العمل
1. تم جمع صور لتصنيفين: *كلاب* و *قطط*.
2. تم تدريب النموذج باستخدام Teachable Machine.
3. تم تصدير النموذج بصيغة TensorFlow (Keras format).
4. تم كتابة كود Python لتحميل النموذج، وقراءة صورة، والتنبؤ بالتصنيف.

## 🛠 المتطلبات
- Python 3.x  
- TensorFlow  
- NumPy  
- Pillow (لتحميل الصور)

### تثبيت المكتبات:
```bash
pip install tensorflow numpy pillow
