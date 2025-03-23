local function sendNotification(title, text, duration)
    pcall(function()
        game.StarterGui:SetCore("SendNotification", {
            Title = title,
            Text = text,
            Duration = duration or 4
        })
    end)
end
sendNotification("NovaX Attached With Cloudy API!", "Ty For Using NovaX! discord.gg/FWZVSRsn8C", 5)
