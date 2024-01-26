# 9-laba-3-kurs


<h2 align="center">ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ПРОФЕССИОНАЛЬНОГО ОБРАЗОВАНИЯ <br> «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ» <br> КАФЕДРА ИНФОРМАТИКИ </h2>
<p align="center">Лабораторная работа №9. «Разработка серверных скриптов». <br>
по предмету «Web-технологии, языки и средства создания web-приложений» 

<p align="center"><b>"Java Script, PHP"</b><p>
<p align="right"><b>Выполнил: </b> студент 331 группы Хорошко Илья Алексеевич</p>
<p  align="right"><b>Проверил: </b> Соболев Е. И., старший преподователь</p>
<br>
<br>
<br>
<p align="center">Южно-Сахалинск <br> СахГУ <br> 2024</p>
<h2> Введение </h2>
<p align="justify"> Разработка серверных скриптов </p>
<h2 align="center">Цели и задачи</h2>

1. По заходу на страницу выведите сколько дней осталось до нового года. 

2. Дан инпут и кнопка. В этот инпут вводится год. По нажатию на кнопку выведите на экран, високосный он или нет. 

3. Дан инпут и кнопка. В этот инпут вводится дата в формате '01.12.1990'. По нажатию на кнопку выведите на экран день недели, соответствующий этой дате, например, 'воскресенье'. 

4. По заходу на страницу выведите текущую дату в формате '12 мая 2015 года, воскресенье'. 

5. Дан инпут и кнопка. В этот инпут вводится дата рождения в формате '01.12.1990'. По нажатию на кнопку выведите на экран сколько дней осталось до дня рождения пользователя. 

6. По заходу на страницу выведите сколько дней осталось до ближайшей масленницы (последнее воскресенье весны). 

7. Дан инпут и кнопка. В этот инпут вводится дата рождения в формате '31.12'. По нажатию на кнопку выведите знак зодиака пользователя. 

8. Дан массив праздников. По заходу на страницу, если сегодня праздник, то поздравьте пользователя с этим праздником. 

9. Сделайте скрипт-гороскоп. Внутри него хранится массив гороскопов на несколько дней вперед для каждого знака зодиака. По заходу на страницу спросите у пользователя дату рождения, определите его знак зодиака и выведите предсказание для этого знака зодиака на текущий день. 

10. Дан текстареа и кнопка. В текстареа вводится текст. По нажатию на кнопку выведите количество слов в тексте, количество символов в тексте, количество символов за вычетом пробелов. 

11. Дан текстареа и кнопка. В текстареа вводится текст. По нажатию на кнопку нужно посчитать процентное содержание каждого символа в тексте. 

12. Дан массив слов, инпут и кнопка. В инпут вводится набор букв. По нажатию на кнопку выведите на экран те слова, которые содержат в себе все введенные буквы. 

13. Дан текстареа и кнопка. В текстареа через пробел вводятся слова. По нажатию на кнопку выведите слова в таком виде: сначала заголовок 'слова на букву а' и под ним все слова, которые начинаются на 'а', потом заголовок 'слова на букву б' и все слова на 'б' и так далее. Буквы должны идти в алфавитном порядке. Брать следует только те буквы, на которые начинаются наши слова. То есть: если нет слов, к примеру, на букву 'в' - такого заголовка тоже не будет. 

14. Дан инпут и кнопка. В этот инпут вводится строка на русском языке. По нажатию на кнопку выведите на экран транслит этой строки. 

15. Дан инпут, 2 радиокнопочки и кнопка. В инпут вводится строка, а с помощью радиокнопочек выбирается - нужно преобразовать эту строку в транслит или из транслита обратно. 

16. Дан массив с вопросами и правильными ответами. Реализуйте тест: выведите на экран все вопросы, под каждым инпут. Пользователь читает вопрос, пишет свой ответ в инпут. Когда вопросы заканчиваются - он жмет на кнопку, страница обновляется и вместо инпутов под вопросами появляется сообщение вида: 'ваш ответ: ... верно!' или 'ваш ответ: ... неверно! Правильный ответ: ...'. Правильно отвеченные вопросы должны гореть зеленым цветом, а неправильно - красным. 

17. Модифицируем предыдущую задачу: пусть теперь тест показывает варианты ответов и радиокнопочки. Пользователь должен выбрать один и вариантов. 

18. Модифицируем предыдущую задачу: пусть теперь на один вопрос может быть несколько правильных ответов. Пользователь должен отметить один или несколько чекбоксов. 

