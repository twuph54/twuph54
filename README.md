local OrionLib = loadstring(game:HttpGet('https://raw.githubusercontent.com/shlexware/Orion/main/source'))()

local Window=OrionLib:makework（{Name=“cd_FBI脚本”，HidePremium=false，SaveConfig=true，IntroText=“com”cd_FBI“com”，ConfigFolder=“cd_FBI”）

local Tab =Window:MakeTab({
Name=“玩家”，
Icon = "rbxassetid://323627983",
PremiumOnly = false
})

Tab:AddTextbox({
Name=“移动速度”，
Default = "",
TextDisappear = true,
回调=函数（值）
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = Value
结束
})

Tab:AddTextbox({
Name=“跳跃高度”，
Default = "",
TextDisappear = true,
回调=函数（值）
game.Players.LocalPlayer.Character.Humanoid.JumpPower = Value
结束
})
