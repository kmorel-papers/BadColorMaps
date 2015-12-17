cmake_minimum_required(VERSION 2.8.4)

project(BadColorMaps NONE)

include(UseLATEX.cmake)

set(images
  images/ColorMapExample.png
  images/RainbowBar.png
  images/pres-log-legend-0042.png
  images/ColorBrewer.png
  images/CheckerShadowIllusion.png
  ipython/CoolWarmMap.pdf
  ipython/CoolWarmLabMap.pdf
  ipython/BlackBodyMap.pdf
  ipython/BlackBodyExtendedMap.pdf
  ipython/KindlmannMap.pdf
  ipython/CoolWarmExtended.pdf
  ipython/BlueOrangeExtended.pdf
  ipython/BlueGreenExtended.pdf
  )

add_latex_document(BadColorMaps.tex
  IMAGES ${images}
  BIBFILES BadColorMaps.bib
  )
