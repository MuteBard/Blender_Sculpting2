# DEV-04, Workflow: Dynamic Topology
### Tags: [Dyntopo, MeshFilter, Remesh, snakehook, draw, claystrips, smooth]
### Link: https://academy.cgboost.com/courses/mastering-sculpting-in-blender-2/lectures/26933745

## Getting a proper cylinder

![](../images/DEV-04/DEV-04-A1.png)

    This allows me to see each an every edge on the surface

![](../images/DEV-04/DEV-04-A2.png)

    The face types are very not useful for sculpting so I are going to remesh. Before I do so, I visually see the resolution I want
    By pressing Shift and R

![](../images/DEV-04/DEV-04-A3.png)

    Then select remesh with this resolution, or with Ctrl + R

![](../images/DEV-04/DEV-04-A4.png)

    Result

![](../images/DEV-04/DEV-04-A5.png)


## Working with Dynamic Topology

    Starting from numpad 7 I am pulling at the geometry, but the longer i pull at the geometry, the uglier it gets.
    This is because we are only working with the existing geometry. I am pulling at what we have and at some point this will be stretched

![](../images/DEV-04/DEV-04-B2.png)

![](../images/DEV-04/DEV-04-B1.png)

    Thats why generating new geometry is great with dyntopo

![](../images/DEV-04/DEV-04-B3.png)

    Result

![](../images/DEV-04/DEV-04-B4.png)

![](../images/DEV-04/DEV-04-B5.png)


## Sculpt tools

    Although I am using the Snake tool here and it is working really well with adding new geometry, not all sculpt tools work effectively alongside Dynamic Topology.

![](../images/DEV-04/DEV-04-B6.png)

![](../images/DEV-04/DEV-04-B7.png)

## Front Faces Only

    This will make sure that you are only sculpting on the faces you actively see and working on

![](../images/DEV-04/DEV-04-C1.png)

## Mass Smoothing with Mesh Filter

![](../images/DEV-04/DEV-04-D1.png)

![](../images/DEV-04/DEV-04-D2.png)

## Tree

![](../images/DEV-04/DEV-04-E1.png)
