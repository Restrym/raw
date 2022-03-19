-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Frame_2 = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local UICorner = Instance.new("UICorner")
local Frame_3 = Instance.new("Frame")
local TextBox = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local TextBox_2 = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Frame_4 = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local Frame_5 = Instance.new("Frame")
local Frame_6 = Instance.new("Frame")
local Frame_7 = Instance.new("Frame")
local MAX = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local MAY = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local MAZ = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local UICorner_8 = Instance.new("UICorner")
local Frame_8 = Instance.new("Frame")
local Frame_9 = Instance.new("Frame")
local Frame_10 = Instance.new("Frame")
local WAX = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local WAY = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local WAZ = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local WavesOn = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local UICorner_13 = Instance.new("UICorner")
local Distance = Instance.new("TextBox")
local UICorner_14 = Instance.new("UICorner")
local Speed = Instance.new("TextBox")
local UICorner_15 = Instance.new("UICorner")
local WaveInt = Instance.new("TextBox")
local UICorner_16 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")
local UICorner_17 = Instance.new("UICorner")
local TextLabel_4 = Instance.new("TextLabel")
local UICorner_18 = Instance.new("UICorner")
local TextLabel_5 = Instance.new("TextLabel")
local UICorner_19 = Instance.new("UICorner")
local TextLabel_6 = Instance.new("TextLabel")
local UICorner_20 = Instance.new("UICorner")
local AudioId = Instance.new("TextBox")
local UICorner_21 = Instance.new("UICorner")
local Amount = Instance.new("TextBox")
local UICorner_22 = Instance.new("UICorner")
local TextBox_3 = Instance.new("TextButton")
local UICorner_23 = Instance.new("UICorner")
local TextBox_4 = Instance.new("TextButton")
local UICorner_24 = Instance.new("UICorner")
local TextBox_5 = Instance.new("TextButton")
local UICorner_25 = Instance.new("UICorner")
local UICorner_26 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = false

Frame.Parent = ScreenGui
Frame.AnchorPoint = Vector2.new(0.5, 0.5)
Frame.BackgroundColor3 = Color3.fromRGB(56, 56, 56)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 2
Frame.Position = UDim2.new(0.309612781, 0, 0.50278008, 0)
Frame.Size = UDim2.new(0, 624, 0, 391)

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(4.89063758e-08, 0, -0.0332480818, 0)
Frame_2.Size = UDim2.new(0, 624, 0, 43)

TextLabel.Parent = Frame_2
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.424331903, 0, -0.0192307699, 0)
TextLabel.Size = UDim2.new(0, 88, 0, 29)
TextLabel.Font = Enum.Font.GothamBlack
TextLabel.Text = "-Crazy Hub-"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 15.000
TextLabel.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_2.Parent = Frame_2
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.46279344, 0, 0.544872582, 0)
TextLabel_2.Size = UDim2.new(0, 40, 0, 21)
TextLabel_2.Font = Enum.Font.GothamBlack
TextLabel_2.Text = "-v1.0-"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 15.000
TextLabel_2.TextXAlignment = Enum.TextXAlignment.Left

UICorner.Parent = Frame_2

Frame_3.Parent = Frame
Frame_3.BackgroundColor3 = Color3.fromRGB(131, 131, 131)
Frame_3.BackgroundTransparency = 1.000
Frame_3.BorderColor3 = Color3.fromRGB(27, 42, 53)
Frame_3.Position = UDim2.new(0.0349347778, 0, 0, 0)
Frame_3.Size = UDim2.new(0, 333, 0, 28)

TextBox.Name = "TextBox"
TextBox.Parent = Frame
TextBox.BackgroundColor3 = Color3.fromRGB(188, 188, 188)
TextBox.BorderColor3 = Color3.fromRGB(140, 0, 255)
TextBox.Position = UDim2.new(0.350873113, 0, 0.122241318, 0)
TextBox.Size = UDim2.new(0, 181, 0, 26)
TextBox.ZIndex = 2
TextBox.Font = Enum.Font.GothamBlack
TextBox.Text = "Visualize"
TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox.TextScaled = true
TextBox.TextSize = 14.000
TextBox.TextWrapped = true

UICorner_2.CornerRadius = UDim.new(0, 10)
UICorner_2.Parent = TextBox

TextBox_2.Name = "TextBox"
TextBox_2.Parent = Frame
TextBox_2.BackgroundColor3 = Color3.fromRGB(188, 188, 188)
TextBox_2.BorderColor3 = Color3.fromRGB(140, 0, 255)
TextBox_2.Position = UDim2.new(0.68314147, 0, 0.122241318, 0)
TextBox_2.Size = UDim2.new(0, 173, 0, 26)
TextBox_2.ZIndex = 2
TextBox_2.Font = Enum.Font.GothamBlack
TextBox_2.Text = "Mass-Play"
TextBox_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox_2.TextScaled = true
TextBox_2.TextSize = 14.000
TextBox_2.TextWrapped = true

UICorner_3.CornerRadius = UDim.new(0, 10)
UICorner_3.Parent = TextBox_2

