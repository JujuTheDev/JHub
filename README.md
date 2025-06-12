local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()
local Window = Rayfield:CreateWindow({
   Name = "Important Warning",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "Juju Hub is loading...",
   LoadingSubtitle = "v4.1.8",
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
      RememberJoins = false -- Set this to false to make them join the discord every time they load it up
   },

   KeySystem = false, -- Set this to true to use our key system
   KeySettings = {
      Title = "Juju Hub | Whitelist | v4.1.8",
      Subtitle = "Whitelist is permanent",
      Note = "Join Discord to get the Whitelist Key (.gg/Q5MZxNDtWa)", -- Use this to tell the user how to get a key
      FileName = "JujuHubWhitelist", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"23071806"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})
local Tab = Window:CreateTab("Please Read",104365492568677) -- Title, Image

local Paragraph = Tab:CreateParagraph({Title = "Message,", Content = "Juju Hub was developed with passion, but exploiting is bad and unfair to others players.. I decided to delete the entire code of original Juju Hub, starting exploits made me happy but now i lost good friends and more... Do not exploit. Be better. PLEASE READ: your account is in danger, roblox anticheat flagged you, you will get banned in few hours, here a list of possible ban : Warn > 1Day ban > 3Days Ban > 1week ban > 6months ban > perm ban"})
