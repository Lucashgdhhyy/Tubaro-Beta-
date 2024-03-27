local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Tubaro V1.0", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
local Tab = Window:MakeTab({
	Name = "Credits",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

OrionLib:MakeNotification({
	Name = "Tubaro",
	Content = "Thank you for use my script again ..player.user",
	Image = "rbxassetid://4483345998",
	Time = 5
})

local Section = Tab:AddSection({
	Name = "Creators"
})

Tab:AddParagraph("Creator","Bacon,rip_kata")

local Section = Tab:AddSection({
	Name = "Beta Testers"
})

Tab:AddParagraph("Beta Testers","Vamp")

local Tab = Window:MakeTab({
	Name = "Blox Fruit",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "No Key"
})

Tab:AddParagraph("Comming Soon","in update 1.3")

local Section = Tab:AddSection({
	Name = "Key"
})


local Tab = Window:MakeTab({
	Name = "Blade Ball",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "No Key"
})

Tab:AddButton({
	Name = "Inferno Hub",
	Callback = function()
      		print("button pressed")               loadstring(game:HttpGet("https://github.com/SadlekAski/Scripts/raw/main/Blade%20Ball/Equip%20any%20ability.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Red Circle",
	Callback = function()
      		print("button pressed")                    getgenv().visualizer = true
loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/main/RedCircleBlock"))()
  	end    
})

Tab:AddButton({
	Name = "Bedol Hub",
	Callback = function()
      		print("button pressed")      loadstring(game:HttpGet("https://raw.githubusercontent.com/3345-c-a-t-s-u-s/-beta-/main/AutoParry.lua"))()
  	end    
})

local Section = Tab:AddSection({
	Name = "Key"
})
