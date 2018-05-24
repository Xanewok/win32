---
title: E
description: A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
Robots: noindex, nofollow
audience: developer
author: REDMOND\\markl
manager: REDMOND\\markl
ms.assetid: 'dd16e80f-dd1e-44dc-9638-8ab2d224e0eb'
ms.prod: 'windows-server-dev'
ms.technology: 'microsoft-management-console'
ms.tgt_platform: multiple
---

# E

[A](a-gly.md) [B](b-gly.md) [C](c-gly.md) [D](d-gly.md) E [F](f-gly.md) [G](g-gly.md) [H](h-gly.md) [I](i-gly.md) J K [L](l-gly.md) [M](m-gly.md) [N](n-gly.md) [O](o-gly.md) [P](p-gly.md) Q [R](r-gly.md) [S](s-gly.md) [T](t-gly.md) [U](u-gly.md) [V](v-gly.md) [W](w-gly.md) X Y Z

<dl> <dt>

<span id="mmc_enumerated_node_gly"></span><span id="MMC_ENUMERATED_NODE_GLY"></span>**enumerated node**
</dt> <dd>

Subtree of nodes under a [*static node*](s-gly.md#mmc-static-node-gly) in the [*console tree*](c-gly.md#mmc-console-tree-gly). When the user selects or expands the static node in the scope pane, the snap-in associated with the static node is notified and can insert enumerated nodes as children of that static node. An enumerated node can have enumerated child nodes of its own. When the user expands an enumerated node for the first time, the snap-in that inserted the enumerated node is notified and can insert the child nodes.

</dd> <dt>

<span id="mmc_exported_data_gly"></span><span id="MMC_EXPORTED_DATA_GLY"></span>**exported data**
</dt> <dd>

Snap-in data that is made available to other snap-ins. To export data, a snap-in must register its extendible [*node types*](n-gly.md#mmc-node-type-gly) and document their data formats so that other (extension) snap-ins will be able to interpret the snap-in's exported data. Documentation should include both the interface methods and the format of the data, including [*clipboard formats*](c-gly.md#mmc-clipboard-format-gly) that snap-ins must support to retrieve the data.

</dd> <dt>

<span id="mmc_extended_view_extension_gly"></span><span id="MMC_EXTENDED_VIEW_EXTENSION_GLY"></span>**Extended View extension**
</dt> <dd>

For MMC 2.0. [*View extension*](v-gly.md#mmc-view-extension-gly) provided by Microsoft as a means of adding user interface elements to an existing view, creating a new view, and using the [*automation object model*](a-gly.md#mmc-automation-object-model-gly).

</dd> <dt>

<span id="mmc_extension_snap_in_gly"></span><span id="MMC_EXTENSION_SNAP_IN_GLY"></span>**extension snap-in**
</dt> <dd>

Snap-in that adds functionality to a [*stand-alone snap-in*](s-gly.md#mmc-stand-alone-snap-in-gly) (or [*primary snap-in*](p-gly.md#mmc-primary-snap-in-gly)). Extension snap-ins can add their own scope items as children of a primary snap-in's scope item. They can also add context menu items, toolbar buttons, property pages, and taskpad tasks to extend the functionality of a primary snap-in. Also see [*dynamic extension*](d-gly.md#mmc-dynamic-extension-gly) and [*required extension*](r-gly.md#mmc-required-extension-gly).

</dd> </dl>

 

 



