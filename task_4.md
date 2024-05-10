# Задание 4

Добавляем сохранение истории изменений

1. При каждом использовании ручки `/set`, добавляем запись в файл 
`history.json`
    <details>
    <summary>Пример файла history.json</summary>

    ```json
    [
        {
            "timestamp": "2024-05-10 13:52:17",
            "value": {
                "eng": "value 1",
                "ru": "значение 1"
            },
        },
        {
            "timestamp": "2024-05-10 13:52:23",
            "value": {
                "eng": "value 2",
                "ru": "значение 2"
            },
        },
    ]
    ```

    </details>

1. Добавляем ручку `/change-log`, которая отдаёт содержимое файла `history.json`
