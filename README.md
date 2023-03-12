game.StarterGui:SetCore("SendNotification", {

    Title = "Prison Life Revenger V1";

    Text = "Made By Azoitr72"; -- what the text says (ofc)

    Duration = 5;

})

wait(1)

game.StarterGui:SetCore("SendNotification", {

    Title = "Executed!";

    Text = "Subscribe To Azoitr72!"; -- what the text says (ofc)

    Duration = 5;

})

local kavoUi = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()

local window = kavoUi.CreateLib("Prison Life Revenger Mobile Version (PRIVATE BETA))","Ocean")

---MAIN

local Tab1 = window:NewTab("Main")

local Tab1Section = Tab1:NewSection("Guis")

Tab1Section:NewButton("Prison Life Admin", "Gives you admin", function()    loadstring(game:HttpGet('https://pastebin.com/raw/iZ64yzjE'))();

end)

Tab1Section:NewButton("Prison Ware v1.3 (PATCHED)", "Adds prision ware v1.3 (PATCHED)", function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/Denverrz/scripts/master/PRISONWARE_v1.3.txt"))()

end)

Tab1Section:NewButton("Prevail X (WIP)", "Adds Prevail x (WIP)", function()

loadstring(game:HttpGet("https://pastebin.com/raw/mHfK0Xk4", true))()

end)

Tab1Section:NewToggle("Auto Kill All", "Auto Kill All!", function(state)

    if state then

        print("Toggle On")

    else

        print("Toggle Off")

    end

end)

Tab1Section:NewButton("Prison Life gui", "gui", function()

loadstring(game:HttpGet("https://pastebin.com/raw/LnAUPBXj",true))()

end)
