
#Student info

##Main info

[Personal photo](3.jpg)

First name:**Uladzislau**
Last name:**Bychkou**

###Contacts:

+vladb.52@gmail.com
+@bedrauk

###About me:
>I came to become a professional programmer, I already have experience in writing programs in C#, Python, Delphi as part of my specialty training at a higher education institution.Nowadays I work as an engineer, my task is to modernize metalworking machines

##Skills

###Programming languages:
*Python*, *C#*, *Autolisp*, *Delphi*
Other: CAM, CAE, CAD, Office

###Example from codewars:
```
from collections import Counter

import re

def top_3_words(text):

    tmp = Counter(re.findall(r"[a-z']+", re.sub(r" '+ ", " ", text.lower())))

    return [w for w,_ in tmp.most_common(3)]
```

###Some tasks from stepik:
```
def magic_sphere():
    answ = [['Бесспорно', 'Предрешено', 'Никаких сомнений', 'Определённо да', 'Можешь быть уверен в этом'],
            ['Мне кажется - да', 'Вероятнее всего', 'Хорошие перспективы', 'Знаки говорят - да', 'Скорее да, чем нет'],
            ['Пока неясно, попробуй снова', 'Спроси позже', 'Лучше не рассказывать', 'Сейчас нельзя предсказать', 'Сконцентрируйся и спроси опять'],
            ['Даже не думай', 'Мой ответ - нет', 'По моим данным - нет', 'Перспективы не очень хорошие', 'Весьма сомнительно']]
    text = 'Чем могу вам помочь?'
    print('''Я магический шар, в моей памяти содержатся данные о прошлом, настоящем и будущем.
    Если хочешь меня о чем то спросить, то сперва подумайте как повляет на вас мой ответ''')
    name = input('Как вас зовут?\n')
    print(f'Приветсвую, {name}!')
    while text not in ['stop', 'нет', 'пока', 'стоп']:
        print('Записываю ваш вопрос, говорите')
        print(answ[random.randint(0, 3)][random.randint(0, 4)])
        text = input('Еще есть вопросы?\n')
```
```
def gen_pass():
    digits = '1234567890'
    low_lett = 'abcdefghijklmnopqrstuvwxyz'
    up_lett = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'
    symbols = '!@#$%^&*()_+|\\?/.,`~;:"<>[]{}'
    passws = []
    res = []
    total = int(input('Сколько паролей генерировать?\n'))
    length = int(input('Сколько символов должно быть в пароле?\n'))
    tmp = length // 4
    for i in range(total):
        for j in (digits, low_lett, up_lett, symbols):
            res += sample(j, tmp)
        for i in range(length - len(res)):
            res += choice(choice([digits, low_lett, up_lett, symbols]))
        shuffle(res)
        passws.append(''.join(res))
        res = []
    return passws
```

##About work

###Jobs

Only as engineer

[Done projects](https://Bedrauk.github.io/rsschool-cv/cv)

##Education

Gomel State Technical University Sukhoi / Machine building

##About English

English level: A2 (not confirmed)
