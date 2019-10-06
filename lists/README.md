# Списки

Стилизуем списки по-умолчанию:

    ul, ol {
        list-style-type: none;
        margin: 0;
        padding: 0;
    }

Создаём свои маркеры:
    
    ul {
        list-style-type: none;
        margin: 0;
        padding: 0;
    }
    
    li {
        position: relative;
        padding-left: 15px;
    }
    
    li::before {
        content: '';
        width: 10px;
        height: 10px;
        border-radius: 50%;
        background-color: green;
        position: absolute;
        top: calc(50% - 5px);
        left: 0;
    }
