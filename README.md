warn('by DinosaurXXX#8305, version 3.3')

loadstring(game:HttpGet("https://paste.ee/r/eiEOz"))()
wait(0.2)
Qver = '2.1'
game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{
	Text = "Welcome to DinoHub v3!",
	Color = Color3.new(75, 0, 130)
})
wait()
Qver = '2.1'
game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{
	Text = "Thanks for using my hub, enjoy!",
	Color = Color3.new(75, 0, 130)
})
wait()
game.StarterGui:SetCore("SendNotification", {
   Title = "Dev Notes:";
   Text = "If your animation nobody sees, use folder 'FE BYPASSES' and find FE Bypass Animation R6 or R15."; 
   Icon = "rbxassetid://2541869220";
   Duration = 10000;
   Callback = animsbindable;
   Button1 = "OK!";
})

local Material = loadstring(game:HttpGet("https://pastebin.com/raw/xNJMHZUS"))()

local FE = Material.Load({
	Title = "DinoHub v3 by DinosaurXXX#8305",
	Style = 3,
	SizeX = 500,
	SizeY = 350,
	Theme = "Light",
	ColorOverrides = {
		MainFrame = Color3.fromRGB(255,215,0)
	}
})

local Tit1 = FE.New({
	Title = "FE Bypasses"
})

local Tit2 = FE.New({
	Title = "FE Dances"
})

local Tit3 = FE.New({
	Title = "FE Fighter's"
})

local Tit4 = FE.New({
	Title = "FE Other"
})

local Tit5 = FE.New({
	Title = "FE Animations"
})

local Tit6 = FE.New({
	Title = "Credits"
})

local BypassAnimR6 = Tit1.Button({
	Text = "FE Bypass Animation R6",
	Callback = function()
		loadstring(game:HttpGet("https://pastebin.com/raw/c07yTPG2"))()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "if no one sees your animation, use this script. ONLY R6."
			})
		end
	}
})

local BypassAnimR15 = Tit1.Button({
	Text = "FE Bypass Animation R15",
	Callback = function()
		loadstring(game:HttpGet("https://pastebin.com/raw/uWZDcyEB"))()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "it loads to R6, when your in R15 game. Also if no one sees your animation, use this script."
			})
		end
	}
})

local BypassR15R15 = Tit1.Button({
	Text = "FE Bypass R15 to R6 R15",
	Callback = function()
		loadstring(game:HttpGet("https://paste.ee/r/RYqM3"))()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "it creates a clone and loads to R6, when your in R15 game, also clone nobody sees."
			})
		end
	}
})

local ReAnimR6 = Tit1.Button({
	Text = "FE ReAnimation R6",
	Callback = function()
		loadstring(game:GetObjects("rbxassetid://4480871791")[1].Source)()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "You can use it, if your animation broken."
			})
		end
	}
})

local OPReAnimR6 = Tit1.Button({
	Text = "FE OP ReAnimation R6 And R15",
	Callback = function()
		loadstring(game:HttpGet("https://paste.ee/r/MD2Ws"))()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "You can use it for other script for working, like Flaming Umbrella, also if animation not will work or your character frozen, try use network bypass, simulation radius or net bypass."
			})
		end
	}
})

local MiztReAnimR6 = Tit1.Button({
	Text = "FE Mizt's ReAnimation R6 And R15",
	Callback = function()
		loadstring(game:HttpGet("https://pastebin.com/raw/m9tTGE8i",true))() --Mizt's Reanimaton works on R15 and R6.
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "It good one reanimation, created by Mizt."
			})
		end
	}
})

local RefreshR6 = Tit1.Button({
	Text = "FE Refresh Character R6",
	Callback = function()
		local mod = Instance.new('Model', workspace) mod.Name = 're '..game.Players.LocalPlayer.Name
		local hum = Instance.new('Humanoid', mod)
		local ins = Instance.new('Part', mod) ins.Name = 'Torso' ins.CanCollide = false ins.Transparency = 1
		game.Players.LocalPlayer.Character = mod
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "You can use it, when using dog or other, but it so buggy."
			})
		end
	}
})

