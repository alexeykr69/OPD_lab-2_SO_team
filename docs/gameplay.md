# Gameplay документация (2D Platformer)

## Физические параметры
- Гравитация: -9.81 - стандартная
- Игрок (CharacterPlatformer): Mass = 10, Gravity Scale = 0, Linear Damping = 1
- Трава (Grass): статическая, без Rigidbody2D
- Рычаг (Lever): статический, без Rigidbody2D
- Физические материалы: отсутствуют (трение стандартное)

## Префабы
### Опасные
- Нет

### Полезные
- Нет

### Нейтральные
- **Lever** — Audio Source, BoxCollider2D, скрипт `Lever`.

## UI
- Нет

## Параметры сложности (Скрипт 'Player Character')
- PlayerController.Speed = 15 (влияет на скорость передвижения)
- PlayerController.JumpForce = 7 (высота прыжка)
- Physics2D.gravity = -9.81 (общая гравитация)
- Can_jump = True (Возможность прыжка)
- Double_jump = True (Возможность двойного прыжка)