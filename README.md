 if game:GetService("CoreGui"):FindFirstChild("Library") then
      game:GetService("CoreGui"):FindFirstChild("Library"):Destroy()
  end
local VLib = loadstring(game:HttpGet("https://pastebin.com/raw/L7c0x6mW"))()
MAINTTL = "TU HUB" 
local win = VLib:Window("", Color3.fromRGB(196, 40, 28))
local Main = win:Tab("Main")
Main:Button("Destroy Gui",function()
game.CoreGui["Library"]:Destroy()
end)

Main:Dropdown("Dropdown",{"1","2","3"},function(Start)
end)

Main:Toggle("_G.FastAttack = true" = true(Start)
end)

Main:Slider("Slider",0,100,16,function(t)

end)
local cred = win:Tab("Misc")
cred:Button("Copy Discord Server",function()
setclipboard("https://discord.gg/dY8rpSktyn")
end)
cred:Label("MADE BY : 03s.#4358")
