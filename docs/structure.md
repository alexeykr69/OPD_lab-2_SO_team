1\)

Assets\\Scenes\\SampleScene - стандартная сцена, созданная движком unity при инициализации проекта, содержит только Камеру и Свет (Main camera, Global light 2d)



Assets\\IndieMarc\\PlatformerDemo\\PlatformerDemo.unity - основная сцена, хранящая в себе

визуальную состовляющую, материалы, персонажа и скрипты для его управления и технической составляющей



2\)

На основной сцене находятся такие объекты как: персонаж, свет, камера, объекты кустов, фона леса и сетка рисования для припятствий (кубов), пребафами являются все объекты, помеченные в структуре проекта синим цветом: персонаж, объекты фона леса и кустов



3\)

Компоненты объекта игрока: transform, sprite renderer, rigidbody 2d, Capusle collider 2d и скрипты (Player Character, Character Anim, Character Hold Item)



В компоненте Transform: можно настроить параметры позиции, поворота или размера

В компоненте Sprite Renderer: можно настроить цвет объекта

В Rigidbody 2d: Можно настроить массу и силу гравитации

В Capsule collider 2d: Можно настроить хитбокс



4)В папке Scripts (Assets/IndieMarc/PlatformerDemo/Scripts):

Assets/IndieMarc/PlatformerDemo/Scripts/CarryItem - отвечает за логику подбираемых предметов

Assets/IndieMarc/PlatformerDemo/Scripts/Character Anim - отвечает за проигрывание анимаций персонажа

Assets/IndieMarc/PlatformerDemo/Scripts/Character Hold Item - отвечает за механику удержания предмета игроком

Assets/IndieMarc/PlatformerDemo/Scripts/Follow Camera - Заставляет камеру следовать за игроком

Assets/IndieMarc/PlatformerDemo/Scripts/Lever - отвечает за переключение рычага в игре

Assets/IndieMarc/PlatformerDemo/Scripts/Parallax Background - Отвечает за создание эффекта параллакса

Assets/IndieMarc/PlatformerDemo/Scripts/Player Character - Отвечает за управление персонажен

Assets/IndieMarc/PlatformerDemo/Scripts/Player Controls - считывает ввод с клавиатуры игроком

Assets/IndieMarc/PlatformerDemo/Scripts/The audio - отвечает за воспроизведение звуков



Не в папке Scripts:

Assets/IndieMarc/PlatformerDemo/Editor/ImportPackage - отвечает за первоначальную настройку проекта

Assets/IndieMarc/PlatformerDemo/Welcome/Welcome2DScript - открывает официальную документацию по 2d для unity

