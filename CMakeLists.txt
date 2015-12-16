cmake_minimum_required(VERSION 2.8.4)

project(BadColorMaps NONE)

include(UseLATEX.cmake)

set(images
  images/ColorMapExample.png
  images/pres-log-legend-0042.png
  images/ColorBrewer.png
  images/CheckerShadowIllusion.png
  ipython/BlackBodyMap.pdf
  ipython/KindlmannMap.pdf
  )

add_latex_document(BadColorMaps.tex
  IMAGES ${images}
  BIBFILES BadColorMaps.bib
  )
