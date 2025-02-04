# Мини-проект: Test Param Editor 

## Описание
Test Param Editor — это простой React-компонент, который позволяет пользователю вводить параметры через текстовые поля. Этот компонент обеспечивает удобный интерфейс для ввода данных.

## Функциональность
- Отображение списка параметров с метками и полями ввода.
- Динамическое обновление значений полей ввода.

## Технологии
- [React](https://reactjs.org/) — библиотека для создания пользовательских интерфейсов.
- CSS — стилизация компонентов с использованием Flexbox для выравнивания.

## Установка
1. Склонируйте репозиторий:
   ```bash
   https://github.com/veluat/test-param-editor.git
   ```
   
2. Перейдите в директорию проекта:
    ```bash
   cd ваш-репозиторий
   ```
   
3. Установите зависимости:
    ```bash
   pnpm install
   ```

4. Запустите проект:
    ```
   pnpm start
   ```
## Использование
1. Вставьте компонент ParamEditor в своё приложение.
2. Передайте массив параметров в качестве пропса params, где каждый параметр должен содержать уникальный id и name.
   Пример:
```javascript
  const params = [
    { id: '1', name: 'Назначение' },
    { id: '2', name: 'Длина' },
    ];

  <ParamEditor params={params} />
```
## Стилизация
Компонент использует CSS для минимальной стилизации. Убедитесь, что вы подключили файл стилей index.css, чтобы применить нужные стили.
