---
layout: post
title:  "Windows Remote Desktop RCE"
date:   2025-07-31
tags: windows, binary exploitation
author: Jarno
---

 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent id condimentum nisl. Cras malesuada sem vitae erat rhoncus, non sodales enim viverra. In vitae urna tristique, tristique velit id, gravida lacus. Interdum et malesuada fames ac ante ipsum primis in faucibus. Mauris sit amet arcu vitae diam lacinia finibus in sed tortor. Cras libero eros, commodo vel feugiat eu, porta ac justo. Cras MessageBoxA posuere neque, non egestas orci feugiat vel. 

  Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Sed neque dolor, maximus et tempor id, bibendum eget metus. Morbi accumsan mi tortor, tristique volutpat purus lobortis elementum. Vestibulum erat justo, tristique vitae maximus ut, iaculis in eros. Vivamus ac nisi eleifend, accumsan sem et, ultrices justo. Pellentesque non massa in mauris molestie pellentesque. Curabitur `Windows.h` eros et diam varius, sed tristique erat finibus. Aenean interdum metus leo, et consequat lacus interdum a. Etiam malesuada id tellus scelerisque fringilla. Fusce volutpat dapibus `MessageBoxA` eu bibendum. 

{% highlight cpp %}
int MessageBoxA(
  HWND   hWnd,      // handle to owner window (can be NULL)
  LPCSTR lpText,    // message to display
  LPCSTR lpCaption, // title of the message box
  UINT   uType      // style of the message box
);
{% endhighlight %}


Lorem ipsum dolor sit amet, consectetur adipiscing elit. [Windows API docs][winuser-docs]  Nulla eget molestie ipsum, tincidunt ultricies justo. Nam non tortor eget nisl commodo vulputate vel sed mauris. Nam condimentum sem at tempus varius.

[winuser-docs]: https://learn.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-messageboxa
