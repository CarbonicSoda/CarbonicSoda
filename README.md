local Me = setmetatable({},{
    __index = {IsFriend = true}
}

Me.Name = "W. David"
Me.Age = 15
Me.Location = "McDonald's"
Me.Case = "PascalCase"
Me.FavLangSyntax = "Lua"
Me.Prev = {"GameDev", "WebDev"}
Me.Curr = "AppDev"

table.freeze(Me)
return Me
