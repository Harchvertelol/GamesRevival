Новый рендер, позволяет использовать возможности DirectX 11.

- ASSAO - даёт реалистичные эффекты окружающего освещения и затенения.
- Screen Space Reflection - имитирует отражающие и блестящие поверхности.
- Тесселяция - увеличивает сложность сетки моделей, придаёт плавность и округлость игровым объектам.
- HDR - имитирует световую адаптацию, добавляет более яркие цвета.
- Parallax Occlusion Mapping - добавляет неровности на поверхностях рядом с камерой.
- и т.п.

#### Установка

1. Скопируйте следующие файлы из папки Common: D3D11Drv.int, Effects11.dll и папку d3d11drv в папку system в папке с игрой. При обновлении рендерера не забудьте удалить предыдущую версию папки d3d11drv.

2. Скопируйте файлы d3d11drv.dll и tessellation.cfg из папки, соответствующей игре (Unreal Tournament_436, Unreal Gold_226 и т.д.) в папку system в директории с игрой.

3. Если вы запускаете игру в первый раз, выберите D3D11 Renderer.
Либо можно перейти к настройкам с помощью системной консоли, вызываемой кнопкой тильды (~). В консоли введите 'preferences' (без кавычек) и далее измените рендер на DirectX 11. Или отредактируйте файл .ini (Unreal Tournament.ini или Unreal.ini), который находится в папке system - в подразделе [Engine.Engine] замените строку с GameRenderDevice на 'GameRenderDevice = D3D11Drv.D3D11RenderDevice' (без кавычек).

4. Установите файлы высот для Parallax Occlusion Mapping

5. Наслаждайтесь игрой :)