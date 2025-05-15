local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()
local Window = Rayfield:CreateWindow({
   Name = "🎩Juju Hub🎩 | 30+ Games | v4.0.5",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "Juju Hub is loading...",
   LoadingSubtitle = "v4.0.5",
   Theme = "AmberGlow", -- Check https://docs.sirius.menu/rayfield/configuration/themes

   DisableRayfieldPrompts = true,
   DisableBuildWarnings = true, -- Prevents Rayfield from warning when the script has a version mismatch with the interface

   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Big Hub"
   },

   Discord = {
      Enabled = true, -- Prompt the user to join your Discord server if their executor supports it
      Invite = "Q5MZxNDtWa", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },

   KeySystem = true, -- Set this to true to use our key system
   KeySettings = {
      Title = "Juju Hub | Key | v4.0.5",
      Subtitle = "Bypassed anticheat ☑️",
      Note = "Join Discord to get Key (.gg/Q5MZxNDtWa)", -- Use this to tell the user how to get a key
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = false, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"23071806"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})
local Tab = Window:CreateTab("📜Welcome",104365492568677) -- Title, Image

local Paragraph = Tab:CreateParagraph({Title = "Welcome !", Content = "If you need any help join : https://discord.gg/Q5MZxNDtWa"})

local Paragraph = Tab:CreateParagraph({Title = "V4.0.5", Content = "Updated on 04/01/25"})

local Paragraph = Tab:CreateParagraph({Title = "More Updates", Content = "Juju Hub is updated weekly you can get latest version on the discord : https://discord.gg/Q5MZxNDtWa"})

local Button = Tab:CreateButton({
   Name = "Close UI",
   Callback = function()
   Rayfield:Destroy()
   end,
})

local Tab = Window:CreateTab("🎲Misc", 104365492568677) -- Title, Image

local Button = Tab:CreateButton({
   Name = "Infinite Yield",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Infinite-Yield_500"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Mobile Aimbot",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Aimbot-Universal-For-Mobile-and-PC-29153"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Stream Snipe",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Guest3D/ZirconHub/refs/heads/main/StreamSniper.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Aimbot",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
                loadstring(game:HttpGet("https://raw.githubusercontent.com/new-gugus/aimbot-neptune/refs/heads/main/aimbot.lua", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Shift Lock",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Mobile-Console-20843"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Freecam",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Freecam'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Keyboard (buttons)",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Mobile-Keyboard-Script-20056"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "AFEM Animations Gui",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-AFEM-14048"))()
   end,
})

local Tab = Window:CreateTab("🎮Games",104365492568677) -- Title, Image

local Button = Tab:CreateButton({
   Name = "Prison Life : PrizzLife",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet('https://raw.githubusercontent.com/elliexmln/PrizzLife/main/pladmin.lua'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Basically FNF : OP Autoplayer",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-basically-FNF-Remix-op-autoplayer-Script-8840"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Basically FNF : Autoplayer Lite",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Basically-FNF:-Remix-AutoPlayer-Lite-9989"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Combat Warriors : Infernium",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/PARRY-V1-Combat-Warriors-Infernium-Hub-Premium-Script-32313"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Doors : Lolhax",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Robloxexploiterz/Release-Lolhax/refs/heads/main/LX%20Doors%20v3.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Murder VS Sheriff Duels : Lx39 (Broke The Hub)",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Murder-vs-sheriff-by-Lx39-17130"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "M.E.G Endless Reality : MegMenu (Broke The Hub)",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/UPDATE-M.E.G.-Endless-Reality-MegMenu-32222"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "GRANNY : Haps (destroy the Hub)",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Granny-Haps-cheat-29970"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Blade Ball : SGC",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Avorrietz/Ghostobfuscate/refs/heads/main/SGC"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "War Tycoon : PastesWares",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Gripen-War-Tycoon-Pastee-29925"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "War Tycoon : Zendex",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/MANGUSTA-War-Tycoon-Zendex-32181"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Brookhaven : Chaos Hub (Need Key, Prenium)",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun ! Join the discord to bypass key",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-Chaos-Hub-V2-33387"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Brookhaven : Darkbones",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Brookhaven-30409"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Granny Multiplayer : Zephyr Gab Edition",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Granny:-Gab-Edition-Retro-Zephyr-Gr4nny-G4b-Ed1tion-31372"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Dead Rails : Lunor",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet('https://raw.githubusercontent.com/Catto-YFCN/Lunor_Dependencies/refs/heads/main/Loader'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Fisch : Speed Hub X",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Blox Fruits : Fruit Finder",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Dev-BlueX/BlueX-Hub/refs/heads/main/FindFruits.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "War Tycoon : Facility Hub",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun ! Join the discord to bypass key",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/FacilityHUB/FacilityHub/refs/heads/main/WarTycoons"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Murder Mystery 2 : Overdrive H",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun ! Join the discord to bypass key",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://api.overdrivehub.xyz/v1/auth"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Legends Of Speed : Proxima",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Legends-Of-Speed-Script-(Proxima-Hub)-2861"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Ninja Legends : Proxima",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Ninja-Legends-Ninja-Script-3113"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Big Paintball : TpKill",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Big-Paintball-Auto-Farm-Kill-All_340"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Fling Things and people : RuHub",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Fling-Things-and-People-RuHub-OP-FTAP-Script-35067"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Superbox Siege Defense : Autofarm V3",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun ! Join the discord to bypass key",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/QuorumHub1/QuorumHub/refs/heads/main/SbsdAutofarmV3.txt"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Piggy",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/StarHackScripts/StarHack-Hub-Deepstar-Hub/refs/heads/main/StarHack%20Hub%20-%20Piggy%20Pro%20Hub.txt"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "RIVALS : Duckhub",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/RIVALS-Best-Script-Duck-Hub-29813"))()
   end,
})

local Tab = Window:CreateTab("Credits", 104365492568677) -- Title, Image

local Paragraph = Tab:CreateParagraph({Title = "Creator", Content = "JujuOfficiel"})

local Paragraph = Tab:CreateParagraph({Title = "Helper", Content = "hb2obsk"})

local Paragraph = Tab:CreateParagraph({Title = "Supporter", Content = "secretmodedajyo"})
