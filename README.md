loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/GameList.lua"))()
for PlaceID, Execute in pairs(Games) do
 if PlaceID == game.PlaceId then
        loadstring(game:HttpGet(Execute))()
 end
end









- ⚡ Fun fact: ...

<!---
leemh7893/leemh7893 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
