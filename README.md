# Некст-ген графическая сборка Skyrim <BR>


<img width="1024" height="256" alt="nvot логотип" src="https://github.com/user-attachments/assets/49f0bafb-093e-4ca0-b7ce-0b8eb6101a13" />

---


# **NVOT** — это:<BR>


<img width="1024" height="256" alt="плюсы сборки" src="https://github.com/user-attachments/assets/6a44c26f-ef66-4b07-a9a9-c0d772c97376" />

---

 
<img width="1024" height="256" alt="ВСЯ НУЖНА ИНФА" src="https://github.com/user-attachments/assets/3bd89966-9083-4929-8f88-ab27bf949abb" />




---

 
<img width="1024" height="256" alt="Системные требования" src="https://github.com/user-attachments/assets/54e40403-c473-4213-b83e-09f209b5c36e" />   <BR>


---

<img width="1024" height="256" alt="установка" src="https://github.com/user-attachments/assets/dc5c6210-2407-492b-ae80-b3dd5454b47c" />  <BR>


<details>
<summary>Нажми, чтобы посмотреть</summary>

> ❗ Требуется заранее установить стимовский **Skyrim Anniversary Edition** в стиме
> ❗️ Отключи **все антивирусы**, потому что они могут удалить SKSE

<details>
<summary><strong>Шаг 1</strong></summary>

Установи [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe)

</details>

<details>
<summary><strong>Шаг 2</strong></summary>

Установи [.NET Runtime 8.0.5 x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-8.0.5-windows-x64-installer)      

Установи [.NET Runtime v6](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.36-windows-x64-installer)      

Установи [.NET Runtime v9](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-9.0.6-windows-x64-installer)      

После чего **ОБЯЗАТЕЛЬНО** перезагрузи компьютер

</details>

<details>
<summary><strong>Шаг 3</strong></summary>

