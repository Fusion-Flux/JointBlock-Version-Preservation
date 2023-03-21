„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª
    JointBlockMod 0.6.0 For Minecraft1.7.10(&Forge)
    JBRobotModelMOD 0.6.0 For Minecraft1.7.10(&Forge)
    
    Copyright (c) 2016 ARUBE(oANCIENTREDo)
„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª„ª


Thanks for downloading JointBlockMod.

This mod needs Minecraft1.7.10 with Forge in order to install&use.

This mod is kind of base mod. Able to used by it self, but doesn't have much contents.
You may try this mod with addon mod "JBRobotModelMOD" included in this zip.


[notcie]
  This mod is not finished yet. In future update, data might not be compatible with newer version.
  So be careful to use it on your mc world. It might cause crash or mess after future update.
  I strongly suggest you to use this mod on your bran new mc world.

[please]
  Please, do not redistribute this mod.


=========== Some explanations about JointBlockMod ===========

  Q:What is this mod for?
  A:Making your original ridable Robots!!!

  Q:What do I have to do to build my Robots?
  A:First you need "JointCore" block.
    Place it where you want to construct your Robots.
    It will be the core of your Robot, and you can "assemble" Robot from right clicking core.(GUI will open)

  Q:I opened the core GUI and saw something says "No unit type".
  A:In JointBlockMod, Robots are called "Unit" after assemble, and Unit have Types.
    For example, "Bipedal Type Unit" is type that have two legs to run around.
    But in order to define "Unit Type" of your Robot, you need to pass some little requirements.
    To know what is required, choose unit type by pressing "<<"or">>" buttons, and press "Test requirement" button.
    The list of lacking parts will show up. 
    Most of requirements is some kind of "Joint".
    (It's not that strict. Kind of guideline. )
    (Requirements is just shapes, sometimes with amount. Motions are not necessary.)

  Q:What are the other blocks for?
  A:-JointSeat
       Where you sit on.
    -JointNormal
       Robot parts with no motion.
    -JointRotator
       Robot parts that can set rotate motion.
    -JointExtender
       Robot parts that can set extend motion.
    -JointSlider
       Robot parts that can set slide motion.
    -JointScaler
       Robot parts that can set scale motion.
    -JointAttracter
       Can attract other unit.

  Q:Motion?
  A:Right click each block. GUI will show up.
    In the bottom of GUI, you will see button name "Set motion" and "Set init".
    Press "Set motion" button. GUI page will change to motion setting page.
    Choose motion type by pressing "<<"or">>" buttons.
    Basic motion comes with "motion with tick" and "motion with move".
    If you want to set motion other than basic ones, try dropping "Motion Items" to upper left slot.

  Q:Model?
  A:Some vanilla blocks can be used as model.
    If you have installed addon mod "JBRobotModelMOD", some more model items is added.

  Q:I assembled my Robot, but I want to fix it.
  A:There is two way to disassemble Unit.
    -1.Throw disassemble ball to your Unit.
      (Only player who assembled Robot can use this way.)
    -2.Get item "Unit Controller".
       Sit on operator seat of your Robot.
       Use "Unit Controller". It will be related to your Robot.
       Use "Unit Controller" again. Unit related to controller will disassemble.

  Q:Is there something to do with item name "UnitParts"?
  A:Yes.
    After testing unit reqirement, qualifiled block starts to show yellow particle.
    Place "UnitParts" to the motion slot of those parts.
    It will turn into related motion item, and some motion params is automatically set for you.
    (This step is NOT required. It's just an assistance function from mod.)
    (Some of it doesn't have related motion. In those case, nothing happens.)

  Q:I placed lots of seats, but many of them doesn't work!
  A:Only four seats can be active per Unit.
    And each seat number have to be set correctly.("Correctly" means no number duplication.)

  Q:I can't get off my Robot seat!!
  A:Double press dismount button.(Double Left SHIFT Key)

  Q:What key is related to "Key Motion Control"?
  A:Default button setting is,
     -Input 1 : Z
     -Input 2 : X
     -Input 3 : C
     -Input 4 : V
     -Input 5 : B
     -Input 6 : N
     -Input 7 : M
     -Input 8 : ,
    You can change it from Control Settings.

  Q:In settings of "Key Motion Control", I saw entry name "Execute Action". What is it?
  A:In addon mods, some Model Item comes with action.
    For examle, beam lazer gun can shoot out beam lazer using Unit Energy.

  Q:How do I change the facing of Model?
  A:Hit block with vanilla Torch or WoodStick.
     -Torch:Changes bottom side of Model.
     -Stick:Rotate facing of Model.

  Q:Some of the parts suddunly exploded and disappeared! What happened?
  A:If the Unit health fall below 50%, random parts destruction will occur.

  Q:Why is my JointBlock dark?
  A:May be it is not connected to core.
    Each block has connection way.
    Check electric-like-particles. Black is parent, and Yellow is child.
   (For JointExtender, yellow energy-like-something is flowing form parent to child.)

  Q:I tried this mod in my SMP server, but it's too laggy.
  A:May be you need more powerful machine to run this mod.
   (Its not reccomendable, but by adding "-XX:+DisableExplicitGC" jvm args might reduce some of lags.)

  Q:This mod is buggy.
  A:Sorry for inconvenient.
    This mod has just started.


Thanks for reading.
Sorry for my funny English.
