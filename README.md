local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

local Window = Library.CreateLib("DEVOWNER#5866", "Midnight")

local dragging = true

local FarmTab = Window:NewTab("Farm")

local FarmSection = FarmTab:NewSection("Farm settings")

FarmSection:NewToggle("TRADE SCAM ", "TRADE SCAM", function(state)

    if state then

       local tp_table = {

            tp1 = Vector3.new(350, 100, -800),

            tp3 = Vector3.new(230000402.1016, 2800.942566, -836.438965, 1, 1.51065606e-07, 4.12622952e-14, -1.51065606e-07, 1, 6.02517289e-08, -3.21603299e-14, -6.0251789e-08, 1),

        }

        

        local tween_s = game:GetService('TweenService')

        local tweeninfo = TweenInfo.new(1,Enum.EasingStyle.Linear)

        

        local lp = game.Players.LocalPlayer

        

        function tween_tp(v)

            if lp.Character and 

            lp.Character:FindFirstChild('HumanoidRootPart') then

                local cf = CFrame.new(v)

                local a = tween_s:Create(lp.Character.HumanoidRootPart,tweeninfo,{CFrame=cf})

                a:Play()

                 a.Completed:Wait()

            end

        end

        

        tween_tp(tp_table.tp1)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

        tween_tp(tp_table.tp3)

wait(5)

    else

 print("toggled off f f")

end

end)

FarmSection:NewToggle("DUPE", "DUPE", function(state)

    if state then

       local tp_table = {

            tp4 = Vector3.new(180, 60, -128893.3),

            tp5 = Vector3.new(999999999999999999999999999999999999, 100, -1836.438965),

        }

        

        local tween_s = game:GetService('TweenService')

        local tweeninfo = TweenInfo.new(1,Enum.EasingStyle.Linear)

        

        local lp = game.Players.LocalPlayer

        

        function tween_tp(v)

            if lp.Character and 

            lp.Character:FindFirstChild('HumanoidRootPart') then

                local cf = CFrame.new(v)

                local a = tween_s:Create(lp.Character.HumanoidRootPart,tweeninfo,{CFrame=cf})

                a:Play()

                 a.Completed:Wait()

            end

        end

        

        tween_tp(tp_table.tp4)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

        tween_tp(tp_table.tp5)

wait(5)

else

print("toggled off f f")

end

end)