Установи **7-Zip** (**НЕ** WinRAR)  
[ССЫЛКА](https://www.7-zip.org/)

</details>

<details>
<summary><strong>Шаг 4</strong></summary>

Скачай архивы отсюда **ПО ОДНОМУ** – **[ЖМАКАЙ СЮДА](https://boosty.to/whistle/posts/32fa6a35-84fd-450a-a9eb-45fa8d1c043e?share=post_link)**

</details>

<details>
<summary><strong>Шаг 5</strong></summary>

После скачивания помести архивы в одну папку и просто нажми распаковать на самый первый архив. Жать нужно именно на архив 001 и распаковывать **ТОЛЬКО** через 7zip
 
 <img width="1046" height="521" alt="firefox_u3tZXN8aoB" src="https://github.com/user-attachments/assets/7f76163b-a7e2-4e09-ba9a-14dec65c25cb" />


</details>

<details>
<summary><strong>Шаг 6</strong></summary>

После распаковки у тебя будет папка **SkyrimDragonis**

</details>

<details> 
<summary><strong>Шаг 7</strong></summary>

Запусти `ModOrganizer.exe` в этой папке

</details>

<details>
<summary><strong>Шаг 8</strong></summary>

Меняем пути к сборке (если ты установил сборку прямо в диск C: - пропускай 8-9 шаг):  

- В верхней панели нажми **шестерёнку**  
  <br><img width="1920" height="1009" alt="ModOrganizer_y7zrkVUuQP" src="https://github.com/user-attachments/assets/2d6521d7-1bd9-4879-9301-8c18e331b320" />

- Перейди во вкладку **Пути**  
- Там поменяй путь "Управляемой игры" на ту которая находится в папке SkyrimDragonis - Stock Game  
  <br><img width="819" height="590" alt="ModOrganizer_rZ67JBmBgW" src="https://github.com/user-attachments/assets/950bbf6b-b8d6-418a-a610-b0378f447eea" />

**ИГРА УЖЕ ЕСТЬ В СБОРКЕ В ПАПКЕ "Stock Game"**  
→ Нажми **ОК**

</details>

<details>
<summary><strong>Шаг 9</strong></summary>

То же самое делаем и с SKSE:  

- Нажми в правом верхнем углу на **Skyrim Dragonis** (или другую программу, которая там может стоять)  
  <br><img width="1011" height="684" alt="ModOrganizer_fLQ4HKhfI2" src="https://github.com/user-attachments/assets/79cbecc0-a7ea-4cd1-8944-0d943662f7d0" />

- У тебя откроется окошко, в котором нужно нажать **Изменить...**  
- Укажи путь для Skyrim Dragonis (или же SKSE64):  
  `Skyrim Dragonis/mods/SKSE/root/skse64_loader.exe`  
  <br><img width="1143" height="495" alt="ModOrganizer_fwuaZ53v6d" src="https://github.com/user-attachments/assets/8340e1a3-3916-4a58-9f44-8bc0c3d3969f" />

  **И ОБЯЗАТЕЛЬНО ПРОВЕРЬТЕ ВКЛЮЧЕНЫ ЛИ У ВАС ВСЕ ПЛАГИНЫ В ПРАВОМ ОКНЕ МО2. ЕСЛИ НЕТ ТО ОБЯЗАТЕЛЬНО ВКЛЮЧИТЕ**

</details>

<details>
<summary><strong>Шаг 10</strong></summary>

Сохраняй и жми **Играть** . СТИМ ДОЛЖЕН БЫТЬ ИЗНАЧАЛЬНО ЗАПУЩЕН ПЕРЕД ЗАПУСКОМ ИГРЫ ЛИБО ПРОГРАММЫ В МО2

</details>

<details>
<summary><strong>❗ ВАЖНО, ЕСЛИ ПИШЕТ, ЧТО НЕ МОЖЕТ НАЙТИ SKSE64</strong></summary>

Проверь:

- Отключили ли вы антивирус перед тем как распаковать сборку  
- Проверьте наличие `skse64_loader.exe` в папке `SkyrimDragonis/mods/SKSE/Root/skse64_loader.exe`  

⚠️ **РЕШЕНИЕ:**  
Скачать [ОТСЮДА](https://skse.silverlock.org/beta/skse64_2_00_20.7z) SKSE64

</details>

> ❌ Сборка не тестировалась на пиратках. Только лицензия!

</details>

</details>

---

<img width="1024" height="256" alt="БАГИ И РЕШЕНИЯ" src="https://github.com/user-attachments/assets/4d95a353-ef0a-4244-8d5f-eea78fe3ab7b" /> <BR>


<details>
<summary>Нажми, чтобы посмотреть</summary>

1. **Фризы?**  
   ➤ Поставь файл подкачки на 40 GB  

2. **Краш при запуске**  
   ➤ Обычно неверная установка  

3. **Архивы не распаковываются**  
   ➤ Перепроверь место и 7-Zip  

4. **Баги в местах**  
   ➤ Пиши в [**ДИСКОРД СЕРВЕР**](https://discord.gg/QV5RP9eKWj)

5. **MO2 не видит SKSE?**  
   ➤ Положи SKSE в `mods/SKSE/Root/`  

6. **Проблемы с разрешением**  
   ➤ Проверь настройки разрешения в  `skyrimprefs.ini` **В САМОМ МО2**  
   ➤ Проверь настройки разрешения SSE Display Tweaks

</details>

---

<img width="1024" height="256" alt="ЧАСТЫЕ ВОПРОСЫ" src="https://github.com/user-attachments/assets/5520283c-5bae-440c-aaab-11f616dbd759" />  <BR>


<details>
<summary>Нажми, чтобы посмотреть</summary>

1. **Поддержка 21:9 / 32:9 / 16:10 мониторов?**  
   ➤ Да. Просто включи её в левом окошке мо2 в самом низу. <br>

2. **Почему нет торрента?**  
   ➤ В моей стране запрещено. <br>

3. **Есть ли в этой сборке поддержка геймпада?**  
   ➤ Да. Просто включи её в левом окошке мо2 в самом низу.   <br>

4. **Есть ли в этой сборке переработка анимаций?**     
   ➤ Да. Было переработано всё начиная от анимаций боёвки и заканчивая анимациями передвижения   <br>

</details>

---

<p align="center"><strong>🌄 Открой новый Скайрим, каким он никогда не был.</strong></p>
<p align="center">💬 Telegram: https://t.me/Whistle69 • Boosty: https://boosty.to/whistle</p>
