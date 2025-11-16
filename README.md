<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GDMemer CM</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f0f0f0;
        }
        h1, h2, h3 {
            color: #333;
        }
        p, ol, li {
            color: #555;
        }
        .full-width-button {
            background-color: #00BFFF; /* голубой */
            color: white;
            padding: 15px 0;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
            font-size: 18px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-top: 20px;
        }
        .full-width-button:hover {
            background-color: #009ACD; /* темнее при наведении */
        }

        .command-section {
            margin-top: 40px;
            background: white;
            padding: 20px;
            border-radius: 8px;
        }

        .command-section h3 {
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <h1>GDMemer CM</h1>
    <p>
        Здравствуйте! Добро пожаловать на сайт <strong>GDMemer Chat Manager</strong> на GitHub.<br>
        Здесь вы можете узнать всё необходимое о боте, включая команды, туториалы и примеры использования.
    </p>

    <h2>1. Установка</h2>

    <h3>Туториал по установке GDMemer в чат</h3>
    <ol>
        <li>Зайдите в профиль к боту и нажмите «Добавить в группу или канал» или воспользуйтесь кнопкой ниже. (обязательно)</li>
        <li>Выберите чат для добавления бота (обязательно)</li>
        <li>Назначьте администратором (обязательно) и установите должность (по желанию)</li>
    </ol>

    <h2>⚠️ ВАЖНО:</h2>
    <p>Не отключайте уже установленные права — это может помешать боту работать как нужно.</p>

    <button class="full-width-button"
        onclick="window.location.href='https://t.me/gdmemer_cm_bot?startgroup=gdmemer&admin=change_info+restrict_members+delete_messages+pin_messages+invite_users+promote_members+anonymous'">
        ➕ Добавить бота в чат
    </button>

    <!-- Раздел с командами -->
    <div class="command-section">
        <h2>2. Команды</h2>
<h3>Модераторские</h3>
<ol>
    <li>/warn ID – выдать предупреждение</li>
    <li>/ban ID – заблокировать пользователя</li>
    <li>/mute ID – заглушить пользователя</li>
    <li>/setrank ID число – установить пользователю ранг</li>
    <li>/warnlimit число – установить лимит предупреждений</li>
    <li>/admin ID – назначить пользователя администратором</li>
    <li>/setrules текст – установить правила чата</li>
</ol>

<h3>Прочие</h3>
<ol>
    <li>/rules – посмотреть правила чата</li>
    <li>/reaction – поставить реакцию на ваше сообщение</li>
</ol>
