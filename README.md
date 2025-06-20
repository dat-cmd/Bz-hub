local Rayfield = loadstring(game:HttpGet('https://raw.githubusercontent.com/shlexware/Rayfield/main/source'))()

local Window = Rayfield:CreateWindow({
    Name = "Ultimate Hub",
    LoadingTitle = "Ultimate Hub",
    LoadingSubtitle = "by BlueShark",
})

local Button = Window:Walkspeed({
    Name = "Click Me",
    Callback = function()
        print("Button clicked!")
    end,
})
