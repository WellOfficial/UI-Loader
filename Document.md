# Update
```bash
  All Update this Show here.

  Add Functions
  + Label [ Can Refresh ]
  + Toggle [ Can Set Defualt]
  + Multidropdown [ Can Clear , Add ]
  + Dropdown [ Can Clear , Add ]
  + Button [  ]
  + Slider [ Can Update ]
  + Color Picker [ Can Update ]
```
# Loadstring
```bash
  local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/WellOfficial/UI-Loader/main/Library"))()
```
# Create UI Window
```bash
  local Library = library:CreateWindow("Well UI Library",Enum.KeyCode.RightControl)
```
# Create Tab
```bash
  local Tab = WellHub:CreateTab("Tab")
```
# Create Section
```bash
  local Sector1 = Tab:CreateSector("Sector","left") --- ซ้าย
  local Sector1 = Tab:CreateSector("Sector","right") --- ขวา
```
# Create Label
```bash
  Sector1:AddLabel("Label")
```
# Create Toggle
```bash
    Sector1:AddToggle("Toggle",false,function(t)
       print(t)
    end)
```
# Create Multi Dropdown
```bash
    Sector1:AddDropdown("Multi Dropdown",{"None","IDK","odl2"},"None",true,function(t) --- ถ้า Multi = true
        print(t)
    end)
```
# Create Dropdown
```bash
    Sector1:AddDropdown("Multi Dropdown",{"None","IDK","odl2"},"None",false,function(t) --- ถ้า Dropdown = false
        print(t)
    end)
```
# Create Button
```bash
    Sector1:AddButton("Button",function()
        print("Well UI Library")
    end)
```
# Create Slider
```bash
    Sector1:AddSlider("Slider",20,50,100,1,function(x)
        print(x)
    end)
```
# Create Color Picker
```bash
    Sector1:AddColorpicker('Color picker',Color3.fromRGB(255, 255, 255),function(t)
        print(t)
    end)
```
