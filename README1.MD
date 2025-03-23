local function sendNotification(title, text, duration)
    pcall(function()
        game.StarterGui:SetCore("SendNotification", {
            Title = title,
            Text = text,
            Duration = duration or 4
        })
    end)
end
sendNotification("NovaX Attached!", "Ty For Using NovaX!", 5)
