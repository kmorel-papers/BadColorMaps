cmake_minimum_required(VERSION 2.8.4)

project(BadColorMaps NONE)

include(UseLATEX.cmake)

set(images
  images/ColorMapExample.png
  )

add_latex_document(BadColorMaps.tex
  IMAGES ${images}
  )
