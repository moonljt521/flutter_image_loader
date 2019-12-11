# imagegrideloader

A new Flutter package project.

## Getting Started

This project is a starting point for a Dart
[package](https://flutter.dev/developing-packages/),
a library module containing code that can be shared easily across
multiple Flutter or Dart projects.

For help getting started with Flutter, view our 
[online documentation](https://flutter.dev/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.

# imageloader
  依赖于 [flutter_cached_network_image](https://github.com/renefloor/flutter_cached_network_image)，做了修饰，便于配置圆角等
  

## How to use
```
  GlideWidget(
          width: 65,
          height: 65,
          clipOval: true,
          placeIcon: "images/avatar_default_icon.webp",
          errorIcon: "images/avatar_default_icon.webp",
          imageUrl: widget._itemData.avatar),
```