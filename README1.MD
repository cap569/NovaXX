local function sendNotification(title, text, duration)
    pcall(function()
        game.StarterGui:SetCore("SendNotification", {
            Title = title,
            Text = text,
            Duration = duration or 4
        })
    end)
end
sendNotification("NovaX V2 Attached With Velocity API!", "Ty For Using NovaX V2!", 5)
