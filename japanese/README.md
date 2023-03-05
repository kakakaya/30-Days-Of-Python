# 🐍 30 Days Of Python

|# Day | Topics                                                    |
|------|:---------------------------------------------------------:|
| 01  |  [Introduction](./readme.md)|
| 02  |  [変数と組み込み関数](./02_Day_Variables_builtin_functions/02_variables_builtin_functions.md)|
| 03  |  [演算子](./03_Day_Operators/03_operators.md)|
| 04  |  [文字列](./04_Day_Strings/04_strings.md)|
| 05  |  [リスト](./05_Day_Lists/05_lists.md)|
| 06  |  [タプル](./06_Day_Tuples/06_tuples.md)|
| 07  |  [集合](./07_Day_Sets/07_sets.md)|
| 08  |  [辞書](./08_Day_Dictionaries/08_dictionaries.md)|
| 09  |  [条件演算子](./09_Day_Conditionals/09_conditionals.md)|
| 10  |  [ループ](./10_Day_Loops/10_loops.md)|
| 11  |  [関数](./11_Day_Functions/11_functions.md)|
| 12  |  [モジュール](./12_Day_Modules/12_modules.md)|
| 13  |  [リストの比較](./13_Day_List_comprehension/13_list_comprehension.md)|
| 14  |  [高階関数](./14_Day_Higher_order_functions/14_higher_order_functions.md)|
| 15  |  [Python Type Errors](./15_Day_Python_type_errors/15_python_type_errors.md)|
| 16 |  [Python Date time](./16_Day_Python_date_time/16_python_datetime.md) |
| 17 |  [例外処理](./17_Day_Exception_handling/17_exception_handling.md)|
| 18 |  [正規表現](./18_Day_Regular_expressions/18_regular_expressions.md)|
| 19 |  [ファイル操作](./19_Day_File_handling/19_file_handling.md)|
| 20 |  [Python のパッケージマネージャ](./20_Day_Python_package_manager/20_python_package_manager.md)|
| 21 |  [クラスとオブジェクト](./21_Day_Classes_and_objects/21_classes_and_objects.md)|
| 22 |  [Web スクレイピング](./22_Day_Web_scraping/22_web_scraping.md)|
| 23 |  [仮想環境](./23_Day_Virtual_environment/23_virtual_environment.md)|
| 24 |  [Statistics](./24_Day_Statistics/24_statistics.md)|
| 25 |  [Pandas](./25_Day_Pandas/25_pandas.md)|
| 26 |  [Python web](./26_Day_Python_web/26_python_web.md)|
| 27 |  [Python with MongoDB](./27_Day_Python_with_mongodb/27_python_with_mongodb.md)|
| 28 |  [API](./28_Day_API/28_API.md)|
| 29 |  [API 構築](./29_Day_Building_API/29_building_API.md)|
| 30 |  [まとめ](./30_Day_Conclusions/30_conclusions.md)|

🧡🧡🧡 HAPPY CODING 🧡🧡🧡

<div>
<small>Support the <strong>author</strong> to create more educational materials</small> <br />
<a href = "https://www.paypal.me/asabeneh"><img src='./images/paypal_lg.png' alt='Paypal Logo' style="width:10%"/></a>
</div>

<div align="center">
  <h1> 30 Days Of Python: Day 1 - Introduction</h1>
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
</div>


[Day 2 >>](./02_Day_Variables_builtin_functions/02_variables_builtin_functions.md)

![30DaysOfPython](./images/30DaysOfPython_banner3@2x.png)

