# Tattoo AR

приложение за визуализране на татуировки чрез добавена реалност - Augmented Reality (AR).

## Елементи на приложението

Начален екран, който се показва докато приложението  зарежда. 
Следва екран на който може да се избере татус от предложения от сървър, вмъкване на картинки от локалната галерия или татуси, които са част от приложението. След избор на татус, се активира камерата и тя започва търсенето на предефиниран маркер. Тук трябва да има помощна информациз за потребителя. При разпознаване на маркера се рисува избараният татус (бонус - премахване на маркера от реалното изображение). Татуса да може да се скалира и върти, за да позволи по-добро позициониране. Полученото изображение да може да се запазва в приложението и на устройството.
Да се позволи редактриането на външни картинки (тези заредени от галериятан на телефона). 

## Сценарии

Потребителя трябва да може да избере татус или да създаде свой в режим "Редактиране". Редактирането на картинка да позволява прилагането на ефекти и изчистване на прозиволна област от картинката. Запазения изходен файл да е с прозрачност и да може да се преизпозлва.


## Технически елементи
 - Списъка на началните татуировки ще идва от сървър под формата на JSON. Желателно е да се кешира списъка и картинките.
 - Визуализиране на елементите в UICollectionView
 - Съхраняване на редактираните картинки на устройството

## Допълнителни указания и идеи
 - да се измисли подходящ маркер, който да се засича лесно от телефона.
 - да се работи само с png картинки, понеже те имат прозрачност.
 - да се изпозлва библиотека за AR

 
## Въпроси и отговори

1. Кога ще има повече детайли за api? - След формирането на отборите ще има информация.
