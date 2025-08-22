---
title: "تماس با ما"
date: 2023-10-27T10:00:00+03:30
draft: false
description: "از طریق فرم زیر یا راه‌های ارتباطی دیگر با ما در تماس باشید."
# اگر قالبتان layout خاصی برای صفحات دارد، اینجا مشخص کنید
# layout: "contact-page" 
---

## در ارتباط باشیم!

ما همیشه از شنیدن نظرات، پیشنهادات و سوالات شما خوشحال می‌شویم. اگر می‌خواهید در مورد پروژه‌ای صحبت کنید یا سوالی دارید، از راه‌های زیر استفاده کنید.

### راه‌های دیگر برای تماس

*   **ایمیل:** `info@your-domain.com`
*   **شبکه‌های اجتماعی:** می‌توانید ما را در [لینکدین](https://linkedin.com/in/yourprofile) یا [توییتر](https://twitter.com/yourprofile) دنبال کنید.

---

## ارسال پیام مستقیم

برای ارسال پیام مستقیم، لطفاً فرم زیر را با دقت تکمیل کنید. ما در اسرع وقت به شما پاسخ خواهیم داد.

<!-- 
    کد HTML فرم تماس در اینجا شروع می‌شود.
    این کد در فایل مارک‌داون به خوبی کار می‌کند چون هوگو می‌تواند HTML خام را پردازش کند.
    قبل از استفاده، حتماً یک اکانت در Formspree.io بسازید و آدرس فرم خود را جایگزین کنید.
-->

<form action="https://formspree.io/f/YOUR_UNIQUE_FORM_ID" method="POST">
    <div class="form-group">
        <label for="name">نام شما:</label>
        <input type="text" id="name" name="name" required>
    </div>
    <div class="form-group">
        <label for="email">ایمیل شما:</label>
        <input type="email" id="email" name="email" required>
    </div>
    <div class="form-group">
        <label for="message">پیام شما:</label>
        <textarea id="message" name="message" rows="5" required></textarea>
    </div>
    <button type="submit">ارسال پیام</button>
</form>

<style>
/* 
    کمی استایل ساده برای زیباتر شدن فرم. 
    می‌توانید این کد را حذف کرده و از CSS اصلی قالبتان استفاده کنید.
*/
.form-group {
    margin-bottom: 1.5rem;
}
label {
    display: block;
    margin-bottom: 0.5rem;
    font-weight: bold;
}
input[type="text"],
input[type="email"],
textarea {
    width: 100%;
    padding: 0.75rem;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box; /* Important */
}
button {
    background-color: #007bff;
    color: white;
    padding: 0.75rem 1.5rem;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 1rem;
}
button:hover {
    background-color: #0056b3;
}
</style>
