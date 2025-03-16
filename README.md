# SkeletonUtils3D

  English description:
  
  GDevelop extensions for manipulating 3D 0bject's skeleton.
  
  Actions:
  
Change bone position - change bone's position on global/local X/Y/Z axis.

Change bone rotation - change bone's rotation on global/local X/Y/Z axis.

Change bone scale. Now you can change the scale only on local axis.

Attach 3D object to bone - 3D object will move and turn around with bone.

Detach 3D object from bone - detach 3D object from bone (if it is attached) and attach it to the scene.

  Expressions:
  
BonePosition. Example: SkeletonTools3D::BonePosition(My3DModel,7,"Global","X").

BoneRotation. Example: SkeletonTools3D::BonePosition(My3DModel,7,"Local","Z"). 
! Note: this expression can return strange value. This is due to the fact that rotation on one axis can be compensated by rotation on the other two.

BoneScale. Only on local axis.

BonesNumber - the number of object's bones.

BoneName. Set by the creator of the 3d model.


  Описание на русском:
  
  Расширение для GDevelop, позволяющее манипулировать костями 3Д-модели.
  
  Действия:
  
Change bone position - изменить позицию кости по одной из осей (X, Y, Z).

Change bone rotation - изменить поворот кости по одной из осей.

Change bone scale - изменить размер кости. В данный момент размер можно менять только по локальным осям (не по глобальным).

Attach 3D object to bone - привязать 3Д-объект к кости. Он будет прикреплён к ней и станет двигаться и поворачиваться вместе с ней.

Detach 3D object from bone - открепить 3Д объект от кости, если он к ней привязан, и привязать его к 3д-сцене.

  Выражения:
  
BonePosition - положение кости. Пример использования: SkeletonTools3D::BonePosition(Моя3дМодель,7,"Global","X").

BoneRotation - угол кости. Пример использования: SkeletonTools3D::BoneRotation(Моя3дМодель,7,"Local","Z"). 
! ПРИМЕЧАНИЕ: это выражение может выдавать странные значения. Это связано с тем, что поворот по одной оси может компенсироваться поворотом по двум другим.

BoneScale - размер кости. Только по локальным осям.

BonesNumber - количество костей объекта.

BoneName - имя кости. Задаётся создателем 3д-модели.
