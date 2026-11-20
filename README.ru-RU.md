<div align="center">
  <h1>Привет, я Алекс 👋</h1>
  <p><strong>Исследователь безопасности · Reverse Engineer · Инженер компьютерного зрения</strong></p>
  <p>
    Я создаю и исследую высокопроизводительные системы на пересечении<br>
    безопасности ПО, native Windows-разработки и computer vision в реальном времени.
  </p>
</div>

<p align="center">
  <a href="https://t.me/in_the_skyyy"><img src="https://img.shields.io/badge/Связаться-%40in__the__skyyy-2AABEE?style=for-the-badge&logo=telegram&logoColor=white" alt="Связаться в Telegram"></a>
  <a href="https://t.me/lunaraim"><img src="https://img.shields.io/badge/LunarAim-%40lunaraim-2548BB?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram-канал LunarAim"></a>
  <a href="https://t.me/lunaraim2"><img src="https://img.shields.io/badge/LunarAim%202-%40lunaraim2-17C3E1?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram-канал LunarAim 2"></a>
</p>

<p align="center"><a href="README.md">English</a> · <a href="README.ru-RU.md">Русский</a> · <a href="README.zh-CN.md">简体中文</a></p>

<details>
<summary>Содержание</summary>
<br>

- [Обо мне](#обо-мне)
- [Направления](#направления)
- [Основной стек](#основной-стек)
- [Главный проект](#главный-проект)
  - [LunarAim 2.2 — redesign на C++](#lunaraim-22--redesign-на-c)
  - [LunarEngine Open — предшественник на Python](#lunarengine-open--предшественник-на-python)
- [Как я работаю](#как-я-работаю)
- [Контакты](#контакты)

</details>

## Обо мне

Я изучаю Computer Security в **HSE MIEM**, выпуск — **2031 год**. Моя работа объединяет reverse engineering, security testing, native systems programming и прикладное машинное обучение.

Мне особенно интересно понимать поведение ПО на границе между high-level приложением, операционной системой, аппаратным ускорением и данными реального времени. Я люблю разбирать систему, измерять происходящее на практике и собирать критический путь заново с явными ограничениями по производительности и надёжности.

## Направления

- **Reverse engineering и security research** — binary analysis, анализ поведения ПО, Windows internals и responsible vulnerability research.
- **Security testing** — binary-focused testing, digital forensics и non-web network security testing.
- **Классическое компьютерное зрение** — OpenCV pipeline, сегментация по цветовым пространствам, геометрический анализ, morphology, filtering и высокопроизводительная обработка изображений.
- **Deep learning для vision** — детекторы семейства YOLO, workflow Ultralytics, подготовка датасетов, обучение, валидация, анализ экспериментов и интеграция inference.
- **Performance engineering** — profiling, debugging, анализ latency, оптимизация pre-processing/inference/post-processing и снижение overhead всего pipeline.

## Основной стек

<p align="center">
  <a href="https://isocpp.org/"><img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++"></a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"></a>
  <a href="https://en.cppreference.com/w/c/language"><img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C"></a>
  <a href="https://en.wikipedia.org/wiki/Assembly_language"><img src="https://img.shields.io/badge/Assembly-525252?style=for-the-badge&logoColor=white" alt="Assembly"></a>
  <a href="https://opencv.org/"><img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"></a>
  <a href="https://pytorch.org/"><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"></a>
  <a href="https://github.com/ultralytics/ultralytics"><img src="https://img.shields.io/badge/Ultralytics%20YOLO-111F68?style=for-the-badge&logoColor=white" alt="Ultralytics YOLO"></a>
  <a href="https://developer.nvidia.com/tensorrt"><img src="https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="TensorRT"></a>
  <a href="https://learn.microsoft.com/en-us/windows/win32/"><img src="https://img.shields.io/badge/Win32-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="Win32 API"></a>
  <a href="https://cmake.org/"><img src="https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white" alt="CMake"></a>
</p>

Я свободно пишу на **C++ и Python**, уверенно работаю с **C** и использую **Assembly**, когда это нужно для низкоуровневого анализа. Также у меня есть практический опыт profiling, debugging, Windows-native API, GPU inference и подготовки данных для computer-vision моделей.

## Главный проект

LunarAim — один большой инженерный проект, который можно рассматривать через два репозитория и два поколения технологий:

<table>
  <tr>
    <td width="50%" valign="middle" align="center">
      <a href="https://github.com/lnTheSky/lunar_v2_showdown">
        <img src="https://raw.githubusercontent.com/lnTheSky/lunar_v2_showdown/main/assets/brand/lunar-aim-banner.png" alt="LunarAim 2.2 — redesign на C++" width="100%">
      </a>
    </td>
    <td width="50%" valign="middle" align="center">
      <a href="https://github.com/lnTheSky/LunarEngine_Open">
        <img src="https://raw.githubusercontent.com/lnTheSky/LunarEngine_Open/main/media/image.png" alt="LunarEngine Open — предшественник на Python" width="100%">
      </a>
    </td>
  </tr>
</table>

### LunarAim 2.2 — redesign на C++

[Открыть showcase LunarAim V2 →](https://github.com/lnTheSky/lunar_v2_showdown)

Текущее поколение — **native redesign на C++** с явной архитектурой runtime и структурированным frontend bridge. Оно всё ещё развивается и не является EOL-проектом.

Проект объединяет:

- модульную orchestration runtime и наблюдаемый lifecycle;
- native UI bridge на базе WebView2;
- Win32 Raw Input и desktop capture через DirectX;
- заменяемые контракты detector, trigger и mouse;
- OpenCV/Colorbot и YOLO-based detection paths;
- CUDA/TensorRT с динамической границей GPU-модуля;
- profiling, telemetry и проектирование pipeline с фокусом на latency.

Публичный репозиторий — это **technical showcase**. Production runtime и proprietary implementation остаются закрытыми.

### LunarEngine Open — предшественник на Python

[Открыть архивный LunarEngine →](https://github.com/lnTheSky/LunarEngine_Open)

Старое поколение — **research snapshot на Python 3.11**. Оно показывает ранний экспериментальный подход: desktop UI на Flet, обработку цветов через OpenCV, model-assisted detection, конфигурационно-ориентированную итерацию и эксперименты с Windows input/output.

Репозиторий сохранён как архив, а не как usable release. В нём прямо указано, что код устарел, не поддерживается и не предназначен для запуска или адаптации.

## Как я работаю

Мои сильнейшие проекты объединяют low-level понимание с измеримым поведением системы:

1. **Понимаю data path.** Анализирую нужное поведение, определяю реальные inputs/outputs и формулирую измеримые параметры.
2. **Строю минимальный эксперимент.** Проверяю алгоритм или integration point отдельно до встраивания в runtime.
3. **Измеряю каждый этап.** Отдельно профилирую capture, pre-processing, inference, post-processing, control logic и output.
4. **Делаю выводы из данных.** Готовлю датасеты, обучаю модели, анализирую ошибки, сравниваю эксперименты и превращаю наблюдения в изменения.
5. **Интегрирую end to end.** Переношу результат в работающее приложение с явными границами, diagnostics и возможностью заменять реализации.

## Контакты

По вопросам проектов и сотрудничества пишите [@in_the_skyyy](https://t.me/in_the_skyyy). Обновления и материалы публикуются в [@lunaraim](https://t.me/lunaraim) и [@lunaraim2](https://t.me/lunaraim2).

<br>

<div align="center">
  <sub>Security research · native systems · computer vision в реальном времени</sub>
</div>
