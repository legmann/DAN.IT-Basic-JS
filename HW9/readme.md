# **Теоретичні питання**

### **1. Опишіть, як можна створити новий HTML тег на сторінці.**

**Відповідь:**
Новий тег можна створити за допомогою команди: document.createElement(element), де element це новий тег, який буде створено.

### **2. Опишіть, що означає перший параметр функції insertAdjacentHTML і опишіть можливі варіанти цього параметра.?**

**Відповідь:**
Перший параметр функції insertAdjacentHTML це position. Він оприділяє позицію куди буде додано елемент стосовно елемента який визвав метод. Може мати наступні значання: beforebegin, afterbegin, beforeend, afterend.

### **3. Як можна видалити елемент зі сторінки?**

**Відповідь:**
Щоб видалити потрібний елемент зі сторінки потрібно звернутись до елемента та викликати метод element.remove()
