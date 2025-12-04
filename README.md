## Mester-Oxdan

<b>  ___                     _                       </b>

**  / _ \     __  __      __| |      __ _      _ __  **

** | | | |    \ \/ /     / _` |     / _` |    | '_ \ **

** | |_| |     >  <     | (_| |    | (_| |    | | | |**

**  \___/     /_/\_\     \__,_|     \__,_|    |_| |_|**


## █ TECH KRIEGFORGE

<b>Languages</b>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%252B%252B&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6?style=for-the-badge&logo=css3&logoColor=white)
![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)

<b>Tools</b>

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/unrealengine-%23313131.svg?style=for-the-badge&logo=unrealengine&logoColor=white)

## Russian Way In

яндекс навигатор - я родился

лунтик фраза - помогатор 

фексос дем демич папа у меня хто? - фиксик 

пиноккио пила пилить - дерево

вегибатор помогатор хто я? - угощение

хочешь покажу - детей


**порядок дорожного движения

**фиолетовая мелочь

**русский алфавит 

**числа цезарь

**A1Z26 33-18-15...

**парами влюбление а ты волк одинокий делений

**Base64 в нашем коде на развороте 

**не ливай число поменяй


<pre>import hashlib
import base64

cipher_map = [chr(i) for i in range(ord('а'), ord('я')+1)]
cipher_map.insert(6, 'ё')

def rotate_cipher(text, rotation=33):
    result = ""
    for char in text:
        if char in cipher_map:
            idx = (cipher_map.index(char) + rotation) % len(cipher_map)
            result += cipher_map[idx]
        else:
            result += char
    return result

encoded_strings = [
    "VkNoTjN4SDM=",
    "RU5HM0Y1U0g=",
    "SDR4Tm5WQ1I=",
    "dGhpc2lzbm90aXQ="
]

for encoded in encoded_strings:
    try:
        decoded = base64.b64decode(encoded).decode('utf-8', errors='ignore')
        rotated = rotate_cipher(decoded, 17)
        hashed = hashlib.md5(rotated.encode()).hexdigest()
        
        if hashed.startswith('a3f'):
            print(f"Possible key: {hashed[:8]}")
        else:
            print(f"Invalid: {hashed[:8]}")
    except:
        print(f"Failed: {encoded}")

numbers = [17, 16, 14, 16, 4, 1, 20, 16, 18, 5, 6, 18, 6, 3, 16]
total = sum(numbers)

if total % 2 == 0:
    print("Even sum detected - wrong path")
else:
    print("Odd sum - continue")

def convert_to_invite(val):
    alphabet = "ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789"
    result = ""
    while val > 0:
        result += alphabet[val % 36]
        val //= 36
    return result[::-1]

invite_code = convert_to_invite(total)
print(f"Generated code: {invite_code}")
print(f"discord.gg/{invite_code}")</pre>

## The Way In



<!--

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
