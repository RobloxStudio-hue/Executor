-- By khngsml1223 
-- Script Test

-- Instances:

local Loader = Instance.new("ScreenGui")
local Drag = Instance.new("Frame")
local Main_Frame = Instance.new("Frame")
local Down_Button = Instance.new("Folder")
local OK_Frame = Instance.new("Frame")
local OK_Button = Instance.new("TextButton")
local Main_Gui = Instance.new("Folder")
local ScrollingFrame = Instance.new("ScrollingFrame")
local Frame_Scrolling = Instance.new("Frame")
local Text_LabelEnd = Instance.new("TextLabel")
local Tab = Instance.new("Folder")
local Main_Tab = Instance.new("Frame")
local POP = Instance.new("Frame")
local File_Button = Instance.new("TextButton")
local Main_ButtonFile = Instance.new("Frame")
local Main_ButtonFile1 = Instance.new("Frame")
local Button_1 = Instance.new("TextButton")
local Button_2 = Instance.new("TextButton")
local Name_Gui_about = Instance.new("Folder")
local ImageLabel = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local Close = Instance.new("TextButton")

--Properties:

Loader.Name = "Loader"
Loader.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Loader.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Drag.Name = "Drag"
Drag.Parent = Loader
Drag.BackgroundColor3 = Color3.fromRGB(107, 167, 246)
Drag.BorderColor3 = Color3.fromRGB(0, 0, 0)
Drag.BorderSizePixel = 0
Drag.Position = UDim2.new(0.272388071, 0, 0.376884431, 0)
Drag.Size = UDim2.new(0, 594, 0, 26)

Main_Frame.Name = "Main_Frame"
Main_Frame.Parent = Drag
Main_Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Main_Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Main_Frame.BorderSizePixel = 0
Main_Frame.Position = UDim2.new(0, 0, 1, 0)
Main_Frame.Size = UDim2.new(0, 594, 0, 289)

Down_Button.Name = "Down_Button"
Down_Button.Parent = Main_Frame

OK_Frame.Name = "OK_Frame"
OK_Frame.Parent = Down_Button
OK_Frame.BackgroundColor3 = Color3.fromRGB(152, 152, 152)
OK_Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
OK_Frame.BorderSizePixel = 0
OK_Frame.Position = UDim2.new(0.814814806, 0, 0.868512094, 0)
OK_Frame.Size = UDim2.new(0, 104, 0, 32)

OK_Button.Name = "OK_Button"
OK_Button.Parent = OK_Frame
OK_Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
OK_Button.BorderColor3 = Color3.fromRGB(0, 0, 0)
OK_Button.BorderSizePixel = 0
OK_Button.Position = UDim2.new(0, 1, 0, 1)
OK_Button.Size = UDim2.new(0, 102, 0, 30)
OK_Button.Font = Enum.Font.Arial
OK_Button.Text = "OK"
OK_Button.TextColor3 = Color3.fromRGB(0, 0, 0)
OK_Button.TextSize = 19.000

Main_Gui.Name = "Main_Gui"
Main_Gui.Parent = Main_Frame

ScrollingFrame.Parent = Main_Gui
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScrollingFrame.BackgroundTransparency = 1.000
ScrollingFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScrollingFrame.BorderSizePixel = 0
ScrollingFrame.Position = UDim2.new(0, 0, 0.110726647, 0)
ScrollingFrame.Size = UDim2.new(0, 594, 0, 210)
ScrollingFrame.BottomImage = "rbxasset://textures/ui/Scroll/scroll-middle.png"
ScrollingFrame.TopImage = "rbxasset://textures/ui/Scroll/scroll-middle.png"

Frame_Scrolling.Name = "Frame_Scrolling"
Frame_Scrolling.Parent = ScrollingFrame
Frame_Scrolling.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_Scrolling.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_Scrolling.BorderSizePixel = 0
Frame_Scrolling.Size = UDim2.new(0, 594, 0, 457)

Text_LabelEnd.Name = "Text_Label=-End-"
Text_LabelEnd.Parent = Frame_Scrolling
Text_LabelEnd.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Text_LabelEnd.BackgroundTransparency = 1.000
Text_LabelEnd.BorderColor3 = Color3.fromRGB(0, 0, 0)
Text_LabelEnd.BorderSizePixel = 0
Text_LabelEnd.Position = UDim2.new(0.33164984, 0, 0.890590787, 0)
Text_LabelEnd.Size = UDim2.new(0, 200, 0, 50)
Text_LabelEnd.Font = Enum.Font.SourceSans
Text_LabelEnd.Text = "-End-"
Text_LabelEnd.TextColor3 = Color3.fromRGB(0, 0, 0)
Text_LabelEnd.TextSize = 14.000

Tab.Name = "Tab"
Tab.Parent = Main_Frame

Main_Tab.Name = "Main_Tab"
Main_Tab.Parent = Tab
Main_Tab.BackgroundColor3 = Color3.fromRGB(242, 242, 242)
Main_Tab.BorderColor3 = Color3.fromRGB(0, 0, 0)
Main_Tab.BorderSizePixel = 0
Main_Tab.Size = UDim2.new(0, 594, 0, 31)