local RespawncharR6 = Tit1.Button({
	Text = "FE Respawn Character R6 And R15",
	Callback = function()
		game.Players.localPlayer.Character:Destroy()
		game.Players.localPlayer.Character.Head:Destroy()
		game.Players.localPlayer.Character.Torso:Destroy()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "You can use it, when using dog or other, but it so buggy."
			})
		end
	}
})

local OPRespawncharR6 = Tit1.Button({
	Text = "FE OP Respawn Character R6 And R15",
	Callback = function()
		game:GetService("Players").LocalPlayer.Character.Humanoid:Destroy()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "You can use it, when using dog or other, but it so buggy."
			})
		end
	}
})

local AnotherRespawncharR6 = Tit1.Button({
	Text = "FE Another Respawn Character R6 And R15",
	Callback = function()
		plr = game.Players.LocalPlayer

if invisRunning then TurnVisible() end
	local char = plr.Character
	if char:FindFirstChildOfClass("Humanoid") then char:FindFirstChildOfClass("Humanoid"):ChangeState(15) end
	char:ClearAllChildren()
	local newChar = Instance.new("Model",workspace)
	plr.Character = newChar
	wait()
	plr.Character = char
	newChar:Destroy()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "You can use it, when using dog or other, but it so buggy."
			})
		end
	}
})

local RejoinR6 = Tit1.Button({
	Text = "FE Rejoin R6 And R15",
	Callback = function()
		game:GetService("TeleportService"):Teleport(game.PlaceId, game.Players.LocalPlayer)
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "If your character buggy, you can use it to rejoin to same server."
			})
		end
	}
})

local ARejoinR6 = Tit1.Button({
	Text = "FE Another Rejoin R6 And R15",
	Callback = function()
		local plr = game.Players.LocalPlayer

game:GetService("TeleportService"):TeleportToPlaceInstance(game.PlaceId, game.JobId, plr)
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "If your character buggy, you can use it to rejoin to same server."
			})
		end
	}
})

local NetworkR6 = Tit1.Button({
	Text = "FE Network Ownership Bypass R6 And R15",
	Callback = function()
		game["Run Service"].RenderStepped:connect(function()
   settings().Physics.AllowSleep = false
   setsimulationradius(math.huge*math.huge,math.huge*math.huge)
end)

print("Loaded Network Ownership Bypass!")
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "If scripts not work, try use it."
			})
		end
	}
})

local NetBypassR6 = Tit1.Button({
	Text = "FE Net Bypass R6 And R15",
	Callback = function()
		loadstring(game:HttpGet("https://paste.ee/r/E8tES"))()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "It bypassing net."
			})
		end
	}
})

local SimulationR6 = Tit1.Button({
	Text = "FE Simulation Radius Infinite R6 And R15",
	Callback = function()
		setsimulationradius(math.huge, math.huge)
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "If scripts not work, try use it."
			})
		end
	}
})

local NullwareR6 = Tit1.Button({
	Text = "FE Nullware Reanimate R6",
	Callback = function()
		--[[Options]]--
_G.CharacterBug = false --Set to true if your uppertorso floats when you use godmode with R15 To R6.
_G.GodMode = false --Set to true if you want godmode.
_G.R6 = false --Set to true if you wanna enable R15 to R6 when your R15.
--[[Reanimate]]--
loadstring(game:HttpGet("https://paste.ee/r/pt8Dx/0"))()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "If your animation nobody sees, try use it."
			})
		end
	}
})

local GodModeR6 = Tit1.Button({
	Text = "FE GodMode R6 And R15",
	Callback = function()
		--[[Options]]--
_G.CharacterBug = false --Set to true if your uppertorso floats when you use godmode with R15 To R6.
_G.GodMode = true --Set to true if you want godmode.
_G.R6 = true --Set to true if you wanna enable R15 to R6 when your R15.
--[[Reanimate]]--
loadstring(game:HttpGet("https://paste.ee/r/pt8Dx/0"))()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "Enables GodMode, u cant die now."
			})
		end
	}
})

