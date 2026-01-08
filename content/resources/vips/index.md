---
date: 2025-02-08T18:52:09-03:00
title: VIPS - What if VIP had a child with Redux
series: ['Pilars, Principles, Patterns']
series_order: 3
tags: ['Architectural Patterns', 'VIP', 'VIPS', 'Clean Architecture', 'Resources', 'Guides']
---

## Description

A comprehensive diagram on how the VIPS (Clean) architecture works and why you might be using it wrong.

![diagram preview](preview.jpg)

> The image above is just a preview of the full diagram.

- It might be an overkill for your TODOs app (overengineering);
- The `Assembler`, aka _Dependency Injector_, could be just a static method in your View, or be part of a Factory or Builder (design patterns) of your app features;
- The original **VIP** arch do not have the **Store** component. It was added to work with **Reactive** frameworks such as SwiftUI;
- **Main Take**: All the data (user input, files, requests, etc.) flows in one direction. Do not fight the _reactiveness_ of your framework;

## Download
Donwload the full diagram on the following link: [PDF](vips.pdf)
