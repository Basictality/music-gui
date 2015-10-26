local screen = Instance.new("ScreenGui")
screen.Name = "Admin"
screen.Parent = game.Players.LocalPlayer.PlayerGui

local z = Instance.new("TextBox")
z.Parent = screen
z.Name = "xd"
z.Text = "MusicID"
z.BackgroundTransparency=0.5
z.BackgroundColor3 = Color3.new(0,0,0)
z.Size = UDim2.new(0, 350,0, 50)
z.FontSize = Enum.FontSize.Size24
z.TextColor3 = Color3.new(1,0,0)
z.Position = UDim2.new(0, 665,0, 0)

local b = Instance.new("TextButton")
b.Parent = screen
b.Name = "cool"
b.Text = "Execute"
b.BackgroundColor3 = Color3.new(255,255,255)
b.Size = UDim2.new(0, 350,0, 50)
b.FontSize = Enum.FontSize.Size24
b.Position = UDim2.new(0, 665,0, 50)

function Click()
	Sound = z.Text
	print'loaded'
O = Instance.new("Sound",workspace)
O.Name = "Sound"
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
h.Text = "Remove Sounds"
h.BackgroundTransparency=0.5
h.BackgroundColor3 = Color3.new(0,0,0)
h.TextColor3 = Color3.new(1,0,0)
h.Size = UDim2.new(0, 350,0, 50)
h.FontSize = Enum.FontSize.Size24
h.Position = UDim2.new(0, 665,0, 100)

function Click()
for i = 1,500 do
	workspace.Sound:remove()
end
end

h.MouseButton1Click:connect(Click)
---------------------------
sf = Instance.new("ScrollingFrame",screen)
sf.Size = UDim2.new(0,350,0,800)
sf.BackgroundColor3 = Color3.new(0,0,0)
sf.Position = UDim2.new(0, 1015,0, 0)
sf.BackgroundTransparency = "0.5"

cha=Instance.new("TextButton",sf)
cha.Text = "Cha Cha - D.R.A.M."
cha.Size = UDim2.new(0,350,0,30)
cha.FontSize = "Size24"

function Click()
	Sound = 263824541
O = Instance.new("Sound",workspace)
O.SoundId = ("http://www.roblox.com/asset/?id="..Sound)
O.Pitch = 1
O.Name = "ss"
O.Volume = 1
O.Looped = true 
O:Play()
end

cha.MouseButton1Click:connect(Click)


wa=Instance.new("TextButton",sf)
wa.Text = "OMI - Cheerleaer"
wa.Size = UDim2.new(0,350,0,30)
wa.FontSize = "Size24"
wa.Position = UDim2.new(0,0,0,30)

function Click()
	Sound = 254695481
O = Instance.new("Sound",workspace)
O.SoundId = ("http://www.roblox.com/asset/?id="..Sound)
O.Pitch = 1
O.Name = "ss"
O.Volume = 1
O.Looped = true 
O:Play()
end

wa.MouseButton1Click:connect(Click)

w5=Instance.new("TextButton",sf)
w5.Text = "Mako - Beam (Proximity)"
w5.Size = UDim2.new(0,350,0,30)
w5.FontSize = "Size24"
w5.Position = UDim2.new(0,0,0,60)

function Click()
	Sound = 165065112
OE = Instance.new("Sound",workspace)
OE.SoundId = ("http://www.roblox.com/asset/?id="..Sound)
OE.Pitch = 1
OE.Name = "ss"
OE.Volume = 1
OE.Looped = true 
OE:Play()
end

w5.MouseButton1Click:connect(Click)
print'works music by bas'

w5e=Instance.new("TextButton",sf)
w5e.Text = "(TRAP) - Blue (Remix)"
w5e.Size = UDim2.new(0,350,0,30)
w5e.FontSize = "Size24"
w5e.Position = UDim2.new(0,0,0,90)

function Click()
	Sounde = 223039537
OEF = Instance.new("Sound",workspace)
OEF.SoundId = ("http://www.roblox.com/asset/?id="..Sounde)
OEF.Pitch = 1
OEF.Name = "ss"
OEF.Volume = 1
OEF.Looped = true 
OEF:Play()
end

w5e.MouseButton1Click:connect(Click)
print'works music by bas'