Frame_4.Parent = Frame
Frame_4.BackgroundColor3 = Color3.fromRGB(107, 107, 107)
Frame_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_4.Position = UDim2.new(0.0232356004, 0, 0.10405948, 0)
Frame_4.Size = UDim2.new(0, 593, 0, 330)

UICorner_4.Parent = Frame_4

Frame_5.Parent = Frame_4
Frame_5.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
Frame_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_5.Position = UDim2.new(0.00892935041, 0, 0.467480749, 0)
Frame_5.Size = UDim2.new(0, 173, 0, 24)

Frame_6.Parent = Frame_5
Frame_6.BackgroundColor3 = Color3.fromRGB(80, 80, 80)
Frame_6.BackgroundTransparency = 0.700
Frame_6.BorderColor3 = Color3.fromRGB(27, 42, 53)
Frame_6.Position = UDim2.new(0.33538273, 0, 0, 0)
Frame_6.Size = UDim2.new(0, 1, 0, 24)

Frame_7.Parent = Frame_5
Frame_7.BackgroundColor3 = Color3.fromRGB(80, 80, 80)
Frame_7.BackgroundTransparency = 0.700
Frame_7.BorderColor3 = Color3.fromRGB(27, 42, 53)
Frame_7.Position = UDim2.new(0.660865009, 0, 0, 0)
Frame_7.Size = UDim2.new(0, 1, 0, 24)

MAX.Name = "MAX"
MAX.Parent = Frame_5
MAX.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MAX.Position = UDim2.new(0.00938036293, 0, 0, 0)
MAX.Size = UDim2.new(0, 56, 0, 24)
MAX.Font = Enum.Font.GothamBlack
MAX.Text = "X"
MAX.TextColor3 = Color3.fromRGB(53, 53, 53)
MAX.TextScaled = true
MAX.TextSize = 14.000
MAX.TextWrapped = true

UICorner_5.CornerRadius = UDim.new(0, 3)
UICorner_5.Parent = MAX

MAY.Name = "MAY"
MAY.Parent = Frame_5
MAY.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MAY.BackgroundTransparency = 1.000
MAY.Position = UDim2.new(0.340008318, 0, 0, 0)
MAY.Size = UDim2.new(0, 55, 0, 24)
MAY.Font = Enum.Font.GothamBlack
MAY.Text = "Y"
MAY.TextColor3 = Color3.fromRGB(255, 255, 255)
MAY.TextScaled = true
MAY.TextSize = 14.000
MAY.TextWrapped = true

UICorner_6.CornerRadius = UDim.new(0, 3)
UICorner_6.Parent = MAY

MAZ.Name = "MAZ"
MAZ.Parent = Frame_5
MAZ.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MAZ.BackgroundTransparency = 1.000
MAZ.Position = UDim2.new(0.661320329, 0, 0, 0)
MAZ.Size = UDim2.new(0, 58, 0, 24)
MAZ.Font = Enum.Font.GothamBlack
MAZ.Text = "Z"
MAZ.TextColor3 = Color3.fromRGB(255, 255, 255)
MAZ.TextScaled = true
MAZ.TextSize = 14.000
MAZ.TextWrapped = true

UICorner_7.CornerRadius = UDim.new(0, 3)
UICorner_7.Parent = MAZ

UICorner_8.CornerRadius = UDim.new(0, 3)
UICorner_8.Parent = Frame_5

Frame_8.Parent = Frame_4
Frame_8.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
Frame_8.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_8.Position = UDim2.new(0.70307076, 0, 0.457882881, 0)
Frame_8.Size = UDim2.new(0, 167, 0, 24)

Frame_9.Parent = Frame_8
Frame_9.BackgroundColor3 = Color3.fromRGB(80, 80, 80)
Frame_9.BackgroundTransparency = 0.700
Frame_9.BorderColor3 = Color3.fromRGB(27, 42, 53)
Frame_9.Position = UDim2.new(0.336509854, 0, 0, 0)
Frame_9.Size = UDim2.new(0, 1, 0, 24)

Frame_10.Parent = Frame_8
Frame_10.BackgroundColor3 = Color3.fromRGB(80, 80, 80)
Frame_10.BackgroundTransparency = 0.700
Frame_10.BorderColor3 = Color3.fromRGB(27, 42, 53)
Frame_10.Position = UDim2.new(0.662698507, 0, 0, 0)
Frame_10.Size = UDim2.new(0, 1, 0, 24)

WAX.Name = "WAX"
WAX.Parent = Frame_8
WAX.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WAX.BackgroundTransparency = 1.000
WAX.Position = UDim2.new(0.00994105544, 0, 0, 0)
WAX.Size = UDim2.new(0, 54, 0, 24)
WAX.Font = Enum.Font.GothamBlack
WAX.Text = "X"
WAX.TextColor3 = Color3.fromRGB(255, 255, 255)
WAX.TextScaled = true
WAX.TextSize = 14.000
WAX.TextWrapped = true

UICorner_9.CornerRadius = UDim.new(0, 3)
UICorner_9.Parent = WAX

