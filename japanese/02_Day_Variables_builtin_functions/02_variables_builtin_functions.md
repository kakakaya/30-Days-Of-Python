<div align="center">
  <h1> 30 Days Of Python: Day 2 - 変数と組み込み関数</h1>
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/asabeneh/">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>
  <a class="header-badge" target="_blank" href="https://twitter.com/Asabeneh">
  <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/asabeneh?style=social">
  </a>

<sub>Author:
<a href="https://www.linkedin.com/in/asabeneh/" target="_blank">Asabeneh Yetayeh</a><br>
<small> Second Edition: July, 2021</small>
</sub>

<sub>Translator:
<a href="https://github.com/kakakaya/" target="_blank">kakakaya</a><br>
</sub>
</div>

[<< Day 1](../readme.md) | [Day 3 >>](../03_Day_Operators/03_operators.md)

![30DaysOfPython](../images/30DaysOfPython_banner3@2x.png)

- [📘 Day 2](#-day-2)
  - [Built in functions](#built-in-functions)
  - [Variables](#variables)
    - [Declaring Multiple Variable in a Line](#declaring-multiple-variable-in-a-line)
  - [Data Types](#data-types)
  - [Checking Data types and Casting](#checking-data-types-and-casting)
  - [Numbers](#numbers)
  - [💻 Exercises - Day 2](#-exercises---day-2)
    - [Exercises: Level 1](#exercises-level-1)
    - [Exercises: Level 2](#exercises-level-2)

# 📘 Day 2

## Built in functions
Python には、数多くの組み込み関数(built-in functions)があります。これは、インポートや設定が不要で、グローバルに使うことができます。
よく使われる組み込み関数は次の通りです。

- `print()`
- `len()`
- `type()`
- `int()`
- `float()`
- `str()`
- `input()`
- `list()`
- `dict()`
- `min()`
- `max()`
- `sum()`
- `sorted()`
- `open()`
- `file()`
- `help()`
- `dir()`


 以下の表は、 [Python documentation](https://docs.python.org/ja/3.11/library/functions.html) に掲載されている組み込み関数の一覧です。

![Built-in Functions](../images/builtin-functions.png)

Python シェルを開き、いくつか使ってみましょう。

![Built-in functions](../images/builtin-functions_practice.png)

他の組み込み関数も触って練習しましょう。

![Help and Dir Built in Functions](../images/help_and_dir_builtin.png)

上のターミナルからもわかるように、 Python には予約語があります。変数や関数の宣言に予約語を使ってはいけません。変数については、次の節で説明します。

だんだん組み込み関数についてわかってきたとおもいます。もうすこし練習して、次の節に進みましょう。

![Min Max Sum](../images/builtin-functional-final.png)

## Variables

変数は計算機のメモリにデータを保存します。変数は、わかりやすい名前だと覚えやすく、役割が明快になるので、推奨されます。
変数はデータを保存しているメモリのアドレスを参照しています。

`x`、`y`、`z`のような短い変数名も可能ですが、`firstname` 、`lastname`、 `age`、`country` のような、より説明的な名前の方が推奨されます。

変数名の規則

- 変数名には大文字または小文字のアルファベット、数字、アンダースコアのみ利用できる。(A-Z, a-z, 0-9, and \_ )
- 文字またはアンダースコア(`_`)から始まること。数字から始めてはならない。
- 変数名は大文字と小文字を区別する。`firstname`、 `Firstname` 、 `FirstName` そして `FIRSTNAME` はすべて別の変数とし扱われる。

以下は利用できる変数名の例

```shell
firstname
lastname
age
country
city
first_name
last_name
capital_city
_if # もし予約語をどうしても変数名として使いたい場合、このようにする
year_2023
year2023
current_year_2023
birth_year
num1
num2
```

利用できない変数名の例

```shell
first-name
first@name
first$name
num-1
1num
```

このチャレンジでは、多くの開発者に受け入れられている標準的なPython の変数名のスタイルを採用します。
変数名にはスネークケース( `snake_case` )を使い、複数の単語を含む変数では各単語の間にアンダースコアを使います(例: `first_name`, `last_name`, `engine_rotation_speed`)。

変数にデータを割り当てることを、変数宣言(variable declaration)と言います。以下の例では、私の名前を変数 `first_name` に割り当てています。等号(`=`)は代入演算子です代入は変数にデータを格納することを意味しており、数学の等号とは異なります。

_Example:_

```python
# Variables in Python
first_name = 'Asabeneh'
last_name = 'Yetayeh'
country = 'Finland'
city = 'Helsinki'
age = 250
is_married = True
skills = ['HTML', 'CSS', 'JS', 'React', 'Python']
person_info = {
    'firstname':'Asabeneh',
    'lastname':'Yetayeh',
    'country':'Finland',
    'city':'Helsinki'
}
```

組み込み関数の`print()` と `len()` を使ってみましょう。 `print()` 関数は無制限の引数を受け取れます。
引数とは、関数の括弧の中に渡すことができる値のことです。

**Example:**

```python
print('Hello, World!') # Hello, World! という文字列が引数
print('Hello', ',', 'World', '!') # 複数の引数を受け取ることができ、ここでは4つ受け取っている
print(len('Hello, World!')) # ここでは Hello, World! という文字列の長さの引数を1つだけ受け取っている
```


**Example:**

```python
# 変数の値を表示する

print('First name:', first_name)
print('First name length:', len(first_name))
print('Last name: ', last_name)
print('Last name length: ', len(last_name))
print('Country: ', country)
print('City: ', city)
print('Age: ', age)
print('Married: ', is_married)
print('Skills: ', skills)
print('Person information: ', person_info)
```

### Declaring Multiple Variable in a Line

1行で複数の変数を宣言することもできます。

**Example:**

```python
first_name, last_name, country, age, is_married = 'Asabeneh', 'Yetayeh', 'Helsink', 250, True

print(first_name, last_name, country, age, is_married)
print('First name:', first_name)
print('Last name: ', last_name)
print('Country: ', country)
print('Age: ', age)
print('Married: ', is_married)
```

組み込み関数の `input()` を使ってユーザーの入力を受け取ることができます。ユーザーから名前と年齢を聞き、変数に格納しましょう。
Getting user input using the _input()_ built-in function. Let us assign the data we get from a user into first_name and age variables.

**Example:**

```python
first_name = input('名前はなんですか: ')
age = input(お年はおいくつですか? ')

print(first_name)
print(age)
```

## Data Types

Python には複数の型があります。変数の型を知るためには、組み込み関数の `type()` を使います。型の違いをしっかり理解することに意識してください。プログラミングにおいて、型はすべてと言ってもいいほど非常に重要な概念です。
2回に渡って型について説明しているのは、各トピックが型に関連しているからです。今後も繰り返し、型について説明します。

## Checking Data types and Casting

**Example:**

```python
# Different python data types
# Let's declare variables with various data types

first_name = 'Asabeneh'     # str
last_name = 'Yetayeh'       # str
country = 'Finland'         # str
city= 'Helsinki'            # str
age = 250                   # int, it is not my real age, don't worry about it

# Printing out types
print(type('Asabeneh'))     # str
print(type(first_name))     # str
print(type(10))             # int
print(type(3.14))           # float
print(type(1 + 1j))         # complex
print(type(True))           # bool
print(type([1, 2, 3, 4]))     # list
print(type({'name':'Asabeneh','age':250, 'is_married':250}))    # dict
print(type((1,2)))                                              # tuple
print(type(zip([1,2],[3,4])))                                   # set
```

キャスト(cast): ある値の型を、他の型に変換することをキャストと言います。ここでは、 `int()`、`float()`、`str()`、`list()`、`set()`を使います。

算術演算を行う場合、数字の文字列(`'123'` など)は最初に整数か浮動小数点数に変換する必要があります。
もし数値を文字列に連結したい(`print("Your age is " + age + ".")` など)場合、数値を文字列に変換する必要があります。

文字列の連結については、先の節でもうすこし説明します。

  **Example:**

```python
# int to float
num_int = 10
print('num_int',num_int)         # 10
num_float = float(num_int)
print('num_float:', num_float)   # 10.0

# float to int
gravity = 9.81
print(int(gravity))             # 9

# int to str
num_int = 10
print(num_int)                  # 10
num_str = str(num_int)
print(num_str)                  # '10'

# str to int or float
num_str = '10.6'
print('num_int', int(num_str))      # 10
print('num_float', float(num_str))  # 10.6

# str to list
first_name = 'Asabeneh'
print(first_name)               # 'Asabeneh'
first_name_to_list = list(first_name)
print(first_name_to_list)            # ['A', 's', 'a', 'b', 'e', 'n', 'e', 'h']
```

## Numbers

数値型

1. 整数
   Example:
   ... -3, -2, -1, 0, 1, 2, 3 ...

2. 浮動小数点数
   Example:
   ... -3.5, -2.25, -1.0, 0.0, 1.1, 2.2, 3.5 ...

3. 複素数の計算
   Example:
   1 + j, 2 + 4j, 1 - 1j

🌕 あんたは偉い!これで2日目のチャレンジは完了し、最強への道の2歩目を踏み出しました。もうすこし演習をして、さらに鍛えましょう。

## 💻 Exercises - Day 2

### Exercises: Level 1

1. 30DaysOfPythonフォルダの中に day_2 というフォルダを作り、 variables.pyというファイルを作ってください。
2. variables.py を開き、 'Day 2: 30 Days of python programming'というコメントを書いてください。
3. 名前(first name)を表す変数を宣言し、そこに値を代入してください。
4. 名字(last name)を表す変数を宣言し、そこに値を代入してください。
5. フルネーム(full name)を表す変数を宣言し、そこに値を代入してください。
6. 住んでいる国(country)を表す変数を宣言し、そこに値を代入してください。
7. 住んでいる市区町村(city)を表す変数を宣言し、そこに値を代入してください。
8. 年齢(age)を表す変数を宣言し、そこに値を代入してください。
9. 現在の年(year)を表す変数を宣言し、そこに値を代入してください。
10. 電灯が点灯しているかどうか(is light on)を表す変数を宣言し、そこに値を代入してください。
11. 1つの行で、複数の変数を宣言してください。

### Exercises: Level 2

1. ここまでで宣言したすべての変数の値の型を確認してください。
1. 組み込み関数の `len()` を使い、あなたの名前の文字数を確認してください。
1. あなたの名前と名字の文字数を比較してください。
1. `5` を変数 `num_one` に格納し、 `4` を `num_two` に代入してください
    1. `num_one` と `num_two` の和を `num_total` に代入してください
    2. `num_one` と `num_two` の差を `num_diff` に代入してください
    3. `num_one` と `num_two` の積を `num_product` に代入してください
    4. `num_one` と `num_two` の商を `num_division` に代入してください
    5. `num_two` で `num_one` を割った剰余を `num_remainder` に代入してください
    6. `num_one` の `num_one` 乗を `num_exp` に代入してください
    7. `num_one` を `num_two` で割って余りを切り捨て、 `floor_division` に代入してください
1. ある円の半径は30メートルです。このとき、
    1. 円の面積を計算し、 `area_of_circle`に代入してください
    2. 円周を計算し、 `circum_of_circle` に代入してください
        - 円周の演習
    3. ユーザーの入力として半径を受け取るように変更し、面積と演習を求めてください
1. `input()` 関数で名前、名字、年齢、を受け取るようにしてください
1. Python Shell で`help('keywords')` を実行し、予約語とキーワードを確認してください。

🎉 CONGRATULATIONS ! 🎉

[<< Day 1](../readme.md) | [Day 3 >>](../03_Day_Operators/03_operators.md)
