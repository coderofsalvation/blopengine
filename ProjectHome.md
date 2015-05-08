<a href='http://www.youtube.com/watch?feature=player_embedded&v=EiRN2khVsB4' target='_blank'><img src='http://img.youtube.com/vi/EiRN2khVsB4/0.jpg' width='425' height=344 /></a>

# What is it #
The blopengine is just a basic C++ 3d framework, just some bunch of usefull classes. Its trying to give you an easy 'start' for your demo/game whatever. Its just a basic rendering loop and some loading of files. It has some OO MVC thingies, which can provide clear code or no benefit at all.
Since this is abandonware, there might be some interesting classes for you.

# Features #
  * 3DS model import
  * fontmap support
  * 3DMAX plugin for exporting camera chases
  * logging & output methods
  * MVC characteristics
  * TGA texture loading with alpha support
  * save to AVI support (compilerflag)
  * some handy tools (Executables) to generate fontmaps, dir-2-headerfile conversion etc
  * 'all-resources-in-one executable' possibilities
  * utility classes for : 3d drawing, animation, fontmaps, simple textfile script parser, unzip, wget (http get), strings
  * simple sequencer & plugin system, which reads textfiles in this format :
```
logoscreen->set(00:00:05:00,fadein,data/intro_1.tga,1,0.6,)
fmod->set(00:00:06:00,play,data/test.xm,,)
logoscreen->set(00:00:08:00,fadeout,,,)
logoscreen->set(00:00:11:00,fadein,data/intro_2.tga,1,0.6,)
animation->set(00:00:03:00,stretch,0,0.0)
skybox->set(00:00:45:00,fadein,,,)
.. and so on
```

# Abandoned project #
This is ABANDONWARE / FREE SOFTWARE.
When things don't work as expected blame yourself for using this and dont bother me with it.
I've written this many years ago, and my perspective on lots of things have changed.
