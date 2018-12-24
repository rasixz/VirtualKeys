# Virtual Keys

This is a simple Project wich contains almost all Default keys in hexadecimal format.

The keys are all copied from [the offical virtual key code list from the Microsoft docs](https://docs.microsoft.com/en-us/windows/desktop/inputdev/virtual-key-codes).

## Usage

To use it you have to add the Keys.hpp to your project.  
After adding it to your project, you can use

```cpp
    Input::K_A //keycode from a
    Input::Mouse::K_LBUTTON //keycode from Left Mousebutton
```

Just use the namespace Input for all keyboard keys and Input::Mouse for Mousebuttons. Or you could use `using namesapce Input` to just use `K_A` or `Mouse::K_LBUTTON`.