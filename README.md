## **Генератор квестов (команда 1c is the future)**  
Инструмент для генерации ветвящихся квестов с заданным СЕТТИНГОМ, ГЛАВНЫМ ГЕРОЕМ и ЦЕЛЬЮ квеста.

## **✨ Ключевые особенности**  
1. 🎭 Ветвистость: 8+ взаимосвязанных сцен.
2. 🤖 AI-генерация: Автоматическое создание контента с помощью дообученной специально для русского языка модели Llama3 (owl/t-Lite)
3. 🕹️ Неожиданные повороты: Смешные, рискованные и логичные варианты действий
4. 📈 Визуализация построенного сюжета в виде связанных событий (BETA).


## **🛠 Установка и запуск**  
Для запуска проекта рекомендуется воспользоваться сервисом Google Colab. 
### **1. Создание блокнота**
Для начала зарегистируйтесь в своём аккаунте Google. 
Затем нажмите на файл quest_generator.ipynb в репозитории, и затем на кнопку "Open in Colab".
<img width="1122" height="279" alt="step1" src="https://github.com/user-attachments/assets/d578bc16-a7cc-48ef-ad88-f7f72aba62cf" />
<img width="1151" height="436" alt="step2" src="https://github.com/user-attachments/assets/dfdbc144-5378-4d3c-a159-0b6eea2b0526" />

### **2. Переход на GPU**  
Для значительного ускорения работы рекомендуется сменить среду выполнения на графический процессор, предоставляемый бесплатно. 
Для этого перейдите в верхнее меню в раздел "Среда выполнения" -> "Сменить среду выполнения".
Затем выберите "Графический процессор T4" и нажмите "Сохранить"
<img width="708" height="652" alt="step3" src="https://github.com/user-attachments/assets/700239d1-3b1f-4a56-bbbe-0a95953c8709" />
<img width="701" height="601" alt="step4" src="https://github.com/user-attachments/assets/8ce83dcd-2130-4d6a-8ca6-652f587e148d" />

### **3. Запуск**  
Для запуска нажмите на кнопку "Выполнить все" и затем после появления предупреждения "Выполнить". 
<img width="787" height="265" alt="step5" src="https://github.com/user-attachments/assets/522c4226-e4d4-4a3d-bac4-135e8af167f7" />
<img width="787" height="265" alt="step6" src="https://github.com/user-attachments/assets/dba90572-dc44-47e6-ba29-fe819b680724" />


Пример построенных графов (BETA):
<img width="1116" height="832" alt="изображение" src="https://github.com/user-attachments/assets/3e1b26db-3318-4d89-ab3a-22a099a51c32" />
<img width="1501" height="764" alt="изображение" src="https://github.com/user-attachments/assets/c311be85-63af-44f7-bfe2-32aaa80cd23f" />


## **📂 Структура проекта**  
```
├── /input – папка с входными текстовыми файлами 
├── quest_generator.ipynb - основной файл проекта
├── quest.json - пример результата генерации
├── requirements.txt - необходимые для работы модули
└── README.md  
```

