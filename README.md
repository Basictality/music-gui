local screen = Instance.new("ScreenGui")
screen.Name = "Admin"
screen.Parent = game.Players.Basictality.PlayerGui

local z = Instance.new("TextBox")
z.Parent = screen
z.Name = "xd"
z.Text = "Music ID Here."
z.BackgroundTransparency=0.5
z.BackgroundColor3 = Color3.new(0,0,0)
z.Size = UDim2.new(0, 350,0, 50)
z.FontSize = Enum.FontSize.Size24
z.TextColor3 = Color3.new(1,0,0)
z.Position = UDim2.new(0, 1000,0, 0)

local b = Instance.new("TextButton")
b.Parent = screen
b.Name = "cool"
b.Text = "Execute"
b.BackgroundColor3 = Color3.new(255,255,255)
b.Size = UDim2.new(0, 350,0, 50)
b.FontSize = Enum.FontSize.Size24
b.Position = UDim2.new(0, 1000,0, 50)

function Click()
	Sound = z.Text
O = Instance.new("Sound",workspace)
O.SoundId = ("http://www.roblox.com/asset/?id="..Sound)
O.Pitch = 1
O.Name = "ss"
O.Volume = 1
O.Looped = true 
O:Play()

end

b.MouseButton1Click:connect(Click)

local h = Instance.new("TextButton")
h.Parent = screen
h.Name = "mum"
h.Text = "Remove Musics"
h.BackgroundTransparency=0.5
h.BackgroundColor3 = Color3.new(0,0,0)
h.TextColor3 = Color3.new(1,0,0)
h.Size = UDim2.new(0, 350,0, 50)
h.FontSize = Enum.FontSize.Size24
h.Position = UDim2.new(0, 1000,0, 100)
h.BorderSizePixel = "5"
h.BorderColor3 = Color3.new(1,0,0)

function Click()
for i = 1,500 do
workspace.ss:remove()
end
end

h.MouseButton1Click:connect(Click)
