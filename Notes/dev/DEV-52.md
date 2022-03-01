# DEV-52, Clay Shader - Bump Map
### Tags: [bump maps, nodes, website]
### Link: https://academy.cgboost.com/courses/master-3d-sculpting-in-blender/lectures/33782398


## Adding in our Voronoi texture

    Shift A > Textures > Voronoi

![](../images/DEV-52/DEV-52-A1.png)

    Shift A > Input > Texture Coordinate

    By having our own texture coordinate instead of the built in one,
    we are able to be independence of scaling of the model for our voronoi texture after applying our changes.

![](../images/DEV-52/DEV-52-A2.png)

## Adding in our Bump node

    Shift A > Vector > Bump

![](../images/DEV-52/DEV-52-B1.png)

## Adding in our Multiply Node to have more control over the strength

    Shift A > Converter > Math
    Add > Multiply
    To manage the strength

![](../images/DEV-52/DEV-52-C1.png)

## Handy controls

![](../images/DEV-52/DEV-52-D1.png)

![](../images/DEV-52/DEV-52-D2.png)

## Website for textures

<https://www.cgbookcase.com/>

![](../images/DEV-52/DEV-52-E1.png)

![](../images/DEV-52/DEV-52-E2.png)

    Shift A > Texture > Image Texture

![](../images/DEV-52/DEV-52-E3.png)

  CTRL + SHIFT + LEFT CLICK

  This is one of the features of the addon, to see a preview immediately of the thing you are working on

![](../images/DEV-52/DEV-52-E4.png)

  Whenever you have a texture where the color is to be disregarded, use non-color

![](../images/DEV-52/DEV-52-E5.png)

  CTRL + T

  The Mapping node you can change the position, rotation and the scale of the texture

![](../images/DEV-52/DEV-52-E6.png)

  Wiring up our new nodes

![](../images/DEV-52/DEV-52-E7.png)

  Change the scaling to .15

![](../images/DEV-52/DEV-52-E8.png)

  Shift A > Color > Invert
  Invert the finger prints

![](../images/DEV-52/DEV-52-E9.png)

  Shift A > Converter > Math
  Add > Multiply
  To manage the strength

  If you a duplicating something inside a nod box label thing, press Ctrl P

![](../images/DEV-52/DEV-52-E10.png)

![](../images/DEV-52/DEV-52-E11.png)S

## Adding all of them together

  Shift A > Color > MixRgb
  MixRgb > Screen

![](../images/DEV-52/DEV-52-F1.png)
