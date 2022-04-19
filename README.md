-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local TextButton_2 = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local DropShadow = Instance.new("ImageLabel")

--Properties:

ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 179, 255)
Frame.Position = UDim2.new(0.400000006, 0, 0.418271989, 0)
Frame.Size = UDim2.new(0, 382, 0, 192)
Frame.Active = true
Frame.Draggable = true

UICorner.Parent = Frame

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.Position = UDim2.new(0.0254634842, 0, 0.104551151, 0)
TextButton.Size = UDim2.new(0, 364, 0, 43)
TextButton.Font = Enum.Font.GothamBold
TextButton.Text = "Trading Ben"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000
TextButton.MouseButton1Down:Connect(function()
	local args = {
		[1] = "Trading Ben"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)

UICorner_2.Parent = TextButton

TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.Position = UDim2.new(0.0228456818, 0, 0.381880552, 0)
TextButton_2.Size = UDim2.new(0, 364, 0, 43)
TextButton_2.Font = Enum.Font.GothamBold
TextButton_2.Text = "Mommeh Long Legs"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextSize = 14.000
TextButton_2.MouseButton1Down:Connect(function()
	local args = {
		[1] = "Mommeh Long Legs"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)

UICorner_3.Parent = TextButton_2

TextButton_3.Parent = Frame
TextButton_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.Position = UDim2.new(0.0228456818, 0, 0.676265359, 0)
TextButton_3.Size = UDim2.new(0, 364, 0, 43)
TextButton_3.Font = Enum.Font.GothamBold
TextButton_3.Text = "Munneh"
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextSize = 14.000
TextButton_3.MouseButton1Down:Connect(function()
	local args = {
		[1] = "Munneh"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)

UICorner_4.Parent = TextButton_3

DropShadow.Name = "DropShadow"
DropShadow.Parent = Frame
DropShadow.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
DropShadow.BackgroundTransparency = 1.000
DropShadow.BorderSizePixel = 0
DropShadow.Position = UDim2.new(-0.0961314887, 0, -0.0913021639, 0)
DropShadow.Size = UDim2.new(1.20557344, 0, 1.19738591, 0)
DropShadow.ZIndex = -100
DropShadow.Image = "rbxassetid://297694300"
DropShadow.ImageTransparency = 0.500
