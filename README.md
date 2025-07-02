local G2L = {};

-- StarterGui.omarStealCharcter
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["DisplayOrder"] = 9999;
G2L["1"]["Name"] = [[omarStealCharcter]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false;


-- StarterGui.omarStealCharcter.Controls
G2L["2"] = Instance.new("LocalScript", G2L["1"]);
G2L["2"]["Name"] = [[Controls]];


-- StarterGui.omarStealCharcter.Info
G2L["3"] = Instance.new("Frame", G2L["1"]);
G2L["3"]["Active"] = true;
G2L["3"]["ZIndex"] = 100000;
G2L["3"]["BorderSizePixel"] = 0;
G2L["3"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3"]["Size"] = UDim2.new(0.35232, 0, 0.04556, 0);
G2L["3"]["Position"] = UDim2.new(0.31101, 0, 0.21012, 0);
G2L["3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3"]["Name"] = [[Info]];


-- StarterGui.omarStealCharcter.Info.UICorner
G2L["4"] = Instance.new("UICorner", G2L["3"]);
G2L["4"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.UIStroke
G2L["5"] = Instance.new("UIStroke", G2L["3"]);
G2L["5"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["5"]["Thickness"] = 0;


-- StarterGui.omarStealCharcter.Info.GameName
G2L["6"] = Instance.new("TextLabel", G2L["3"]);
G2L["6"]["TextWrapped"] = true;
G2L["6"]["ZIndex"] = 1000000000;
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["TextSize"] = 14;
G2L["6"]["TextScaled"] = true;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["6"]["TextColor3"] = Color3.fromRGB(219, 219, 219);
G2L["6"]["BackgroundTransparency"] = 1;
G2L["6"]["Size"] = UDim2.new(0.66565, 0, 0.94601, 0);
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["Text"] = [[Steal a Character v0.1]];
G2L["6"]["Name"] = [[GameName]];
G2L["6"]["Position"] = UDim2.new(-0.03522, 0, 0, 0);


-- StarterGui.omarStealCharcter.Info.minimize
G2L["7"] = Instance.new("ImageButton", G2L["3"]);
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["ZIndex"] = 100000;
G2L["7"]["Image"] = [[rbxassetid://73326636016913]];
G2L["7"]["Size"] = UDim2.new(0.06928, 0, 0.6257, 0);
G2L["7"]["BackgroundTransparency"] = 1;
G2L["7"]["Name"] = [[minimize]];
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["Position"] = UDim2.new(0.83874, 0, 0.1414, 0);


-- StarterGui.omarStealCharcter.Info.XButton
G2L["8"] = Instance.new("ImageButton", G2L["3"]);
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8"]["ZIndex"] = 100000;
G2L["8"]["Image"] = [[rbxassetid://103344771690872]];
G2L["8"]["Size"] = UDim2.new(0.04077, 0, 0.65806, 0);
G2L["8"]["BackgroundTransparency"] = 1;
G2L["8"]["Name"] = [[XButton]];
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["Position"] = UDim2.new(0.93261, 0, 0.1414, 0);


-- StarterGui.omarStealCharcter.Info.sigma
G2L["9"] = Instance.new("Frame", G2L["3"]);
G2L["9"]["Active"] = true;
G2L["9"]["ZIndex"] = 0;
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["9"]["Size"] = UDim2.new(0.98697, 0, 11.01718, 0);
G2L["9"]["Position"] = UDim2.new(0.00451, 0, 0.92467, 0);
G2L["9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9"]["Name"] = [[sigma]];
G2L["9"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarStealCharcter.Info.sigma.UICorner
G2L["a"] = Instance.new("UICorner", G2L["9"]);
G2L["a"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame
G2L["b"] = Instance.new("Frame", G2L["9"]);
G2L["b"]["Visible"] = false;
G2L["b"]["Active"] = true;
G2L["b"]["ZIndex"] = 0;
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(47, 47, 47);
G2L["b"]["Size"] = UDim2.new(0.78204, 0, 1.00699, 0);
G2L["b"]["Position"] = UDim2.new(0.21796, 0, 0, 0);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Name"] = [[EspFrame]];
G2L["b"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.UICorner
G2L["c"] = Instance.new("UICorner", G2L["b"]);
G2L["c"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.playerimage
G2L["d"] = Instance.new("ImageLabel", G2L["b"]);
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d"]["Image"] = [[rbxasset://textures/ui/GuiImagePlaceholder.png]];
G2L["d"]["Size"] = UDim2.new(0.27217, 0, 0.29805, 0);
G2L["d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["BackgroundTransparency"] = 1;
G2L["d"]["Name"] = [[playerimage]];
G2L["d"]["Position"] = UDim2.new(0.01103, 0, 0.06069, 0);


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.playerimage.UICorner
G2L["e"] = Instance.new("UICorner", G2L["d"]);
G2L["e"]["CornerRadius"] = UDim.new(10, 10);


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Welcom
G2L["f"] = Instance.new("TextLabel", G2L["b"]);
G2L["f"]["TextWrapped"] = true;
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["TextSize"] = 14;
G2L["f"]["TextScaled"] = true;
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["TextDirection"] = Enum.TextDirection.LeftToRight;
G2L["f"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["f"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["BackgroundTransparency"] = 1;
G2L["f"]["Size"] = UDim2.new(0.63963, 0, 0.12589, 0);
G2L["f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["Text"] = [[WELCOM]];
G2L["f"]["Name"] = [[Welcom]];
G2L["f"]["Position"] = UDim2.new(0.31615, 0, 0.17866, 0);


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.credits
G2L["10"] = Instance.new("TextLabel", G2L["b"]);
G2L["10"]["TextWrapped"] = true;
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["TextSize"] = 14;
G2L["10"]["TextScaled"] = true;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["10"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["BackgroundTransparency"] = 1;
G2L["10"]["Size"] = UDim2.new(0.97655, 0, 0.17498, 0);
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["Text"] = [[Credits: omar: /dev/owner/designer/scripter]];
G2L["10"]["Name"] = [[credits]];
G2L["10"]["Position"] = UDim2.new(-0, 0, 0.44647, 0);


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Copy
G2L["11"] = Instance.new("TextButton", G2L["b"]);
G2L["11"]["TextWrapped"] = true;
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["TextSize"] = 14;
G2L["11"]["TextScaled"] = true;
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(137, 137, 137);
G2L["11"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["11"]["Size"] = UDim2.new(0.16083, 0, 0.10082, 0);
G2L["11"]["Name"] = [[Copy]];
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["Text"] = [[COPY]];
G2L["11"]["Position"] = UDim2.new(0.76289, 0, 0.85019, 0);


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Copy.UICorner
G2L["12"] = Instance.new("UICorner", G2L["11"]);
G2L["12"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Copy.UIStroke
G2L["13"] = Instance.new("UIStroke", G2L["11"]);
G2L["13"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["13"]["Thickness"] = 3;


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Copy.LocalScript
G2L["14"] = Instance.new("LocalScript", G2L["11"]);



-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Copy.soundclick
G2L["15"] = Instance.new("LocalScript", G2L["11"]);
G2L["15"]["Name"] = [[soundclick]];


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Copy
G2L["16"] = Instance.new("TextButton", G2L["b"]);
G2L["16"]["TextWrapped"] = true;
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["TextSize"] = 14;
G2L["16"]["TextScaled"] = true;
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(137, 137, 137);
G2L["16"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["16"]["Size"] = UDim2.new(0.14722, 0, 0.09403, 0);
G2L["16"]["Name"] = [[Copy]];
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["Text"] = [[COPY]];
G2L["16"]["Position"] = UDim2.new(0.82933, 0, 0.70494, 0);


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Copy.UICorner
G2L["17"] = Instance.new("UICorner", G2L["16"]);
G2L["17"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Copy.UIStroke
G2L["18"] = Instance.new("UIStroke", G2L["16"]);
G2L["18"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["18"]["Thickness"] = 3;


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Copy.LocalScript
G2L["19"] = Instance.new("LocalScript", G2L["16"]);



-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Copy.soundclick
G2L["1a"] = Instance.new("LocalScript", G2L["16"]);
G2L["1a"]["Name"] = [[soundclick]];


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Link
G2L["1b"] = Instance.new("TextLabel", G2L["b"]);
G2L["1b"]["TextWrapped"] = true;
G2L["1b"]["BorderSizePixel"] = 0;
G2L["1b"]["TextSize"] = 14;
G2L["1b"]["TextScaled"] = true;
G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1b"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1b"]["BackgroundTransparency"] = 1;
G2L["1b"]["Size"] = UDim2.new(0.78978, 0, 0.11608, 0);
G2L["1b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1b"]["Text"] = [[ discord: https://discord.gg/HJSfaPTDCX]];
G2L["1b"]["Name"] = [[Link]];
G2L["1b"]["Position"] = UDim2.new(0.01233, 0, 0.68098, 0);


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.subto
G2L["1c"] = Instance.new("TextLabel", G2L["b"]);
G2L["1c"]["TextWrapped"] = true;
G2L["1c"]["BorderSizePixel"] = 0;
G2L["1c"]["TextSize"] = 14;
G2L["1c"]["TextScaled"] = true;
G2L["1c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["BackgroundTransparency"] = 1;
G2L["1c"]["Size"] = UDim2.new(0.70246, 0, 0.12617, 0);
G2L["1c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["Text"] = [[Channel: omargamer8198]];
G2L["1c"]["Name"] = [[subto]];
G2L["1c"]["Position"] = UDim2.new(0.04627, 0, 0.82173, 0);


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Main
G2L["1d"] = Instance.new("LocalScript", G2L["b"]);
G2L["1d"]["Name"] = [[Main]];


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Toggle
G2L["1e"] = Instance.new("TextButton", G2L["b"]);
G2L["1e"]["TextWrapped"] = true;
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["TextSize"] = 14;
G2L["1e"]["TextScaled"] = true;
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(69, 69, 69);
G2L["1e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1e"]["Size"] = UDim2.new(0.18468, 0, 0.0741, 0);
G2L["1e"]["Name"] = [[Toggle]];
G2L["1e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["Text"] = [[Hide]];
G2L["1e"]["Visible"] = false;
G2L["1e"]["Position"] = UDim2.new(0.53122, 0, 0.0765, 0);


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Toggle.UICorner
G2L["1f"] = Instance.new("UICorner", G2L["1e"]);
G2L["1f"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Toggle.UIStroke
G2L["20"] = Instance.new("UIStroke", G2L["1e"]);
G2L["20"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["20"]["Thickness"] = 3;


-- StarterGui.omarStealCharcter.Info.sigma.Selection
G2L["21"] = Instance.new("Frame", G2L["9"]);
G2L["21"]["Active"] = true;
G2L["21"]["ZIndex"] = 0;
G2L["21"]["BorderSizePixel"] = 0;
G2L["21"]["BackgroundColor3"] = Color3.fromRGB(36, 36, 36);
G2L["21"]["Size"] = UDim2.new(0.2198, 0, 1.00699, 0);
G2L["21"]["Position"] = UDim2.new(0, 0, 0, 0);
G2L["21"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["21"]["Name"] = [[Selection]];


-- StarterGui.omarStealCharcter.Info.sigma.Selection.Esp
G2L["22"] = Instance.new("TextButton", G2L["21"]);
G2L["22"]["TextWrapped"] = true;
G2L["22"]["BorderSizePixel"] = 0;
G2L["22"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["TextSize"] = 14;
G2L["22"]["TextScaled"] = true;
G2L["22"]["BackgroundColor3"] = Color3.fromRGB(51, 94, 33);
G2L["22"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["22"]["Size"] = UDim2.new(0.77026, 0, 0.12599, 0);
G2L["22"]["Name"] = [[Esp]];
G2L["22"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["Text"] = [[Home]];
G2L["22"]["Position"] = UDim2.new(0.1103, 0, 0.05268, 0);


-- StarterGui.omarStealCharcter.Info.sigma.Selection.Esp.UICorner
G2L["23"] = Instance.new("UICorner", G2L["22"]);
G2L["23"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.Selection.Esp.UIStroke
G2L["24"] = Instance.new("UIStroke", G2L["22"]);
G2L["24"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["24"]["Thickness"] = 3;


-- StarterGui.omarStealCharcter.Info.sigma.Selection.UICorner
G2L["25"] = Instance.new("UICorner", G2L["21"]);
G2L["25"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.Selection.Main
G2L["26"] = Instance.new("TextButton", G2L["21"]);
G2L["26"]["TextWrapped"] = true;
G2L["26"]["BorderSizePixel"] = 0;
G2L["26"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["26"]["TextSize"] = 14;
G2L["26"]["TextScaled"] = true;
G2L["26"]["BackgroundColor3"] = Color3.fromRGB(51, 94, 33);
G2L["26"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["26"]["Size"] = UDim2.new(0.77025, 0, 0.11457, 0);
G2L["26"]["Name"] = [[Main]];
G2L["26"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["26"]["Text"] = [[Main]];
G2L["26"]["Position"] = UDim2.new(0.1103, 0, 0.21603, 0);


-- StarterGui.omarStealCharcter.Info.sigma.Selection.Main.UICorner
G2L["27"] = Instance.new("UICorner", G2L["26"]);
G2L["27"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.Selection.Main.UIStroke
G2L["28"] = Instance.new("UIStroke", G2L["26"]);
G2L["28"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["28"]["Thickness"] = 2;


-- StarterGui.omarStealCharcter.Info.sigma.Selection.Misc
G2L["29"] = Instance.new("TextButton", G2L["21"]);
G2L["29"]["TextWrapped"] = true;
G2L["29"]["BorderSizePixel"] = 0;
G2L["29"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["TextSize"] = 14;
G2L["29"]["TextScaled"] = true;
G2L["29"]["BackgroundColor3"] = Color3.fromRGB(51, 94, 33);
G2L["29"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["29"]["Size"] = UDim2.new(0.77025, 0, 0.11457, 0);
G2L["29"]["Name"] = [[Misc]];
G2L["29"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["Text"] = [[Misc]];
G2L["29"]["Position"] = UDim2.new(0.11, 0, 0.364, 0);


-- StarterGui.omarStealCharcter.Info.sigma.Selection.Misc.UICorner
G2L["2a"] = Instance.new("UICorner", G2L["29"]);
G2L["2a"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.Selection.Misc.UIStroke
G2L["2b"] = Instance.new("UIStroke", G2L["29"]);
G2L["2b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["2b"]["Thickness"] = 2;


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame
G2L["2c"] = Instance.new("Frame", G2L["9"]);
G2L["2c"]["Visible"] = false;
G2L["2c"]["Active"] = true;
G2L["2c"]["ZIndex"] = 0;
G2L["2c"]["BorderSizePixel"] = 0;
G2L["2c"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["2c"]["Size"] = UDim2.new(0.7802, 0, 1.00699, 0);
G2L["2c"]["Position"] = UDim2.new(0.2198, 0, 0, 0);
G2L["2c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2c"]["Name"] = [[MainFrame]];
G2L["2c"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.UIStroke
G2L["2d"] = Instance.new("UIStroke", G2L["2c"]);
G2L["2d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["2d"]["Thickness"] = 3;


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.UICorner
G2L["2e"] = Instance.new("UICorner", G2L["2c"]);
G2L["2e"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first1
G2L["2f"] = Instance.new("TextButton", G2L["2c"]);
G2L["2f"]["TextWrapped"] = true;
G2L["2f"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["2f"]["BorderSizePixel"] = 0;
G2L["2f"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["2f"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["2f"]["TextSize"] = 14;
G2L["2f"]["TextScaled"] = true;
G2L["2f"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2f"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2f"]["Size"] = UDim2.new(0.82802, 0, 0.08816, 0);
G2L["2f"]["Name"] = [[first1]];
G2L["2f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2f"]["Text"] = [[Collect Money]];
G2L["2f"]["Position"] = UDim2.new(0.03515, 0, 0.07023, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first1.UICorner
G2L["30"] = Instance.new("UICorner", G2L["2f"]);
G2L["30"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first1.UIStroke
G2L["31"] = Instance.new("UIStroke", G2L["2f"]);
G2L["31"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["31"]["Thickness"] = 1.7;
G2L["31"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first1.soundclick
G2L["32"] = Instance.new("LocalScript", G2L["2f"]);
G2L["32"]["Name"] = [[soundclick]];


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first1.fingerprint
G2L["33"] = Instance.new("ImageLabel", G2L["2f"]);
G2L["33"]["BorderSizePixel"] = 0;
G2L["33"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["33"]["Image"] = [[rbxassetid://12333784627]];
G2L["33"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["33"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["33"]["BackgroundTransparency"] = 1;
G2L["33"]["Name"] = [[fingerprint]];
G2L["33"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first1.UIPadding
G2L["34"] = Instance.new("UIPadding", G2L["2f"]);
G2L["34"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first1.realone
G2L["35"] = Instance.new("LocalScript", G2L["2f"]);
G2L["35"]["Name"] = [[realone]];


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first2
G2L["36"] = Instance.new("TextButton", G2L["2c"]);
G2L["36"]["TextWrapped"] = true;
G2L["36"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["36"]["BorderSizePixel"] = 0;
G2L["36"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["36"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["36"]["TextSize"] = 14;
G2L["36"]["TextScaled"] = true;
G2L["36"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["36"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["36"]["Size"] = UDim2.new(0.82802, 0, 0.08816, 0);
G2L["36"]["Name"] = [[first2]];
G2L["36"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["36"]["Text"] = [[Auto Lock]];
G2L["36"]["Position"] = UDim2.new(0.03515, 0, 0.19811, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first2.UICorner
G2L["37"] = Instance.new("UICorner", G2L["36"]);
G2L["37"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first2.UIStroke
G2L["38"] = Instance.new("UIStroke", G2L["36"]);
G2L["38"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["38"]["Thickness"] = 1.7;
G2L["38"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first2.soundclick
G2L["39"] = Instance.new("LocalScript", G2L["36"]);
G2L["39"]["Name"] = [[soundclick]];


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first2.fingerprint
G2L["3a"] = Instance.new("ImageLabel", G2L["36"]);
G2L["3a"]["BorderSizePixel"] = 0;
G2L["3a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3a"]["Image"] = [[rbxassetid://12333784627]];
G2L["3a"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["3a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3a"]["BackgroundTransparency"] = 1;
G2L["3a"]["Name"] = [[fingerprint]];
G2L["3a"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first2.UIPadding
G2L["3b"] = Instance.new("UIPadding", G2L["36"]);
G2L["3b"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first2.LocalScript
G2L["3c"] = Instance.new("LocalScript", G2L["36"]);



-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first3
G2L["3d"] = Instance.new("TextButton", G2L["2c"]);
G2L["3d"]["TextWrapped"] = true;
G2L["3d"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["3d"]["BorderSizePixel"] = 0;
G2L["3d"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["3d"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["3d"]["TextSize"] = 14;
G2L["3d"]["TextScaled"] = true;
G2L["3d"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3d"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3d"]["Size"] = UDim2.new(0.82802, 0, 0.08816, 0);
G2L["3d"]["Name"] = [[first3]];
G2L["3d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3d"]["Text"] = [[Faster Steal/Purchase]];
G2L["3d"]["Position"] = UDim2.new(0.03515, 0, 0.31184, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first3.UICorner
G2L["3e"] = Instance.new("UICorner", G2L["3d"]);
G2L["3e"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first3.UIStroke
G2L["3f"] = Instance.new("UIStroke", G2L["3d"]);
G2L["3f"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["3f"]["Thickness"] = 1.7;
G2L["3f"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first3.soundclick
G2L["40"] = Instance.new("LocalScript", G2L["3d"]);
G2L["40"]["Name"] = [[soundclick]];


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first3.fingerprint
G2L["41"] = Instance.new("ImageLabel", G2L["3d"]);
G2L["41"]["BorderSizePixel"] = 0;
G2L["41"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["41"]["Image"] = [[rbxassetid://12333784627]];
G2L["41"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["41"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["41"]["BackgroundTransparency"] = 1;
G2L["41"]["Name"] = [[fingerprint]];
G2L["41"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first3.UIPadding
G2L["42"] = Instance.new("UIPadding", G2L["3d"]);
G2L["42"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first3.LocalScript
G2L["43"] = Instance.new("LocalScript", G2L["3d"]);



-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first4
G2L["44"] = Instance.new("TextButton", G2L["2c"]);
G2L["44"]["TextWrapped"] = true;
G2L["44"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["44"]["BorderSizePixel"] = 0;
G2L["44"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["44"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["44"]["TextSize"] = 14;
G2L["44"]["TextScaled"] = true;
G2L["44"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["44"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["44"]["Size"] = UDim2.new(0.82802, 0, 0.08816, 0);
G2L["44"]["Name"] = [[first4]];
G2L["44"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["44"]["Text"] = [[Auto Rebirth]];
G2L["44"]["Position"] = UDim2.new(0.03515, 0, 0.42557, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first4.UICorner
G2L["45"] = Instance.new("UICorner", G2L["44"]);
G2L["45"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first4.UIStroke
G2L["46"] = Instance.new("UIStroke", G2L["44"]);
G2L["46"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["46"]["Thickness"] = 1.7;
G2L["46"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first4.soundclick
G2L["47"] = Instance.new("LocalScript", G2L["44"]);
G2L["47"]["Name"] = [[soundclick]];


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first4.fingerprint
G2L["48"] = Instance.new("ImageLabel", G2L["44"]);
G2L["48"]["BorderSizePixel"] = 0;
G2L["48"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["48"]["Image"] = [[rbxassetid://12333784627]];
G2L["48"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["48"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["48"]["BackgroundTransparency"] = 1;
G2L["48"]["Name"] = [[fingerprint]];
G2L["48"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first4.UIPadding
G2L["49"] = Instance.new("UIPadding", G2L["44"]);
G2L["49"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first4.LocalScript
G2L["4a"] = Instance.new("LocalScript", G2L["44"]);



-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame
G2L["4b"] = Instance.new("Frame", G2L["9"]);
G2L["4b"]["Active"] = true;
G2L["4b"]["ZIndex"] = 0;
G2L["4b"]["BorderSizePixel"] = 0;
G2L["4b"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["4b"]["Size"] = UDim2.new(0.7802, 0, 1.00699, 0);
G2L["4b"]["Position"] = UDim2.new(0.2198, 0, 0, 0);
G2L["4b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4b"]["Name"] = [[MiscFrame]];
G2L["4b"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.UIStroke
G2L["4c"] = Instance.new("UIStroke", G2L["4b"]);
G2L["4c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["4c"]["Thickness"] = 3;


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.UICorner
G2L["4d"] = Instance.new("UICorner", G2L["4b"]);
G2L["4d"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first2
G2L["4e"] = Instance.new("TextButton", G2L["4b"]);
G2L["4e"]["TextWrapped"] = true;
G2L["4e"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["4e"]["BorderSizePixel"] = 0;
G2L["4e"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["4e"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["4e"]["TextSize"] = 14;
G2L["4e"]["TextScaled"] = true;
G2L["4e"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4e"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4e"]["Size"] = UDim2.new(0.82802, 0, 0.09934, 0);
G2L["4e"]["Name"] = [[first2]];
G2L["4e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4e"]["Text"] = [[Auto Buy Speed Coil]];
G2L["4e"]["Position"] = UDim2.new(0.03515, 0, 0.04355, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first2.UICorner
G2L["4f"] = Instance.new("UICorner", G2L["4e"]);
G2L["4f"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first2.UIStroke
G2L["50"] = Instance.new("UIStroke", G2L["4e"]);
G2L["50"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["50"]["Thickness"] = 1.7;
G2L["50"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first2.soundclick
G2L["51"] = Instance.new("LocalScript", G2L["4e"]);
G2L["51"]["Name"] = [[soundclick]];


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first2.fingerprint
G2L["52"] = Instance.new("ImageLabel", G2L["4e"]);
G2L["52"]["BorderSizePixel"] = 0;
G2L["52"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["52"]["Image"] = [[rbxassetid://12333784627]];
G2L["52"]["Size"] = UDim2.new(0.10999, 0, 0.9265, 0);
G2L["52"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["52"]["BackgroundTransparency"] = 1;
G2L["52"]["Name"] = [[fingerprint]];
G2L["52"]["Position"] = UDim2.new(0.88888, 0, 0.02538, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first2.UIPadding
G2L["53"] = Instance.new("UIPadding", G2L["4e"]);
G2L["53"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first2.LocalScript
G2L["54"] = Instance.new("LocalScript", G2L["4e"]);



-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.info
G2L["55"] = Instance.new("TextLabel", G2L["4b"]);
G2L["55"]["TextWrapped"] = true;
G2L["55"]["BorderSizePixel"] = 0;
G2L["55"]["TextSize"] = 14;
G2L["55"]["TextScaled"] = true;
G2L["55"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["55"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["55"]["TextColor3"] = Color3.fromRGB(61, 230, 14);
G2L["55"]["BackgroundTransparency"] = 1;
G2L["55"]["Size"] = UDim2.new(0.14452, 0, 0.11392, 0);
G2L["55"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["55"]["Text"] = [[Cost 100k]];
G2L["55"]["Name"] = [[info]];
G2L["55"]["Position"] = UDim2.new(0.86317, 0, 0.02897, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first3
G2L["56"] = Instance.new("TextButton", G2L["4b"]);
G2L["56"]["TextWrapped"] = true;
G2L["56"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["56"]["BorderSizePixel"] = 0;
G2L["56"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["56"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["56"]["TextSize"] = 14;
G2L["56"]["TextScaled"] = true;
G2L["56"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["56"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["56"]["Size"] = UDim2.new(0.82802, 0, 0.09934, 0);
G2L["56"]["Name"] = [[first3]];
G2L["56"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["56"]["Text"] = [[Auto Buy Fast]];
G2L["56"]["Position"] = UDim2.new(0.03798, 0, 0.17186, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first3.UICorner
G2L["57"] = Instance.new("UICorner", G2L["56"]);
G2L["57"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first3.UIStroke
G2L["58"] = Instance.new("UIStroke", G2L["56"]);
G2L["58"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["58"]["Thickness"] = 1.7;
G2L["58"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first3.soundclick
G2L["59"] = Instance.new("LocalScript", G2L["56"]);
G2L["59"]["Name"] = [[soundclick]];


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first3.fingerprint
G2L["5a"] = Instance.new("ImageLabel", G2L["56"]);
G2L["5a"]["BorderSizePixel"] = 0;
G2L["5a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5a"]["Image"] = [[rbxassetid://12333784627]];
G2L["5a"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["5a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5a"]["BackgroundTransparency"] = 1;
G2L["5a"]["Name"] = [[fingerprint]];
G2L["5a"]["Position"] = UDim2.new(0.86407, 0, 0.02538, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first3.UIPadding
G2L["5b"] = Instance.new("UIPadding", G2L["56"]);
G2L["5b"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first3.LocalScript
G2L["5c"] = Instance.new("LocalScript", G2L["56"]);



-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.info
G2L["5d"] = Instance.new("TextLabel", G2L["4b"]);
G2L["5d"]["TextWrapped"] = true;
G2L["5d"]["BorderSizePixel"] = 0;
G2L["5d"]["TextSize"] = 14;
G2L["5d"]["TextScaled"] = true;
G2L["5d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5d"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5d"]["TextColor3"] = Color3.fromRGB(61, 230, 14);
G2L["5d"]["BackgroundTransparency"] = 1;
G2L["5d"]["Size"] = UDim2.new(0.14452, 0, 0.11392, 0);
G2L["5d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5d"]["Text"] = [[Cost 50k]];
G2L["5d"]["Name"] = [[info]];
G2L["5d"]["Position"] = UDim2.new(0.866, 0, 0.16311, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third
G2L["5e"] = Instance.new("TextButton", G2L["4b"]);
G2L["5e"]["TextWrapped"] = true;
G2L["5e"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["5e"]["BorderSizePixel"] = 0;
G2L["5e"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["5e"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["5e"]["TextSize"] = 14;
G2L["5e"]["TextScaled"] = true;
G2L["5e"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5e"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5e"]["Size"] = UDim2.new(0.79685, 0, 0.08073, 0);
G2L["5e"]["Name"] = [[third]];
G2L["5e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5e"]["Text"] = [[Auto Anti Afk]];
G2L["5e"]["Position"] = UDim2.new(0.05059, 0, 0.40047, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.UICorner
G2L["5f"] = Instance.new("UICorner", G2L["5e"]);
G2L["5f"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.UIStroke
G2L["60"] = Instance.new("UIStroke", G2L["5e"]);
G2L["60"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["60"]["Thickness"] = 1.7;
G2L["60"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.soundclick
G2L["61"] = Instance.new("LocalScript", G2L["5e"]);
G2L["61"]["Name"] = [[soundclick]];


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.fingerprint
G2L["62"] = Instance.new("ImageLabel", G2L["5e"]);
G2L["62"]["BorderSizePixel"] = 0;
G2L["62"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["62"]["Image"] = [[rbxassetid://12333784627]];
G2L["62"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["62"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["62"]["BackgroundTransparency"] = 1;
G2L["62"]["Name"] = [[fingerprint]];
G2L["62"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.UIPadding
G2L["63"] = Instance.new("UIPadding", G2L["5e"]);
G2L["63"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.LocalScript
G2L["64"] = Instance.new("LocalScript", G2L["5e"]);



-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third
G2L["65"] = Instance.new("TextButton", G2L["4b"]);
G2L["65"]["TextWrapped"] = true;
G2L["65"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["65"]["BorderSizePixel"] = 0;
G2L["65"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["65"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["65"]["TextSize"] = 14;
G2L["65"]["TextScaled"] = true;
G2L["65"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["65"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["65"]["Size"] = UDim2.new(0.79685, 0, 0.08456, 0);
G2L["65"]["Name"] = [[third]];
G2L["65"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["65"]["Text"] = [[Speed]];
G2L["65"]["Position"] = UDim2.new(0.05626, 0, 0.29623, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.UICorner
G2L["66"] = Instance.new("UICorner", G2L["65"]);
G2L["66"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.UIStroke
G2L["67"] = Instance.new("UIStroke", G2L["65"]);
G2L["67"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["67"]["Thickness"] = 1.7;
G2L["67"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.soundclick
G2L["68"] = Instance.new("LocalScript", G2L["65"]);
G2L["68"]["Name"] = [[soundclick]];


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.fingerprint
G2L["69"] = Instance.new("ImageLabel", G2L["65"]);
G2L["69"]["BorderSizePixel"] = 0;
G2L["69"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["69"]["Image"] = [[rbxassetid://12333784627]];
G2L["69"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["69"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["69"]["BackgroundTransparency"] = 1;
G2L["69"]["Name"] = [[fingerprint]];
G2L["69"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.UIPadding
G2L["6a"] = Instance.new("UIPadding", G2L["65"]);
G2L["6a"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.LocalScript
G2L["6b"] = Instance.new("LocalScript", G2L["65"]);



-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third
G2L["6c"] = Instance.new("TextButton", G2L["4b"]);
G2L["6c"]["TextWrapped"] = true;
G2L["6c"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["6c"]["BorderSizePixel"] = 0;
G2L["6c"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["6c"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["6c"]["TextSize"] = 14;
G2L["6c"]["TextScaled"] = true;
G2L["6c"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6c"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6c"]["Size"] = UDim2.new(0.79685, 0, 0.08456, 0);
G2L["6c"]["Name"] = [[third]];
G2L["6c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6c"]["Text"] = [[Hitbox Aura]];
G2L["6c"]["Position"] = UDim2.new(0.05342, 0, 0.50036, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.UICorner
G2L["6d"] = Instance.new("UICorner", G2L["6c"]);
G2L["6d"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.UIStroke
G2L["6e"] = Instance.new("UIStroke", G2L["6c"]);
G2L["6e"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["6e"]["Thickness"] = 1.7;
G2L["6e"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.soundclick
G2L["6f"] = Instance.new("LocalScript", G2L["6c"]);
G2L["6f"]["Name"] = [[soundclick]];


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.fingerprint
G2L["70"] = Instance.new("ImageLabel", G2L["6c"]);
G2L["70"]["BorderSizePixel"] = 0;
G2L["70"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["70"]["Image"] = [[rbxassetid://12333784627]];
G2L["70"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["70"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["70"]["BackgroundTransparency"] = 1;
G2L["70"]["Name"] = [[fingerprint]];
G2L["70"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.UIPadding
G2L["71"] = Instance.new("UIPadding", G2L["6c"]);
G2L["71"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.LocalScript
G2L["72"] = Instance.new("LocalScript", G2L["6c"]);



-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third
G2L["73"] = Instance.new("TextButton", G2L["4b"]);
G2L["73"]["TextWrapped"] = true;
G2L["73"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["73"]["BorderSizePixel"] = 0;
G2L["73"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["73"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["73"]["TextSize"] = 14;
G2L["73"]["TextScaled"] = true;
G2L["73"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["73"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["73"]["Size"] = UDim2.new(0.79685, 0, 0.08456, 0);
G2L["73"]["Name"] = [[third]];
G2L["73"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["73"]["Text"] = [[Complete Steal (N)]];
G2L["73"]["Position"] = UDim2.new(0.05626, 0, 0.60826, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.UICorner
G2L["74"] = Instance.new("UICorner", G2L["73"]);
G2L["74"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.UIStroke
G2L["75"] = Instance.new("UIStroke", G2L["73"]);
G2L["75"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["75"]["Thickness"] = 1.7;
G2L["75"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.soundclick
G2L["76"] = Instance.new("LocalScript", G2L["73"]);
G2L["76"]["Name"] = [[soundclick]];


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.UIPadding
G2L["77"] = Instance.new("UIPadding", G2L["73"]);
G2L["77"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.LocalScript
G2L["78"] = Instance.new("LocalScript", G2L["73"]);



-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.fingerprint
G2L["79"] = Instance.new("ImageLabel", G2L["73"]);
G2L["79"]["BorderSizePixel"] = 0;
G2L["79"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["79"]["Image"] = [[rbxassetid://12333784627]];
G2L["79"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["79"]["Visible"] = false;
G2L["79"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["79"]["BackgroundTransparency"] = 1;
G2L["79"]["Name"] = [[fingerprint]];
G2L["79"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third
G2L["7a"] = Instance.new("TextButton", G2L["4b"]);
G2L["7a"]["TextWrapped"] = true;
G2L["7a"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["7a"]["BorderSizePixel"] = 0;
G2L["7a"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["7a"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["7a"]["TextSize"] = 1;
G2L["7a"]["TextScaled"] = true;
G2L["7a"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7a"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7a"]["Size"] = UDim2.new(0.79685, 0, 0.08456, 0);
G2L["7a"]["Name"] = [[third]];
G2L["7a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7a"]["Text"] = [[Check if Anyone have Godzilla]];
G2L["7a"]["Position"] = UDim2.new(0.05626, 0, 0.71033, 0);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.UICorner
G2L["7b"] = Instance.new("UICorner", G2L["7a"]);
G2L["7b"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.UIStroke
G2L["7c"] = Instance.new("UIStroke", G2L["7a"]);
G2L["7c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["7c"]["Thickness"] = 1.7;
G2L["7c"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.soundclick
G2L["7d"] = Instance.new("LocalScript", G2L["7a"]);
G2L["7d"]["Name"] = [[soundclick]];


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.UIPadding
G2L["7e"] = Instance.new("UIPadding", G2L["7a"]);
G2L["7e"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.LocalScript
G2L["7f"] = Instance.new("LocalScript", G2L["7a"]);



-- StarterGui.omarStealCharcter.Info.drag localscript
G2L["80"] = Instance.new("LocalScript", G2L["3"]);
G2L["80"]["Name"] = [[drag localscript]];


-- StarterGui.omarStealCharcter.Changer
G2L["81"] = Instance.new("LocalScript", G2L["1"]);
G2L["81"]["Name"] = [[Changer]];


-- StarterGui.omarStealCharcter.Controls
local function C_2()
local script = G2L["2"];
	local TweenService = game:GetService("TweenService")
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	local gui = player:WaitForChild("PlayerGui"):WaitForChild("omarStealCharcter")
	
	local info = gui:WaitForChild("Info") -- Header
	local sigma = info:WaitForChild("sigma") -- Content under header
	
	local minimizeBtn = info:WaitForChild("minimize")
	local xButton = info:WaitForChild("XButton")
	
	local isMinimized = false
	local tweenTime = 0.35
	
	local function minimize()
		-- Just hide sigma without tweening position (since it's inside Info)
		sigma.Visible = false
	end
	
	local function maximize()
		-- Make sigma visible again
		sigma.Visible = true
	end
	
	minimizeBtn.MouseButton1Click:Connect(function()
		if not isMinimized then
			minimize()
		else
			maximize()
		end
		isMinimized = not isMinimized
	end)
	
	xButton.MouseButton1Click:Connect(function()
		for _, descendant in ipairs(gui:GetDescendants()) do
			if descendant:IsA("TextButton") or descendant:IsA("ImageButton") or descendant:IsA("TextLabel") then
				for _, child in ipairs(descendant:GetChildren()) do
					if child:IsA("LocalScript") then
						child.Disabled = true
					end
				end
			end
		end
	
		wait(0.2)
		gui:Destroy()
	end)
	
end;
task.spawn(C_2);
-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Copy.LocalScript
local function C_14()
local script = G2L["14"];
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		if setclipboard then
			setclipboard("omargamer8198")
			game.StarterGui:SetCore("SendNotification", {
				Title = "Success!",
				Text = "Copied Youtube Link",
				Duration = 3
			})
		else
			warn("Clipboard function not available.")
		end
	end)
	
end;
task.spawn(C_14);
-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Copy.soundclick
local function C_15()
local script = G2L["15"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_15);
-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Copy.LocalScript
local function C_19()
local script = G2L["19"];
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		if setclipboard then
			setclipboard("https://discord.gg/HJSfaPTDCX")
			game.StarterGui:SetCore("SendNotification", {
				Title = "Success!",
				Text = "Copied Discord Link",
				Duration = 3
			})
		else
			warn("Clipboard function not available.")
		end
	end)
	
end;
task.spawn(C_19);
-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Copy.soundclick
local function C_1a()
local script = G2L["1a"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_1a);
-- StarterGui.omarStealCharcter.Info.sigma.EspFrame.Main
local function C_1d()
local script = G2L["1d"];
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	
	-- UI references
	local gui = script.Parent
	local textLabel = gui:WaitForChild("Welcom")
	local playerImage = gui:WaitForChild("playerimage")
	local toggleButton = gui:WaitForChild("Toggle")
	
	-- Headshot image
	playerImage.Image = "https://www.roblox.com/headshot-thumbnail/image?userId=" .. player.UserId .. "&width=420&height=420&format=png"
	
	-- Enable RichText
	textLabel.RichText = true
	toggleButton.Visible = false -- Hide toggle at start
	
	local welcomeText = "Welcome " .. player.Name
	
	-- Function to type text with optional color
	local function typeText(text, speed, color)
		for i = 1, #text do
			local part = text:sub(1, i)
			if color then
				textLabel.Text = "<font color='" .. color .. "'>" .. part .. "</font>"
			else
				textLabel.Text = part
			end
			wait(speed)
		end
	end
	
	-- Function to delete text while keeping color
	local function deleteRichText(text, speed, color)
		for i = #text, 0, -1 do
			local part = text:sub(1, i)
			if color then
				textLabel.Text = "<font color='" .. color .. "'>" .. part .. "</font>"
			else
				textLabel.Text = part
			end
			wait(speed)
		end
	end
	
	-- MAIN SEQUENCE
	
	-- Step 1: Type in RED
	typeText(welcomeText, 0.1, "rgb(255,0,0)")
	wait(1)
	
	-- Step 2: Delete in RED
	deleteRichText(welcomeText, 0.05, "rgb(255,0,0)")
	wait(0.5)
	
	-- Step 3: Type again in normal color
	typeText(welcomeText, 0.1, nil)
	wait(0.5)
	
	-- Step 4: Show the Toggle button
	toggleButton.Visible = true
	toggleButton.Text = "Hide"
	
	-- Step 5: Toggle behavior
	local visible = true
	
	toggleButton.MouseButton1Click:Connect(function()
		visible = not visible
		textLabel.Visible = visible
		toggleButton.Text = visible and "Hide" or "Show"
	end)
	
end;
task.spawn(C_1d);
-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first1.soundclick
local function C_32()
local script = G2L["32"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_32);
-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first1.realone
local function C_35()
local script = G2L["35"];
	-- LocalScript (inside your TextButton)
	
	local button       = script.Parent
	local uiStroke     = button:FindFirstChildOfClass("UIStroke")
	local fingerprint  = button:FindFirstChild("fingerprint")
	assert(uiStroke and fingerprint, "UIStroke or fingerprint ImageLabel not found!")
	
	-- store original colors to restore later
	local origStrokeColor = uiStroke.Color
	local origImageColor  = fingerprint.ImageColor3
	
	local Players = game:GetService("Players")
	local player  = Players.LocalPlayer
	
	-- helper to fire a touch on a part
	local function fireTouch(part)
		local char = player.Character or player.CharacterAdded:Wait()
		local hrp  = char:WaitForChild("HumanoidRootPart")
		firetouchinterest(part, hrp, 0)
		firetouchinterest(part, hrp, 1)
	end
	
	-- traverse to your Studio’s Collect parts and fire them
	local function triggerCollects()
		local studios = workspace:FindFirstChild("Studios")
		if not studios then return end
	
		local targetText = player.Name .. "'s Studio"
	
		for _, studioModel in ipairs(studios:GetChildren()) do
			if studioModel:IsA("Model") then
				local sign = studioModel:FindFirstChild("Sign")
				local label = sign
					and sign:FindFirstChild("SurfaceGui")
					and sign.SurfaceGui:FindFirstChild("TextLabel")
	
				if label and label.Text == targetText then
					local pfolder = studioModel:FindFirstChild("Platforms")
					if pfolder then
						for _, plat in ipairs(pfolder:GetChildren()) do
							if plat:IsA("Model") then
								-- only if it contains another Model
								local nested = false
								for _, c in ipairs(plat:GetChildren()) do
									if c:IsA("Model") then
										nested = true
										break
									end
								end
								if nested then
									local collectPart = plat:FindFirstChild("Collect")
									if collectPart and collectPart:IsA("BasePart") then
										fireTouch(collectPart)
									end
								end
							end
						end
					end
					return  -- stop after the one matching Studio
				end
			end
		end
	end
	
	-- toggle state & auto-loop handle
	local isOn = false
	local loopThread
	
	button.MouseButton1Click:Connect(function()
		isOn = not isOn
	
		if isOn then
			-- turn green
			uiStroke.Color = Color3.new(0,1,0)
			fingerprint.ImageColor3 = Color3.new(0,1,0)
	
			-- start auto-loop
			loopThread = coroutine.create(function()
				while isOn do
					triggerCollects()
					wait(0.5)  -- adjust the interval as needed
				end
			end)
			coroutine.resume(loopThread)
		else
			-- turn off: restore colors and stop auto-loop
			uiStroke.Color = origStrokeColor
			fingerprint.ImageColor3 = origImageColor
			-- flag isOn = false breaks the loop; no explicit cancel needed
		end
	end)
	
end;
task.spawn(C_35);
-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first2.soundclick
local function C_39()
local script = G2L["39"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_39);
-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first2.LocalScript
local function C_3c()
local script = G2L["3c"];
	-- LocalScript (put inside your TextButton)
	
	local button       = script.Parent
	local uiStroke     = button:FindFirstChildOfClass("UIStroke")
	local fingerprint  = button:FindFirstChild("fingerprint")
	assert(uiStroke and fingerprint, "UIStroke or fingerprint ImageLabel not found!")
	
	-- store original colors
	local origStrokeColor = uiStroke.Color
	local origImageColor  = fingerprint.ImageColor3
	
	local Players = game:GetService("Players")
	local player  = Players.LocalPlayer
	
	-- find your studio Model by matching "<PlayerName>'s Studio" on its Sign.TextLabel
	local function findMyStudioModel()
		local studios = workspace:FindFirstChild("Studios")
		if not studios then return nil end
	
		local targetText = player.Name .. "'s Studio"
		for _, mdl in ipairs(studios:GetChildren()) do
			if mdl:IsA("Model") then
				local sign  = mdl:FindFirstChild("Sign")
				local gui   = sign and sign:FindFirstChild("SurfaceGui")
				local label = gui  and gui:FindFirstChild("TextLabel")
				if label and label.Text == targetText then
					return mdl
				end
			end
		end
		return nil
	end
	
	-- fire a TouchInterest by touching the part with your HumanoidRootPart
	local function tapPart(part)
		local char = player.Character or player.CharacterAdded:Wait()
		local hrp  = char:WaitForChild("HumanoidRootPart")
		firetouchinterest(part, hrp, 0)
		firetouchinterest(part, hrp, 1)
	end
	
	-- the routine that finds the TouchInterest under LockOneMin.Hitbox and fires it
	local function triggerLockHit()
		local studio = findMyStudioModel()
		if not studio then return end
	
		local lockOne = studio:FindFirstChild("LockOneMin")
		if not lockOne then return end
	
		local hitbox = lockOne:FindFirstChild("Hitbox")
		if not hitbox or not hitbox:IsA("BasePart") then return end
	
		-- this will simulate the touch
		tapPart(hitbox)
	end
	
	-- toggle state & auto-loop handle
	local isOn = false
	local loopThread
	
	button.MouseButton1Click:Connect(function()
		isOn = not isOn
	
		if isOn then
			-- switch UI to green
			uiStroke.Color = Color3.new(0,1,0)
			fingerprint.ImageColor3 = Color3.new(0,1,0)
	
			-- start auto-loop
			loopThread = coroutine.create(function()
				while isOn do
					triggerLockHit()
					wait(0.5)  -- fire once per second; adjust as needed
				end
			end)
			coroutine.resume(loopThread)
		else
			-- restore original UI
			uiStroke.Color = origStrokeColor
			fingerprint.ImageColor3 = origImageColor
			-- exiting the loop automatically
		end
	end)
	
end;
task.spawn(C_3c);
-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first3.soundclick
local function C_40()
local script = G2L["40"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_40);
-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first3.LocalScript
local function C_43()
local script = G2L["43"];
	local button       = script.Parent
	local uiStroke     = button:FindFirstChildOfClass("UIStroke")
	local fingerprint  = button:FindFirstChild("fingerprint")  -- your ImageLabel
	assert(uiStroke, "UIStroke not found!")
	assert(fingerprint and fingerprint:IsA("ImageLabel"), "ImageLabel named 'fingerprint' not found!")
	
	-- Store original colors so we can restore them
	local originalStrokeColor   = uiStroke.Color
	local originalImageColor3   = fingerprint.ImageColor3
	
	local on = false
	
	local function setPromptsHoldDurationZero()
		for _, obj in ipairs(workspace:GetDescendants()) do
			if obj:IsA("ProximityPrompt") then
				obj.HoldDuration = 0
			end
		end
	end
	
	local function toggle()
		on = not on
	
		if on then
			-- turn visuals green
			uiStroke.Color = Color3.fromRGB(0, 255, 0)
			fingerprint.ImageColor3 = Color3.fromRGB(0, 255, 0)
	
			-- start background loop
			spawn(function()
				while on do
					setPromptsHoldDurationZero()
					wait(5)
				end
			end)
	
		else
			-- restore visuals
			uiStroke.Color = originalStrokeColor
			fingerprint.ImageColor3 = originalImageColor3
		end
	end
	
	-- hook up click
	button.MouseButton1Click:Connect(toggle)
end;
task.spawn(C_43);
-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first4.soundclick
local function C_47()
local script = G2L["47"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_47);
-- StarterGui.omarStealCharcter.Info.sigma.MainFrame.first4.LocalScript
local function C_4a()
local script = G2L["4a"];
	--!strict
	local button = script.Parent
	local uistroke = button:WaitForChild("UIStroke")
	local fingerprint = button:WaitForChild("fingerprint")
	
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local AttemptRebirth = ReplicatedStorage:WaitForChild("RemoteEvents"):WaitForChild("AttemptRebirth")
	
	local isActive = false
	local loopThread = nil
	
	-- Store original colors
	local originalStrokeColor = uistroke.Color
	local originalImageColor = fingerprint.ImageColor3
	
	local greenColor = Color3.fromRGB(0, 255, 0)
	
	local function startLoop()
		loopThread = task.spawn(function()
			while isActive do
				AttemptRebirth:FireServer()
				task.wait(0.5)
			end
		end)
	end
	
	button.MouseButton1Click:Connect(function()
		isActive = not isActive
	
		if isActive then
			uistroke.Color = greenColor
			fingerprint.ImageColor3 = greenColor
			startLoop()
		else
			uistroke.Color = originalStrokeColor
			fingerprint.ImageColor3 = originalImageColor
			isActive = false
		end
	end)
	
end;
task.spawn(C_4a);
-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first2.soundclick
local function C_51()
local script = G2L["51"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_51);
-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first2.LocalScript
local function C_54()
local script = G2L["54"];
	local button = script.Parent
	local uiStroke = button:WaitForChild("UIStroke")
	local fingerprint = button:WaitForChild("fingerprint")
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local ItemBuyRequest = ReplicatedStorage:WaitForChild("RemoteEvents"):WaitForChild("ItemBuyRequest")
	
	local isOn = false
	local heartbeatConnection = nil
	
	-- Save original colors
	local originalStrokeColor = uiStroke.Color
	local originalImageColor = fingerprint.ImageColor3
	
	-- Colors to toggle to
	local activeColor = Color3.fromRGB(0, 255, 0) -- Green
	
	button.MouseButton1Click:Connect(function()
		isOn = not isOn
	
		if isOn then
			-- Turn ON visuals
			uiStroke.Color = activeColor
			fingerprint.ImageColor3 = activeColor
	
			-- Start loop
			heartbeatConnection = game:GetService("RunService").Heartbeat:Connect(function(dt)
				local now = tick()
				if not isOn then return end
	
				if not button:GetAttribute("LastFire") or now - button:GetAttribute("LastFire") >= 1 then
					button:SetAttribute("LastFire", now)
					ItemBuyRequest:FireServer("Speed Coil")
				end
			end)
		else
			-- Turn OFF visuals
			uiStroke.Color = originalStrokeColor
			fingerprint.ImageColor3 = originalImageColor
	
			-- Disconnect loop
			if heartbeatConnection then
				heartbeatConnection:Disconnect()
				heartbeatConnection = nil
			end
		end
	end)
	
end;
task.spawn(C_54);
-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first3.soundclick
local function C_59()
local script = G2L["59"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_59);
-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.first3.LocalScript
local function C_5c()
local script = G2L["5c"];
	local button = script.Parent
	local uiStroke = button:FindFirstChildOfClass("UIStroke")
	local fingerprint = button:FindFirstChild("fingerprint")
	
	-- Get the correct TouchInterest
	local speedPurchases = workspace:WaitForChild("SpeedPurchases")
	local hitbox = speedPurchases:GetChildren()[2]:WaitForChild("Hitbox")
	local touchInterest = hitbox:FindFirstChildOfClass("TouchInterest")
	
	-- Save original colors
	local originalStrokeColor = uiStroke.Color
	local originalImageColor = fingerprint.ImageColor3
	
	-- Toggle state
	local isOn = false
	local autoFireConnection
	
	local function fireTouchInterest()
		local player = game.Players.LocalPlayer
		local character = player.Character or player.CharacterAdded:Wait()
		local humanoidRootPart = character:WaitForChild("HumanoidRootPart")
	
		firetouchinterest(humanoidRootPart, hitbox, 0)
		task.wait()
		firetouchinterest(humanoidRootPart, hitbox, 1)
	end
	
	local function startAutoFire()
		autoFireConnection = task.spawn(function()
			while isOn do
				fireTouchInterest()
				task.wait(0.1) -- Autofire rate
			end
		end)
	end
	
	local function stopAutoFire()
		isOn = false
		if autoFireConnection then
			task.cancel(autoFireConnection)
		end
	end
	
	button.MouseButton1Click:Connect(function()
		isOn = not isOn
	
		if isOn then
			-- Turn ON (green)
			uiStroke.Color = Color3.fromRGB(0, 255, 0)
			fingerprint.ImageColor3 = Color3.fromRGB(0, 255, 0)
			startAutoFire()
		else
			-- Turn OFF (original)
			stopAutoFire()
			uiStroke.Color = originalStrokeColor
			fingerprint.ImageColor3 = originalImageColor
		end
	end)
	
end;
task.spawn(C_5c);
-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.soundclick
local function C_61()
local script = G2L["61"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_61);
-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.LocalScript
local function C_64()
local script = G2L["64"];
	-- Anti-AFK Toggle Button Script
	local button = script.Parent
	local player = game.Players.LocalPlayer
	local uiStroke = button:WaitForChild("UIStroke")
	local image = button:WaitForChild("fingerprint") -- Make sure this is the image
	local originalColor = uiStroke.Color
	local originalImageColor = image.ImageColor3
	
	local VirtualUser = game:GetService("VirtualUser")
	local StarterGui = game:GetService("StarterGui")
	
	local isAntiAfkEnabled = false
	local afkConnection
	
	-- Function to send a notification
	local function sendNotification(title, text)
		pcall(function()
			StarterGui:SetCore("SendNotification", {
				Title = title,
				Text = text,
				Duration = 4
			})
		end)
	end
	
	-- Function to enable anti-AFK
	local function enableAntiAfk()
		if afkConnection then return end
		afkConnection = player.Idled:Connect(function()
			VirtualUser:CaptureController()
			VirtualUser:ClickButton2(Vector2.new())
		end)
	end
	
	-- Function to disable anti-AFK
	local function disableAntiAfk()
		if afkConnection then
			afkConnection:Disconnect()
			afkConnection = nil
		end
	end
	
	-- Toggle button logic
	button.MouseButton1Click:Connect(function()
		isAntiAfkEnabled = not isAntiAfkEnabled
	
		if isAntiAfkEnabled then
			uiStroke.Color = Color3.fromRGB(0, 255, 0) -- Green when ON
			image.ImageColor3 = Color3.fromRGB(0, 255, 0)
			enableAntiAfk()
			sendNotification("Anti AFK", "Anti AFK is now ON")
		else
			uiStroke.Color = originalColor
			image.ImageColor3 = originalImageColor
			disableAntiAfk()
			sendNotification("Anti AFK", "Anti AFK is now OFF")
		end
	end)
	
	-- Cleanup on script or GUI removal
	local function onDestroy()
		disableAntiAfk()
	end
	
	-- Disconnect when GUI or script is removed
	button.AncestryChanged:Connect(function(_, parent)
		if not parent then
			onDestroy()
		end
	end)
	
	script:GetPropertyChangedSignal("Disabled"):Connect(function()
		if script.Disabled then
			onDestroy()
		end
	end)
	
end;
task.spawn(C_64);
-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.soundclick
local function C_68()
local script = G2L["68"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_68);
-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.LocalScript
local function C_6b()
local script = G2L["6b"];
	-- LocalScript under the button
	
	local button = script.Parent
	local player = game.Players.LocalPlayer
	local uiStroke = button:FindFirstChildOfClass("UIStroke")
	local imageLabel = button:FindFirstChild("fingerprint")
	
	local originalColor = uiStroke and uiStroke.Color
	local originalImageColor = imageLabel and imageLabel.ImageColor3
	
	local humanoid
	local isSpeeding = false
	local normalSpeed = 25
	local boostedSpeed = 25 -- Not too fast to avoid detection
	
	-- Wait for character and humanoid
	local function getHumanoid()
		local character = player.Character or player.CharacterAdded:Wait()
		return character:WaitForChild("Humanoid")
	end
	
	-- Reapply on respawn
	player.CharacterAdded:Connect(function()
		humanoid = getHumanoid()
	end)
	
	humanoid = getHumanoid()
	
	-- Loop to constantly enforce boosted speed when enabled
	task.spawn(function()
		while true do
			if isSpeeding and humanoid and humanoid.WalkSpeed ~= boostedSpeed then
				humanoid.WalkSpeed = boostedSpeed
			end
			task.wait(0.1) -- Check every 0.1 seconds
		end
	end)
	
	button.MouseButton1Click:Connect(function()
		isSpeeding = not isSpeeding
	
		if humanoid then
			humanoid.WalkSpeed = isSpeeding and boostedSpeed or normalSpeed
		end
	
		-- UI feedback
		if uiStroke then
			uiStroke.Color = isSpeeding and Color3.fromRGB(0, 255, 0) or originalColor
		end
		if imageLabel then
			imageLabel.ImageColor3 = isSpeeding and Color3.fromRGB(0, 255, 0) or originalImageColor
		end
	end)
	
end;
task.spawn(C_6b);
-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.soundclick
local function C_6f()
local script = G2L["6f"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_6f);
-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.LocalScript
local function C_72()
local script = G2L["72"];
	local button = script.Parent
	local player = game.Players.LocalPlayer
	local UIS = game:GetService("UserInputService")
	local RunService = game:GetService("RunService")
	
	-- UI elements
	local uiStroke = button:FindFirstChildOfClass("UIStroke")
	local imageLabel = button:FindFirstChild("fingerprint")
	
	-- Store original colors
	local originalStrokeColor = uiStroke and uiStroke.Color or Color3.new(1, 1, 1)
	local originalImageColor = imageLabel and imageLabel.ImageColor3 or Color3.new(1, 1, 1)
	
	-- Config
	local HITBOX_SIZE = Vector3.new(15, 15, 15)
	local HITBOX_TRANSPARENCY = 0.9
	local DEFAULT_SIZE = Vector3.new(2, 2, 1)
	
	-- Toggle state
	local hitboxEnabled = false
	local teamCheck = false -- Change if you want to support team filtering
	
	-- Function to apply or reset hitboxes
	local function updateHitboxes()
		for _, target in ipairs(game.Players:GetPlayers()) do
			if target ~= player and target.Character and target.Character:FindFirstChild("HumanoidRootPart") then
				local root = target.Character.HumanoidRootPart
				local sameTeam = (player.Team == target.Team)
	
				if hitboxEnabled and (not teamCheck or not sameTeam) then
					pcall(function()
						root.Size = HITBOX_SIZE
						root.Transparency = HITBOX_TRANSPARENCY
						root.BrickColor = BrickColor.new("Really black")
						root.Material = Enum.Material.Neon
						root.CanCollide = false
					end)
				else
					pcall(function()
						root.Size = DEFAULT_SIZE
						root.Transparency = 1
						root.BrickColor = BrickColor.new("Medium stone grey")
						root.Material = Enum.Material.Plastic
						root.CanCollide = false
					end)
				end
			end
		end
	end
	
	-- Run hitbox updates on a loop while active
	RunService.RenderStepped:Connect(function()
		if hitboxEnabled then
			updateHitboxes()
		end
	end)
	
	-- On character respawn, restore hitbox state
	player.CharacterAdded:Connect(function()
		if hitboxEnabled then
			task.wait(1)
			updateHitboxes()
		end
	end)
	
	-- Button click toggles hitbox and UI
	button.MouseButton1Click:Connect(function()
		hitboxEnabled = not hitboxEnabled
	
		-- **ADDED** immediately apply (or reset) hitboxes on toggle
		updateHitboxes()
	
		if uiStroke then
			uiStroke.Color = hitboxEnabled and Color3.fromRGB(0, 255, 0) or originalStrokeColor
		end
	
		if imageLabel then
			imageLabel.ImageColor3 = hitboxEnabled and Color3.fromRGB(0, 255, 0) or originalImageColor
		end
	end)
	
end;
task.spawn(C_72);
-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.soundclick
local function C_76()
local script = G2L["76"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_76);
-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.LocalScript
local function C_78()
local script = G2L["78"];
	local button       = script.Parent
	local uiStroke     = button:FindFirstChildOfClass("UIStroke")
	local fingerprint  = button:FindFirstChild("fingerprint")
	assert(uiStroke and fingerprint, "UIStroke or fingerprint ImageLabel not found!")
	
	local Players           = game:GetService("Players")
	local UserInputService  = game:GetService("UserInputService")
	local player            = Players.LocalPlayer
	
	-- original UI colors
	local origStrokeColor = uiStroke.Color
	local origImageColor  = fingerprint.ImageColor3
	
	-- flag for state
	local isOn = false
	
	-- find the player's own Studio model
	local function findMyStudio()
		local studios = workspace:FindFirstChild("Studios")
		if not studios then return nil end
	
		local myStudioName = player.Name .. "'s Studio"
		for _, studio in ipairs(studios:GetChildren()) do
			if studio:IsA("Model") then
				local sign = studio:FindFirstChild("Sign")
				local label = sign
					and sign:FindFirstChild("SurfaceGui")
					and sign.SurfaceGui:FindFirstChild("TextLabel")
				if label and label.Text == myStudioName then
					return studio
				end
			end
		end
	
		return nil
	end
	
	-- teleport function (upright)
	local function teleportToZone()
		local studio = findMyStudio()
		if not studio then return end
	
		local zone = studio:FindFirstChild("CompletePurchaseZone")
		if zone and zone:IsA("BasePart") then
			local char = player.Character or player.CharacterAdded:Wait()
			local hrp  = char:WaitForChild("HumanoidRootPart")
	
			-- calculate a position just above the top face of the zone:
			local topY = zone.Position.Y + (zone.Size.Y/2) + 3
			local targetPos = Vector3.new(zone.Position.X, topY, zone.Position.Z)
	
			-- new CFrame with default orientation (facing -Z), so you won't be tipped over
			hrp.CFrame = CFrame.new(targetPos)
		end
	end
	
	-- the action when toggled on
	local function activate()
		isOn = true
		uiStroke.Color       = Color3.new(0, 1, 0)
		fingerprint.ImageColor3 = Color3.new(0, 1, 0)
	
		teleportToZone()
	
		-- Immediately toggle off after teleporting
		isOn = false
		uiStroke.Color       = origStrokeColor
		fingerprint.ImageColor3 = origImageColor
	end
	
	-- click handler
	button.MouseButton1Click:Connect(activate)
	
	-- keybind handler
	UserInputService.InputBegan:Connect(function(input, processed)
		if processed then return end
		if input.KeyCode == Enum.KeyCode.N then
			activate()
		end
	end)
	
end;
task.spawn(C_78);
-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.soundclick
local function C_7d()
local script = G2L["7d"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_7d);
-- StarterGui.omarStealCharcter.Info.sigma.MiscFrame.third.LocalScript
local function C_7f()
local script = G2L["7f"];
	-- LocalScript inside your TextButton
	
	local button      = script.Parent
	local Players     = game:GetService("Players")
	local StarterGui  = game:GetService("StarterGui")
	local player      = Players.LocalPlayer
	
	-- helper to send a core notification
	local function notify(title, text)
		StarterGui:SetCore("SendNotification", {
			Title    = title;
			Text     = text;
			Duration = 5;
		})
	end
	
	button.MouseButton1Click:Connect(function()
		local studios = workspace:FindFirstChild("Studios")
		if not studios then
			notify("Godzilla Alert", "No Studios folder found")
			return
		end
	
		local foundAny = false
		for _, studioModel in ipairs(studios:GetChildren()) do
			if studioModel:IsA("Model") then
				-- skip your own studio
				local sign = studioModel:FindFirstChild("Sign")
				local label = sign
					and sign:FindFirstChild("SurfaceGui")
					and sign.SurfaceGui:FindFirstChild("TextLabel")
	
				if label and label.Text ~= (player.Name .. "'s Studio") then
					-- extract other player's name
					local otherName = label.Text:match("^(.-)'s Studio$")
					if otherName then
						local pfolder = studioModel:FindFirstChild("Platforms")
						if pfolder then
							for _, plat in ipairs(pfolder:GetChildren()) do
								if plat:IsA("Model") then
									-- check for a child named "Godzilla"
									if plat:FindFirstChild("Godzilla") then
										notify("Godzilla Alert", otherName .. " has Godzilla")
										foundAny = true
									end
								end
							end
						end
					end
				end
			end
		end
	
		if not foundAny then
			notify("Godzilla Alert", "No one has Godzilla")
		end
	end)
	
end;
task.spawn(C_7f);
-- StarterGui.omarStealCharcter.Info.drag localscript
local function C_80()
local script = G2L["80"];
	local frame = script.Parent
	local UIS = game:GetService("UserInputService")
	
	local dragging = false
	local dragStart
	local startPos
	local activeInput -- Used only for touch
	
	-- Update frame position
	local function update(input)
		local delta = input.Position - dragStart
		frame.Position = UDim2.new(
			startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y
		)
	end
	
	frame.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = frame.Position
			activeInput = input
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	frame.InputChanged:Connect(function(input)
		if dragging then
			if input.UserInputType == Enum.UserInputType.Touch and input == activeInput then
				update(input)
			elseif input.UserInputType == Enum.UserInputType.MouseMovement then
				update(input)
			end
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if dragging then
			if input.UserInputType == Enum.UserInputType.Touch and input == activeInput then
				update(input)
			elseif input.UserInputType == Enum.UserInputType.MouseMovement then
				update(input)
			end
		end
	end)
	
end;
task.spawn(C_80);
-- StarterGui.omarStealCharcter.Changer
local function C_81()
local script = G2L["81"];
	-- LocalScript: UISelectionController (Esp & Misc Only)
	print("[UISelectionController] Script initializing...")
	
	-- Find the parent ScreenGui
	local screenGui = script:FindFirstAncestorWhichIsA("ScreenGui")
	if not screenGui then
		warn("[UISelectionController] ERROR: Not inside a ScreenGui!")
		return
	end
	print("[UISelectionController] Found ScreenGui: " .. screenGui.Name)
	
	-- Grab Info and Sigma
	local info = screenGui:FindFirstChild("Info")
	if not info then
		warn("[UISelectionController] ERROR: Info frame not found under ScreenGui")
		return
	end
	print("[UISelectionController] Found Info: " .. info.Name)
	
	local sigma = info:FindFirstChild("sigma")
	if not sigma then
		warn("[UISelectionController] ERROR: Sigma frame not found under Info")
		return
	end
	print("[UISelectionController] Found Sigma: " .. sigma.Name)
	
	-- Grab Selection
	local selection = sigma:FindFirstChild("Selection")
	if not selection then
		warn("[UISelectionController] ERROR: Selection frame not found under Sigma")
		return
	end
	print("[UISelectionController] Found Selection: " .. selection.Name)
	
	-- Define active tabs only: Esp and Misc
	local tabs = {
		Esp  = {buttonName = "Esp",  frameName = "EspFrame"},
		Misc = {buttonName = "Misc", frameName = "MiscFrame"},
		Main = {buttonName = "Main", frameName = "MainFrame"},
	}
	
	-- Prepare storage
	local activeKey
	local defaultStrokes = {}
	
	-- Initialize each tab
	for key, def in pairs(tabs) do
		local btn = selection:FindFirstChild(def.buttonName)
		if not btn or not btn:IsA("TextButton") then
			warn(string.format("[UISelectionController] ERROR: %s button '%s' not found or not a TextButton", key, def.buttonName))
		else
			print(string.format("[UISelectionController] Found button '%s' for %s", def.buttonName, key))
		end
	
		local frm = sigma:FindFirstChild(def.frameName)
		if not frm or not frm:IsA("Frame") then
			warn(string.format("[UISelectionController] ERROR: %s frame '%s' not found or not a Frame", key, def.frameName))
		else
			print(string.format("[UISelectionController] Found frame '%s' for %s", def.frameName, key))
		end
	
		local stroke = btn:FindFirstChildOfClass("UIStroke") or Instance.new("UIStroke", btn)
		defaultStrokes[key] = stroke.Color
	
		if frm then frm.Visible = false end
	
		def.button = btn
		def.frame  = frm
		def.stroke = stroke
	end
	
	-- Tab switch function
	local function switchTo(key)
		print("[UISelectionController] switchTo called for " .. key)
		if activeKey and tabs[activeKey].stroke then
			tabs[activeKey].stroke.Color = defaultStrokes[activeKey]
			if tabs[activeKey].frame then tabs[activeKey].frame.Visible = false end
			print("[UISelectionController] Hiding frame for " .. activeKey)
		end
	
		local current = tabs[key]
		if not current then
			warn("[UISelectionController] ERROR: No tab definition for key " .. key)
			return
		end
		current.stroke.Color = Color3.new(1, 0, 0)
		if current.frame then current.frame.Visible = true end
		print("[UISelectionController] Showing frame for " .. key)
		activeKey = key
	end
	
	-- Connect tab buttons
	for key, def in pairs(tabs) do
		if def.button then
			def.button.Activated:Connect(function()
				print("[UISelectionController] Button " .. def.buttonName .. " activated")
				switchTo(key)
			end)
			print("[UISelectionController] Connected Activated for " .. def.buttonName)
		end
	end
	
	-- Auto-open Esp tab
	switchTo("Esp")
	
end;
task.spawn(C_81);

return G2L["1"], require;
