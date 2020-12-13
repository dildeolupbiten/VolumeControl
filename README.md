# VolumeControl

VolumeControl is a mix of canvas objects that is aimed to be used as an alternative for Tkinter Scale widget.
## How to use
```python
import tkinter as tk

from volume_control import VolumeControl

root = tk.Tk()
canvas = tk.Canvas(master=root)
canvas.pack()
widget = VolumeControl(
    master=canvas,
    x=100,
    y=100,
    start=0,
    end=100,
    radius=50,
    distance=40,
    length=5,
    width=4,
    color_gradient={"from": "red", "to": "pink"}
)

root.mainloop()

# Alternative color gradients:

# {"from": "red", "to": "yellow"}
# {"from": "pink", "to": "red"}
# {"from": "pink", "to": "blue"}
# {"from": "yellow", "to": "red"}
# {"from": "yellow", "to": "green"}
# {"from": "green", "to": "yellow"}
# {"from": "green", "to": "cyan"}
# {"from": "cyan", "to": "green"}
# {"from": "cyan", "to": "blue"}
# {"from": "blue", "to": "pink"}
# {"from": "blue", "to": "cyan"}
```    
# Animated Pictures

**From blue to cyan**

![from_blue_to_cyan](https://user-images.githubusercontent.com/29302909/100809987-7b8c1600-3448-11eb-9be2-a8c1472b778d.gif)

**From blue to pink**

![from_blue_to_pink](https://user-images.githubusercontent.com/29302909/100809992-8050ca00-3448-11eb-87d9-1cfc47d47b9d.gif)

**From cyan to blue**

![from_cyan_to_blue](https://user-images.githubusercontent.com/29302909/100810002-8646ab00-3448-11eb-8c0a-fa0810f25f43.gif)

**From cyan to green**

![from_cyan_to_green](https://user-images.githubusercontent.com/29302909/100810009-89da3200-3448-11eb-95a8-12f9e5e447a3.gif)

**From green to cyan**

![from_green_to_cyan](https://user-images.githubusercontent.com/29302909/100810027-8cd52280-3448-11eb-8100-df0fa06cff36.gif)

**From green to yellow**

![from_green_to_yellow](https://user-images.githubusercontent.com/29302909/100810037-93639a00-3448-11eb-9bbd-b79f358d9537.gif)

**From pink to blue**

![from_pink_to_blue](https://user-images.githubusercontent.com/29302909/100810049-98c0e480-3448-11eb-8cd9-10eb27f1b8a6.gif)

**From pink to red**

![from_pink_to_red](https://user-images.githubusercontent.com/29302909/100810053-9fe7f280-3448-11eb-91b4-52787b10bad5.gif)

**From red to pink**

![from_red_to_pink](https://user-images.githubusercontent.com/29302909/100810068-a8d8c400-3448-11eb-9ae8-7faab99ecb7d.gif)

**From red to yellow**

![from_red_to_yellow](https://user-images.githubusercontent.com/29302909/100810086-af673b80-3448-11eb-99f5-6da82d398d02.gif)

**From yellow to green**

![from_yellow_to_green](https://user-images.githubusercontent.com/29302909/100810095-b4c48600-3448-11eb-8b14-54f34ae4e596.gif)

**From yellow to red**
![from_yellow_to_red](https://user-images.githubusercontent.com/29302909/100810098-b68e4980-3448-11eb-8939-84e8dd5bf434.gif)
    
