<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Валентиновские штаны — услуги лечебной физкультуры, коррекция осанки, реабилитация, профилактика заболеваний. Запишитесь на курсы!">
    <title>Валентиновы штаны — услуги лечебной физкультуры</title>
    <style>
        /* Сброс стилей */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Основные стили */
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #fafafa;
            color: #333;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }

        /* Верхняя панель */
        header {
            background-color: #ffccff;
            color: #6a1b9a;
            padding: 15px 20px;
            border-bottom: 4px solid #ff80ab;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            font-size: 2.5em;
            margin: 0;
            letter-spacing: 2px;
        }

        header nav ul {
            list-style: none;
            display: flex;
            justify-content: flex-end;
            gap: 20px;
            margin: 0;
        }

        header nav ul li {
            display: inline-block;
        }

        header nav ul li a {
            text-decoration: none;
            color: #6a1b9a;
            font-weight: 600;
            font-size: 1em;
            transition: all 0.3s ease;
        }

        header nav ul li a:hover {
            color: #ff80ab;
            transform: scale(1.1);
        }

        /* Баннер */
        .banner {
            background-color: #ff80ab;
            color: white;
            padding: 50px 0;
            text-align: center;
            font-size: 1.5em;
            margin-top: 100px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            position: relative;
        }

        .banner p {
            font-size: 1.3em;
        }

        /* Основное содержание */
        main {
            padding: 80px 20px;
        }

        h2 {
            text-align: center;
            color: #ff80ab;
            font-size: 2.5em;
            margin-bottom: 50px;
        }

        /* Стили для списка товаров и услуг */
        .services-list, .products-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            margin-top: 20px;
        }

        .service-item, .product-item {
            background-color: #ffffff;
            border: 2px solid #ffccff;
            border-radius: 12px;
            width: 280px;
            padding: 25px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: all 0.3s ease;
            position: relative;
        }

        .service-item img, .product-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
            margin-bottom: 20px;
        }

        .service-item h3, .product-item h3 {
            color: #6a1b9a;
            font-size: 1.5em;
            margin-bottom: 15px;
        }

        .service-item p, .product-item p {
            color: #555;
            font-size: 1em;
            margin-bottom: 15px;
        }

        .service-item:hover, .product-item:hover {
            transform: scale(1.05);
        }

        .button {
            background-color: #ff80ab;
            color: white;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.1em;
            display: inline-block;
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #ff5e8f;
        }

        /* Звезды для отзывов */
        .stars {
            color: #ffcc00;
            font-size: 1.5em;
            margin-bottom: 10px;
        }

        /* Отзывы */
        .reviews {
            background-color: #fff0f6;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .review-item {
            background-color: #ffffff;
            border: 1px solid #ffccff;
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .review-item h4 {
            color: #6a1b9a;
            font-size: 1.3em;
            margin-bottom: 10px;
        }

        .review-item p {
            font-size: 1em;
            color: #555;
        }

        .social-links {
            text-align: center;
            margin-top: 40px;
        }

        .social-links a {
            color: #6a1b9a;
            margin: 0 10px;
            font-size: 1.5em;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .social-links a:hover {
            color: #ff80ab;
        }

        /* Наша команда */
        .team {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
            margin-top: 50px;
        }

        .team-member {
            width: 200px;
            text-align: center;
        }

        .team-member img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        .team-member h3 {
            font-size: 1.2em;
            color: #6a1b9a;
        }

        .team-member p {
            font-size: 1em;
            color: #555;
        }

        /* Футер */
        footer {
            background-color: #ffccff;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
            font-size: 1em;
            color: #6a1b9a;
        }
    </style>
</head>
<body>
<header>
    <div class="container">
        <h1>Валентиновы штаны</h1>
        <nav>
            <ul>
                <li><a href="#services">Услуги</a></li>
                <li><a href="#products">Продукты</a></li>
                <li><a href="#reviews">Отзывы</a></li>
                <li><a href="#contact">Контакты</a></li>
                <li><a href="#team">Наша команда</a></li>
            </ul>
        </nav>
    </div>
</header>

<div class="banner">
    <p>Валентиновы штаны — во все стороны равны</p>
</div>

<main>
    <h2 id="services">Наши услуги</h2>
    <div class="services-list">
        <!-- Услуги (15 услуг) -->
        <div class="service-item"><img src="1.png" alt="Услуга 1">
            <h3>Коррекция осанки</h3>
            <p>Услуга направлена на улучшение осанки и профилактику заболеваний позвоночника.</p>
            <a href="https://vk.com/id348913324#" class="button">Записаться</a>
        </div>
        <div class="service-item"><img src="i (1).webp" alt="Услуга 2">
            <h3>Массаж спины</h3>
            <p>Эффективный массаж для снятия напряжения в спине и улучшения циркуляции крови.</p>
            <a href="https://vk.com/id348913324#" class="button">Записаться</a>
        </div>
        <div class="service-item"><img src="i.webp" alt="Услуга 3">
            <h3>Физиотерапия</h3>
            <p>Комплекс процедур для реабилитации и восстановления после травм.</p>
            <a href="https://vk.com/id348913324#" class="button">Записаться</a>
        </div>
        <div class="service-item"><img src="i (14).webp" alt="Услуга 4">
            <h3>Реабилитация после операций</h3>
            <p>Индивидуальные программы для восстановления после хирургических вмешательств.</p>
            <a href="https://vk.com/id348913324#" class="button">Записаться</a>
        </div>
        <div class="service-item"><img src="i (3).webp" alt="Услуга 5">
            <h3>Профилактика заболеваний суставов</h3>
            <p>Профилактические занятия для поддержания здоровья суставов и их функциональности.</p>
            <a href="https://vk.com/id348913324#" class="button">Записаться</a>
        </div>
        <div class="service-item"><img src="i (4).webp" alt="Услуга 6">
            <h3>Групповые занятия</h3>
            <p>Занятия в группах для улучшения физической формы и общего самочувствия.</p>
            <a href="https://vk.com/id348913324#" class="button">Записаться</a>
        </div>
        <div class="service-item"><img src="i (6).webp" alt="Услуга 7">
            <h3>Индивидуальные тренировки</h3>
            <p>Персональные тренировки с учетом ваших особенностей и целей.</p>
            <a href="https://vk.com/id348913324#" class="button">Записаться</a>
        </div>
        <div class="service-item"><img src="i (7).webp" alt="Услуга 8">
            <h3>Кардио тренировки</h3>
            <p>Упражнения для укрепления сердечно-сосудистой системы и общего состояния здоровья.</p>
            <a href="https://vk.com/id348913324#" class="button">Записаться</a>
        </div>
        <div class="service-item"><img src="i (5).webp" alt="Услуга 9">
            <h3>Занятия на тренажерах</h3>
            <p>Работа на специализированных тренажерах для увеличения силы и выносливости.</p>
            <a href="https://vk.com/id348913324#" class="button">Записаться</a>
        </div>
        <div class="service-item"><img src="i (8).webp" alt="Услуга 10">
            <h3>Дыхательная гимнастика</h3>
            <p>Комплекс дыхательных упражнений для улучшения кислородного обмена и снятия стресса.</p>
            <a href="https://vk.com/id348913324#" class="button">Записаться</a>
        </div>
        <div class="service-item"><img src="i (9).webp" alt="Услуга 11">
            <h3>Занятия для беременных</h3>
            <p>Программа для будущих мам, направленная на укрепление мышц и подготовку к родам.</p>
            <a href="https://vk.com/id348913324#" class="button">Записаться</a>
        </div>
        <div class="service-item"><img src="i (10).webp" alt="Услуга 12">
            <h3>Плавание</h3>
            <p>Занятия плаванием для укрепления всего организма и улучшения общего самочувствия.</p>
            <a href="https://vk.com/id348913324#" class="button">Записаться</a>
        </div>
        <div class="service-item"><img src="i (11).webp" alt="Услуга 13">
            <h3>Йога</h3>
            <p>Практика для улучшения гибкости и гармонизации тела и разума.</p>
            <a href="https://vk.com/id348913324#" class="button">Записаться</a>
        </div>
        <div class="service-item"><img src="i (12).webp" alt="Услуга 14">
            <h3>Медитация</h3>
            <p>Занятия медитацией для снятия стресса и улучшения психоэмоционального состояния.</p>
            <a href="https://vk.com/id348913324#" class="button">Записаться</a>
        </div>
        <div class="service-item"><img src="i (13).webp" alt="Услуга 15">
            <h3>Семейная реабилитация</h3>
            <p>Комплексное восстановление для всей семьи после травм и заболеваний.</p>
            <a href="https://vk.com/id348913324#" class="button">Записаться</a>
        </div>
    </div>

    <h2 id="products">Наши продукты</h2>
    <div class="products-list">
        <!-- Товары (15 товаров) -->
        <div class="product-item">
            <img src="6466182950.jpg" alt="Продукт 1">
            <h3>Пояс для коррекции осанки</h3>
            <p>Помогают улучшить осанку и разгрузить позвоночник.</p>
            <a href="https://vk.com/id348913324#" class="button">Купить</a>
        </div>
        <div class="product-item">
            <img src="i (15).webp" alt="Продукт 2">
            <h3>Ремень для поддержания спины</h3>
            <p>Специальный ремень для поддержания правильной осанки.</p>
            <a href="https://vk.com/id348913324#" class="button">Купить</a>
        </div>
        <div class="product-item">
            <img src="orig.webp" height="100"  alt="Продукт 3">
            <h3>Массажный валик</h3>
            <p>Идеален для снятия напряжения и болей в спине и шее.</p>
            <a href="https://vk.com/id348913324#" class="button">Купить</a>
        </div>
        <div class="product-item">
            <img src="vwOfimxakdg.jpg" alt="Продукт 4">
            <h3>Тренажер для позвоночника</h3>
            <p>Устройство для восстановления и поддержания здоровья спины.</p>
            <a href="https://vk.com/id348913324#" class="button">Купить</a>
        </div>
        <div class="product-item">
            <img src="orig (1).webp" alt="Продукт 5">
            <h3>Гимнастический мяч</h3>
            <p>Используется для тренировки гибкости и укрепления мышц.</p>
            <a href="https://vk.com/id348913324#" class="button">Купить</a>
        </div>
        <div class="product-item">
            <img src="massazhnyj-sharik-s-shipami-s-odnim-massazhnym-kolechkom-sudzhok-new.jpg" alt="Продукт 6">
            <h3>Шарик для массажа</h3>
            <p>Массажный шарик для глубокого расслабления мышц.</p>
            <a href="https://vk.com/id348913324#" class="button">Купить</a>
        </div>
        <div class="product-item">
            <img src="7029143208.jpg" alt="Продукт 7">
            <h3>Корсет для спины</h3>
            <p>Обеспечивает поддержку и разгрузку позвоночника.</p>
            <a href="https://vk.com/id348913324#" class="button">Купить</a>
        </div>
        <div class="product-item">
            <img src="orig (2).webp" alt="Продукт 8">
            <h3>Пояс для фитнеса</h3>
            <p>Для поддержания мышц и улучшения осанки во время тренировок.</p>
            <a href="https://vk.com/id348913324#" class="button">Купить</a>
        </div>
        <div class="product-item">
            <img src="orig (3).webp" alt="Продукт 9">
            <h3>Подушка для шеи</h3>
            <p>Обеспечивает комфорт и поддержку шейного отдела позвоночника.</p>
            <a href="https://vk.com/id348913324#" class="button">Купить</a>
        </div>
        <div class="product-item">
            <img src="i (16).webp" alt="Продукт 10">
            <h3>Эластичные бинты</h3>
            <p>Для фиксации суставов и снятия напряжения.</p>
            <a href="https://vk.com/id348913324#" class="button">Купить</a>
        </div>
        <div class="product-item">
            <img src="i (17).webp" alt="Продукт 11">
            <h3>Массажные наколенники</h3>
            <p>Для профилактики и лечения болей в коленях.</p>
            <a href="https://vk.com/id348913324#" class="button">Купить</a>
        </div>
        <div class="product-item">
            <img src="Fitness-Training-Latex-Resistance-Rubber-Pulling-up-Yoga-Exercise-Bands-for-Home-Gym.avif" alt="Продукт 12">
            <h3>Лента для тренировок</h3>
            <p>Для укрепления мышц и улучшения гибкости.</p>
            <a href="https://vk.com/id348913324#" class="button">Купить</a>
        </div>
        <div class="product-item">
            <img src="6569508217.jpg" alt="Продукт 13">
            <h3>Тренажер для рук</h3>
            <p>Устройство для тренировки и укрепления рук и плеч.</p>
            <a href="https://vk.com/id348913324#" class="button">Купить</a>
        </div>
        <div class="product-item">
            <img src="6123429942.jpg" alt="Продукт 14">
            <h3>Скакалка</h3>
            <p>Для кардионагрузок и улучшения общей физической формы.</p>
            <a href="https://vk.com/id348913324#" class="button">Купить</a>
        </div>
        <div class="product-item">
            <img src="i (18).webp" alt="Продукт 15">
            <h3>Фитнес-резинки</h3>
            <p>Для тренировок на гибкость и укрепление мышц.</p>
            <a href="https://vk.com/id348913324#" class="button">Купить</a>
        </div>
    </div>

    <h2 id="reviews">Отзывы</h2>
    <div class="reviews">
        <!-- Отзывы (20 отзывов) -->
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Анна С.</h4>
            <p>Занимаюсь на групповых занятиях уже несколько месяцев. Очень довольна результатом!</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Максим П.</h4>
            <p>Отличное место для реабилитации после травм. Очень профессиональные специалисты!</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Ирина Т.</h4>
            <p>Очень помогла реабилитация после операции. Рекомендую всем!</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Оксана Л.</h4>
            <p>Прекрасное место для оздоровления и восстановления. Отличные тренеры!</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Сергей В.</h4>
            <p>После курса массажа спины почувствовал значительное улучшение. Отлично!</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Марина Ф.</h4>
            <p>Тренировки индивидуально подобраны под меня. Очень довольна результатом.</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Алексей Д.</h4>
            <p>Занимаюсь с личным тренером, чувствую улучшения каждый день!</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Екатерина И.</h4>
            <p>Мне понравились занятия йогой. Очень полезно для организма и душевного состояния.</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Наталья К.</h4>
            <p>Курсы по улучшению осанки — это просто спасение для моей спины!</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Дмитрий П.</h4>
            <p>Очень хорошая реабилитация после травм, благодарю!</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Елена В.</h4>
            <p>Групповые занятия очень поддерживают в хорошем физическом состоянии. Всем рекомендую!</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Татьяна Ш.</h4>
            <p>Очень эффективные занятия для восстановления после родов!</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Светлана К.</h4>
            <p>Массаж и тренировки на тренажерах — это лучшее, что я пробовала для своей спины.</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Галина Б.</h4>
            <p>Тренеры внимательные, атмосфера уютная, результат — на лицо!</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Роман С.</h4>
            <p>Очень профессиональные специалисты, хороший подход к каждому клиенту.</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Никита О.</h4>
            <p>Благодарю команду за качественную работу и отличные результаты!</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Анна К.</h4>
            <p>Занятия на тренажерах были именно тем, что мне нужно было для восстановления после травмы.</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Павел Г.</h4>
            <p>Очень понравилась реабилитация после операции. Я чувствую себя намного лучше!</p>
        </div>
        <div class="review-item">
            <div class="stars">★★★★★</div>
            <h4>Виктория Н.</h4>
            <p>Прекрасная атмосфера, внимательное отношение и профессиональные услуги.</p>
        </div>
    </div>greet seven deven gred 

    <h2 id="team">Наша команда</h2>
    <div class="team">
        <div class="team-member">
            <img src="Изображение WhatsApp 2024-08-29 в 10.28.40_e2d9cd7a.jpg" alt="Сотрудник 1">
            <h3>Валентина Егорова</h3>
            <p>Опытный специалист, который всегда находит индивидуальный подход к каждому пациенту. Под ее руководством клиника предоставляет высококачественные медицинские и реабилитационные услуги.</p>
        </div>
        <div class="team-member">
            <img src="259177cbfb55b621e5b26fdec5416e78.jpg" alt="Сотрудник 2">
            <h3>Александр Иванов</h3>
            <p>Врач-физиотерапевт</p>
        </div>
        <div class="team-member">
            <img src="preview.jpg" alt="Сотрудник 3">
            <h3>Мария Смирнова</h3>
            <p>Инструктор по лечебной физкультуре</p>
        </div>
        <div class="team-member">
            <img src="preview (1).jpg" alt="Сотрудник 4">
            <h3>Екатерина Романова</h3>
            <p>Реабилитолог</p>
        </div>
        <div class="team-member">
            <img src="474780E600000578-0-image-a-5_1513154665720.jpg" alt="Сотрудник 5">
            <h3>Иван Петров</h3>
            <p>Массажист</p>
        </div>
        <div class="team-member">
            <img src="858x540.jpg" alt="Сотрудник 6">
            <h3>Татьяна Андреева</h3>
            <p>Тренер по йоге</p>
        </div>
        <div class="team-member">
            <img src="988a29b006c6958a835cafb09cd322b7.jpg" alt="Сотрудник 7">
            <h3>Дмитрий Ковалев</h3>
            <p>Физиотерапевт</p>
        </div>
    </div>

    <div class="social-links">
        <a href="https://instagram.com/">Instagram</a>
        <a href="http://www.facebook.com.vn/">Facebook</a>
        <a href="https://careers.linkedin.cn/">LinkedIn</a>
    </div>
</main>
<section class="form-container">
    <h3>Зарегистрироваться на курсы</h3>
    <form id="registrationForm">
        <input type="text" id="name" placeholder="Ваше имя" required>
        <input type="email" id="email" placeholder="Ваш email" required>
        <input type="phone" id="phone" placeholder="Ваш номер телефона" required>
        <button type="submit">Зарегистрироваться</button>
    </form>
</section>
</main>
<footer>
    <p>&copy; 2024 Валентиновы штаны. Все права защищены.</p>
</footer>
</body>
</html>
