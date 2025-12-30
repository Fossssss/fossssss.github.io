---
series: ['Godot笔记']
series_order: 1
title: 'Godot笔记1:Node与Scene'
date: 2025-12-29
featureimage: "featured.png"
---

## Node

一个 Godot 游戏是一个由场景(scene)组成的树，而场景又是又一个由节点组成的数(node)

> a Godot game is a tree of scenes and that each scene is a tree of nodes

node 是构成游戏的基本模块，node 有很多种类，他们可以帮助你显示图片，播放音乐，作为相机。

所有的 node 都有下列特性：

- 名字
- 可编辑的属性
- 他们会在每一帧接收回调，进行更新(They receive callbacks to update every frame.)
- 你可以用新属性和函数来拓展他们
- 你可以让他们作为其他 node 的子节点

## Scence

当你组织一了一个节点树，比如一个角色，我们就称这个结构为一个场景。

> When you organize nodes in a tree, like our character, we call this construct a scene.

当你保存了这个场景，他在编辑器中就像一个新的节点类型，你可以把他作为其他节点的子节点。
