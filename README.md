# Liferay Animate.css Client Extension  

[![License](https://img.shields.io/badge/license-hippocratic%20license-orange.svg?longCache=true&style=for-the-badge)](https://github.com/slemarchand/liferay-animate-css/blob/main/LICENSE)

A **Liferay CSS Client Extension** that integrates [Animate.css](https://animate.style/) into your Liferay site.  

With this extension, you can add animation effects to any fragment simply by adding the appropriate **Animate.css class** (e.g. `animate__fadeIn`, `animate__bounce`) to the field  **Advanced → CSS → CSS Classes** of your fragment.  

---

## ✨ Features  

- 🔌 **Plug & Play**: Deploy once, available globally across your site.  
- 🎨 **Animate Anything**: Apply animations to fragments by just adding CSS classes.  
- ⚡ **Powered by Animate.css**: Brings over 70 animation effects.  
- 🧩 **No Code Changes**: Works with existing Liferay fragments.  

---

## 📦 Installation  

Install from Lliferay Marketplace (soon available).

---

## 🚀 Usage  

1. Add the client extension at the page level (Configure → Design → Customization → CSS → CSS Client Extension) or at the layout set level (Pages  → Configuration → Design → Customization → CSS → CSS Client Extension).

2. Go to your **Fragment Advanced configuration tab** in Liferay.  

3. Add the desired Animate.css classes in the **CSS Classes** field.  
   - Example:  

   ```css
   animate__animated animate__bounce
   ```

4. Save and publish your content page. Your fragment will now animate 🎉.  

> Tip: You can chain classes (e.g., `animate__animated animate__fadeIn animate__faster`). See [Animate.css docs for timing helpers](https://animate.style/#utilities).

---

## 📚 References  

- [Liferay Client Extensions](https://learn.liferay.com/dxp/latest/en/developing-applications/client-extensions.html)  
- [Animate.css Documentation](https://animate.style/)  

---

## 📄 License  

This project is licensed under the [MIT License](LICENSE).  

---

⚡ Bring your Liferay fragments to life with **Animate.css**!