19. Напишите скрипт, который будет считать факториал числа. Само число вводится в инпут и после нажатия на кнопку пользователь должен увидеть результат. 

20. Напишите скрипт, который будет находить корни квадратного уравнения. Для этого сделайте 3 инпута, в которые будут вводиться коэффициенты уравнения. 

21. Даны 3 инпута. В них вводятся числа. Проверьте, что эти числа являются тройкой Пифагора: квадрат самого большого числа должен быть равен сумме квадратов двух остальных. 

22. Дан инпут и кнопка. В инпут вводится число. По нажатию на кнопку выведите список делителей этого числа. 

23. Дан инпут и кнопка. В инпут вводится число. По нажатию на кнопку разложите число на простые множители. 

24. Даны 2 инпута и кнопка. В инпуты вводятся числа. По нажатию на кнопку выведите список общих делителей этих двух чисел. 

25. Даны 2 инпута и кнопка. В инпуты вводятся числа. По нажатию на кнопку выведите наибольший общий делитель этих двух чисел. 

26. Даны 2 инпута и кнопка. В инпуты вводятся числа. По нажатию на кнопку выведите наименьшее число, которое делится и на одно, и на второе из введенных чисел. 

27. Даны 3 селекта и кнопка. Первый селект - это дни от 1 до 31, второй селект - это месяцы от января до декабря, а третий - это годы от 1990 до 2025. С помощью этих селектов можно выбрать дату. По нажатию на кнопку выведите на экран день недели, соответствующий этой дате, например, ‘воскресенье'.
 <h2 align="center">Решение задач</h2>