local NullwareR15 = Tit1.Button({
	Text = "FE Nullware Reanimate R15",
	Callback = function()
		--[[Options]]--
_G.CharacterBug = false --Set to true if your uppertorso floats when you use godmode with R15 To R6.
_G.GodMode = false --Set to true if you want godmode.
_G.R6 = true --Set to true if you wanna enable R15 to R6 when your R15.
--[[Reanimate]]--
loadstring(game:HttpGet("https://paste.ee/r/pt8Dx/0"))()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "If your animation nobody sees, try use it, it also loads to R6, when your in R15."
			})
		end
	}
})

local R15Remake = Tit1.Button({
	Text = "FE R15 Remake Animation Bundle R15",
	Callback = function()
		loadstring(game:HttpGet("https://paste.ee/r/rWV2A"))()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "Remaking your animation to other."
			})
		end
	}
})

local R6VaporGun = Tit3.Button({
	Text = "FE VaporGun V3 R6",
	Callback = function()
		setclipboard("https://paste.ee/r/bRGlF")
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "Your character loads to VaporGun V3, if you not know how to use, then (Where saying item = char[''NAME OF YOUR HAT''] at 269 line, change in NAME OF YOUR HAT to your name of hat, not in catalog, in dex explorer/explorer or dark dex, you can use in my dinohub, it also copying the link to script)."
			})
		end
	}
})

local R6Scout = Tit3.Button({
	Text = "FE Scout R6",
	Callback = function()
		loadstring(game:HttpGet("https://paste.ee/r/4JSUi"))()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "Your character loads to Scout."
			})
		end
	}
})

local R6VoidEye = Tit3.Button({
	Text = "FE Void Eye R6",
	Callback = function()
		loadstring(game:HttpGet("https://paste.ee/r/lZQa5"))()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "Your character loads to Void Eye."
			})
		end
	}
})

local R6Abyss = Tit3.Button({
	Text = "FE Abyss R6",
	Callback = function()
		setclipboard("https://paste.ee/r/IKQVh")
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "Your character loads to Abyss, if you not know how to use, then (Where saying local ToolName = ''NAME OF YOUR HAT'' at 271 line, change in NAME OF YOUR HAT to your name of hat, not in catalog, in dark dex or something, you can find in my dinohub, also it copying to your clipboard)."
			})
		end
	}
})

local R6Chatbreaker = Tit4.Button({
	Text = "FE Chat Breaker R6 And R15",
	Callback = function()
		loadstring(game:HttpGet("https://paste.ee/r/3qTKX"))()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "Breaks chat."
			})
		end
	}
})

local R6ShibaHub = Tit4.Button({
	Text = "FE Shiba Hub R6 And R15",
	Callback = function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/rawget69420/Shiba/main/main.lua"))()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "It loads to shiba hub free version."
			})
		end
	}
})

local R6HeadSnaxp = Tit5.Button({
	Text = "FE Head Snaxp R6",
	Callback = function()
		loadstring(game:HttpGet("https://paste.ee/r/A2Z1y"))()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "Snaxping ur head."
			})
		end
	}
})

local YouTubeDino = Tit6.Button({
	Text = "Copy YouTube Dinosaur XxX",
	Callback = function()
		setclipboard("https://www.youtube.com/channel/UCHBxhQ_-wt-ZP3Exti78YGQ")
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "Dinosaur XxX"
			})
		end
	}
})

local DiscordDino = Tit6.Button({
	Text = "Copy Discord Dinosaur XxX",
	Callback = function()
		setclipboard("https://discord.com/invite/HGy6nwt")
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "DinosaurXXX#8305"
			})
		end
	}
})

local DeleteGUI = Tit6.Button({
	Text = "Delete GUI",
	Callback = function()
		game.CoreGui["DinoHub v3 by DinosaurXXX#8305"]:Destroy()
	end,
	Menu = {
		Information = function(self)
			FE.Banner({
				Text = "Deleting GUI"
			})
		end
	}
})
