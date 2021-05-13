# OOP-6-Dynamic
An esoteric attempt to run Framework dynamically in iOS simulator app as plugin

This project shows how to using Darwin functions use dynamic linking of Framework.
- Build Shapes using your Swift compiler version for iOS Simulator.
- Delete old  Shapes from both Trapezium and OOP projects, add your compiled version. In project target choose Embed without signing.
- Compile Trapezium and put it in DynamicFramework folder
- Update path of dynamic library in last method in file OOP/Controller/MainViewController.swift
- Run
- Tap + to add Trapezium "plugin"