1. 
```php
<!DOCTYPE html>
<head>
  <title>Lab9</title>
</head>
<style>
body {
    background-color: #DDA0DD;
}
</style>
<body>
  <!-- Задание 1 -->
  <?php
  $today = date_create();
  $nextYear = date_format($today, "Y") + 1;
  $nyDate = date_create("$nextYear-01-01");
  $dateDiff = date_diff($today, $nyDate);
  echo "Осталось до нг: $dateDiff->days";
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 2 -->
  <form action="" method="POST">
    <label>Год:</label>
    <input type="text" name="task2">
    <input type="submit" value="жмакнуть">
  </form>
  <?php
  if (isset($_POST["task2"])) {
    $year = $_POST["task2"];
    echo "$year - ", date("L", strtotime("$year-01-01")) ? "Високос" : "Невисокос";
  }
  ?>
  <!--------------->
  <br><br>

  <!-- Задание 3 -->
  <form action="" method="post">
    <label>Дата:</label>
    <input type="date" name="task3">
    <input type="submit" value="Тык">
  </form>
  <?php
  if (isset($_POST["task3"])) {
    $days = ["понедельник", "вторник", "среда", "четверг", "пятница", "суббота", "воскресенье"];
    $date = strtotime($_POST["task3"]);
    $day = date("N", $date);
    echo $days[$day - 1];
  }
  ?>
  <!--------------->
  <br><br>

  <!-- Задание 4 -->
  <?php
  echo date("jS \of F Y\, l");
  ?>
  <!--------------->
  <br><br>

  <!-- Задание 5 -->
  <form method="POST" action="">
        <label for="dob">Введите дату рождения (дд.мм.гггг):</label>
        <input type="text" name="dob" id="dob" required>

        <button type="submit">Жмяк для рассчета</button>
    </form>
    <?php
if (isset($_POST["dob"])) {
  // Получаем введенную дату 
  $inputDate = $_POST["dob"];

  // проверка не пустая ли 
  if (!empty($inputDate)) {
      // Парсим введенную дату
      $dob = DateTime::createFromFormat("d.m.Y", $inputDate);

      // текущая дата
      $currentDate = new DateTime();

      // меняем  год  рождения на  текущий год
      $dob->setDate($currentDate->format("Y"), $dob->format("m"), $dob->format("d"));

      // смотрим, если др уже прошел в этом, то меняем   на след год
      if ($currentDate > $dob) {
          $dob->modify("+1 year");
      }

      // разница в днях
      $diff = $dob->diff($currentDate);
      $daysLeft = $diff->days;

     
      echo "До вашего др осталось: $daysLeft дней";
  }
}
?>
  <!--------------->
  <br><br>
  <!-- Задание 6 -->
  <?php
  $today = date_create();
  $date = date_create("last Sunday of February");
  if ($today > $date) $date = date_create("last Sunday of February next year");
  echo "осталось до  масленицы: " . date_diff($today, $date)->days;
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 7 -->
  <form action="" method="post">
    <label>Дата рождения(ДД.ММ):</label>
    <input type="text" name="task7">
    <input type="submit" value="Жмяк">
  </form>
  <?php
    function getZodiac($month, $day){
      $zodiacName = array(
          "Козерог", "Водолей", "Рыбы", 
          "Овен", "Телец", "Близнецы", 
          "Рак", "Лев", "Девы", 
          "Весы", "Скорпион", "Стрелец"
      );

      $zodiacDate = array(
          21, 20, 20, 20, 20, 20, 
          21, 22, 23, 23, 23, 23
      );

      if ($day < $zodiacDate[$month - 1]){
          $result = $zodiacName[$month - 1];
      }else{
          if($month == 12) $month = 0; 
          $result = $zodiacName[$month];
      }
      return $result;
    }

  if (isset($_POST["task7"])) {
    $str = $_POST["task7"];
    $date = explode(".", $str);
    if(count($date) > 1) {
      $zodiacSign = getZodiac($date[1], $date[0]);
      echo "Знак зодиака: " . $zodiacSign;
    }
  }
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 8 -->
  <?php
  // заполнить массиво данными
  $HappyBirthday = date("12-20");
  $hallowen = date("5-10");
  $christmas = date("01-03");
  $deniNEZAVISIMOSTI = date("21-30");
  $holidays = [
    $HappyBirthday => "с дршкой",
    $hallowen => "бу! праздник мертвых!",
    $christmas => "с новай годой!",
    $deniNEZAVISIMOSTI => "День независимости!"
  ];
  // выводим
  $today = date("m-d");
  foreach ($holidays as $key => $value) {
    if ($today == $key) {
      $output = "Поздравляем с праздником: $value!";
      break;
    }
    $output = "Сегодня нет никакого праздника";
  }
  echo $output;
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 9 -->
  <?php
  function GetHoroscopeFor($zodiacSign)
  {
    switch($zodiacSign){
        case 'Овен':
          return 'Вам следует избегать дальних поездок в ближайшие дни'; 
          break;
        case 'Телец':
          return 'Будте осторожны на работе! С вами захотят поссорится.'; 
          break;
        case 'Близнецы':
          return 'Сегодня вам следует валяться и тюленнится '; 
          break;
        case 'Рак':
          return 'Говорят что вам скоро повезет в любви'; 
          break;
        case 'Лев':
          return 'Не бойетсь новых начинаний! У вас все получится'; 
          break;
        case 'Девы':
          return 'Посторайтесь никого не "задушить" сегодня'; 
          break;
        case 'Весы':
          return 'Сегодня ваш счастливый день, дерзайте!'; 
          break;
        case 'Скорпион':
         return 'Вам стоит больше думать, над тем, что вы говорите окружающим, чаще всего ваши слова могут сильно ранить ваших близких'; 
          break;
        case 'Стрелец':
          return 'Сегодня вам, возможно, придется быть весьма внимательным к оттенкам интонаций как голосов окружающих'; 
          break;
        case 'Козерог':
          return 'Звезды благоволят хорошие сделки сегодня'; 
          break;
        case 'Водолей':
          return 'Все будет так как вы захотите. ауф.'; 
          break;
        case 'Рыбы':
          return 'Вам стоит больше слушать близких вам людей!'; 
          break;
    }
  }

  if (isset($_POST["task7"])) {
    $str = $_POST["task7"];
    $date = explode(".", $str);
    if(count($date) > 1) {
      $zodiacSign = getZodiac($date[1], $date[0]);
      echo "ваш знак зодиака: $zodiacSign.<br> Гороскоп дня:<br>" . GetHoroscopeFor($zodiacSign);
    }
  }
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 10 -->
  <form action="" method="post">
    <textarea name="task10"></textarea>
    <input type="submit" value="Тык">
  </form>
  <?php
  if (isset($_POST["task10"])) {
    $text = $_POST["task10"];
    $alphabet = "АБВГДЕЁЖЗИЙКЛМНОПРСТУФХЦЧШЩЪЫЬЭЮЯабвгдеёжзийклмнопрстуфхцчшщъыьэюя";
    echo "Количество слов: " . str_word_count($text, 0, $alphabet) . "<br>";
    echo "Количество символов: " . iconv_strlen($text) . "<br>";
    echo "Количество символов за вычетом пробелов: " . (iconv_strlen($text) - substr_count($text, " ")) . "<br>";
  }
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 11 -->
  <form action="" method="post">
    <textarea name="task11"></textarea>
    <input type="submit" value="жмяк">
  </form>
  <?php
  if (isset($_POST["task11"])) {
    $text = $_POST["task11"];
    $len = mb_strlen($text);
    $chars_count = array_count_values(mb_str_split($text));
    foreach ($chars_count as $char => $count) {
      echo "$char - " . round($count / $len * 100, 0, PHP_ROUND_HALF_EVEN) . "%<br>";
    }
  }
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 12 -->
  <form action="" method="post">
    <label>Набор букв:</label>
    <input type="text" name="task12">
    <input type="submit" value="ТЫК">
  </form>
  <?php
  if (isset($_POST["task12"])) {
    $letters = mb_str_split($_POST["task12"]);
    $words = ["папа", "мама", "брат", "сестра", "малыш", "машина", "карета", "утро", "день", "вечер", "ночь", "обед", "сегодня", "завтра", "весело", "хорошо", "да", "нет", "один", "два", "три"];
    $result = [];
    foreach ($words as $word) {
      $inString = true;
      foreach ($letters as $letter) {
        if (mb_stripos($word, $letter) === false) {
          $inString = false;
          break;
        }
      }
      if ($inString) array_push($result, $word);
    }

    echo "Слова, которые содержат все введенные буквы:<br>";
    for ($i = count($result) - 1; $i >= 0; $i--) {
      echo $result[$i];
      if ($i > 0) echo ", ";
    }
  }
  ?>
<!--------------->
<br><br>
  
<!-- Задание 13 -->
  <form action="" method="post">
    <textarea name="task13"></textarea>
    <input type="submit" value="Жмяк">
  </form>
  <?php
  if (isset($_POST["task13"])) {
    $words = explode(" ", $_POST["task13"]);
    sort($words);
    $prev = "";
    foreach ($words as $word) {
      $char = mb_str_split($word)[0];
      if ($prev !== $char)
        echo "<br>Слова на букву " . $char . ": ";
      else
        echo ", ";
      echo $word;
      $prev = $char;
    }
  }
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 14 -->
  <form action="" method="post">
    <label>Строка на русском:</label>
    <input type="text" name="task14">
    <input type="submit" value="Кнопка для тыков">
  </form>
  <?php
  function RusToLat($source = false)
  {
      if ($source) {
          $rus = [
              "А", "Б", "В", "Г", "Д", "Е", "Ё", "Ж", "З", "И", "Й", "К", "Л", "М", "Н", "О", "П", "Р", "С", "Т", "У", "Ф", "Х", "Ц", "Ч", "Ш", "Щ", "Ъ", "Ы", "Ь", "Э", "Ю", "Я",
              "а", "б", "в", "г", "д", "е", "ё", "ж", "з", "и", "й", "к", "л", "м", "н", "о", "п", "р", "с", "т", "у", "ф", "х", "ц", "ч", "ш", "щ", "ъ", "ы", "ь", "э", "ю", "я"
          ];
          $lat = [
              "A", "B", "V", "G", "D", "E", "Yo", "Zh", "Z", "I", "J", "K", "L", "M", "N", "O", "P", "R", "S", "T", "U", "F", "H", "C", "Ch", "Sh", "Shh", "\`\`", "Y`", "`", "E`", "Yu", "Ya", "a", "b", "v", "g", "d", "e", "yo", "zh", "z", "i", "j", "k", "l", "m", "n", "o", "p", "r", "s", "t", "u", "f", "h", "c", "ch", "sh", "shh", "``", "y`", "`", "e`", "yu", "ya"
          ];
          return str_replace($rus, $lat, $source);
      }
  }

  if (isset($_POST["task14"])) {
    echo "Транслит: " . RusToLat($_POST["task14"]);
  }
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 15 -->
  <form action="" method="get">
    <input type="text" name="task15">
    <input type="submit" value="ЖЖЖЖмяк"><br>
    <input type="radio" name="radio15" value="To" checked><label>В транслит</label>
    <input type="radio" name="radio15" value="From"><label>Из транслита</label>
  </form>
  <?php
  function LatToRus($source = false)
  {
      if ($source) {
          $rus = [
              "А", "Б", "В", "Г", "Д", "Е", "Ё", "Ж", "З", "И", "Й", "К", "Л", "М", "Н", "О", "П", "Р", "С", "Т", "У", "Ф", "Х", "Ц", "Ч", "Ш", "Щ", "Ъ", "Ы", "Ь", "Э", "Ю", "Я",
              "а", "б", "в", "г", "д", "е", "ё", "ж", "з", "и", "й", "к", "л", "м", "н", "о", "п", "р", "с", "т", "у", "ф", "х", "ц", "ч", "ш", "щ", "ъ", "ы", "ь", "э", "ю", "я"
          ];
          $lat = [
              "A", "B", "V", "G", "D", "E", "Yo", "Zh", "Z", "I", "J", "K", "L", "M", "N", "O", "P", "R", "S", "T", "U", "F", "H", "C", "Ch", "Sh", "Shh", "\`\`", "Y`", "`", "E`", "Yu", "Ya", "a", "b", "v", "g", "d", "e", "yo", "zh", "z", "i", "j", "k", "l", "m", "n", "o", "p", "r", "s", "t", "u", "f", "h", "c", "ch", "sh", "shh", "``", "y`", "`", "e`", "yu", "ya"
          ];
          return str_replace($lat, $rus, $source);
      }
  }

  if (isset($_POST["task15"])) {
    if ($_POST["radio15"] === "To")
      echo "Транслит: " . RusToLat($_POST["task15"]);
    else
      echo "Перевод: " . LatToRus($_POST["task15"]);
  }
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 16 -->

  <style>
    .correct {
      background-color: PaleGreen;
    }

    .wrong {
      background-color: DarkSalmon;
    }
  </style>
  <p><b>Ответы "да" или "нет":</b></p>
  <form action="" method="post">
    <?php
    $quests = [
      "Вопрос 1" => "да",
      "Вопрос 2" => "нет",
      "Вопрос 3" => "нет",
      "Вопрос 4" => "да",
      "Вопрос 5" => "нет",
    ];

    $i = 0;
    foreach ($quests as $quest => $answer) {
      echo $quest . "<br>";
      if (isset($_POST["q$i"])) {
        echo "<p>Ваш ответ: " . $_POST["q$i"] . " - ";
        if ($_POST["q$i"] === $answer)
          echo '<span class = "correct">молодец, у тебя лапки!';
        else
          echo '<span class = "wrong">неправильно, у тебя лапки!';
        echo "</span></p>";
      } else
        echo '<input type="text" name="q' . $i . '"><br>';

      $i++;
    }
    ?>
    <input type="submit" value="жМяК!">
  </form>
  <!--------------->
  <br><br>
  
  <!-- Задание 17 -->
  <form action="" method="post">
    <?php
    $quests = [
      "Вопрос 1" => "да",
      "Вопрос 2" => "нет",
      "Вопрос 3" => "нет",
      "Вопрос 4" => "да",
      "Вопрос 5" => "нет",
    ];

    $i = 0;
    foreach ($quests as $quest => $answer) {
      echo $quest . "<br>";
      if (isset($_POST["radio17$i"])) {
        echo "<p>Ваш ответ: " . $_POST["radio17$i"] . " - ";
        if ($_POST["radio17$i"] === $answer)
          echo '<span class = "correct">молодец, у тебя лапки!';
        else
          echo '<span class = "wrong">неправильно, у тебя лапки!';
        echo "</span></p>";
      } else
        echo '
        <input type="radio" name="radio17' . $i . '" value="да">
        <label>да</label>
        <input type="radio" name="radio17' . $i . '" value="нет">
        <label>нет</label>
        <br>
        ';

      $i++;
    }
    ?>
    <input type="submit" value="ТЫЫЫЫК">
  </form>
  <!--------------->
  <br><br>
  
  <!-- Задание 18 -->
  <form action="" method="post">
    <?php
    $quests = [
      "Вопрос 1" => ["да", "нет"],
      "Вопрос 2" => ["нет", "не знаю"],
      "Вопрос 3" => ["нет"],
      "Вопрос 4" => ["да"],
      "Вопрос 5" => ["да", "не знаю"],
    ];

    $variants = [
      ["да", "нет", "не знаю"],
      ["да", "нет", "не знаю"],
      ["да", "нет", "не знаю"],
      ["да", "нет", "не знаю"],
      ["да", "нет", "не знаю"],
    ];

    $i = 0;
    foreach ($quests as $quest => $answer) {
      // вопрос №
      echo $quest . "<br>";
      // ответ: 
      if (isset($_POST["submit"])) {
        echo "Ваш ответ: [";
        $userAnswer = [];
        for ($j = 0; $j < count($variants[$i]); $j++) {
          if (isset($_POST["radio18$i$j"])) {
            array_push($userAnswer, $_POST["radio18$i$j"]);
          }
        }
        // ответ
        echo implode(", ", $userAnswer) . "] - ";
        // Верно/Неверно
        if (!array_diff($userAnswer, $answer) && !array_diff($answer, $userAnswer))
          echo '<span class = "correct">молодец, у тебя лапки!';
        else
          echo '<span class = "wrong">неправильно, у тебя лапки!';
        echo "</span></p>";
      } else {
        // чекбоксы 
        for ($j = 0; $j < count($variants[$i]); $j++)
          echo '
            <input type="checkbox" name="radio18' . $i . $j . '" value="' . $variants[$i][$j] . '">
            <label>' . $variants[$i][$j] . '</label>
          ';
        echo "<br>";
      }
      $i++;
    }

    if (isset($_POST["reset"])) $_POST["submit"] = "";
    ?>
    <input type="submit" name="submit" value="ТЫкнуть">
    <input type="submit" name="reset" value="Обновить">
  </form>
  <!--------------->
  <br><br>
  
  <!-- Задание 19 -->
  <form action="" method="post">
    <input type="text" name="task19">
    <input type="submit" value="submit">
  </form>
  <?php
  if (isset($_POST["task19"])) {
    $num = $_POST["task19"];
    $res = 1;
    for ($i = 1; $i <= $num; $i++) {
      $res *= $i;
    }
    echo "Ответ: " . $res;
  }
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 20 -->
  <form method="post">
    <label for="a">Коэффициент a:</label>
    <input type="text" id="a" name="a" required><br><br>

    <label for="b">Коэффициент b:</label>
    <input type="text" id="b" name="b" required><br><br>

    <label for="c">Коэффициент c:</label>
    <input type="text" id="c" name="c" required><br><br>

    <input type="submit" value="Решить">
  </form>
  <?php
  // Проверяем, были ли переданы значения коэффициентов через форму
  if (isset($_POST['a']) && isset($_POST['b']) && isset($_POST['c'])) {
    // Получаем значения коэффициентов из формы
    $a = $_POST['a'];
    $b = $_POST['b'];
    $c = $_POST['c'];

    // Вычисляем дискриминант
    $D = $b * $b - 4 * $a * $c;

    // Проверяем условия и вычисляем корни уравнения
    if ($D > 0) {
      $x1 = (-$b + sqrt($D)) / (2 * $a);
      $x2 = (-$b - sqrt($D)) / (2 * $a);
      echo "Корни уравнения: x1 = $x1, x2 = $x2";
    } elseif ($D == 0) {
      $x = -$b / (2 * $a);
      echo "Уравнение имеет один корень: x = $x";
    } else {
      echo "Нет корней";
    }
  }
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 21 -->
  <form action="" method="post">
    <label>a = </label>
    <input type="text" name="task21a">
    <label>b = </label>
    <input type="text" name="task21b">
    <label>c = </label>
    <input type="text" name="task21c">
    <br>
    <input type="submit" name="task21sbm" value="тыкаем">
  </form>
  <?php
  if (isset($_POST["task21sbm"])) {
    $a = $_POST["task21a"];
    $b = $_POST["task21b"];
    $c = $_POST["task21c"];
    $sum = 0;
    $max;
    if ($a > $b) {
      $sum += $b * $b;
      $max = $a;
    } else {
      $sum += $a * $a;
      $max = $b;
    }
    if ($max > $c) {
      $sum += $c * $c;
      $max *= $max;
    } else {
      $sum += $max * $max;
      $max = $c * $c;
    }

    if ($max == $sum) echo "тройка Пифагора";
    else echo "не тройка Пифагора";
  }
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 22 -->
  <form method="post">
        <label for="number">Введите число:</label>
        <input type="number" name="number" id="number" required>
        <input type="submit" name="submit" value="ищем делители">
    </form>
    <?php
if(isset($_POST['submit'])) {
    if(isset($_POST['number'])) {
        $number = $_POST['number'];
        echo "Делители числа $number: ";
        for($i = 1; $i <= $number; $i++) {
            if($number % $i == 0) {
                echo "$i ";
            }
        }
    } else {
        echo "";
    }
}
?>
  
  <!--------------->
  <br><br>
  
  <!-- Задание 23 -->
  <form action="" method="post">
    <input type="text" name="task23">
    <input type="submit" value="Тык">
  </form>
  <?php
  if (isset($_POST["task23"])) {
    $num = $_POST["task23"];
    $results = [];
    $i = 1;
    while ($num != 1) {
      $i++;
      if ($num % $i == 0) {
        $num /= $i;
        array_push($results, $i);
        $i = 1;
      }
    }

    echo "Простые множители: " . implode(", ", $results);
  }
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 24 -->
  <form action="" method="post">
    <input type="text" name="task24a">
    <input type="text" name="task24b">
    <input type="submit" value="жмяк">
  </form>
  <?php
  if (isset($_POST["task24a"]) && isset($_POST["task24b"])) {
    $a = $_POST["task24a"];
    $b = $_POST["task24b"];
    $results = [];
    for ($i = 1; $i <= intdiv(max($a, $b), 2); $i++) {
      if ($a % $i == 0 && $b % $i == 0)
        array_push($results, $i);
    }

    echo "Общие делители: " . implode(", ", $results);
  }
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 25 -->
  <form action="" method="post">
    <input type="text" name="task25a">
    <input type="text" name="task25b">
    <input type="submit" value="тыкни сюда">
  </form>
  <?php
  if (isset($_POST["task25a"]) && isset($_POST["task25b"])) {
    $a = $_POST["task25a"];
    $b = $_POST["task25b"];
    echo "НОД = " . gcd($a, $b);
  }

  function gcd($a, $b)
  {
    $a = abs($a);
    $b = abs($b);
    while ($b) {
      $temp = $b;
      $b = $a % $b;
      $a = $temp;
    }
    return $a;
  }
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 26 -->
  <form action="" method="post">
    <input type="text" name="task26a">
    <input type="text" name="task26b">
    <input type="submit" value="жми сюды">
  </form>
  <?php
  if (isset($_POST["task26a"]) && isset($_POST["task26b"])) {
    $a = $_POST["task26a"];
    $b = $_POST["task26b"];
    echo "НОК = " . lcm($a, $b);
  }

  function lcm($a, $b)
  {
    return abs($a * $b / gcd($a, $b));
  }
  ?>
  <!--------------->
  <br><br>
  
  <!-- Задание 27 -->
  <form method="POST" action="">
    <label for="day">День:</label>
    <input type="number" name="day" min="1" max="31">
    
    <label for="month">Месяц:</label>
    <select name="month">
        <option value="1">январь</option>
        <option value="2">февраль</option>
        <option value="3">март</option>
        <option value="4">апрель</option>
        <option value="5">май</option>
        <option value="6">июнь</option>
        <option value="7">июль</option>
        <option value="8">август</option>
        <option value="9">сентябрь</option>
        <option value="10">октябрь</option>
        <option value="11">ноябрь</option>
        <option value="12">декабрь</option>
    </select>
    
    <label for="year">Год:</label>
    <input type="number" name="year" min="1990" max="2025">
    
    <input type="submit" name="submit" value="день недели">
</form>
    <?php

if(isset($_POST['submit'])) {
  if(isset($_POST['day']) && isset($_POST['month']) && isset($_POST['year'])) {
      $day = $_POST['day'];
      $month = $_POST['month'];
      $year = $_POST['year'];
      
      // Формируем дату в формате "год-месяц-день"
      $date = $year . '-' . $month . '-' . $day;
      
      // Преобразуем дату в формат, пригодный для получения дня недели
      $timestamp = strtotime($date);
      
      // Получаем день недели по номеру (от 0 до 6, где 0 - воскресенье)
      $weekday = date('w', $timestamp);
      
      // определяем название дня недели
      $daysOfWeek = ['воскресенье', 'понедельник', 'вторник', 'среда', 'четверг', 'пятница', 'суббота'];
      $dayOfWeek = $daysOfWeek[$weekday];
      
      
      echo 'День недели: ' . $dayOfWeek;
  } else {
      echo "";
  }
}
?>
  <!--------------->
</body>
</html>

```
<h2 align="center">Вывод</h2>
Вспомнил как работать  с СУБД MySQL и научился делать серверные скрипты.
