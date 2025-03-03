# CS:GO Basehook

Проект демонстрирует основную базу для изменения игрового процесса Counter-Strike: Global Offensive. 

## Основное

1. Отрисовка основана на получении `IDirect3DDevice9`; выполняется перехват функций `D3DCreate` `D3DDevice` `D3DEndScene` `D3DnReset`.
2. Демонстрация получения и использования функций игрового движка через виртуальные таблицы интерфейсов `VClient017` `GameMovement001` `VEngineClient014` `VClientEntityList003`. 
3. В качестве примера показан перехват функций `HUD_Key_Event` `CL_CreateMove`
  
## Автор
Ve4niySooN, 2016 https://vk.com/mr.soon

