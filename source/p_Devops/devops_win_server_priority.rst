=========================================
Win Server 2012文件共享权限管理
=========================================

正常来说我们将一个分区共享出去并配置Everyone读写权限，这是个一劳永逸的方案，任何用户都能访问共享，但是经常我们有具体文件夹具体权限分配的问题，比如一个分区中有个档案文件夹需要关闭所有人访问权限，只授予某些人的单独权限，可以在档案文件夹上右键选择共享>停止共享，这样设置之后就没有用户能访问这个文件夹了，然后在右键>属性>安全添加某一个用户的权限，这样就可以将这个文件夹权限做了特定用户权限，而无须每个文件夹去配置权限。