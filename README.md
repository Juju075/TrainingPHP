# TrainingPHP

Main RECAP
https://www.w3schools.com/php/default.asp

---

Top 30 methods to t

Rank Function Frequency Average

1 count [PHP Array]
count — Compte tous les éléments d'un tableau ou dans un objet Countable
https://www.php.net/manual/fr/function.count.php
https://www.w3schools.com/php/func_array_count.asp
http://www.lephpfacile.com/manuel-php/function.count.php

count(Countable|array $value, int $mode = COUNT_NORMAL): int

<?php
$cars=array("Volvo","BMW","Toyota");
echo count($cars);
?>

---

2 is_array [PHP Variable Handling]
is_array — Détermine si une variable est un tableau
https://www.php.net/manual/fr/function.is-array.php
https://www.w3schools.com/php/func_var_is_array.asp
http://www.lephpfacile.com/manuel-php/function.is-array.php

is_array(mixed $value): bool

<?php
$a = "Hello";
echo "a is " . is_array($a) . "<br>";

$b = array("red", "green", "blue");
echo "b is " . is_array($b) . "<br>";

$c = array("Peter"=>"35", "Ben"=>"37", "Joe"=>"43");
echo "c is " . is_array($c) . "<br>";

$d = "red, green, blue";
echo "d is " . is_array($d) . "<br>";
?>

---

3 substr [PHP String]
substr — Retourne un segment de chaîne
https://www.php.net/manual/fr/function.substr.php
https://www.w3schools.com/php/func_string_substr.asp
http://www.lephpfacile.com/manuel-php/function.substr.php

substr(string $string, int $offset, ?int $length = null): string

<?php
echo substr("Hello world",6);
?>

---

4 in_array [PHP Array]
in_array — Indique si une valeur appartient à un tableau
https://www.php.net/manual/fr/function.in-array.php
https://www.w3schools.com/php/func_array_in_array.asp

in_array(mixed $needle, array $haystack, bool $strict = false): bool

<?php
$people = array("Peter", "Joe", "Glenn", "Cleveland");

if (in_array("Glenn", $people))
  {
  echo "Match found";
  }
else
  {
  echo "Match not found";
  }
?>

---

5 explode [PHP String]
explode — Scinde une chaîne de caractères en segments
https://www.php.net/manual/fr/function.explode.php
https://www.w3schools.com/php/func_string_explode.asp
http://www.lephpfacile.com/manuel-php/function.explode.php

explode(string $separator, string $string, int $limit = PHP_INT_MAX): array

<?php
$str = "Hello world. It's a beautiful day.";
print_r (explode(" ",$str));
?>

---

6 str_replace [PHP String]
str_replace — Remplace toutes les occurrences dans une chaîne
https://www.php.net/manual/fr/function.str-replace.php
https://www.w3schools.com/php/func_string_explode.asp
https://www.php.net/manual/fr/function.str-replace.php

str_replace(
array|string $search,
    array|string $replace,
    string|array $subject,
    int &$count = null
): string|array

---

7 implode
implode — Rassemble les éléments d'un tableau en une chaîne
https://www.php.net/manual/fr/function.implode.php

implode(string $separator, array $array): string

---

8 strlen
strlen — Calcule la taille d'une chaîne
https://www.php.net/manual/fr/function.strlen.php

strlen(string $string): int

---

9 array_merge
array_merge — Fusionne plusieurs tableaux en un seul
https://www.php.net/manual/fr/function.array-merge.php

array_merge(array ...$arrays): array

---

10 strpos

11 preg_match

---

12 sprintf

---

13 trim

---

14 strtolower

---

15 file_exists

---

16 is_string

---

17 preg_replace

---

18 file_get_contents

---

19 array_key_exists

---

20 array_keys

---

21 dirname

---

22 function_exists

---

23 array_map

---

24 get_class

---

25 class_exists

---

26 is_object

---

27 time

---

28 json_encode

---

29 date

---

30 is_null

31 is_numeric 49.49 % 40.69
32 array_shift 49.49 % 23.28
33 defined 48.72 % 86.82
34 is_dir 48.57 % 22.86
35 json_decode 48.42 % 17.39
36 header 48.16 % 59.71
37 strtoupper 47.80 % 30.95
38 array_values 47.24 % 17.27
39 md5 46.88 % 23.74
40 method_exists 46.73 % 19.05
41 file_put_contents 46.68 % 12.49
42 rtrim 45.91 % 18.08
43 array_pop 45.51 % 20.60
44 unlink 44.59 % 23.55
45 basename 44.59 % 27.23
46 realpath 44.08 % 15.90
47 call_user_func 43.97 % 16.41
48 call_user_func_array 43.92 % 18.40
49 fopen 43.77 % 25.61
50 microtime 43.46 % 14.41
51 fclose 42.85 % 28.36
52 is_int 42.75 % 15.78
53 is_file 42.08 % 20.52
54 array_slice 41.83 % 13.20
55 preg_match_all 40.55 % 14.66
56 ucfirst 40.25 % 17.02
57 intval 40.19 % 88.13
58 str_repeat 40.14 % 19.51
59 serialize 40.14 % 22.05
60 array_filter 39.99 % 13.87
61 mkdir 39.79 % 11.17
62 is_callable 39.43 % 11.94
63 ltrim 39.17 % 10.90
64 ob_start 39.12 % 13.26
65 round 39.07 % 28.56
66 fwrite 38.97 % 23.39
67 array_unique 38.87 % 15.96
68 array_search 38.82 % 14.19
69 reset 38.71 % 20.79
70 array_unshift 38.10 % 10.32
71 parse_url 37.90 % 9.61
72 func_get_args 37.79 % 28.33
73 end 37.49 % 12.70
74 base64_encode 37.39 % 14.15
75 unserialize 37.18 % 18.35
76 max 36.98 % 22.88
77 preg_split 36.98 % 13.27
78 gettype 36.93 % 16.16
79 strrpos 36.67 % 11.95
80 version_compare 36.67 % 14.87
81 array_push 36.67 % 26.18
82 floor 36.11 % 18.78
83 strtotime 36.01 % 27.94
84 htmlspecialchars 35.96 % 51.08
85 ini_get 35.85 % 19.25
86 ini_set 35.60 % 14.49
87 chr 35.34 % 186.97
88 extension_loaded 35.29 % 14.17
89 is_bool 35.24 % 11.44
90 ksort 34.98 % 10.82
91 array_reverse 34.93 % 8.27
92 ord 34.73 % 53.17
93 uniqid 34.68 % 9.83
94 strtr 34.47 % 12.90
95 array_diff 34.32 % 11.13
96 error_reporting 34.17 % 8.99
97 ceil 33.35 % 11.99
98 urlencode 33.30 % 29.63
99 min 32.69 % 18.31
100 print_r 32.64 % 14.12