WAY.Name = "WAY"
WAY.Parent = Frame_8
WAY.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WAY.Position = UDim2.new(0.341145575, 0, 0, 0)
WAY.Size = UDim2.new(0, 54, 0, 24)
WAY.Font = Enum.Font.GothamBlack
WAY.Text = "Y"
WAY.TextColor3 = Color3.fromRGB(53, 53, 53)
WAY.TextScaled = true
WAY.TextSize = 14.000
WAY.TextWrapped = true

UICorner_10.CornerRadius = UDim.new(0, 3)
UICorner_10.Parent = WAY

WAZ.Name = "WAZ"
WAZ.Parent = Frame_8
WAZ.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WAZ.BackgroundTransparency = 1.000
WAZ.Position = UDim2.new(0.663155019, 0, 0, 0)
WAZ.Size = UDim2.new(0, 54, 0, 24)
WAZ.Font = Enum.Font.GothamBlack
WAZ.Text = "Z"
WAZ.TextColor3 = Color3.fromRGB(255, 255, 255)
WAZ.TextScaled = true
WAZ.TextSize = 14.000
WAZ.TextWrapped = true

UICorner_11.CornerRadius = UDim.new(0, 3)
UICorner_11.Parent = WAZ

WavesOn.Name = "WavesOn"
WavesOn.Parent = Frame_8
WavesOn.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
WavesOn.Position = UDim2.new(0.756418586, 0, 1.37134552, 0)
WavesOn.Size = UDim2.new(0, 40, 0, 26)
WavesOn.Font = Enum.Font.GothamBlack
WavesOn.Text = ""
WavesOn.TextColor3 = Color3.fromRGB(53, 53, 53)
WavesOn.TextSize = 14.000

UICorner_12.CornerRadius = UDim.new(0, 3)
UICorner_12.Parent = WavesOn

UICorner_13.CornerRadius = UDim.new(0, 3)
UICorner_13.Parent = Frame_8

Distance.Name = "Distance"
Distance.Parent = Frame_4
Distance.BackgroundColor3 = Color3.fromRGB(188, 188, 188)
Distance.BorderColor3 = Color3.fromRGB(140, 0, 255)
Distance.Position = UDim2.new(0.673413336, 0, 0.706147254, 0)
Distance.Size = UDim2.new(0, 173, 0, 29)
Distance.Font = Enum.Font.GothamBlack
Distance.PlaceholderColor3 = Color3.fromRGB(77, 77, 77)
Distance.PlaceholderText = "Distance (5)"
Distance.Text = ""
Distance.TextColor3 = Color3.fromRGB(0, 0, 0)
Distance.TextScaled = true
Distance.TextSize = 14.000
Distance.TextWrapped = true

UICorner_14.CornerRadius = UDim.new(0, 3)
UICorner_14.Parent = Distance

Speed.Name = "Speed"
Speed.Parent = Frame_4
Speed.BackgroundColor3 = Color3.fromRGB(188, 188, 188)
Speed.BorderColor3 = Color3.fromRGB(140, 0, 255)
Speed.Position = UDim2.new(0.0320927463, 0, 0.708476961, 0)
Speed.Size = UDim2.new(0, 173, 0, 29)
Speed.Font = Enum.Font.GothamBlack
Speed.PlaceholderColor3 = Color3.fromRGB(77, 77, 77)
Speed.PlaceholderText = "Speed (1)"
Speed.Text = ""
Speed.TextColor3 = Color3.fromRGB(0, 0, 0)
Speed.TextScaled = true
Speed.TextSize = 14.000
Speed.TextWrapped = true

UICorner_15.CornerRadius = UDim.new(0, 3)
UICorner_15.Parent = Speed

WaveInt.Name = "WaveInt"
WaveInt.Parent = Frame_4
WaveInt.BackgroundColor3 = Color3.fromRGB(188, 188, 188)
WaveInt.BorderColor3 = Color3.fromRGB(140, 0, 255)
WaveInt.Position = UDim2.new(0.352787107, 0, 0.708476961, 0)
WaveInt.Size = UDim2.new(0, 173, 0, 29)
WaveInt.Font = Enum.Font.GothamBlack
WaveInt.PlaceholderColor3 = Color3.fromRGB(77, 77, 77)
WaveInt.PlaceholderText = "Wave Intensity (3)"
WaveInt.Text = ""
WaveInt.TextColor3 = Color3.fromRGB(0, 0, 0)
WaveInt.TextScaled = true
WaveInt.TextSize = 12.000
WaveInt.TextWrapped = true

UICorner_16.CornerRadius = UDim.new(0, 3)
UICorner_16.Parent = WaveInt

TextLabel_3.Parent = Frame_4
TextLabel_3.BackgroundColor3 = Color3.fromRGB(188, 188, 188)
TextLabel_3.Position = UDim2.new(0.70307076, 0, 0.557617128, 0)
TextLabel_3.Size = UDim2.new(0, 115, 0, 26)
TextLabel_3.Font = Enum.Font.GothamBlack
TextLabel_3.Text = "On / Off :"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 13.000
TextLabel_3.TextWrapped = true

UICorner_17.CornerRadius = UDim.new(0, 3)
UICorner_17.Parent = TextLabel_3

