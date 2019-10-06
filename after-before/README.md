# ::after, ::before
Работаем с псевдоэлементами

    li::before, li::after {
        content: '&ndash;';
    }

## Примеры
Отмена схлопывания:

    .clearfix::after {
        content: '';
        display: block;
        clear:   both;
    }