- [🐍 30 Days Of Python](#-30-days-of-python)
- [📘 Day 1](#-day-1)
  - [ようこそ](#welcome)
  - [Introduction](#introduction)
  - [なぜ Python ?](#why-python-)
  - [環境構築](#environment-setup)
    - [Python のインストール](#installing-python)
    - [Python Shell](#python-shell)
    - [Installing Visual Studio Code](#installing-visual-studio-code)
      - [How to use visual studio code](#how-to-use-visual-studio-code)
  - [Python の基本](#basic-python)
    - [Python の構文](#python-syntax)
    - [Python のインデント](#python-indentation)
    - [コメント](#comments)
    - [データの型](#data-types)
      - [数値](#number)
      - [文字列](#string)
      - [真偽](#booleans)
      - [リスト](#list)
      - [辞書](#dictionary)
      - [タプル](#tuple)
      - [集合](#set)
    - [データの型を調べる](#checking-data-types)
    - [Python File](#python-file)
  - [💻 Exercises - Day 1](#-exercises---day-1)
    - [Exercise: Level 1](#exercise-level-1)
    - [Exercise: Level 2](#exercise-level-2)
    - [Exercise: Level 3](#exercise-level-3)

# 📘 Day 1

## Welcome

30日間 Python プログラミングチャレンジへのご参加、 **おめでとうございます** !
このチャレンジでは、 Python プログラマーになるために必要なことすべてと、プログラミングのコンセプトをすべて学ぶことができます。

もし積極的にチャレンジに参加したい場合、[30DaysOfPython challenge](https://t.me/ThirtyDaysOfPython)のテレグラムグループに参加することもで

## Introduction

Python 汎用の高水準プログラミング言語です。オープンソースで、インタプリタ型で、オブジェクト指向の言語です。
Python はオランダの開発者、Guido van Rossum に開発されており、最初のバージョンは1991年2月20日にリリースされました。 Python という名前は、イギリスのコメディ番組、『空飛ぶモンティ・パイソン』が由来になっています。

この30日間 Python プログラミングチャレンジでは、最新のバージョンである Python 3 を一歩ずつ学べるように手助けします。
それぞれのトピックを30日間に分割し、理解しやすい説明や、現実世界での例、たくさんのハンズオン演習やプロジェクトを含んでいます。

このチャレンジは、 Python を学習したい初心者からプロフェッショナルまでに向けて書かれています。おそらく30日から100日で完了し、テレグラムグループに参加した方々がチャレンジを完了できる割合はより高いです。

This challenge is designed for beginners and professionals who want to learn python programming language. It may take 30 to 100 days to complete the challenge, people who actively participate on the telegram group have a high probability of completing the challenge.

もし解説動画を視聴したい場合は、ここから見ることができます [Python for Absolute Beginners video](https://www.youtube.com/watch?v=11OYpBrhdyM) (英語)。

## Why Python ?

人間が使う言語に非常に近く、学習や利用が容易だからです。
Google を含む多くの産業や企業に利用されており、その用途は Web アプリケーション、デスクトップアプリケーション、システム管理、機械学習ライブラリなど、多岐に渡ります。データサイエンスや、AI関連の用途にも非常に相性が良いです。

Python を学ぶ理由に納得していただけたでしょうか。 Pyton は現在世界中で使われており、あなたはこれから Python に使われる前に Python を使いこなそうとしています。

## Environment Setup

### Installing Python

Python スクリプトを実行するには、 Python のランタイムをインストールしなければなりません。ここからインストーラーを[ダウンロード](https://www.python.org/) しましょう。

Windows はこちら
[![installing on Windows](./images/installing_on_windows.png)](https://www.python.org/)

macOS ユーザーはこちら

[![installing on Windows](./images/installing_on_macOS.png)](https://www.python.org/)

Linux ユーザーは各パッケージマネージャを利用してください。

Python が正常にインストールされたかを確認する場合、次のコマンドをターミナルで実行してください。

```shell
python --version
```

![Python Version](./images/python_versio.png)

ご覧の通り、私は _Python 3.7.5_ を使っています。バージョンが異なるかもしれませんが、 3.6 以上と表示されたなら大丈夫です。
正常にインストールされたのを確認し、次に進みましょう。

### Python Shell

Python はインタプリタ型のスクリプト言語であり、コンパイルは不要です。
つまり、コードを1行ずつ実行するということです。Python には _Python Shell (Python Interactive Shell、Python 対話型シェル)_ が含まれており、各 Python のコマンドを実行して結果を確認することができます。Python Shell はユーザーから Python のコードを入力されると、コードを実行して次の行に出力を表示します。ターミナルを開き、次のように入力してください。

```shell
python
```

![Python Scripting Shell](./images/opening_python_shell.png)

Python Shellが開き、あなたが Python のコードを入力するのを待っています。 >>> という記号に続けて Python のコードを書くことができます。次のように入力してみましょう。
![Python script on Python shell](./images/adding_on_python_shell.png)

** よくできました! ** 最初の Python スクリプトを Python Shell に入力することができました。
この Python Shell を終了するには、 >>> の記号の次に `exit()` と入力して Enter を押すことで終了できます。

![Exit from python shell](./images/exit_from_shell.png)

これで、 Python Shell を開く方法と抜ける方法を学びました。

あなたのコードを Python が理解できた場合は、 実行結果を出力しますが、もし理解できなければエラーを返します。わざとミスをして、 Python がどうなるか見てみましょう。

![Invalid Syntax Error](./images/invalid_syntax_error.png)

エラーを見てわかる通り、 Python は賢いので、私たちが作ったミスを理解し、 _Syntax Error: invalid syntax_ だと指摘してくれています。 `x` を乗算の記号に使おうとしていますが、これは Python では正しい記法ではないので、シンタックスエラー(構文のエラー)になっています。乗算をするには `x` ではなく、アスタリスク( `*` )を使うのが正しい記法です。画面に表示されたエラーは例外の起きた場所を明示しています。

このように、プログラムの中からエラーを発見して除去する流れを **デバッグ** と言います。早速、 `x` を `*` に入れ替えてデバッグしましょう。

![Fixing Syntax Error](./images/fixing_syntax_error.png)

バグは修正され、コードは実行され、期待通りの結果を得られました。
プログラマーはこのようなエラーと対面するのは日常であり、どのようにデバッグすればいいかを知るのは大切です。
どのような種類のエラーに対面しているのか理解できると、デバッグも上達します。読者がこれから遭遇するエラーには、次のようなものがあります。

- `SyntaxError`
  - 構文のエラー
- `IndexError`
  - 配列外アクセスのエラー
- `NameError`
  - 変数名のエラー
- `ModuleNotFoundError`
  - モジュールが見つからないときのエラー
- `KeyError`
  - 辞書キーのエラー
- `ImportError`
  - インポート時のエラー
- `AttributeError`
  - オブジェクト属性のエラー
- `TypeError`
  - 型のエラー
- `ValueError`
  - 値のエラー
- `ZeroDivisionError`
  - ゼロ除算エラー

より先のセクションでは、これら以外のエラーも見ることができます。
一旦、もうすこし Python シェルの使い方を学習しましょう。もし閉じてしまっているなら開き直してください。

![Python Scripting Shell](./images/opening_python_shell.png)

今度は、四則演算のような基本的な計算です。

Python のコードを書く前に、簡単な計算を確認しましょう:

- 2 + 3 = 5
- 3 - 2 = 1
- 3 \* 2 = 6
- 3 / 2 = 1.5
- 3 ^ 2 = 3 x 3 = 9
  - 3の2乗

Python では、これらに加えて追加の計算方法があります。

- 3 % 2 = 1 # 剰余(あまり)の計算
- 3 // 2 = 1 # 割り算の小数を切り捨てる計算

Python での数学表現に挑戦しましょう。また、コメントにも挑戦しましょう。

コメントはコードの一部ですが、 Python には実行されません。これにより、文章をコード中に残してわかりやすくすることができます。Python はコメントを無視します。
コメントはハッシュ(#) から始まるもので、次のようなものです。

```shell
 # コメントは # からはじまる
 # this is a python comment, because it starts with a (#) symbol
```

コメントを行いつつ、数学表現をしましょう。


![Maths on python shell](./images/maths_on_python_shell.png)

次の節に進む前に、Python シェルの練習を十分にしておきましょう。 `exit()` と入力するとシェルから抜けることができ、ターミナルで `python` と入力すると再度 Python シェルに入れます。

![Writing String on python shell](./images/writing_string_on_shell.png)

### Installing Visual Studio Code

The Python interactive shell is good to try and test small script codes but it will not be for a big project. In real work environment, developers use different code editors to write codes. In this 30 days of Python programming challenge we will use visual studio code. Visual studio code is a very popular open source text editor. I am a fan of vscode and I would recommend to [download](https://code.visualstudio.com/) visual studio code, but if you are in favor of other editors, feel free to follow with what you have.

[![Visual Studio Code](./images/vscode.png)](https://code.visualstudio.com/)

If you installed visual studio code, let us see how to use it.
If you prefer a video, you can follow this Visual Studio Code for Python [Video tutorial](https://www.youtube.com/watch?v=bn7Cx4z-vSo)

#### How to use visual studio code

Open the visual studio code by double clicking the visual studio icon. When you open it you will get this kind of interface. Try to interact with the labeled icons.

![Visual studio Code](./images/vscode_ui.png)

Create a folder named 30DaysOfPython on your desktop. Then open it using visual studio code.

![Opening Project on Visual studio](./images/how_to_open_project_on_vscode.png)

![Opening a project](./images/opening_project.png)

After opening it you will see shortcuts for creating files and folders inside of 30DaysOfPython project's directory. As you can see below, I have created the very first file, helloworld.py. You can do the same.

![Creating a python file](./images/helloworld.png)

After a long day of coding, you want to close your code editor, right? This is how you will close the opened project.

![Closing project](./images/closing_opened_project.png)

Congratulations, you have finished setting up the development environment. Let us start coding.

## Basic Python

### Python Syntax

Python スクリプトを Python シェルに書くこともできますし、エディタに書くこともできます。Python のファイルは `.py` という拡張子を持ちます。

### Python Indentation

インデント(段落)とは、文章中の空白を指します。他の多くのプログラミング言語ではコードを読み易くするためにインデントを使いますが、Python ではコードのブロックを表現するために使われます(他の言語では、波括弧`{}`がコードのブロックを表現するのに使われます)。
Python でのよくあるバグの一つが、誤ったインデントです。

![Indentation Error](./images/indentation.png)

### Comments

コメントはコードを読みやすくしたり、備考を残すために非常に重要です。Pythonはコメントを無視します。

ハッシュ(#)から始まる行はコメントとして扱われます。

**Example: 1行のコメント**

```shell
    # This is the first comment
    # This is the second comment
    # Python is eating the world
```

3つの引用符(`'''` または `"""`)を使うと、複数行のコメントとすることができます。

**Example: 複数行のコメント**

```shell
"""This is multiline comment
multiline comment takes multiple lines.
python is eating the world
"""
```

### Data types

Python には複数の型があります。一般的なものから始めましょう。
詳細は今後の節で解説しますが、まずは異なる型を見比べて慣れるだけにしましょう。まだ明確に理解できなくても大丈夫です。

#### Number

- `int`: 整数(正の整数、負の整数、ゼロを含む)
    Example:
    ... -3, -2, -1, 0, 1, 2, 3 ...
- `float`: 実数
    Example
    ... -3.5, -2.25, -1.0, 0.0, 1.1, 2.2, 3.5 ...
- `complex`: 複素数
    Example
    1 + j, 2 + 4j

#### String
一重引用符(`'`)や二重引用符(`"`)で囲まれた、0文字以上の文字は文字列になります。
改行を含む複数の行の場合、3重にすることで表現ができます。

**Example:**

```py
'Asabeneh'
"Finland"
'Python'
'I love teaching'
'I hope you are enjoying the first day of 30DaysOfPython Challenge'

"""これは複数行の文字列です。
改行を表現することができます。
"""
```

#### Booleans
真偽値は、 `True` か `False` を表わす値です。 `T` も `F` も大文字にしなくてはいけません。

**Example:**

```python
    True  # Is the light on? If it is on, then the value is True
    False # Is the light on? If it is off, then the value is False
```

#### List

Python のリストは、複数の型の要素を持てる順序付きの集合です。Javascriptの array に似ています。

**Example:**

```python
[0, 1, 2, 3, 4, 5]  # all are the same data types - a list of numbers
['Banana', 'Orange', 'Mango', 'Avocado'] # all the same data types - a list of strings (fruits)
['Finland','Estonia', 'Sweden','Norway'] # all the same data types - a list of strings (countries)
['Banana', 10, False, 9.81, ['apple', 'orange']] # list can contain different data types - string, integer, boolean, float, and list of strings
```

#### Dictionary

Python の辞書は、順序を持たないキーと値の組み合わせの集合です。

**Example:**

```python
{
  'first_name': 'Asabeneh',
  'last_name': 'Yetayeh',
  'country': 'Finland',
  'age': 250,
  'is_married': True,
  'skills': ['JS', 'React', 'Node', 'Python']
}
```

#### Tuple
Python のタプルは、複数の型の要素を持てる順序付きの集合で、リストと似ていますが、一度セットした値は変更できない(Immutable)のが特徴です。

**Example:**

```python
('Asabeneh', 'Pawel', 'Brook', 'Abraham', 'Lidiya') # Names
('Earth', 'Jupiter', 'Neptune', 'Mars', 'Venus', 'Saturn', 'Uranus', 'Mercury') # planets
```

#### Set
Python の集合型は、複数の型の要素を持つ集合で、リストやタプルに似ていますが、順序を持ちません。
また、数学の集合と同様、重複する要素を格納しません。


**Example:**

```python
{2, 4, 3, 5}
{3.14, 9.81, 2.7} # order is not important in set
```

他にも型はありますが、今後の節で紹介します。

### Checking Data types

値や変数の型を知るには、 `type` 関数を利用します。

![Checking Data types](./images/checking_data_types.png)

### Python File
このプロジェクト(30DaysOfPython)のプロジェクトを開いき、 `helloworld.py` を開いてください。もしなければ、 `30DaysOfPython` というフォルダを作成し、 `helloworld.py` というファイルをその中に作り、以下の内容を書き込んでください。

Python シェルは `print` せずとも実行結果を出力していましたが、スクリプトのファイルを実行する場合は結果を `print` しないとわかりません。
組み込み関数の `print()` は、1つ以上の引数を `print('arg1', 'arg2', 'arg3')` のように受け取って出力します。

**Example:**

helloworld.py

```py
# Python の紹介
# Day 1 - 30DaysOfPython Challenge

print(2 + 3)   # 加算、addition(+)
print(3 - 1)   # 減算、subtraction(-)
print(2 * 3)   # 乗算、multiplication(*)
print(3 / 2)   # 除算、division(/)
print(3 ** 2)  # べき乗、exponential(**)
print(3 % 2)   # 剰余、modulus(%)
print(3 // 2)  # 整数除算、Floor division operator(//)

# データの型を調べる

print(type(10))                  # 整数 (int)
print(type(3.14))                # 浮動小数点 (float)
print(type(1 + 3j))              # 複素数 (complex)
print(type('Asabeneh'))          # 文字列 (str)
print(type([1, 2, 3]))           # リスト (list)
print(type({'name':'Asabeneh'})) # 辞書 (dict)
print(type({9.8, 3.14, 2.7}))    # 集合 (set)
print(type((9.8, 3.14, 2.7)))    # タプル (tuple)
```

この Python スクリプトを Visual Studio Code で実行するには、下の画像を参照してください。ターミナルで `python helloworld.py` と入力しても実行できます。

![Running python script](./images/running_python_script.png)

🌕 あんたはすごい!ついに初日のチャレンジを完了し、最強になるための第一歩を踏み出しました。もうすこし演習をして、さらに鍛えましょう。

## 💻 Exercises - Day 1

### Exercise: Level 1

1. 現在使っている Python のバージョンを教えてください。
2. Python シェルを開き、次の計算をしてください。オペランドは3と4です(被演算子、計算に使われる項。最初の加算では3+4を行う。)
   - 加算(+)
   - 減算(-)
   - 乗算(\*)
   - 剰余(%)
   - 除算(/)
   - べき乗(\*\*)
   - 整数除算(//)
3. Python シェルで次の文字列を書いてください。
   - あなたの名前
   - あなたの名字
   - 住んでいる国
   - `30日間 Python プログラミングチャレンジを楽しんでいます` というテーマの文章
4. 次の値の型を調べてください。
   - `10`
   - `9.8`
   - `3.14`
   - `4 - 4j`
   - `['Asabeneh', 'Python', 'Finland']`

### Exercise: Level 2

1. `day_1` というフォルダを作り、その中に `helloworld.py` というファイルを作ってください。
2. そのファイルに、上記の1-4の問題を解き直してください。ただし、`print()` を使って、結果が出力されるようにしてください。
3. 作成した `helloworld.py` を実行し、結果を確認してください。

### Exercise: Level 3

1. 2と3、および10と8の間の[ユークリッド距離](https://ja.wikipedia.org/wiki/%E3%83%A6%E3%83%BC%E3%82%AF%E3%83%AA%E3%83%83%E3%83%89%E8%B7%9D%E9%9B%A2)を計算してください。
2. 整数、浮動小数点数、複素数、文字列、真偽値、リスト、タプル、集合、辞書など、これまでに学んだPython の型の値を書いてみてください。

🎉 CONGRATULATIONS ! 🎉

[Day 2 >>](./02_Day_Variables_builtin_functions/02_variables_builtin_functions.md)