TextLabel_4.Parent = Frame_4
TextLabel_4.BackgroundColor3 = Color3.fromRGB(188, 188, 188)
TextLabel_4.Position = UDim2.new(0.0116659487, 0, 0.378829211, 0)
TextLabel_4.Size = UDim2.new(0, 171, 0, 27)
TextLabel_4.Font = Enum.Font.GothamBlack
TextLabel_4.Text = "Main Angle"
TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 13.000
TextLabel_4.TextWrapped = true

UICorner_18.CornerRadius = UDim.new(0, 3)
UICorner_18.Parent = TextLabel_4

TextLabel_5.Parent = Frame_4
TextLabel_5.BackgroundColor3 = Color3.fromRGB(188, 188, 188)
TextLabel_5.Position = UDim2.new(0.704757094, 0, 0.343391925, 0)
TextLabel_5.Size = UDim2.new(0, 167, 0, 31)
TextLabel_5.Font = Enum.Font.GothamBlack
TextLabel_5.Text = "Waves"
TextLabel_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.TextScaled = true
TextLabel_5.TextSize = 13.000
TextLabel_5.TextWrapped = true

UICorner_19.CornerRadius = UDim.new(0, 3)
UICorner_19.Parent = TextLabel_5

TextLabel_6.Parent = Frame_4
TextLabel_6.BackgroundColor3 = Color3.fromRGB(188, 188, 188)
TextLabel_6.Position = UDim2.new(0.311834574, 0, 0.260647386, 0)
TextLabel_6.Size = UDim2.new(0, 226, 0, 124)
TextLabel_6.Font = Enum.Font.GothamBlack
TextLabel_6.Text = "Owner/Designer: FOZY#7024 Scripter: Restrym#5899"
TextLabel_6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_6.TextScaled = true
TextLabel_6.TextSize = 13.000
TextLabel_6.TextWrapped = true

UICorner_20.CornerRadius = UDim.new(0, 10)
UICorner_20.Parent = TextLabel_6

AudioId.Name = "AudioId"
AudioId.Parent = Frame
AudioId.BackgroundColor3 = Color3.fromRGB(188, 188, 188)
AudioId.BorderColor3 = Color3.fromRGB(140, 0, 255)
AudioId.Position = UDim2.new(0.0325461179, 0, 0.122241318, 0)
AudioId.Size = UDim2.new(0, 173, 0, 26)
AudioId.Font = Enum.Font.GothamBlack
AudioId.PlaceholderColor3 = Color3.fromRGB(77, 77, 77)
AudioId.PlaceholderText = "Audio-ID"
AudioId.Text = ""
AudioId.TextColor3 = Color3.fromRGB(0, 0, 0)
AudioId.TextScaled = true
AudioId.TextSize = 14.000
AudioId.TextWrapped = true

UICorner_21.CornerRadius = UDim.new(0, 3)
UICorner_21.Parent = AudioId

Amount.Name = "Amount"
Amount.Parent = Frame
Amount.BackgroundColor3 = Color3.fromRGB(188, 188, 188)
Amount.BorderColor3 = Color3.fromRGB(140, 0, 255)
Amount.Position = UDim2.new(0.0325461179, 0, 0.220942587, 0)
Amount.Size = UDim2.new(0, 173, 0, 26)
Amount.Font = Enum.Font.GothamBlack
Amount.PlaceholderColor3 = Color3.fromRGB(77, 77, 77)
Amount.PlaceholderText = "Amount"
Amount.Text = ""
Amount.TextColor3 = Color3.fromRGB(0, 0, 0)
Amount.TextScaled = true
Amount.TextSize = 14.000
Amount.TextWrapped = true

UICorner_22.CornerRadius = UDim.new(0, 3)
UICorner_22.Parent = Amount

TextBox_3.Name = "TextBox"
TextBox_3.Parent = Frame
TextBox_3.BackgroundColor3 = Color3.fromRGB(188, 188, 188)
TextBox_3.BorderColor3 = Color3.fromRGB(140, 0, 255)
TextBox_3.Position = UDim2.new(0.350873113, 0, 0.220942587, 0)
TextBox_3.Size = UDim2.new(0, 181, 0, 26)
TextBox_3.Font = Enum.Font.GothamBlack
TextBox_3.Text = "Dupe Amount"
TextBox_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox_3.TextScaled = true
TextBox_3.TextSize = 14.000
TextBox_3.TextWrapped = true

UICorner_23.CornerRadius = UDim.new(0, 10)
UICorner_23.Parent = TextBox_3

TextBox_4.Name = "TextBox"
TextBox_4.Parent = Frame
TextBox_4.BackgroundColor3 = Color3.fromRGB(188, 188, 188)
TextBox_4.BorderColor3 = Color3.fromRGB(140, 0, 255)
TextBox_4.Position = UDim2.new(0.68314147, 0, 0.220942587, 0)
TextBox_4.Size = UDim2.new(0, 173, 0, 26)
TextBox_4.Font = Enum.Font.GothamBlack
TextBox_4.Text = "Steal Tools"
TextBox_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox_4.TextScaled = true
TextBox_4.TextSize = 14.000
TextBox_4.TextWrapped = true

