# UnicornDialer

Easily create your own floating action button list

![alt text](https://github.com/tiagojencmartins/unicornspeeddial/blob/master/vertical.gif?raw=true)

![alt text](https://github.com/tiagojencmartins/unicornspeeddial/blob/master/horizontal.gif?raw=true)


## Installing

Add UnicornDialer to your **pubspec.yaml**

```
unicorndialer: "^1.0.1"
```

## Options ##

**UnicornDialer class**

`int orientation` - **Vertical or horizontal floating button list**

 `bool rotateMain` - **Animate your main floating button icon**

` Icon parentButton` - **The main floating button icon**

` parentButtonBackground` - **The main floating button background color**

 `List<UnicornButton> childButtons` **Floating button list**

 `int animationDuration` **Rotation and expanding animation duration (in milliseconds)**

 `double childPadding` - **Right padding on the button label**

 `Function onMainButtonPressed` - **To be called if set on the UnicornDialer parent widget**

 **UnicornButton class**

 `Chip label` - **Creates a label for the current floating button**

 `FloatingActionButton currentButton` - **Floating list button **


 ## Example ##



## Authors

* **Tiago Martins **


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