POP.Name = "POP"
POP.Parent = Main_Tab
POP.BackgroundColor3 = Color3.fromRGB(227, 227, 227)
POP.BorderColor3 = Color3.fromRGB(0, 0, 0)
POP.BorderSizePixel = 0
POP.Position = UDim2.new(0, 0, 1, 0)
POP.Size = UDim2.new(0, 594, 0, 1)

File_Button.Name = "File_Button"
File_Button.Parent = Main_Tab
File_Button.BackgroundColor3 = Color3.fromRGB(243, 243, 243)
File_Button.BorderColor3 = Color3.fromRGB(0, 0, 0)
File_Button.BorderSizePixel = 0
File_Button.Size = UDim2.new(0, 60, 0, 31)
File_Button.Font = Enum.Font.SourceSans
File_Button.Text = "FILE"
File_Button.TextColor3 = Color3.fromRGB(0, 0, 0)
File_Button.TextSize = 14.000

Main_ButtonFile.Name = "Main_ButtonFile"
Main_ButtonFile.Parent = Main_Tab
Main_ButtonFile.BackgroundColor3 = Color3.fromRGB(195, 195, 195)
Main_ButtonFile.BorderColor3 = Color3.fromRGB(0, 0, 0)
Main_ButtonFile.BorderSizePixel = 0
Main_ButtonFile.Position = UDim2.new(0, 0, 1.03225803, 0)
Main_ButtonFile.Size = UDim2.new(0, 170, 0, 220)
Main_ButtonFile.Visible = false

Main_ButtonFile1.Name = "Main_ButtonFile1"
Main_ButtonFile1.Parent = Main_ButtonFile
Main_ButtonFile1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Main_ButtonFile1.BorderColor3 = Color3.fromRGB(0, 0, 0)
Main_ButtonFile1.BorderSizePixel = 0
Main_ButtonFile1.Position = UDim2.new(0, 1, 0, 1)
Main_ButtonFile1.Size = UDim2.new(0, 167, 0, 217)

Button_1.Name = "Button_1"
Button_1.Parent = Main_ButtonFile1
Button_1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button_1.BorderColor3 = Color3.fromRGB(0, 0, 0)
Button_1.BorderSizePixel = 0
Button_1.Position = UDim2.new(0.0179640725, 0, 0, 0)
Button_1.Size = UDim2.new(0, 164, 0, 20)
Button_1.Font = Enum.Font.SourceSans
Button_1.Text = "Button_1"
Button_1.TextColor3 = Color3.fromRGB(0, 0, 0)
Button_1.TextSize = 14.000

Button_2.Name = "Button_2"
Button_2.Parent = Main_ButtonFile1
Button_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Button_2.BorderSizePixel = 0
Button_2.Position = UDim2.new(0.0119760484, 0, 0.0921659023, 0)
Button_2.Size = UDim2.new(0, 164, 0, 20)
Button_2.Font = Enum.Font.SourceSans
Button_2.Text = "Button_2"
Button_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Button_2.TextSize = 14.000

Name_Gui_about.Name = "Name_Gui_about"
Name_Gui_about.Parent = Drag

ImageLabel.Parent = Name_Gui_about
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0, 4, 0.115384616, 0)
ImageLabel.Size = UDim2.new(0, 23, 0, 20)
ImageLabel.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

TextLabel.Parent = Name_Gui_about
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.107744105, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 465, 0, 26)
TextLabel.Font = Enum.Font.Arial
TextLabel.Text = "Loader"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 15.000

Close.Name = "Close"
Close.Parent = Drag
Close.BackgroundColor3 = Color3.fromRGB(201, 78, 78)
Close.BorderColor3 = Color3.fromRGB(0, 0, 0)
Close.BorderSizePixel = 0
Close.Position = UDim2.new(0.905723929, 0, 0, 0)
Close.Size = UDim2.new(0, 50, 0, 20)
Close.Font = Enum.Font.ArialBold
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(246, 226, 225)
Close.TextSize = 14.000
Close.TextWrapped = true

-- Scripts:

local function KYZY_fake_script() -- File_Button.Script_OpenClose 
	local script = Instance.new('LocalScript', File_Button)

	script.Parent.MouseButton1Click:connect(function()
	    if script.Parent.Parent.Main_ButtonFile.Visible == false then
	        script.Parent.Parent.Main_ButtonFile.Visible = true
		
		else
	        script.Parent.Parent.Main_ButtonFile.Visible = false
	end 
	 end)
end
coroutine.wrap(KYZY_fake_script)()
local function LPZFMOH_fake_script() -- Drag.Drag_Frame 
	local script = Instance.new('LocalScript', Drag)

	local UserInputService = game:GetService("UserInputService")
	
	local gui = script.Parent
	
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	local function update(input)
		local delta = input.Position - dragStart
		gui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	end
	
	gui.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = gui.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	gui.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	UserInputService.InputChanged:Connect(function(input)
		if input == dragInput and dragging then
			update(input)
		end
	end)
end
coroutine.wrap(LPZFMOH_fake_script)()
local function ANQFWJB_fake_script() -- Close.Script_Close 
	local script = Instance.new('LocalScript', Close)

	local Frame = script.Parent.Parent
	
	script.Parent.MouseButton1Click:Connect(function()
		Frame.Visible = false
	end)
end
coroutine.wrap(ANQFWJB_fake_script)()