UICorner_24.CornerRadius = UDim.new(0, 10)
UICorner_24.Parent = TextBox_4

TextBox_5.Name = "TextBox"
TextBox_5.Parent = Frame
TextBox_5.BackgroundColor3 = Color3.fromRGB(188, 188, 188)
TextBox_5.BorderColor3 = Color3.fromRGB(140, 0, 255)
TextBox_5.Position = UDim2.new(0.354078233, 0, 0.827106357, 0)
TextBox_5.Size = UDim2.new(0, 181, 0, 35)
TextBox_5.Font = Enum.Font.GothamBlack
TextBox_5.Text = "Sync"
TextBox_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox_5.TextScaled = true
TextBox_5.TextSize = 14.000
TextBox_5.TextWrapped = true

UICorner_25.CornerRadius = UDim.new(0, 10)
UICorner_25.Parent = TextBox_5

UICorner_26.Parent = Frame

-- Scripts:

local function DBGS_fake_script() -- TextBox.LocalScript 
	local script = Instance.new('LocalScript', TextBox)

	local currentid=""
	local currentconnection=nil
	local vis = nil
	local dt =0
	local CurrentSound=nil
	local CurrentTimePosition=0
	game:service'RunService'.Stepped:Connect(function(e,d)
		dt+=d
	end)
	local dont=1
	function setupadded()
		game.Players.LocalPlayer.Character.ChildAdded:Connect(function(child)
			if child:IsA("Tool") and dont ==0 then
				wait()
				child.Parent=game.Players.LocalPlayer.Backpack
				wait(.3)
				dont=1
				if vis ~=nil then
					vis(currentid,CurrentTimePosition)
				end
			end
		end)
	end
	setupadded()
	vis=function(id,timepos)
		_G.tov={}
		if _G.NetFix==nil then
			_G.NetFix=" "
			game:service'RunService'.Heartbeat:Connect(function()
				for i,v in pairs(_G.tov) do
					v[1].Velocity=Vector3.new(2e2,0,0)
					v[1].CFrame=v[2].CFrame
				end
			end)
		end
		local Stopped=false
		local visstuff={}
		local function align(i)
			l=Instance.new("Part")
			l.Transparency=1
			l.Parent=i.Parent
			l.Size=Vector3.new(0,0,0)
			l.Name=""
			l.CanCollide=false
			l.Anchored=true
			l.CFrame=i.CFrame
			table.insert(_G.tov,{i,l})
			local att0 = Instance.new("Attachment", i)
			att0.Position = Vector3.new(0,0,0)
			local att1 = Instance.new("Attachment", l)
			att1.Position = Vector3.new(0,0,0)
			local AP = Instance.new("AlignPosition", i)
			AP.Attachment0 = att0
			AP.Attachment1 = att1
			AP.RigidityEnabled = true
			AP.ReactionForceEnabled = false
			AP.ApplyAtCenterOfMass = true
			AP.MaxForce = 9999999
			AP.MaxVelocity = math.huge
			AP.Responsiveness = 200
			local AO = Instance.new("AlignOrientation", i)
			AO.Attachment0 = att0
			AO.Attachment1 = att1
			AO.ReactionTorqueEnabled = false
			AO.PrimaryAxisOnly = false
			AO.MaxTorque = 9999999
			AO.MaxAngularVelocity = math.huge
			AO.Responsiveness = 200
			table.insert(visstuff,{AO,AP,att0,att1,l})
			return l
		end
		local Visualizer={}
		local First=false
		local Handles={}
		local ToolCount=0
		for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
			if v:IsA("Tool") then
				ToolCount=ToolCount+1
			end
		end
		local cf=game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
			if v:IsA("Tool") then
				coroutine.wrap(function()
					if First==false then
						First=v
					end
					local Handle=v:FindFirstChildOfClass("Part")
					v.Parent=game.Players.LocalPlayer.Character
					if Handle:FindFirstChildOfClass("Sound") then
						Handle:FindFirstChildOfClass("Sound").Parent=Instance.new("Part")
					end
					currentid=id
					v:FindFirstChildOfClass("RemoteEvent"):FireServer("PlaySong",(id))
					repeat wait() until Handle:FindFirstChildOfClass("Sound") and Handle:FindFirstChildOfClass("Sound").IsPlaying
					for i,v in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
						if v.Name=="RightGrip" then
							v:Destroy()
						end
					end
					Handle.Name=""
					if First==v then
						CurrentSound=Handle:FindFirstChildOfClass("Sound")
					end
					Handle:FindFirstChildOfClass("Sound").Playing=false
					coroutine.wrap(function()
						repeat wait() until v.Parent~=game.Players.LocalPlayer.Character
						Handle.Name="Handle"
						Stopped=true
						dont=1
						_G.tov={}
						for i,v in pairs(visstuff) do
							for i,v in pairs(v) do
								v:Destroy()
							end
						end
					end)()
					table.insert(Handles,Handle)
					table.insert(Visualizer,align(Handle))
				end)()
			end
		end
		local Root=game.Players.LocalPlayer.Character.HumanoidRootPart
		repeat wait() until #Visualizer==ToolCount and CurrentSound
		wait(1)
		for i,v in pairs(Handles) do
			coroutine.wrap(function()
				v:FindFirstChildOfClass("Sound").TimePosition=timepos
				v:FindFirstChildOfClass("Sound").Playing=true
			end)()
		end
		spawn(function()
			while wait(.6) do
				if Stopped == true then
					break
				end
				if CurrentSound.IsPlaying == true then
					CurrentTimePosition=CurrentSound.TimePosition
				end
			end
		end)
		local RenderStepped = game:GetService('RunService').RenderStepped
		local Wait = RenderStepped.Wait
		local Selected=CurrentSound
		local p = Instance.new("Part")
		function CF2V(cf)
			p.CFrame=cf
			return p.Rotation
		end
		local function AngleFromSettings(angle,str)
			if str=="X" then
				return CFrame.Angles(angle,0,0)
			elseif str=="Y" then
				return CFrame.Angles(0,angle,0)
			elseif str=="Z" then
				return CFrame.Angles(0,0,angle)
			end
		end
		local function VectorFromSettings(angle,str)
			if str=="X" then
				return Vector3.new(angle,0,0)
			elseif str=="Y" then
				return Vector3.new(0,angle,0)
			elseif str=="Z" then
				return Vector3.new(0,0,angle)
			end
		end
		dont=0
		setupadded()
		for K,V in next, Visualizer do
			coroutine.wrap(function()
				repeat
					local Spin = 0
					repeat
						if CurrentSound then
							local Volume = CurrentSound['PlaybackLoudness']
							local Iterator=math.rad(Spin+(K*(360/#Visualizer)))
							local Z = _G.Distance + Volume / (1 ~= 100 and (100 - 1) or .01)
							local G =  Volume / (35 ~= 100 and (100 - 35) or .01)
							local P = CFrame.new(Root['Position']) * AngleFromSettings(Iterator,_G.VisAngle) * CFrame.new(0,0,Z)
							local AddVector =Vector3.new(0,0,0)
							if _G.WavesOn == "On" then
								AddVector=VectorFromSettings(math.sin((((dt*_G.WaveInt)+(K/#Visualizer)*(math.pi*2)))),_G.WavesAngle)
							end
							V['Position'] = P.p+AddVector
							V['Rotation'] = CF2V(CFrame.new(V.Position, Root['Position'] + Vector3.new(0, G, 0)))
						end
						Spin+=_G.Speed
						game:service'RunService'.RenderStepped:Wait()
					until Stopped or ((Spin >= 360)) 
				until Stopped
				ccc:Disconnect()
			end)()
		end
	end
	script.Parent.MouseButton1Click:Connect(function()
		vis(script.Parent.Parent.AudioId.Text:gsub("%D+", ""),0)
	end)
end
coroutine.wrap(DBGS_fake_script)()
local function YUCXPRS_fake_script() -- TextBox_2.LocalScript 
	local script = Instance.new('LocalScript', TextBox_2)

	script.Parent.MouseButton1Click:Connect(function()
		local Backpack=game.Players.LocalPlayer.Backpack
		local lp=game.Players.LocalPlayer
		local tosync=false
		local tt=0
		for i,v in pairs(Backpack:GetChildren()) do
			if v:IsA("Tool") then
				tt=tt+1
			end
		end
		local t = {}
		for i,v in pairs(Backpack:GetChildren()) do
			if v:IsA("Tool") then
				coroutine.wrap(function()
					if v.Handle:FindFirstChildOfClass("Sound") then
						v.Handle:FindFirstChildOfClass("Sound"):Destroy()
					end
					v.Parent=lp.Character
					v:FindFirstChildOfClass("RemoteEvent"):FireServer("PlaySong",(script.Parent.Parent.AudioId.Text:gsub("%D+", "")))
					repeat wait() until v.Handle:FindFirstChildOfClass("Sound")
					repeat wait() until v.Handle:FindFirstChildOfClass("Sound").IsPlaying
					v.Handle:FindFirstChildOfClass("Sound").Playing=false
					table.insert(t,v)
				end)()
			end
		end
		repeat game:service'RunService'.Heartbeat:Wait() until #t==tt
		wait(1)
		for i,v in pairs(t) do
			coroutine.wrap(function()
				v.Handle:FindFirstChildOfClass("Sound").TimePosition=0
				v.Handle:FindFirstChildOfClass("Sound").Playing=true
			end)()
		end
		print("done")
	end)
end
coroutine.wrap(YUCXPRS_fake_script)()
local function UTKJKGJ_fake_script() -- MAX.LocalScript 
	local script = Instance.new('LocalScript', MAX)

	script.Parent.MouseButton1Click:Connect(function()
		_G.VisAngle=script.Parent.Name:gsub("MA","")
	end)
	while wait() do
		if script.Parent.Name=="MA"..tostring(_G.VisAngle) then
			script.Parent.BackgroundTransparency=0
			script.Parent.TextColor3=Color3.fromRGB(53, 53, 53)
		else
			script.Parent.BackgroundTransparency=1
			script.Parent.TextColor3=Color3.fromRGB(255,255,255)
		end
	end
end
coroutine.wrap(UTKJKGJ_fake_script)()
local function TFNVJA_fake_script() -- MAY.LocalScript 
	local script = Instance.new('LocalScript', MAY)

	script.Parent.MouseButton1Click:Connect(function()
		_G.VisAngle=script.Parent.Name:gsub("MA","")
	end)
	while wait() do
		if script.Parent.Name=="MA"..tostring(_G.VisAngle) then
			script.Parent.BackgroundTransparency=0
			script.Parent.TextColor3=Color3.fromRGB(53, 53, 53)
		else
			script.Parent.BackgroundTransparency=1
			script.Parent.TextColor3=Color3.fromRGB(255,255,255)
		end
	end
end
coroutine.wrap(TFNVJA_fake_script)()
local function OZTLZI_fake_script() -- MAZ.LocalScript 
	local script = Instance.new('LocalScript', MAZ)

	script.Parent.MouseButton1Click:Connect(function()
		_G.VisAngle=script.Parent.Name:gsub("MA","")
	end)
	while wait() do
		if script.Parent.Name=="MA"..tostring(_G.VisAngle) then
			script.Parent.BackgroundTransparency=0
			script.Parent.TextColor3=Color3.fromRGB(53, 53, 53)
		else
			script.Parent.BackgroundTransparency=1
			script.Parent.TextColor3=Color3.fromRGB(255,255,255)
		end
	end
end
coroutine.wrap(OZTLZI_fake_script)()
local function JDOBGR_fake_script() -- WAX.LocalScript 
	local script = Instance.new('LocalScript', WAX)

	script.Parent.MouseButton1Click:Connect(function()
		_G.WavesAngle=script.Parent.Name:gsub("WA","")
	end)
	while wait() do
		if script.Parent.Name=="WA"..tostring(_G.WavesAngle) then
			script.Parent.BackgroundTransparency=0
			script.Parent.TextColor3=Color3.fromRGB(53, 53, 53)
		else
			script.Parent.BackgroundTransparency=1
			script.Parent.TextColor3=Color3.fromRGB(255,255,255)
		end
	end
end
coroutine.wrap(JDOBGR_fake_script)()
local function DCNSPIX_fake_script() -- WAY.LocalScript 
	local script = Instance.new('LocalScript', WAY)

	script.Parent.MouseButton1Click:Connect(function()
		_G.WavesAngle=script.Parent.Name:gsub("WA","")
	end)
	while wait() do
		if script.Parent.Name=="WA"..tostring(_G.WavesAngle) then
			script.Parent.BackgroundTransparency=0
			script.Parent.TextColor3=Color3.fromRGB(53, 53, 53)
		else
			script.Parent.BackgroundTransparency=1
			script.Parent.TextColor3=Color3.fromRGB(255,255,255)
		end
	end
end
coroutine.wrap(DCNSPIX_fake_script)()
local function DZJU_fake_script() -- WAZ.LocalScript 
	local script = Instance.new('LocalScript', WAZ)

	script.Parent.MouseButton1Click:Connect(function()
		_G.WavesAngle=script.Parent.Name:gsub("WA","")
	end)
	while wait() do
		if script.Parent.Name=="WA"..tostring(_G.WavesAngle) then
			script.Parent.BackgroundTransparency=0
			script.Parent.TextColor3=Color3.fromRGB(53, 53, 53)
		else
			script.Parent.BackgroundTransparency=1
			script.Parent.TextColor3=Color3.fromRGB(255,255,255)
		end
	end
end
coroutine.wrap(DZJU_fake_script)()
local function UMKP_fake_script() -- WavesOn.LocalScript 
	local script = Instance.new('LocalScript', WavesOn)

	script.Parent.MouseButton1Click:Connect(function()
		if "Waves".._G.WavesOn==script.Parent.Name then
			_G.WavesOn="Off"
		else
			_G.WavesOn="On"
		end
	end)
	while wait() do
		if script.Parent.Name=="Waves"..tostring(_G.WavesOn) then
			script.Parent.BackgroundColor3=Color3.fromRGB(255, 255, 127)
		else
			script.Parent.BackgroundColor3=Color3.fromRGB(31,31,31)
		end
	end 
end
coroutine.wrap(UMKP_fake_script)()
local function GKDLP_fake_script() -- Distance.LocalScript 
	local script = Instance.new('LocalScript', Distance)

	_G[script.Parent.Name]=5
	script.Parent.Changed:Connect(function(t)
		if t=="Text" then
			_G[script.Parent.Name]=tonumber(script.Parent.Text) or 0
		end
	end)
end
coroutine.wrap(GKDLP_fake_script)()
local function WNBNQ_fake_script() -- WaveInt.LocalScript 
	local script = Instance.new('LocalScript', WaveInt)

	_G[script.Parent.Name]=3
	script.Parent.Changed:Connect(function(t)
		if t=="Text" then
			_G[script.Parent.Name]=tonumber(script.Parent.Text) or 0
		end
	end)
end
coroutine.wrap(WNBNQ_fake_script)()
local function WYFU_fake_script() -- Speed.LocalScript 
	local script = Instance.new('LocalScript', Speed)

	_G[script.Parent.Name]=1
	script.Parent.Changed:Connect(function(t)
		if t=="Text" then
			_G[script.Parent.Name]=tonumber(script.Parent.Text) or 0
		end
	end)
end
coroutine.wrap(WYFU_fake_script)()
local function MDGLVEO_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)

	_G.VisAngle="X"
	_G.WavesOn="Off"
	_G.WavesAngle="Y"
	_G.BoomboxDependantSpeed="Off"
end
coroutine.wrap(MDGLVEO_fake_script)()
local function JZFN_fake_script() -- Frame.Dragify 
	local script = Instance.new('LocalScript', Frame)

	local UIS = game:GetService("UserInputService")
	function dragify(Frame)
		dragToggle = nil
		local dragSpeed = 0.50
		dragInput = nil
		dragStart = nil
		local dragPos = nil
		function updateInput(input)
			local Delta = input.Position - dragStart
			local Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
			game:GetService("TweenService"):Create(Frame, TweenInfo.new(0), {Position = Position}):Play()
		end
		Frame.InputBegan:Connect(function(input)
			if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) and UIS:GetFocusedTextBox() == nil then
				dragToggle = true
				dragStart = input.Position
				startPos = Frame.Position
				input.Changed:Connect(function()
					if input.UserInputState == Enum.UserInputState.End then
						dragToggle = false
					end
				end)
			end
		end)
		Frame.InputChanged:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
				dragInput = input
			end
		end)
		game:GetService("UserInputService").InputChanged:Connect(function(input)
			if input == dragInput and dragToggle then
				updateInput(input)
			end
		end)
	end

	dragify(script.Parent)
end
coroutine.wrap(JZFN_fake_script)()
local function CIGR_fake_script() -- TextBox_3.LocalScript 
	local script = Instance.new('LocalScript', TextBox_3)

	script.Parent.MouseButton1Click:Connect(function()
		for i=1,tonumber(script.Parent.Parent.Amount.Text) or 1 do
			char=game.Players.LocalPlayer.Character
			game.Players.LocalPlayer.Character=nil
			game.Players.LocalPlayer.Character=char
			char.Animate:Destroy()
			char.HumanoidRootPart.CFrame=CFrame.new(0,9999,0)
			wait(.1)
			char.HumanoidRootPart.Anchored=true
			for i,v in pairs(char:GetChildren()) do
				if v:IsA("Tool") then
					v.Parent=game.Players.LocalPlayer.Backpack
				end
			end
			wait(game.Players.RespawnTime-0.3)
			local t = {}
			for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
				v.Parent=char
				v.Parent=workspace
				t[i]=v
			end
			char.Humanoid:Destroy()
			game.Players.LocalPlayer.Character=nil
			game.Players.LocalPlayer.CharacterAdded:Wait()
			char=game.Players.LocalPlayer.Character
			char:WaitForChild("Humanoid")
			wait(.1)
			for i,v in pairs(t) do
				char.Humanoid:EquipTool(v)
			end
			wait(.3)
		end	
	end)
end
coroutine.wrap(CIGR_fake_script)()
local function KOHXP_fake_script() -- TextBox_4.LocalScript 
	local script = Instance.new('LocalScript', TextBox_4)

	_G.grabtools=false
	game:service'RunService'.Heartbeat:Connect(function()
		local h=game.Players.LocalPlayer.Character:FindFirstChild("Humanoid")
		if _G.grabtools==true and h then
			for i,v in pairs(workspace:GetChildren()) do
				coroutine.wrap(function()
					if v:IsA("Tool") then
						h:EquipTool(v)
					end	
				end)()
			end
		end
	end)
	spawn(function()
		while wait() do
			if _G.grabtools==true then
				script.Parent.TextColor3=Color3.fromRGB(53, 53, 53)
				script.Parent.BackgroundColor3=Color3.fromRGB(255, 255, 127)
			else
				script.Parent.TextColor3=Color3.fromRGB(255,255,255)
				script.Parent.BackgroundColor3=Color3.fromRGB(20, 20, 20)
			end
		end 	
	end)
	script.Parent.MouseButton1Click:Connect(function()
		_G.grabtools=not _G.grabtools
	end)
end
coroutine.wrap(KOHXP_fake_script)()
local function LPDFVEO_fake_script() -- TextBox_5.LocalScript 
	local script = Instance.new('LocalScript', TextBox_5)

	script.Parent.MouseButton1Click:Connect(function()
		print(pcall(function()
			for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
				if v:IsA("Tool") and v:FindFirstChildOfClass("Part"):FindFirstChildOfClass("Sound") then
					coroutine.wrap(function()
						v:FindFirstChildOfClass("Part"):FindFirstChildOfClass("Sound").Playing=false
						wait()
						v:FindFirstChildOfClass("Part"):FindFirstChildOfClass("Sound").TimePosition=0
						v:FindFirstChildOfClass("Part"):FindFirstChildOfClass("Sound").Playing=true
					end)()
				end
			end
		end))
	end)
end
coroutine.wrap(LPDFVEO_fake_script)()
