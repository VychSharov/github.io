<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>
        Сайт о студенте
    </title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>


<body>
    <div class="main">
        <header>
            <h1>
                <strong>
                    <center>
                        Шаров Вячеслав Александрович
                    </center>
                </strong>
            </h1>
        </header>
        <br>
        <center>
            <img class="image" src="https://sun9-27.userapi.com/impf/BBGsyNPyBetnEcM42cAFRuYN1VInyIV88SutHQ/KzMq-Y283IM.jpg?size=1617x1618&quality=96&proxy=1&sign=c5ae2c89df9dc47a2ac790e4efdbe86d" alt="Фотография студента" style="width:250px; height: 250px;">
        </center>

        <ul>
            Электронная почта студента: <a href="slava.slavyan.86@mail.ru">slava.slavyan.86@mail.ru</a><br>
            Ссылка на сайт вуза студента: <a href="https://nvsu.ru/">НВГУ</a>
        </ul>
        <br>
        <br>

        <h2>
            Мой ВУЗ
        </h2>
        <article>
            Нижневартовский госудврственный университет лучший ВУЗ в котором я учился.
        </article>
        <br>
        <br>
        
        <div>
            <ul>
                Моя группа: 3802<br>
                Моя будующая профессия: Инженер-программист<br>
                Мои увлечения: Игры<br>
            </ul>
        </div>
        <br>
        <div>
            <table class="tab-1">
                <caption>2.1 Создание таблицы</caption>
                <tr>
                    <td colspan="5"> </td>
                </tr>
                <tr>
                    <td rowspan="3"> </td>
                    <td> </td>
                    <td rowspan="3"> </td>
                    <td> </td>
                    <td> </td>
                </tr>
                <tr>
                    <td rowspan="3"> </td>
                    <td rowspan="3"> </td>
                    <td> </td>
                </tr>
                <tr>
                    <td> </td>
                </tr>
                <tr>
                    <td> </td>
                    <td> </td>
                    <td> </td>
                </tr>
            </table>
        </div>
        <br>
        <br>
        <div>
            <table class="tab-2">
                <caption>2.2 Создание таблицы</caption>
                <tr>
                    <td colspan="8" style="background-color: aquamarine"></td>
                </tr>
                <tr>
                    <td rowspan="6" style="background-color:bisque"></td>
                    <td colspan="6" style="background-color: aquamarine"></td>
                    <td rowspan="6" style="background-color:bisque"></td>
                </tr>
                <tr>
                    <td rowspan="4" style="background-color:bisque"></td>
                    <td colspan="4" style="background-color: aquamarine"></td>
                    <td rowspan="4" style="background-color:bisque"></td>

                </tr>
                <tr>
                    <td rowspan="2" style="background-color:bisque"></td>
                    <td style="background-color:red"></td>
                    <td style="background-color:blue"></td>
                    <td rowspan="2" style="background-color:bisque"></td>

                </tr>
                <tr>
                    <td style="background-color:greenyellow"></td>
                    <td style="background-color:yellow"></td>
                </tr>
                <tr>
                    <td colspan="4" style="background-color: aquamarine"></td>
                </tr>
                <tr>
                    <td colspan="6" style="background-color: aquamarine"></td>
                </tr>
                <tr>
                    <td colspan="8" style="background-color: aquamarine"></td>
                </tr>
            </table>
        </div>
        <br>
        <div class="form_1">
            <h3>ЗАО Птицефабрика №1</h3>
            <form action="" method="post">
                <label for="family">Фамилия</label><input type="text" name="family">
                <br>
                <label for="initial">Инициалы</label><input type="text" name="initial">
                <br>
                <label for="password">Пароль</label><input type="password" name="password">
                <br>
                <label for="adress">Адрес получателя</label><input type="text" name="adress">
                <br>
                <label for="quantity">Количество</label><input type="text" name="quantity">
                <br>
                <label for="type">Тип</label><select name="type" id="type">
                    <option value="chicken">Куриные</option>
                </select>
                <select name="type" id="type">
                    <option value="select">Отборные</option>
                </select>
                <br>
                <label for="delivery">Доставка</label><input name="delivery" type="radio" checked>Почтой
                <input name="delivery" type="radio">Электронно
                <input name="delivery" type="radio">Курьером
                <br>
                <label for="checkbox">Требуется накладная</label><input type="checkbox" name="checkbox">
                <br>
                <label for="info">Дополнительная информация</label><textarea name="info" id="" cols="20" rows="2"></textarea>
                <br>
                <input type="submit" value="Заказать">
                <input type="submit" value="Отменить">
            </form>
        </div>
        <br>
        <div class="form_2">
            <h4>Пример формы регистрации сайта</h4>
            <form action="" method="post" enctype="multipart/form-data">
                <label for="">Логин:</label>
                <br>
                <input type="text">
                <br>
                <label for="">Пароль:</label>
                <br>
                <input type="password">
                <br>
                <label for="">URL-адрес сайта:</label>
                <br>
                <input type="url" value="http://">
                <br>
                <label for="">Название сайта:</label>
                <br>
                <input type="text">
                <br>
                <label for="">Описание сайта:</label>
                <br>
                <textarea name="" id="" cols="60" rows="5"></textarea>
                <br>
                <label for="">Тема сайта:</label>
                <br>
                <select name="" id="">
                    <option value="">Тема не выбрана</option>
                </select>
                <br>
                <label for="">Баннер 88x31:</label>
                <br>
                <input type="file">
                <br>
                <br>
                <input type="reset" value="Очистить"> <input type="submit" value="Отправить">
            </form>
        </div>
    </div>
</body>

</html>
