---
title: Задать вопрос
layout: default
redirect_from:
  - /answer
---

Уважаемые посетители, для получения консультации необходимо заполнить представленную нижу форму, однако просим иметь ввиду следующее:

- ответ носит рекомендательный характер и не заменяет собой визита к специалисту;
- ответ будет тем более точен, чем более полно вы опишете свою проблему;
- администрация сайта оставляет за собой право производить отбор вопросов, на которые будет дан ответ.

Администрация сайта считает нецелесообразным отвечать на вопрос, если:

- вопрос не относится к области компетенции специалистов ЛПУ;
- в ответе требуются комментарии по поводу схемы лечения, назначенной другими специалистами;
- в ответе требуются комментарии по поводу результатов лабораторных исследований при неуказанных нормах лаборатории, где они были проведены;
- в вопросе содержится нецензурная лексика, оскорбительные выражения;
- указанные данные являются неполными или недостоверными;
- обращение ограничивается постановкой вопросов риторического характера.

Поля помеченные символ "<span class="is-req">*</span>" являются обязательными к заполнению.

<form>
  <fieldset>
  <legend>Форма обратной связи</legend>
    <div class="is-row">
        <div class="form-item is-col">
            <label>Фамилия <span class="is-req">*</span></label>
            <input type="text" name="surname" required>
        </div>
        <div class="form-item is-col">
            <label>Имя <span class="is-req">*</span></label>
            <input type="text" name="name" required>
        </div>
    </div>
    <div class="is-row">
        <div class="form-item is-col">
            <label>Отчество</label>
            <input type="text" name="middlename">
        </div>
        <div class="form-item is-col">
            <label>Возраст <span class="is-req">*</span></label>
            <input type="text" name="age" required>
        </div>
    </div>
    <div class="is-row">
        <div class="form-item is-col">
            <label>Эл. почта <span class="is-req">*</span></label>
            <input type="text" name="email" required>
        </div>
        <div class="form-item is-col">
            <label>Телефон</label>
            <input type="text" name="phone">
        </div>
    </div>
    <div class="is-row">
        <div class="form-item is-col">
            <label>Адрес проживания <span class="is-req">*</span></label>
            <input type="text" name="address" required>
        </div>
    </div>
    <div class="form-item">
      <label>Обращение <span class="is-req">*</span></label>
      <textarea name="user-about" rows="5" name="message" required></textarea>
    </div>
    <div class="form-item">
        <label class="is-checkbox"><input type="checkbox" required> Настоящим даю согласие на совершение с моими персональными данными перечисленных ниже действий: сбор, запись, систематизацию, накопление, хранение, уточнение (обновление, изменение), обезличивание, блокирование, удаление, уничтожение и обработку <span class="is-req">*</span></label>
    </div>
    <div class="form-item is-buttons">
      <button type="submit" class="button">Отправить</button>
    </div>
  </fieldset>
</form>