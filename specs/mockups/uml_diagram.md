graph TD
    Gamer([Геймер / Пользователь])
    Admin([Администратор / Фиксер])

    Gamer --> U1(Просмотр базы оружия и имплантов)
    Gamer --> U2(Поиск квестов и секретов)
    Gamer --> U3(Создание и сохранение билда персонажа)
    Gamer --> U4(Регистрация и авторизация)
    Gamer --> U5(Лайки и комментарии к чужим билдам)

    Admin --> A1(Добавление новых предметов/патчей)
    Admin --> A2(Модерация комментариев геймеров)
    Admin --> A3(Управление учетными записями)

    style Gamer fill:#00f0ff,stroke:#000,stroke-width:2px
    style Admin fill:#fee75c,stroke:#000,stroke-width:2px
    style U3 fill:#ff0055,stroke:#fff,stroke-width:1px
