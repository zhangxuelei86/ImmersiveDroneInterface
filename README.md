# Immersive Semi-Autonomous Aerial Command System

## Setup
We are using Unity 2017.2.

These commands will handle updating of the ROS submodules. Run them from the top directory of the project.

> git submodule update --init

> cd Assets/ROSBridgeLib

> git reset --hard HEAD

> printf '[submodule "Pointcloud"]\n\tpath = Pointcloud\n\turl = https://github.com/srv/Pointcloud.git'>.gitmodules

> git submodule sync

> git submodule update --init

## Documentation
[Our Documentation](https://docs.google.com/document/d/1SNp_7TKreH0aQJi-O4z-tOPAddoI61xs9drVxUI1xbE/edit?usp=sharing)

[Oculus Input SDK](https://developer.oculus.com/documentation/unity/latest/concepts/unity-ovrinput/#unity-ovrinput)

[Oculus Avatar SDK](http://static.oculus.com/documentation/pdfs/avatarsdk/1.12/avatarsdk.pdf)

[VRTK Documentation](https://vrtoolkit.readme.io/docs)

[Touch Interface](https://github.com/tcheng96/2d-drone-interface)
