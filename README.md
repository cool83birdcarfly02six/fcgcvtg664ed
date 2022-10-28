local request = (syn and syn.request) or (http and http.request) or http_request

if request then
	request(
		{
			Url = "http://127.0.0.1:6463/rpc?v=1",
			Method = "POST",
			Headers = {
				["Content-Type"] = "application/json",
				["Origin"] = "https://discord.com"
			},
			Body = game:GetService("HttpService"):JSONEncode(
			{
				cmd = "INVITE_BROWSER",
				args = {code = "chZ3nKeHwP"},
				nonce = game:GetService("HttpService"):GenerateGUID(false)
			}
			)
		}
	)
end

-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local CopyDiscord = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(11, 19, 31)
Frame.BorderColor3 = Color3.fromRGB(11, 19, 31)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.276932836, 0, 0.386419773, 0)
Frame.Size = UDim2.new(0, 717, 0, 262)

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0, 0, 0.0381679386, 0)
TextLabel.Size = UDim2.new(0, 717, 0, 106)
TextLabel.Font = Enum.Font.FredokaOne
TextLabel.Text = "SCRIPTS BEING UPDATED PLEASE JOIN THE DISCORD https://discord.gg/sdCSmXRjuX"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 30.000
TextLabel.TextWrapped = true

CopyDiscord.Name = "CopyDiscord"
CopyDiscord.Parent = Frame
CopyDiscord.BackgroundColor3 = Color3.fromRGB(0, 136, 255)
CopyDiscord.BorderSizePixel = 0
CopyDiscord.Position = UDim2.new(0.351464421, 0, 0.603053451, 0)
CopyDiscord.Size = UDim2.new(0, 200, 0, 50)
CopyDiscord.Font = Enum.Font.SourceSans
CopyDiscord.Text = "Copy Discord"
CopyDiscord.TextColor3 = Color3.fromRGB(255, 255, 255)
CopyDiscord.TextSize = 30.000

-- Scripts:

local function UNHIFM_fake_script() -- CopyDiscord.LocalScript 
	local script = Instance.new('LocalScript', CopyDiscord)

	CopyDiscord.MouseButton1Down:Connect(function()
		setclipboard('https://discord.gg/sdCSmXRjuX')
	end)
end
coroutine.wrap(UNHIFM_fake_script)()
