# Обо мне

<div class="profile-section">
<img src="/ava.jpg" alt="Наталья Кошкарёва" class="profile-avatar" />

Я 15 лет работаю техническим писателем и могу написать практически любой документ по любым требованиям.\
Умею работать с Word и хочу освоить docs-as-code. 
</div>

::: tip Моя философия
Архитектура документации должна быть такой же чистой, как и архитектура кода.
:::

::: tip Тра-ля-ля
:::

## Контакты

Связаться со мной можно по почте <writer@example.com> или в соцсетях:

* Профиль с проектами: [GitHub](https://github.com/example "Профиль GitHub")
* Профессиональный трек: [LinkedIn](https://linkedin.com/in/example "Профиль LinkedIn")
* Оперативная связь: [Telegram](https://t.me/example "Написать в Telegram")

<!-- <style scoped>
.profile-section {
display: flow-root;
margin-bottom: 24px;
}

.profile-avatar {
width: 140px;
height: 140px;
border-radius: 16px;
float: right;
margin: 12px 0 16px 24px; /* 12px сверху отделяют фото от заголовка */
object-fit: cover;
box-shadow: var(--vp-shadow-2);
}

/* На мобильных сохраняем float, но пропорционально уменьшаем фото */
@media (max-width: 640px) {
.profile-avatar {
    width: 96px;
    height: 96px;
    margin: 6px 0 12px 14px; /* Компактные отступы для узких экранов */
}
}
</style> -->

<style scoped>

.profile-section {
display: flow-root;
margin-bottom: 24px;
}
.profile-avatar {
  /* Размер аватарки */
  width: 250px;
  height: 250px;
  
  /* Делаем картинку круглой и предотвращаем её искажение */
  border-radius: 50%;
  object-fit: cover;
  
  /* Включаем обтекание текстом слева */
  float: right;
  
  /* Отступы от текста справа и снизу */
  margin: 0 16px 8px 0;
  
  /* Заставляем текст обтекать именно круг, а не квадрат */
  shape-outside: circle();
}

/* Очистка потока (clearfix), чтобы родительский блок не схлопнулся, если текста мало */
.post::after {
  content: "";
  display: table;
  clear: both;
}
</style>