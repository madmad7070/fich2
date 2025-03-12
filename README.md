local Games = loadstring(game:HttpGet("https://raw.githubusercontent.com/madmad7070/fish/refs/heads/main/README.md"))()

for PlaceID, Execute in pairs(Games) do
    if PlaceID == game.PlaceId then
        loadstring(game:HttpGet(Execute))()
    end
end
