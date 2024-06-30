Uladzislau Bychkou
Contacts:
vladb.52@gmail.com
@bedrauk
About me:
I came to become a professional programmer, I already have experience in writing programs in C#, Python, Delphi as part of my specialty training at a higher education institution
Nowadays I work as an engineer, my task is to modernize metalworking machines
Skills: Python, C#, Autolisp, Delphi, CAM, CAE, CAD.

Example from codewars:
from collections import Counter

import re

def top_3_words(text):

    tmp = Counter(re.findall(r"[a-z']+", re.sub(r" '+ ", " ", text.lower())))

    return [w for w,_ in tmp.most_common(3)]

Jobs: Only as engineer

Done projects: https://Bedrauk.github.io/rsschool-cv/cv

English level: A2
