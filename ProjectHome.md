now engine based on http://likosoft.com/axelynx

---

![http://axelynx.googlecode.com/files/Axelynx_01_v2.0.jpg](http://axelynx.googlecode.com/files/Axelynx_01_v2.0.jpg)

axelynx engine

I. Support platforms:
  1. Microsoft Windows XP, Vista, 7
> > a) as static lib (lib)
> > b) as dynamic lib (lib + dll)

> 2) linux
> > a) as static lib (lib)
> > b) as shared lib (lib + so)

II. Core features
  1. GAPI is OpenGl 3.3 and above
  1. Support compilers (gcc 4.4, cl (msvc compiler)

III. Library depended
  1. [zlib](http://zlib.net/)
  1. libpng
  1. libjpeg
  1. freetype
  1. libogg
  1. libvorbis
  1. libtheora
  1. bullet physics

IV. Current futeres:
  1. Fast Render static geometry (packed vertex for big mesh-es for best memory latency)
  1. Fast Render volume lines (fake and real)
  1. Fast Render point sprites (fake and real)
  1. Fast text output
  1. Lightmaps for static geometry
  1. Compressed textures
  1. Rendertargets (with MRT)
  1. HDR Textures
  1. bmp, jpg, png, dds, pcx, tga image formats supported to load from file
  1. html logging with shaders compile errors source highlighting
  1. multisampling (win32)
  1. scene hierarchy
  1. frustum culling
  1. geometry shaders

V. June TODO list
  1. theora vide playing
  1. openal sound subsystem
  1. create conext on exists window
  1. vorbis sound playing
  1. vorbis stream playing
  1. freetype unicode text output
  1. easy posteffects

![http://axelynx.googlecode.com/files/deffered_shading.png](http://axelynx.googlecode.com/files/deffered_shading.png)
![http://axelynx.googlecode.com/files/dof.png](http://axelynx.googlecode.com/files/dof.png)
![http://axelynx.googlecode.com/files/MoutionBlur_Release%202011-06-02%2022-25-23-66.jpg](http://axelynx.googlecode.com/files/MoutionBlur_Release%202011-06-02%2022-25-23-66.jpg)
![http://axelynx.googlecode.com/files/hc_hdr_rtt.jpg](http://axelynx.googlecode.com/files/hc_hdr_rtt.jpg)