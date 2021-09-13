---
layout: section
---

## Стадія розробки вимог до програмної системи

Моделювання діяльності
---

## Дорожня карта

<center style="margin: 2em 1em">
    <img src="/4.1.png" style="opacity: 1; width:100%">
</center>


---
    layout: two-cols
---



## Моделювання діяльності

<center style="margin:1em">
    <img src="/4.2.jpg" style="opacity: 1; width:100%">
</center>


::right::


<style>

.small-text{
    font-size:0.8rem;    
}

.small-text h1 {
    font-size: 1.4rem !important;
    margin: 0 !important;
    line-height: 1 !important;
}

.small-text h2 {
    font-size: 1.1rem !important;
    margin: 0.3rem !important;
    line-height: 1 !important;
}

.small-text h3 {
    font-size: 1rem !important;
    margin: 0 !important;
    line-height: 0.9 !important;
}

.small-text p  {
    font-size: inherit !important;
    line-height: 1.2 !important;
}



</style>


<div class="small-text">

…

## Характеристика ділових процесів

*[В цьому розділі визначаються зовнішні фактори, що впливають на бізнес (бізнес-актори), та внутрішні фактори (робітники), дається загальна характеристика діяльності бізнес-акторів та робітників, яка здійснюється за допомогою бізнесу.
Дається опис бізнес-сценаріїв взаємодії бізнес-акторів, робітників і, можливо, інформаційної системи за допомогою наступної специфікації:*

**ID:**

**НАЗВА:**

**УЧАСНИКИ:**

**ПЕРЕДУМОВИ:**

**РЕЗУЛЬТАТ:**

**ВИКЛЮЧНІ СИТУАЦІЇ:**

**ОСНОВНИЙ СЦЕНАРІЙ:**

*Кількість сценаріїв визначається у відповідності до специфіки завдання та необхідного рівня деталізації (зазвичай, 5-6 сценаріїв).*

</div>

--- 

## Специфікація бізнес-сценарію 

<center style="margin:1em; width:85%">
    <img src="/4.3.png" style="opacity: 1; width:100%">
</center>

---
    layout: two-cols
---

<style>
    .small-text{
        font-size:0.8rem;    
    }

    .small-text h1 {
        font-size: 1.4rem !important;
        margin: 0 !important;
        line-height: 1 !important;
    }

    .small-text h2 {
        font-size: 1.1rem !important;
        margin: 0.3rem !important;
        line-height: 1 !important;
    }

    .small-text h3 {
        font-size: 1rem !important;
        margin: 0 !important;
        line-height: 0.9 !important;
    }

    .small-text p  {
        font-size: inherit !important;
        line-height: 1.2 !important;
    }

    .red {
        background-color:#d32f2f;
        color:white;
    }

    .green {
        background-color:#2e7d32;
        color:white;
    
    }

</style>

## <div style="color:#d32f2f"> рама мылась мамой </div>

<div class="small-text" style="    
    border-radius:4px;
    border: 1px solid #cfd7e6;
    box-shadow: 0 1px 3px 0 rgba(89,105,129,.05), 0 1px 1px 0 rgba(0,0,0,.025);
    padding:1em; 
    margin:1em 1em 0 0;
">

**3.5. Сценарій реєстрації нового користувача**

**Передумова** - користувач має бути незареєстрованим.

**Результат** - <span class="red"> створюється </span> акаунт нового користувача.

1. Користувач переходить на офіційний сайт сервісу.
2. Користувач натискає на кнопку «Зареєструватися».
3. Користувач заповнює реєстраційну форму.
4. Реєстраційні дана <span class="red"> фіксуються </span> у <span class="red"> базі даних сервісу анкетування </span>.
5. <span class="red"> Реєстрацію завершено. </span>
6. <span class="red"> Користувач має змогу користуватися усіма ресурсами сервісу. </span>

</div>

::right::


## <div style="color:#2e7d32; text-align: right;"> мама мыла раму </div>

<div class="small-text" style="    
    border-radius:4px;
    border: 1px solid #cfd7e6;
    box-shadow: 0 1px 3px 0 rgba(89,105,129,.05), 0 1px 1px 0 rgba(0,0,0,.025);
    padding:1em; 
    margin:1em 0 0 1em;
">

**3.5 Сценарій реєстрації нового користувача**

**Передумова** - користувач має бути незареєстрованим.(Обліковий запис користувача в системі відсутній)

**Результат** – <span class="green"> обліковий запис </span> нового користувача.

1. <span class="green"> Користувач розпочинає взаємодію. </span>
2. Користувач натискає на кнопку «Зареєструватися».
3. Користувач заповнює реєстраційну форму.
4. <span class="green"> Система створює новий обліковий запис та фіксує в ньому </span> реєстраційні дані користувача.
5. <span class="green"> Система направляє користувачу повідомлення на електронну пошту. </span>
6. <span class="green"> Система надає користувачу сторінку входу в систему. </span>
7. <span class="green"> Користувач закінчує взаємодію. </span>

</div>

---

## Виявлення вимог до системи

<div style="margin:1em; width:95%">
    <img src="/4.4.png" style="opacity: 1; width:100%">
</div>

