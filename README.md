# guiencoder.sk
GuiEncoder is a skript made to generate the code of an inventory in minecraft. Naturally, the code will include all the objects inside it with their respective attributes.<br>
Do you need to see how to use it in-game? You can watch the <a href="https://youtu.be/NTQKm2ngiqs">tutorial</a> to find out.

#### Required Plugins:
- Skript (oh! surprise)
- SkBee (Depends on the version you use)
- skript-reflect (Depends on the version you use)

#### Command:
``/guiencoder <type> <ID> [rows] [name]``
- ``<type>`` The type of inventory to be created, metadata or normal.
- ``<ID>`` The identifier to use in ``<ID>.sk``, ``function <ID>(p:player)`` and other values ​​in code.
- ``[rows]`` The number of rows the inventory will have (1-6). This value is optional, by default it will have 1.
- ``[name]`` The name that the inventory will have. This value is optional, by default it will be "".
