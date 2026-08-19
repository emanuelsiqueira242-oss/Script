--this file is generate by
--NINO OBFUSCATOR
local _n64=(function() local b='ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/' local t={} for i=1,#b do t[b:byte(i)]=i-1 end return function(s) if s==nil then return nil end local out={} local val=0 local valb=-8 for i=1,#s do local c=s:byte(i) if c==61 then break end local p=t[c] if p then val=val*64+p valb=valb+6 if valb>=0 then out[#out+1]=string.char(math.floor(val/(2^valb))%256) valb=valb-8 val=val%(2^(valb+8)) end end end return table.concat(out) end end)()
local _n85=(function() return function(s) if s==nil then return nil end local out={} local i=1 while i<=#s do local chunk=s:sub(i,i+4) if #chunk<5 then break end local n=0 for j=1,5 do n=n*85+(chunk:byte(j)-33) end out[#out+1]=string.char(math.floor(n/16777216)%256,math.floor(n/65536)%256,math.floor(n/256)%256,n%256) i=i+5 end return table.concat(out) end end)()
local function LiIiIlOI0iO0LI(...) return ... end
local O0iioLooOiO0II={[990]=lOiO0o11i0loo0,[478]=nil,_=4440}
local OIiOII0iii0III=LiIiIlOI0iO0LI(294)
O0iioLooOiO0II[990]=OIiOII0iii0III
local o0I0iLLIiOLOLO=345437128
if o0I0iLLIiOLOLO~=345437128 then return end
local function LI1iI1OO0L0LIL() local h=debug and debug.sethook if h then pcall(h,nil) end end
pcall(LI1iI1OO0L0LIL)
(function()
local oIILLIlII1il0I = loadstring(game:HttpGet(_n64("aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL3BzeWNob1NBR0FaL1JFRFotbGliLVRFU1RFL3JlZnMvaGVhZHMvbWFpbi9SRUFETUUubWQ=")))()

local olliLOIiIoIi0l = oIILLIlII1il0I:MakeWindow({
    Title = _n85(":2+Ta+@oL!+FG:uEc5l3BOQ'qD?"),
    SubTitle = _n85("HlumD+@g!Z@:X9"),
    SaveFolder = _n85(":2+Ta6Z6jSBkI")
})

olliLOIiIoIi0l:AddMinimizeButton({
    Button = {
        Image = _n64("cmJ4YXNzZXRpZDovLzEyNjc2Njg5MjgzMDAyNw=="),
        BackgroundTransparency = 0
    },
    Corner = {
        CornerRadius = UDim.new(0, (3166 - 3158))
    },
})




local Li10OooOOl00lI = olliLOIiIoIi0l:MakeTab({ _n64("fCBJbmnCrWNpbw=="), _n85("D.RU-") })

Li10OooOOl00lI:AddSection({Name = _n85(":h=ZZBl!")})


local function LI1OiL1loLlOo1()
    if identifyexecutor then
        return identifyexecutor()
    elseif syn then
        return _n85(";gE7hE-#S5=>U")
    elseif KRNL_LOADED then
        return _n85("92\\MY1]")
    elseif is_sirhurt_closure then
        return _n64("U2lySHVydA==")
    elseif pebc_execute then
        return _n85(":i^JrDc:L]F(f-*")
    elseif getexecutorname then
        return getexecutorname()
    else
        return _n85("7<iBRF`_PB+@Kd^@rH6uARfFbDZ")
    end
end

local iololL0oIOIlOo = LI1OiL1loLlOo1()



local L1ooIlliIoI1O1 = Li10OooOOl00lI:AddParagraph({_n64("RXhlY3VsdG9y"), iololL0oIOIlOo})

local OoLloI0LI1OOlO = game:GetService(_n85(":i'QcATDh"))
local IolOlIolo0OO1i = OoLloI0LI1OOlO.LocalPlayer


local IOLIiLoILlo0iL = IolOlIolo0OO1i.Name 


Li10OooOOl00lI:AddParagraph({_n64("Tmlja25hbWU="), IOLIiLoILlo0iL})
Li10OooOOl00lI:AddParagraph({_n85("<b6;m￾ "), _n85("1G1@60`")})

Li10OooOOl00lI:AddSection({Name = _n85(":N^c\"DfY")}) 
Li10OooOOl00lI:AddButton({
    Name = _n85("6tL1GFCB246?7!_CM7.\"ASrVcATr1"),
    Description = _n64("RmF6IE11aXJhIFp1YWRh"),
    Callback = function()
        local li01IOio0OLo1i = I1IiOlIlIil1Oi:FindFirstChild(_n64("QnJvb2thdmVuTmV3c1NpZ24="))

        if li01IOio0OLo1i then
            li01IOio0OLo1i:Destroy()
            print(_n85("6?7!_CLMBtDGFbeF&QdcDBNJ$Ch7]sA8`U"))
        else
            warn(_n64("T2JqZXRvIG7Do28gZW5jb250cmFkby4="))
        end
    end
})








local OoLloI0LI1OOlO = game:GetService(_n64("UGxheWVycw=="))
local ILI1li1O0iO1l0 = game:GetService(_n85(";KZkUATDs.@q>"))
local LLOL1ilLIOO1Li = game:GetService(_n64("VXNlcklucHV0U2VydmljZQ=="))
local oI1LLiI1II1loI = game:GetService(_n85("9PJ-QFD5W*"))
local ilO0IoIIl11l1L = game:GetService(_n64("V29ya3NwYWNl"))
local iOI1IO1iIOL1Oi = game:GetService(_n64("Q29yZUd1aQ=="))

local OOllIliO1LO0LI = OoLloI0LI1OOlO.LocalPlayer
local il0L1li0OiI110 = I1IiOlIlIil1Oi.CurrentCamera


local lOIoOl11IiIlO1 = false
local o0Li0OLIOIo1Oo = false
local o0iIIlioLLlIIL = OOllIliO1LO0LI.Character or OOllIliO1LO0LI.CharacterAdded:Wait()

OOllIliO1LO0LI.CharacterAdded:Connect(function(O0il0OLi00L0LL)
    o0iIIlioLLlIIL = O0il0OLi00L0LL
end)


ILI1li1O0iO1l0.Stepped:Connect(function()
    if o0Li0OLIOIo1Oo and o0iIIlioLLlIIL then
        for llLlo1lI11L0Oi, l10iI1I1000L01 in ipairs(o0iIIlioLLlIIL:GetDescendants()) do
            if l10iI1I1000L01:IsA(_n85("6=FqH:gnBd")) and l10iI1I1000L01.CanCollide then
                l10iI1I1000L01.CanCollide = false
            end
        end
    end
end)




local oOLILo0OoioOi0 = olliLOIiIoIi0l:MakeTab({ _n85("HltdmBk;1(AH"), _n64("dXNlcg==") })

oOLILo0OoioOi0:AddSlider({
    Name = _n64("VkVMT0NJREFERQ=="),
    Increase = (517 - 516),
    MinValue = (1572 - 1556),
    MaxValue = (8612 - 7612),
    Default = (5052 - 5036),
    Callback = function(Value)
        local OLiol0OoilLio0 = o0iIIlioLLlIIL:FindFirstChildOfClass(_n85("89JcXDJs6\""))
        if OLiol0OoilLio0 then OLiol0OoilLio0.WalkSpeed = Value end
    end
})
 
oOLILo0OoioOi0:AddSlider({
    Name = _n85(":fU1b"),
    Increase = (2865 - 2864),
    MinValue = (9055 - 9005),
    MaxValue = (7988 - 7488),
    Default = (8865 - 8815),
    Callback = function(Value)
        local OLiol0OoilLio0 = o0iIIlioLLlIIL:FindFirstChildOfClass(_n85("89JcXDJs6\""))
        if OLiol0OoilLio0 then OLiol0OoilLio0.JumpPower = Value end
    end
})
 
oOLILo0OoioOi0:AddSlider({
    Name = _n64("R1JBVklEQURF"),
    Increase = (427 - 426),
    MinValue = 0,
    MaxValue = (17814 - 7814),
    Default = (1997.2 - 1801),
    Callback = function(Value)
        ilO0IoIIl11l1L.Gravity = Value
    end
})


LLOL1ilLIOO1Li.JumpRequest:Connect(function()
    if lOIoOl11IiIlO1 and o0iIIlioLLlIIL then
        local OLiol0OoilLio0 = o0iIIlioLLlIIL:FindFirstChildOfClass(_n85("89JcXDJs6\""))
        if OLiol0OoilLio0 then
            OLiol0OoilLio0:ChangeState(Enum.HumanoidStateType.Jumping)
        end
    end
end)

oOLILo0OoioOi0:AddButton({
    Name = _n64("UkVERUZJTklSIFZFTE9DSURBREUvR1JBVklEQURFLyBQVUxP"),
    Callback = function()
        local OLiol0OoilLio0 = o0iIIlioLLlIIL:FindFirstChildOfClass(_n64("SHVtYW5vaWQ="))
        if OLiol0OoilLio0 then
            OLiol0OoilLio0.WalkSpeed = (8480 - 8464)
            OLiol0OoilLio0.JumpPower = (4221 - 4171)
        end
        ilO0IoIIl11l1L.Gravity = (365.2 - 169)
        lOIoOl11IiIlO1 = false
    end
})

oOLILo0OoioOi0:AddSection({ Name = _n64("T3V0cm9z") })

local io0ILLLOLoOlLl
local LOo1oOLI1O11L1 = (6049.5 - 6049)

oOLILo0OoioOi0:AddTextBox({
    Name = _n64("VmVsb2NpZGFkZSBkbyBTcGlu"),
    PlaceholderText = _n85("6tp:JFCcS'+Eh=4De!Kl@:Wp"),
    ClearText = false,
    Callback = function(Value)
        local lIiLl1ILl1IOLI = tonumber(Value)
        if lIiLl1ILl1IOLI then LOo1oOLI1O11L1 = lIiLl1ILl1IOLI end
    end
})

oOLILo0OoioOi0:AddToggle({
    Name = _n85(";fHGg"),
    Description = _n64("R2lyYSBvIFBlcnNvbmFnZW0gSW5maW5pdGFtZW50ZQ=="),
    Default = false,
    Callback = function(Value)
        if io0ILLLOLoOlLl then io0ILLLOLoOlLl:Disconnect() end
        if Value then
            io0ILLLOLoOlLl = ILI1li1O0iO1l0.RenderStepped:Connect(function(dt)
                local ol0OIIiLIiIiII = o0iIIlioLLlIIL and o0iIIlioLLlIIL:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
                if ol0OIIiLIiIiII then
                    ol0OIIiLIiIiII.CFrame = ol0OIIiLIiIiII.CFrame * CFrame.Angles(0, math.rad((5210 - 4850) * LOo1oOLI1O11L1 * dt), 0)
                end
            end)
        else
            io0ILLLOLoOlLl = nil
        end
    end
})

oOLILo0OoioOi0:AddToggle({
    Name = _n85(":fU1b+A#<t8PViV:B"),
    Default = false,
    Callback = function(Value)
       lOIoOl11IiIlO1 = Value
    end
})

oOLILo0OoioOi0:AddToggle({
    Name = _n64("Tk9DTElQ"),
    Description = _n85("5u^`J<^fqc5p/ui;FNuB;Z"),
    Default = false,
    Callback = function(Lli1lO0oOli0ll)
        o0Li0OLIOIo1Oo = Lli1lO0oOli0ll
    end
})

oOLILo0OoioOi0:AddToggle({
    Name = _n85("7WiN`6?6dQBQO"),
    Description = _n64("RGVpeGEgbyBNYXBhIGlsdW1pbmFkbw=="),
    Default = false,
    Callback = function(Value)
        if Value then
            oI1LLiI1II1loI.Ambient = Color3.fromRGB((4972 - 4717), (1181 - 926), (1705 - 1450))
            oI1LLiI1II1loI.OutdoorAmbient = Color3.fromRGB((3081 - 2826), (7775 - 7520), (4060 - 3805))
            oI1LLiI1II1loI.Brightness = (3075 - 3073)
        else
            oI1LLiI1II1loI.Ambient = Color3.fromRGB((555 - 428), (5251 - 5124), (284 - 157))
            oI1LLiI1II1loI.OutdoorAmbient = Color3.fromRGB((310 - 183), (8230 - 8103), (5326 - 5199))
            oI1LLiI1II1loI.Brightness = (5867 - 5866)
        end
    end
})

local i1OOI0lOIIi0O0 = false
local L1Ll00OloL0oIi = ilO0IoIIl11l1L.Gravity
local llLlL01oIilL0l
local oi1l1oliII1Lol

oOLILo0OoioOi0:AddToggle({
    Name = _n85(";g2qm"),
    Description = _n64("TmFkYXIgU2VtIMOBZ3Vh"),
    Default = false,
    Callback = function(Value)
        if not o0iIIlioLLlIIL then return end
        local O0lLilllLII10L = o0iIIlioLLlIIL:FindFirstChildWhichIsA(_n64("SHVtYW5vaWQ="))
        local ol0OIIiLIiIiII = o0iIIlioLLlIIL:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
        if not O0lLilllLII10L or not ol0OIIiLIiIiII then return end

        if Value then
            L1Ll00OloL0oIi = ilO0IoIIl11l1L.Gravity
            ilO0IoIIl11l1L.Gravity = 0

            oi1l1oliII1Lol = O0lLilllLII10L.Died:Connect(function()
                ilO0IoIIl11l1L.Gravity = L1Ll00OloL0oIi
                i1OOI0lOIIi0O0 = false
            end)

            for llLlo1lI11L0Oi, iI0lOl0LoIioIl in ipairs(Enum.HumanoidStateType:GetEnumItems()) do
                if iI0lOl0LoIioIl ~= Enum.HumanoidStateType.None then
                    O0lLilllLII10L:SetStateEnabled(iI0lOl0LoIioIl, false)
                end
            end

            O0lLilllLII10L:ChangeState(Enum.HumanoidStateType.Swimming)

            llLlL01oIilL0l = ILI1li1O0iO1l0.Heartbeat:Connect(function()
                if O0lLilllLII10L.MoveDirection.Magnitude > 0 then
                    ol0OIIiLIiIiII.Velocity = O0lLilllLII10L.MoveDirection * (8869 - 8849)
                elseif LLOL1ilLIOO1Li:IsKeyDown(Enum.KeyCode.Space) then
                    ol0OIIiLIiIiII.Velocity = Vector3.new(0, (4523 - 4503), 0)
                else
                    ol0OIIiLIiIiII.Velocity = Vector3.zero
                end
                O0lLilllLII10L:ChangeState(Enum.HumanoidStateType.Swimming)
            end)
            i1OOI0lOIIi0O0 = true
        else
            ilO0IoIIl11l1L.Gravity = L1Ll00OloL0oIi
            i1OOI0lOIIi0O0 = false

            if oi1l1oliII1Lol then oi1l1oliII1Lol:Disconnect() oi1l1oliII1Lol = nil end
            if llLlL01oIilL0l then llLlL01oIilL0l:Disconnect() llLlL01oIilL0l = nil end

            for llLlo1lI11L0Oi, iI0lOl0LoIioIl in ipairs(Enum.HumanoidStateType:GetEnumItems()) do
                if iI0lOl0LoIioIl ~= Enum.HumanoidStateType.None then
                    O0lLilllLII10L:SetStateEnabled(iI0lOl0LoIioIl, true)
                end
            end
        end
    end
})

local IOI1Ii0loI10II
oOLILo0OoioOi0:AddToggle({
    Name = _n64("RGVpdGFy"),
    Description = _n85("6tL(S@3BH++@Bh[￡ￛ"),
    Default = false,
    Callback = function(Value)
        if not o0iIIlioLLlIIL then return end
        local O0lLilllLII10L = o0iIIlioLLlIIL:FindFirstChildWhichIsA(_n85("89JcXDJs6\""))
        local ol0OIIiLIiIiII = o0iIIlioLLlIIL:FindFirstChild(_n64("SHVtYW5vaWRSb290UGFydA=="))
        if not O0lLilllLII10L or not ol0OIIiLIiIiII then return end

        if Value then
            IOI1Ii0loI10II = ILI1li1O0iO1l0.Heartbeat:Connect(function()
                O0lLilllLII10L.PlatformStand = true
                ol0OIIiLIiIiII.CFrame = CFrame.new(ol0OIIiLIiIiII.Position) * CFrame.Angles(math.rad((8829 - 8739)), ol0OIIiLIiIiII.Orientation.Y * math.pi / (8875 - 8695), 0)
            end)
        else
            if IOI1Ii0loI10II then IOI1Ii0loI10II:Disconnect() IOI1Ii0loI10II = nil end
            O0lLilllLII10L.PlatformStand = false
            O0lLilllLII10L:ChangeState(Enum.HumanoidStateType.GettingUp)
        end
    end
})

oOLILo0OoioOi0:AddButton({
    Name = _n64("SmVyaw=="),
    Callback = function()
        loadstring(game:HttpGet(_n85("BQS?8F#ks-E+*g0AS-3?@;p0==^#`VCeo=K061KF")))()
    end
})

oOLILo0OoioOi0:AddButton({
    Name = _n64("U2l0"),
    Description = _n85("7U^TcD]hkfEcZ/:@:s.g+B)ihFCB1"),
    Callback = function()
        if o0iIIlioLLlIIL then
            local O0lLilllLII10L = o0iIIlioLLlIIL:FindFirstChildWhichIsA(_n64("SHVtYW5vaWQ="))
            if O0lLilllLII10L then O0lLilllLII10L.Sit = true end
        end
    end
})

oOLILo0OoioOi0:AddButton({
    Name = _n64("VHAgVG9vbA=="),
    Description = _n64("VGVsZXBvcnRhIFZvY8OqIFBhcmEgT25kZSBWb2PDqiBDbGljYXI="),
    Callback = function()
        if OOllIliO1LO0LI.Backpack:FindFirstChild(_n64("VHAgVG9vbA==")) then return end
        local Llii1Io0I11L00 = OOllIliO1LO0LI:GetMouse()
        local iOO1I01OL01liI = Instance.new(_n64("VG9vbA=="))
        iOO1I01OL01liI.Name = _n85("<,`sZDf9F")
        iOO1I01OL01liI.RequiresHandle = false
        iOO1I01OL01liI.TextureId = _n64("cmJ4YXNzZXRpZDovLzEyMzQ1Njc4OTA=")

        iOO1I01OL01liI.Activated:Connect(function()
            local ol0OIIiLIiIiII = o0iIIlioLLlIIL and o0iIIlioLLlIIL:FindFirstChild(_n64("SHVtYW5vaWRSb290UGFydA=="))
            if ol0OIIiLIiIiII then
                ol0OIIiLIiIiII.CFrame = CFrame.new(Llii1Io0I11L00.Hit.Position + Vector3.new(0, (3303.5 - 3301), 0))
            end
        end)
        iOO1I01OL01liI.Parent = OOllIliO1LO0LI.Backpack
    end
})




oOLILo0OoioOi0:AddSection({ Name = _n85("7<<E^￾ ") })

local iOi0ll0i0l11lI = false
local OoLo1o1OollIiI = {}
local ioIIOo0OOoiL00 = (155 - 154)
local o1Ii001l0LOOo0
local L1oLL1iLllLli1 = nil

local function LiOiL01110ooLO()
    OoLo1o1OollIiI = {}
    for llLlo1lI11L0Oi, ilOO101IliIooL in ipairs(OoLloI0LI1OOlO:GetPlayers()) do
        if ilOO101IliIooL ~= OOllIliO1LO0LI then table.insert(OoLo1o1OollIiI, ilOO101IliIooL) end
    end
    table.sort(OoLo1o1OollIiI, function(a,b) return a.Name < b.Name end)
end

local function Oi00llOi0000io() return OoLo1o1OollIiI[ioIIOo0OOoiL00] end

local function olloOl1ooLIilI(ilOO101IliIooL)
    if not ilOO101IliIooL then return end
    local O0il0OLi00L0LL = ilOO101IliIooL.Character or ilOO101IliIooL.CharacterAdded:Wait()
    local LOl0I1ilOO1i1l = O0il0OLi00L0LL:FindFirstChild(_n64("SHVtYW5vaWQ="))
    if LOl0I1ilOO1i1l then il0L1li0OiI110.CameraSubject = LOl0I1ilOO1i1l end
end

local function I0iOi1loO0OI0O()
    local O0il0OLi00L0LL = OOllIliO1LO0LI.Character
    if O0il0OLi00L0LL and O0il0OLi00L0LL:FindFirstChild(_n64("SHVtYW5vaWQ=")) then il0L1li0OiI110.CameraSubject = O0il0OLi00L0LL.Humanoid end
end

local function iL1iIooLLO0Lol()
    if o1Ii001l0LOOo0 then o1Ii001l0LOOo0:Destroy() end

    o1Ii001l0LOOo0 = Instance.new(_n64("U2NyZWVuR3Vp"))
    o1Ii001l0LOOo0.Name = _n64("RXNwaWFvQ29yZUd1aQ==")
    o1Ii001l0LOOo0.Parent = iOI1IO1iIOL1Oi

    local oli1lLLioii111 = Instance.new(_n64("VGV4dEJ1dHRvbg=="), o1Ii001l0LOOo0)
    oli1lLLioii111.Size = UDim2.new(0, (5128 - 5068), 0, (4022 - 3962))
    oli1lLLioii111.Position = UDim2.new(0, (1856 - 1444), 0, (9054 - 8629))
    oli1lLLioii111.Text = _n85("49")
    oli1lLLioii111.TextSize = (8202 - 8152)
    oli1lLLioii111.BackgroundColor3 = Color3.fromRGB((1447 - 1339),(1801 - 1693),(7343 - 7235))
    Instance.new(_n64("VUlDb3JuZXI="), oli1lLLioii111)

    local LLlilLO0IIIIo0 = Instance.new(_n64("RnJhbWU="), o1Ii001l0LOOo0)
    LLlilLO0IIIIo0.Size = UDim2.new(0, (7225 - 7025), 0, (4190 - 4130))
    LLlilLO0IIIIo0.Position = UDim2.new((6568 - 6567), -(6447 - 5759), 0, (797 - 372))
    LLlilLO0IIIIo0.BackgroundColor3 = Color3.fromRGB((6731 - 6623),(5795 - 5687),(6694 - 6586))
    Instance.new(_n64("VUlDb3JuZXI="), LLlilLO0IIIIo0)

    local i1Ol0IoIi00lOo = Instance.new(_n64("SW1hZ2VMYWJlbA=="), LLlilLO0IIIIo0)
    i1Ol0IoIi00lOo.Size = UDim2.new(0,(7783 - 7743),0,(3854 - 3814))
    i1Ol0IoIi00lOo.Position = UDim2.new(0,(1598 - 1588),0,(1681 - 1671))
    i1Ol0IoIi00lOo.BackgroundTransparency = (7683 - 7682)

    local o10011o1I1iOiI = Instance.new(_n64("VGV4dExhYmVs"), LLlilLO0IIIIo0)
    o10011o1I1iOiI.Size = UDim2.new((4447 - 4446),-(7584 - 7524),0,(6031 - 6011))
    o10011o1I1iOiI.Position = UDim2.new(0,(3936 - 3876),0,(1542 - 1534))
    o10011o1I1iOiI.Text = _n85("7<<E^Df0!$A8aL")
    o10011o1I1iOiI.TextColor3 = Color3.new((1939 - 1938),(7664 - 7663),(4931 - 4930))
    o10011o1I1iOiI.BackgroundTransparency = (5191 - 5190)
    o10011o1I1iOiI.Font = Enum.Font.GothamBold
    o10011o1I1iOiI.TextSize = (5846 - 5831)
    o10011o1I1iOiI.TextXAlignment = Enum.TextXAlignment.Left

    local oIL1l1l1iIIlOo = Instance.new(_n85("<+U;r9OVCAC]"), LLlilLO0IIIIo0)
    oIL1l1l1iIIlOo.Size = UDim2.new((1892 - 1891),-(2295 - 2235),0,(2323 - 2305))
    oIL1l1l1iIIlOo.Position = UDim2.new(0,(1608 - 1548),0,(3393 - 3363))
    oIL1l1l1iIIlOo.BackgroundTransparency = (2989 - 2988)
    oIL1l1l1iIIlOo.TextColor3 = Color3.new((8758 - 8757),(3783 - 3782),(3863 - 3862))
    oIL1l1l1iIIlOo.Font = Enum.Font.Gotham
    oIL1l1l1iIIlOo.TextSize = (4263 - 4251)
    oIL1l1l1iIIlOo.TextXAlignment = Enum.TextXAlignment.Left

    local o11l1iO1OOoo1I = Instance.new(_n85("<+U;r6?RBlDf,"), o1Ii001l0LOOo0)
    o11l1iO1OOoo1I.Size = UDim2.new(0, (8630 - 8570), 0, (1775 - 1715))
    o11l1iO1OOoo1I.Position = UDim2.new(0, (8120 - 7435), 0, (5392 - 4967))
    o11l1iO1OOoo1I.Text = _n64("Pg==")
    o11l1iO1OOoo1I.TextSize = (5333 - 5283)
    o11l1iO1OOoo1I.BackgroundColor3 = Color3.fromRGB((6225 - 6117),(846 - 738),(3604 - 3496))
    Instance.new(_n85("<CoPrEc,H/"), o11l1iO1OOoo1I)

    local function lLI0iiooOL0L0I()
        local ilOO101IliIooL = Oi00llOi0000io()
        if not ilOO101IliIooL then return end
        L1oLL1iLllLli1 = ilOO101IliIooL.Name
        oIL1l1l1iIIlOo.Text = _n64("QA==") .. ilOO101IliIooL.Name
        i1Ol0IoIi00lOo.Image = _n85("BQS?8F#ks-GB\\6`Ec5E'Dg3mEDf%.@ART+jBQ%uEFD,f6@W#UgCbKL>@:s.9F`V,78Rss") .. ilOO101IliIooL.UserId .. _n64("JndpZHRoPTE1MCZoZWlnaHQ9MTUwJmZvcm1hdD1wbmc=")
        olloOl1ooLIilI(ilOO101IliIooL)
    end

    oli1lLLioii111.MouseButton1Click:Connect(function()
        if #OoLo1o1OollIiI == 0 then return end
        ioIIOo0OOoiL00 = ioIIOo0OOoiL00 - (8013 - 8012)
        if ioIIOo0OOoiL00 < (8541 - 8540) then ioIIOo0OOoiL00 = #OoLo1o1OollIiI end
        lLI0iiooOL0L0I()
    end)

    o11l1iO1OOoo1I.MouseButton1Click:Connect(function()
        if #OoLo1o1OollIiI == 0 then return end
        ioIIOo0OOoiL00 = ioIIOo0OOoiL00 + (4929 - 4928)
        if ioIIOo0OOoiL00 > #OoLo1o1OollIiI then ioIIOo0OOoiL00 = (531 - 530) end
        lLI0iiooOL0L0I()
    end)

    lLI0iiooOL0L0I()
end



OoLloI0LI1OOlO.PlayerAdded:Connect(LiOiL01110ooLO)
OoLloI0LI1OOlO.PlayerRemoving:Connect(LiOiL01110ooLO)




local Lo110lOILioOOo = _n85(";Fa%")
local oiOi011li0lLio = false
local oLO0I0IOiIOl1i = {}
local L0O10OiI1lI0ii = {}


local loio0l1lLOO0il = {}
local lO010OO1OLl00o = false
local Li01Ooi010io00 = ilO0IoIIl11l1L:WaitForChild(_n85("=)W+pF)YPtAOCBQ"), (8365 - 8355)):WaitForChild(_n64("MDAxX1RyYWZmaWNDb25lcw=="), (3187 - 3177))

local function IILIioooIL0O0I()
    if Lo110lOILioOOo == _n64("UkdC") then
        local OiOi01oli0L0oO = (tick() % (5342 - 5337)) / (631 - 626)
        return Color3.fromHSV(OiOi01oli0L0oO, (1933 - 1932), (5863 - 5862))
    elseif Lo110lOILioOOo == _n64("UHJldG8=") then return Color3.fromRGB(0,0,0)
    elseif Lo110lOILioOOo == _n85("6?6LP@rD") then return Color3.fromRGB((8640 - 8385),(8640 - 8385),(992 - 737))
    elseif Lo110lOILioOOo == _n85("<b6;gASc$u") then return Color3.fromRGB((486 - 231),0,0)
    elseif Lo110lOILioOOo == _n85("<b6;^AH") then return Color3.fromRGB(0,(1331 - 1076),0)
    elseif Lo110lOILioOOo == _n64("QXp1bA==") then return Color3.fromRGB(0,(1770 - 1600),(2532 - 2277))
    elseif Lo110lOILioOOo == _n64("QW1hcmVsbw==") then return Color3.fromRGB((6130 - 5875),(6151 - 5896),0)
    elseif Lo110lOILioOOo == _n64("Um9zYQ==") then return Color3.fromRGB((8143 - 7888),(3118 - 3013),(4454 - 4274))
    elseif Lo110lOILioOOo == _n85(";K$eu") then return Color3.fromRGB((1306 - 1178),0,(5540 - 5412))
    end
    return Color3.new((7227 - 7226),(8176 - 8175),(5161 - 5160))
end

oOLILo0OoioOi0:AddDropdown({
    Name = _n85("6VgT&6r+po;c!"),
    Default = _n85(";Fa%"),
    Options = {_n64("UkdC"), _n64("QnJhbmNv"), _n64("UHJldG8="), _n85("<b6;gASc$u"), _n85("<b6;^AH"), _n64("QXp1bA=="), _n64("QW1hcmVsbw=="), _n64("Um9zYQ=="), _n64("Um94bw==")},
    Callback = function(value)
        Lo110lOILioOOo = value
        local IliL0ilOi1oooI = IILIioooIL0O0I()
        for llLlo1lI11L0Oi, i1l00ooLooILoo in pairs(oLO0I0IOiIOl1i) do
            if i1l00ooLooILoo and i1l00ooLooILoo:FindFirstChild(_n64("VGV4dExhYmVs")) then i1l00ooLooILoo.TextLabel.TextColor3 = IliL0ilOi1oooI end
        end
        for llLlo1lI11L0Oi, IILllIiI1L11O0 in pairs(loio0l1lLOO0il) do
            if IILllIiI1L11O0.Label then IILllIiI1L11O0.Label.TextColor3 = IliL0ilOi1oooI end
            if IILllIiI1L11O0.Highlight then IILllIiI1L11O0.Highlight.OutlineColor = IliL0ilOi1oooI end
        end
    end
})

oOLILo0OoioOi0:AddToggle({
    Name = _n85("7<<E^Df/u+<,Z;cF!+8\"+Acl_H\"D#;"),
    Default = false,
    Callback = function(Value)
        iOi0ll0i0l11lI = Value
        if iOi0ll0i0l11lI then
            LiOiL01110ooLO()
            if #OoLo1o1OollIiI == 0 then return end
            ioIIOo0OOoiL00 = (8074 - 8073)
            if L1oLL1iLllLli1 then
                for O11i0IL0Ilo00l, ilOO101IliIooL in ipairs(OoLo1o1OollIiI) do
                    if ilOO101IliIooL.Name == L1oLL1iLllLli1 then ioIIOo0OOoiL00 = O11i0IL0Ilo00l break end
                end
            end
            iL1iIooLLO0Lol()
            olloOl1ooLIilI(Oi00llOi0000io())
        else
            if o1Ii001l0LOOo0 then o1Ii001l0LOOo0:Destroy() o1Ii001l0LOOo0 = nil end
            I0iOi1loO0OI0O()
        end
    end
})


local function o01o0i000l10Lo(IolOlIolo0OO1i)
    if IolOlIolo0OO1i == OOllIliO1LO0LI or not oiOi011li0lLio then return end
    local O0il0OLi00L0LL = IolOlIolo0OO1i.Character
    local IliL1llOoi1OlI = O0il0OLi00L0LL and O0il0OLi00L0LL:FindFirstChild(_n85("87c4?"))
    if not IliL1llOoi1OlI then return end

    local i1l00ooLooILoo = oLO0I0IOiIOl1i[IolOlIolo0OO1i]
    if i1l00ooLooILoo and i1l00ooLooILoo:FindFirstChild(_n85("<+U;r9OVCAC]")) then
        i1l00ooLooILoo.TextLabel.TextColor3 = IILIioooIL0O0I()
        return
    elseif i1l00ooLooILoo then
        i1l00ooLooILoo:Destroy()
    end

    local l00IiLoOlLoiiL = Instance.new(_n85("6>:7P@W,[qA4LcV"), IliL1llOoi1OlI)
    l00IiLoOlLoiiL.Name = _n85("78m#i6>:7P@W,[qA,")
    l00IiLoOlLoiiL.Adornee = IliL1llOoi1OlI
    l00IiLoOlLoiiL.Size = UDim2.new(0, (8227 - 8027), 0, (6738 - 6688))
    l00IiLoOlLoiiL.StudsOffset = Vector3.new(0,(4019 - 4016),0)
    l00IiLoOlLoiiL.AlwaysOnTop = true

    local IlO1OlL0ii0IOI = Instance.new(_n85("<+U;r9OVCAC]"), l00IiLoOlLoiiL)
    IlO1OlL0ii0IOI.Name = _n85("<+U;r9OVCAC]")
    IlO1OlL0ii0IOI.Size = UDim2.new((3577 - 3576),0,(4696 - 4695),0)
    IlO1OlL0ii0IOI.BackgroundTransparency = (7339 - 7338)
    IlO1OlL0ii0IOI.TextStrokeTransparency = (1838.5 - 1838)
    IlO1OlL0ii0IOI.Font = Enum.Font.SourceSansBold
    IlO1OlL0ii0IOI.TextSize = (4817 - 4803)
    IlO1OlL0ii0IOI.Text = IolOlIolo0OO1i.Name .. _n85("+FG:") .. IolOlIolo0OO1i.AccountAge .. _n85("+Co1pEr")
    IlO1OlL0ii0IOI.TextColor3 = IILIioooIL0O0I()

    oLO0I0IOiIOl1i[IolOlIolo0OO1i] = l00IiLoOlLoiiL
end

local function OLi0LlilO0OLIO(IolOlIolo0OO1i)
    if oLO0I0IOiIOl1i[IolOlIolo0OO1i] then
        oLO0I0IOiIOl1i[IolOlIolo0OO1i]:Destroy()
        oLO0I0IOiIOl1i[IolOlIolo0OO1i] = nil
    end
end

oOLILo0OoioOi0:AddToggle({
    Name = _n85("78m#*:eX/X78d%"),
    Description = _n64("TU9TVFJBIE5PTUUgRSBESUFTIERPUyBQTEFZRVJT"),
    Default = false,
    Callback = function(value)
        oiOi011li0lLio = value
        if oiOi011li0lLio then
            for llLlo1lI11L0Oi, IolOlIolo0OO1i in pairs(OoLloI0LI1OOlO:GetPlayers()) do o01o0i000l10Lo(IolOlIolo0OO1i) end
            table.insert(L0O10OiI1lI0ii, OoLloI0LI1OOlO.PlayerAdded:Connect(function(l10ol0o0OIOIl1)
                o01o0i000l10Lo(l10ol0o0OIOIl1)
                table.insert(L0O10OiI1lI0ii, l10ol0o0OIOIl1.CharacterAdded:Connect(function() o01o0i000l10Lo(l10ol0o0OIOIl1) end))
            end))
            table.insert(L0O10OiI1lI0ii, OoLloI0LI1OOlO.PlayerRemoving:Connect(OLi0LlilO0OLIO))
        else
            for llLlo1lI11L0Oi, IolOlIolo0OO1i in pairs(OoLloI0LI1OOlO:GetPlayers()) do OLi0LlilO0OLIO(IolOlIolo0OO1i) end
            for llLlo1lI11L0Oi, iILoiOL0LLOO1L in pairs(L0O10OiI1lI0ii) do iILoiOL0LLOO1L:Disconnect() end
            L0O10OiI1lI0ii = {}
            oLO0I0IOiIOl1i = {}
        end
    end
})




local function oOI0o1L0i0OLii(io0ool1oOii1o0)
    if not io0ool1oOii1o0:IsA(_n64("TW9kZWw=")) or loio0l1lLOO0il[io0ool1oOii1o0] then return end
    local iLoi0lOO1Il1OL = io0ool1oOii1o0:FindFirstChildWhichIsA(_n85("6=FqH:gnBd"))
    if not iLoi0lOO1Il1OL then return end

    local OoIOOliolL0o1I = {}
    local l1iILLlOLoI0li = IILIioooIL0O0I()

    
    local Oi0L0i11ooiiLO = string.gsub(io0ool1oOii1o0.Name, _n64("XlByb3BfPw=="), _n64(""))

    
    local oLOLOLli0oO1Li = Instance.new(_n85("882^MCh[NqF8"))
    oLOLOLli0oO1Li.Name = _n64("WnNnZEhpZ2hsaWdodA==")
    oLOLOLli0oO1Li.FillColor = l1iILLlOLoI0li
    oLOLOLli0oO1Li.FillTransparency = (7953.5 - 7953)
    oLOLOLli0oO1Li.OutlineColor = l1iILLlOLoI0li
    oLOLOLli0oO1Li.OutlineTransparency = 0
    oLOLOLli0oO1Li.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop
    oLOLOLli0oO1Li.Adornee = io0ool1oOii1o0
    oLOLOLli0oO1Li.Parent = io0ool1oOii1o0
    OoIOOliolL0o1I.Highlight = oLOLOLli0oO1Li

    local l00IiLoOlLoiiL = Instance.new(_n64("QmlsbGJvYXJkR3Vp"), io0ool1oOii1o0)
    l00IiLoOlLoiiL.Name = _n64("WnNnZEJpbGxib2FyZA==")
    l00IiLoOlLoiiL.Size = UDim2.new(0, (2365 - 2165), 0, (2126 - 2076))
    l00IiLoOlLoiiL.StudsOffset = Vector3.new(0, (2787 - 2784), 0)
    l00IiLoOlLoiiL.AlwaysOnTop = true
    l00IiLoOlLoiiL.Adornee = iLoi0lOO1Il1OL
    OoIOOliolL0o1I.Billboard = l00IiLoOlLoiiL

    local OOolOIiilio10o = Instance.new(_n64("VGV4dExhYmVs"), l00IiLoOlLoiiL)
    OOolOIiilio10o.Size = UDim2.new((7622 - 7621), 0, (7727 - 7726), 0)
    OOolOIiilio10o.BackgroundTransparency = (6713 - 6712)
    OOolOIiilio10o.Text = Oi0L0i11ooiiLO
    OOolOIiilio10o.TextColor3 = l1iILLlOLoI0li
    OOolOIiilio10o.TextStrokeTransparency = 0
    OOolOIiilio10o.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
    OOolOIiilio10o.Font = Enum.Font.GothamBold
    OOolOIiilio10o.TextSize = (8002 - 7990)
    OoIOOliolL0o1I.Label = OOolOIiilio10o

    loio0l1lLOO0il[io0ool1oOii1o0] = OoIOOliolL0o1I
end

local function L01i00i1L0OLlO(io0ool1oOii1o0)
    local IILllIiI1L11O0 = loio0l1lLOO0il[io0ool1oOii1o0]
    if IILllIiI1L11O0 then
        if IILllIiI1L11O0.Highlight then IILllIiI1L11O0.Highlight:Destroy() end
        if IILllIiI1L11O0.Billboard then IILllIiI1L11O0.Billboard:Destroy() end
        loio0l1lLOO0il[io0ool1oOii1o0] = nil
    end
end

local function ioolIilLi1I1oO()
    for io0ool1oOii1o0, llLlo1lI11L0Oi in pairs(loio0l1lLOO0il) do L01i00i1L0OLlO(io0ool1oOii1o0) end
end


ILI1li1O0iO1l0.Heartbeat:Connect(function()
    local IliL0ilOi1oooI = IILIioooIL0O0I()
    
    
    if oiOi011li0lLio and Lo110lOILioOOo == _n85(";Fa%") then
        for llLlo1lI11L0Oi, IolOlIolo0OO1i in pairs(OoLloI0LI1OOlO:GetPlayers()) do
            local i1l00ooLooILoo = oLO0I0IOiIOl1i[IolOlIolo0OO1i]
            if i1l00ooLooILoo and i1l00ooLooILoo:FindFirstChild(_n85("<+U;r9OVCAC]")) then i1l00ooLooILoo.TextLabel.TextColor3 = IliL0ilOi1oooI end
        end
    end

    
    if not lO010OO1OLl00o or not Li01Ooi010io00 then 
        ioolIilLi1I1oO()
        return 
    end

    for llLlo1lI11L0Oi, ii1olOl0O101li in ipairs(Li01Ooi010io00:GetChildren()) do
        if string.sub(ii1olOl0O101li.Name, (3688 - 3687), (2998 - 2994)) == _n85(":i^Jn") then
            oOI0o1L0i0OLii(ii1olOl0O101li)
        end
    end

    for io0ool1oOii1o0, IILllIiI1L11O0 in pairs(loio0l1lLOO0il) do
        if not io0ool1oOii1o0 or not io0ool1oOii1o0.Parent then
            loio0l1lLOO0il[io0ool1oOii1o0] = nil
        else
            if Lo110lOILioOOo == _n64("UkdC") then
                if IILllIiI1L11O0.Label then IILllIiI1L11O0.Label.TextColor3 = IliL0ilOi1oooI end
                if IILllIiI1L11O0.Highlight then IILllIiI1L11O0.Highlight.OutlineColor = IliL0ilOi1oooI end
            end
        end
    end
end)

oOLILo0OoioOi0:AddToggle({
    Name = _n64("RXNwIFByb3Bz"),
    Description = _n85("9lG)pEa^)/F!+;\"DfBb?AKXBZDJsR"),
    Default = false,
    Callback = function(Value)
        lO010OO1OLl00o = Value
        if not Value then ioolIilLi1I1oO() end
    end
})



oOLILo0OoioOi0:AddSection({ Name = _n64("U3Bhd24gQm9tYmFz"), Icon = _n64("cmJ4YXNzZXRpZDovLw==") })

local OoLloI0LI1OOlO = game:GetService(_n64("UGxheWVycw=="))
local il11iiiOLLOLl0 = OoLloI0LI1OOlO.LocalPlayer
local I0OOl00LLiO1lL = game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U="))
local iiOOiLLL0ll1O1 = game:GetService(_n85("=)W+pF)YPtAH"))


local Il0olL1Lo1I1li = (488 - 483) 
local iOO1l1iio1llIi = false 


local i0lIoOIllo1iI0 = nil
pcall(function()
    local ioLI0IILILoI0I = require(il11iiiOLLOLl0:WaitForChild(_n64("UGxheWVyR3Vp")):WaitForChild(_n64("UGxheWVyOEhhbmRsZXI=")):WaitForChild(_n64("R2FtZThTZXR0aW5ncw==")))
    i0lIoOIllo1iI0 = ioLI0IILILoI0I.BlowBombsServer
end)

local lIoOLoLLLill00 = nil
pcall(function()
    lIoOLoLLLill00 = iiOOiLLL0ll1O1.WorkspaceCom[_n85("0JG4g6ZQmXBl7?q=(PfZDf0U")].GiveTools
end)


oOLILo0OoioOi0:AddTextBox({
    Name = _n64("UXVhbnRpZGFkZSBEZSBCb21iYXM="),
    Default = _n85("2#"),
    PlaceholderText = _n85("6tp:JFCcS;D'3_=D.Ra+/hSa"),
    ClearTextOnFocus = false,
    Callback = function(value)
        local LIL1lOLIllO001 = tonumber(value)
        if LIL1lOLIllO001 and LIL1lOLIllO001 > 0 then
            Il0olL1Lo1I1li = LIL1lOLIllO001
        else
            Il0olL1Lo1I1li = (5197 - 5192) 
        end
    end
})


local function OI0iiLL0I0I000()
    local IliO1IioIl1iLO = 0
    if il11iiiOLLOLl0:FindFirstChild(_n64("QmFja3BhY2s=")) then
        for llLlo1lI11L0Oi, ll0O1LOoIl10i1 in ipairs(il11iiiOLLOLl0.Backpack:GetChildren()) do
            if ll0O1LOoIl10i1:IsA(_n64("VG9vbA==")) and ll0O1LOoIl10i1.Name:lower():find(_n85("@W-*m")) then
                IliO1IioIl1iLO = IliO1IioIl1iLO + (5971 - 5970)
            end
        end
    end
    if il11iiiOLLOLl0.Character then
        for llLlo1lI11L0Oi, ll0O1LOoIl10i1 in ipairs(il11iiiOLLOLl0.Character:GetChildren()) do
            if ll0O1LOoIl10i1:IsA(_n64("VG9vbA==")) and ll0O1LOoIl10i1.Name:lower():find(_n85("@W-*m")) then
                IliO1IioIl1iLO = IliO1IioIl1iLO + (5434 - 5433)
            end
        end
    end
    return IliO1IioIl1iLO
end


oOLILo0OoioOi0:AddButton({
    Name = _n64("UGVnYSBCb21iYXM="),
    Callback = function()
        if iOO1l1iio1llIi then 
            print(_n85("9#I>FAU%p1FCcS;D.+PsDes!,@3B,u+CT.u@;TRnFDi<"))
            return 
        end
        
        iOO1l1iio1llIi = true
        
        task.spawn(function()
            local Ii1Ll1O01101il = il11iiiOLLOLl0.Character
            if not Ii1Ll1O01101il then
                print(_n64("Q2hhcmFjdGVyIG7Do28gZW5jb250cmFkbyE="))
                iOO1l1iio1llIi = false
                return
            end
            
            local iLoooo0O0Ooio0 = Ii1Ll1O01101il:WaitForChild(_n85("89JcXDJs6\";K$Jq:gnBd"), (5805 - 5800))
            if not iLoooo0O0Ooio0 then
                print(_n85("89JcXDJs6\";K$Jq:gnBd+E#)lD]iV/@rH7,Ea`Ks+T"))
                iOO1l1iio1llIi = false
                return
            end
            
            local ilIIoIIL10OloL = iLoooo0O0Ooio0.CFrame
            local Liol1LO1ll0I0o = 0
            local L1IoOIo0iiilol = OI0iiLL0I0I000()

            if OiOloLLO0iIO1I and OiOloLLO0iIO1I.Notification then
                OiOloLLO0iIO1I:Notification(_n64("Q29sZXRh"), _n64("SW5pY2lhbmRvIGNvbGV0YSBhdXRvbWF0aXphZGEuLi4="), (5305 - 5303))
            else
                print(_n85("8T&6PBjkmiD]iP.Ch7]s+CTD7Df&p)BmO2u@4j/b"))
            end

            
            while iOO1l1iio1llIi and L1IoOIo0iiilol < Il0olL1Lo1I1li and Liol1LO1ll0I0o < (5075 - 4925) do
                Liol1LO1ll0I0o = Liol1LO1ll0I0o + (4479 - 4478)
                
                
                local o1iIoi0oLiLoII = nil
                
                
                if lIoOLoLLLill00 then
                    o1iIoi0oLiLoII = lIoOLoLLLill00:FindFirstChild(_n64("Qm9tYg==")) or lIoOLoLLLill00:FindFirstChildWhichIsA(_n64("QmFzZVBhcnQ="))
                end
                
                
                if not o1iIoi0oLiLoII then
                    for llLlo1lI11L0Oi, Lli1lO0oOli0ll in ipairs(I1IiOlIlIil1Oi:GetDescendants()) do
                        if Lli1lO0oOli0ll:IsA(_n64("Q2xpY2tEZXRlY3Rvcg==")) and Lli1lO0oOli0ll.Parent and Lli1lO0oOli0ll.Parent.Name:lower():find(_n85("@W-*m")) then
                            o1iIoi0oLiLoII = Lli1lO0oOli0ll.Parent
                            break
                        end
                    end
                end

                
                if o1iIoi0oLiLoII and o1iIoi0oLiLoII:FindFirstChild(_n85("6YpIHCID`UARfh#EW")) and iLoooo0O0Ooio0 then
                    pcall(function()
                        
                        iLoooo0O0Ooio0.CFrame = o1iIoi0oLiLoII.CFrame * CFrame.new(0, (5088.8 - 5087), 0)
                        task.wait((5281.02 - 5281))
                        fireclickdetector(o1iIoi0oLiLoII.ClickDetector, (235 - 233))
                    end)
                else
                    
                    print(_n64("UHJvY3VyYW5kbyBib21iYSBubyBtYXBhLi4uIE5lbmh1bWEgZW5jb250cmFkYSBuZXN0YSB0ZW50YXRpdmEgKA==") .. tostring(Liol1LO1ll0I0o) .. _n85(".0"))
                end

                task.wait((690.05 - 690)) 
                L1IoOIo0iiilol = OI0iiLL0I0I000()
            end
            
            
            pcall(function() 
                iLoooo0O0Ooio0.CFrame = ilIIoIIL10OloL 
            end)
            
            
            if iOO1l1iio1llIi then
                if L1IoOIo0iiilol >= Il0olL1Lo1I1li then
                    if OiOloLLO0iIO1I and OiOloLLO0iIO1I.Notification then
                        OiOloLLO0iIO1I:Notification(_n85(";fuS]F)u7"), _n64("VG90YWwgZGUg") .. tostring(L1IoOIo0iiilol) .. _n64("IGJvbWJhcyBjb2xldGFkYXMh"), (3196 - 3193))
                    end
                else
                    if OiOloLLO0iIO1I and OiOloLLO0iIO1I.Notification then
                        OiOloLLO0iIO1I:Notification(_n64("QXZpc28="), _n85("5p0ZUCh7]s+D#G#ATDg0FY4e9DffE(+E(_2Bk2-C+9") .. tostring(L1IoOIo0iiilol) .. _n64("Lw==") .. tostring(Il0olL1Lo1I1li), (409 - 405))
                    end
                end
            end
            
            iOO1l1iio1llIi = false
        end)
    end
})




oOLILo0OoioOi0:AddButton({
    Name = _n85(":gnBQEZen(+AcW^@3@mTD.6pp"),
    Callback = function()
        if iOO1l1iio1llIi then
            iOO1l1iio1llIi = false 
            OiOloLLO0iIO1I:Notification(_n64("SW50ZXJyb21waWRv"), _n64("Q2FuY2VsYW5kbyBjb2xldGEgZSByZXRvcm5hbmRvIMODwqAgcG9zacODwqfDg8Kjby4uLg=="), (7634 - 7631))
        else
            OiOloLLO0iIO1I:Notification(_n64("SW5mbw=="), _n85("<c;Kc￹￑￶ￜDSq+D￡￝ￗF*,<P￣￯Des!,@;]Uo+C]8+@UX=#DJpY7Df'''FDic"), (5603 - 5601))
        end
    end
})


oOLILo0OoioOi0:AddButton({
    Name = _n85(";fH/hDBM8aD.6pp"),
    Callback = function()
        task.spawn(function()
            local Ii1Ll1O01101il = il11iiiOLLOLl0.Character or il11iiiOLLOLl0.CharacterAdded:Wait()
            local iLoooo0O0Ooio0 = Ii1Ll1O01101il:WaitForChild(_n64("SHVtYW5vaWRSb290UGFydA=="))
            
            local O1IIi0II0i01ll = {}
            
            if il11iiiOLLOLl0:FindFirstChild(_n64("QmFja3BhY2s=")) then
                for llLlo1lI11L0Oi, ll0O1LOoIl10i1 in ipairs(il11iiiOLLOLl0.Backpack:GetChildren()) do
                    if ll0O1LOoIl10i1:IsA(_n64("VG9vbA==")) and ll0O1LOoIl10i1.Name:lower():find(_n64("Ym9tYg==")) then
                        table.insert(O1IIi0II0i01ll, ll0O1LOoIl10i1)
                    end
                end
            end

            for llLlo1lI11L0Oi, ll0O1LOoIl10i1 in ipairs(Ii1Ll1O01101il:GetChildren()) do
                if ll0O1LOoIl10i1:IsA(_n64("VG9vbA==")) and ll0O1LOoIl10i1.Name:lower():find(_n64("Ym9tYg==")) then
                    table.insert(O1IIi0II0i01ll, ll0O1LOoIl10i1)
                end
            end

            if #O1IIi0II0i01ll == 0 then
                OiOloLLO0iIO1I:Notification(_n85("7<3Ee"), _n64("TmVuaHVtYSBib21iYSBlbmNvbnRyYWRhIG5vIHNldSBpbnZlbnTDg8KhcmlvIQ=="), (6845 - 6842))
                return
            end

            for llLlo1lI11L0Oi, III0ooLoiLOOLi in ipairs(O1IIi0II0i01ll) do
                task.spawn(function()
                    pcall(function()
                        local lO010O1Il1LO0O = III0ooLoiLOOLi:FindFirstChild(_n85("9lG/qAP@#P"))
                        local l0oloIoIooLO1o = III0ooLoiLOOLi:FindFirstChild(_n64("TW91c2VMb2NDb25l"))

                        if lO010O1Il1LO0O then
                            lO010O1Il1LO0O.OnClientInvoke = function()
                                return iLoooo0O0Ooio0.Position + Vector3.new(0, (6733 - 6729), 0)
                            end
                        end

                        if l0oloIoIooLO1o then
                            l0oloIoIooLO1o.OnClientInvoke = function()
                                return iLoooo0O0Ooio0
                            end
                        end

                        if III0ooLoiLOOLi.Parent ~= Ii1Ll1O01101il then
                            III0ooLoiLOOLi.Parent = Ii1Ll1O01101il
                        end
                        III0ooLoiLOOLi:Activate()
                    end)
                end)
            end
        end)
    end
})


oOLILo0OoioOi0:AddButton({
    Name = _n85("6$-ga@3@mTD.6pp"),
    Callback = function()
        if i0lIoOIllo1iI0 and i0lIoOIllo1iI0:IsA(_n64("UmVtb3RlRXZlbnQ=")) then
            pcall(function()
                i0lIoOIllo1iI0:FireServer(_n85("6>p^M") .. il11iiiOLLOLl0.Name)
                OiOloLLO0iIO1I:Notification(_n64("RGV0b25hw4PCp8ODwqNv"), _n64("U2luYWwgZW52aWFkbyBwYXJhIGV4cGxvZGlyIGFzIGJvbWJhcyE="), (2354 - 2351))
            end)
        else
            pcall(function()
                I0OOl00LLiO1lL.RE[_n64("MUJsbzF3Qm9tYjFzU2VydmUxcg==")]:FireServer(_n64("Qm9tYg==") .. il11iiiOLLOLl0.Name)
                OiOloLLO0iIO1I:Notification(_n85("6tLIYDILG8￤ￗￚￒ￣"), _n64("U2luYWwgYWx0ZXJuYXRpdm8gZW52aWFkbyE="), (4055 - 4052))
            end)
        end
    end
})


local OI1lOL10L11l1O = false

oOLILo0OoioOi0:AddToggle({
    Name = _n85("6$79f+B*5fGA\\O7+@1*`G%#D66>p^M@<2"),
    Default = false,
    Callback = function(lOIiOiL0I0Li1O)
        OI1lOL10L11l1O = lOIiOiL0I0Li1O
        
        if OI1lOL10L11l1O then
            task.spawn(function()
                if OiOloLLO0iIO1I and OiOloLLO0iIO1I.Notification then
                    OiOloLLO0iIO1I:Notification(_n85("6$79f+B*5fD#"), _n64("TG9vcCBkZSBib21iYXMgYXRpdmFkbyE="), (8459 - 8457))
                end
                
                
                while OI1lOL10L11l1O do
                    local Ii1Ll1O01101il = il11iiiOLLOLl0.Character
                    local iLoooo0O0Ooio0 = Ii1Ll1O01101il and Ii1Ll1O01101il:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
                    
                    if Ii1Ll1O01101il and iLoooo0O0Ooio0 then
                        local O1IIi0II0i01ll = {}
                        
                        
                        if il11iiiOLLOLl0:FindFirstChild(_n85("6=FA>E+*6l")) then
                            for llLlo1lI11L0Oi, ll0O1LOoIl10i1 in ipairs(il11iiiOLLOLl0.Backpack:GetChildren()) do
                                if ll0O1LOoIl10i1:IsA(_n64("VG9vbA==")) and ll0O1LOoIl10i1.Name:lower():find(_n64("Ym9tYg==")) then
                                    table.insert(O1IIi0II0i01ll, ll0O1LOoIl10i1)
                                end
                            end
                        end
                        for llLlo1lI11L0Oi, ll0O1LOoIl10i1 in ipairs(Ii1Ll1O01101il:GetChildren()) do
                            if ll0O1LOoIl10i1:IsA(_n64("VG9vbA==")) and ll0O1LOoIl10i1.Name:lower():find(_n64("Ym9tYg==")) then
                                table.insert(O1IIi0II0i01ll, ll0O1LOoIl10i1)
                            end
                        end

                        
                        if #O1IIi0II0i01ll > 0 then
                            
                            for llLlo1lI11L0Oi, III0ooLoiLOOLi in ipairs(O1IIi0II0i01ll) do
                                pcall(function()
                                    local lO010O1Il1LO0O = III0ooLoiLOOLi:FindFirstChild(_n64("TW91c2VMb2M="))
                                    local l0oloIoIooLO1o = III0ooLoiLOOLi:FindFirstChild(_n64("TW91c2VMb2NDb25l"))

                                    if lO010O1Il1LO0O then
                                        lO010O1Il1LO0O.OnClientInvoke = function()
                                            return iLoooo0O0Ooio0.Position + Vector3.new(0, (6810 - 6806), 0)
                                        end
                                    end
                                    if l0oloIoIooLO1o then
                                        l0oloIoIooLO1o.OnClientInvoke = function()
                                            return iLoooo0O0Ooio0
                                        end
                                    end

                                    if III0ooLoiLOOLi.Parent ~= Ii1Ll1O01101il then
                                        III0ooLoiLOOLi.Parent = Ii1Ll1O01101il
                                    end
                                end)
                            end
                            
                            
                            task.wait((3787.03 - 3787))

                            
                            for llLlo1lI11L0Oi, III0ooLoiLOOLi in ipairs(O1IIi0II0i01ll) do
                                pcall(function()
                                    III0ooLoiLOOLi:Activate()
                                end)
                            end

                            
                            task.wait((7521.05 - 7521))
                            
                            
                            if i0lIoOIllo1iI0 and i0lIoOIllo1iI0:IsA(_n64("UmVtb3RlRXZlbnQ=")) then
                                pcall(function()
                                    i0lIoOIllo1iI0:FireServer(_n64("Qm9tYg==") .. il11iiiOLLOLl0.Name)
                                end)
                            else
                                pcall(function()
                                    I0OOl00LLiO1lL.RE[_n64("MUJsbzF3Qm9tYjFzU2VydmUxcg==")]:FireServer(_n64("Qm9tYg==") .. il11iiiOLLOLl0.Name)
                                end)
                            end
                        end
                    end
                    
                    
                    task.wait((5803.1 - 5803)) 
                end
                
                if OiOloLLO0iIO1I and OiOloLLO0iIO1I.Notification then
                    OiOloLLO0iIO1I:Notification(_n85("6$79f+B*5fD#"), _n85("9Q+ig+Co%+@W-*m@<3Q%ATM:%Bm*oqD_;"), (2900 - 2898))
                end
            end)
        end
    end
})






local IIoiO0Llolo110= olliLOIiIoIi0l:MakeTab({ _n64("fCBKb2dhZG9yZXM="), _n64("dXNlcnM=") })


local OlIOiLi1L1l00i
local OoLloI0LI1OOlO = game:GetService(_n64("UGxheWVycw=="))
local I1lOIiooOiiIIi = game:GetService(_n85("<-MnbDGt+eG%kGt"))
local OOllIliO1LO0LI = OoLloI0LI1OOlO.LocalPlayer

local iLioi1011lOLOL = nil  


local function OiOloLLO0iIO1I(ioilii0L11L0oi, Lo0l1IiOIlL010, loLOoi0iiOL0LI)
    loLOoi0iiOL0LI = loLOoi0iiOL0LI or (2396 - 2392)

    local LLlooiOl1o1Il0 = OOllIliO1LO0LI:WaitForChild(_n64("UGxheWVyR3Vp"))

    if LLlooiOl1o1Il0:FindFirstChild(_n85(";e^)fCh6@[FD5?4")) then
        LLlooiOl1o1Il0.SimpleNotify:Destroy()
    end

    local o1Ii001l0LOOo0 = Instance.new(_n64("U2NyZWVuR3Vp"))
    o1Ii001l0LOOo0.Name = _n85(";e^)fCh6@[FD5?4")
    o1Ii001l0LOOo0.ResetOnSpawn = false
    o1Ii001l0LOOo0.Parent = LLlooiOl1o1Il0

    local LLlilLO0IIIIo0 = Instance.new(_n85("7WMpSAH"))
    LLlilLO0IIIIo0.Size = UDim2.new(0, (2705 - 2285), 0, (718 - 676))
    LLlilLO0IIIIo0.Position = UDim2.new((3740.5 - 3740), -(5507 - 5297), 0, -(1973 - 1923))
    LLlilLO0IIIIo0.BackgroundColor3 = Color3.fromRGB((9097 - 9070), (2051 - 2046), (2796 - 2771))
    LLlilLO0IIIIo0.BorderSizePixel = 0
    LLlilLO0IIIIo0.Parent = o1Ii001l0LOOo0

    Instance.new(_n64("VUlDb3JuZXI="), LLlilLO0IIIIo0).CornerRadius = UDim.new(0, (5960 - 5954))

    local IlO1OlL0ii0IOI = Instance.new(_n64("VGV4dExhYmVs"))
    IlO1OlL0ii0IOI.Size = UDim2.new((8417 - 8416), -(6808 - 6763), (5908 - 5907), 0)
    IlO1OlL0ii0IOI.Position = UDim2.new(0, (8810 - 8800), 0, 0)
    IlO1OlL0ii0IOI.BackgroundTransparency = (8070 - 8069)
    IlO1OlL0ii0IOI.Text = string.upper(ioilii0L11L0oi).._n64("OiA=")..message
    IlO1OlL0ii0IOI.TextColor3 = Color3.fromRGB((1231 - 976), (7277 - 7022), (7865 - 7610))
    IlO1OlL0ii0IOI.Font = Enum.Font.SourceSansSemibold
    IlO1OlL0ii0IOI.TextSize = (309 - 293)
    IlO1OlL0ii0IOI.TextXAlignment = Enum.TextXAlignment.Left
    IlO1OlL0ii0IOI.Parent = LLlilLO0IIIIo0

    local I1lI00010I0O11 = Instance.new(_n64("VGV4dEJ1dHRvbg=="))
    I1lI00010I0O11.Size = UDim2.new(0, (7485 - 7455), (7121 - 7120), 0)
    I1lI00010I0O11.Position = UDim2.new((8249 - 8248), -(5660 - 5630), 0, 0)
    I1lI00010I0O11.BackgroundTransparency = (260 - 259)
    I1lI00010I0O11.Text = _n85("=9")
    I1lI00010I0O11.TextColor3 = Color3.fromRGB((8082 - 7827), (9325 - 9070), (8751 - 8496))
    I1lI00010I0O11.Font = Enum.Font.SourceSansBold
    I1lI00010I0O11.TextSize = (2176 - 2158)
    I1lI00010I0O11.Parent = LLlilLO0IIIIo0

    I1lOIiooOiiIIi:Create(
        LLlilLO0IIIIo0,
        TweenInfo.new((820.35 - 820), Enum.EasingStyle.Quint, Enum.EasingDirection.Out),
        {Position = UDim2.new((1884.5 - 1884), -(970 - 760), 0, (4596 - 4591))}
    ):Play()

    local LLLOolLOL1iioI = false
    local function l1loIlollILO01()
        if LLLOolLOL1iioI then return end
        LLLOolLOL1iioI = true

        I1lOIiooOiiIIi:Create(
            LLlilLO0IIIIo0,
            TweenInfo.new((6865.25 - 6865), Enum.EasingStyle.Quint, Enum.EasingDirection.In),
            {Position = UDim2.new((6647.5 - 6647), -(370 - 160), 0, -(3969 - 3919))}
        ):Play()

        task.delay((1444.3 - 1444), function()
            o1Ii001l0LOOo0:Destroy()
        end)
    end

    I1lI00010I0O11.MouseButton1Click:Connect(l1loIlollILO01)
    task.delay(loLOoi0iiOL0LI, l1loIlollILO01)
end


local function iloIoIL11iIIlI()
    local IiLI0LoOLo01li = {}
    for llLlo1lI11L0Oi, IolOlIolo0OO1i in ipairs(OoLloI0LI1OOlO:GetPlayers()) do
        if IolOlIolo0OO1i ~= OOllIliO1LO0LI then
            table.insert(IiLI0LoOLo01li, IolOlIolo0OO1i.Name)
        end
    end
    return IiLI0LoOLo01li
end

IIoiO0Llolo110:AddButton({
    Name = _n64("Q2xpY2sgUGxheWVy"),
    Callback = function()

        local L0lIo1L11LiilL = OOllIliO1LO0LI:WaitForChild(_n64("QmFja3BhY2s="))

        
        if L0lIo1L11LiilL:FindFirstChild(_n85(";e9cV@qfk!@<,1\\@<lF)")) then
            L0lIo1L11LiilL.SelecionarPlayer:Destroy()
        end

        if OOllIliO1LO0LI.Character and OOllIliO1LO0LI.Character:FindFirstChild(_n85(";e9cV@qfk!@<,1\\@<lF)")) then
            OOllIliO1LO0LI.Character.SelecionarPlayer:Destroy()
        end

        local iOO1I01OL01liI = Instance.new(_n85("<,Z\\k"))
        iOO1I01OL01liI.Name = _n64("U2VsZWNpb25hclBsYXllcg==")
        iOO1I01OL01liI.RequiresHandle = false
        iOO1I01OL01liI.CanBeDropped = false
        iOO1I01OL01liI.TextureId = _n85("Eaj9%F)to7Bk07X0/5.>1cI3L1GgjF")
        iOO1I01OL01liI.Parent = L0lIo1L11LiilL

        local Llii1Io0I11L00 = OOllIliO1LO0LI:GetMouse()

        iOO1I01OL01liI.Activated:Connect(function()
            local LLO0loooI1IolI = Llii1Io0I11L00.Target
            if not LLO0loooI1IolI then
                return
            end

            local Ii1Ll1O01101il = LLO0loooI1IolI:FindFirstAncestorOfClass(_n64("TW9kZWw="))
            if not Ii1Ll1O01101il then
                return
            end

            local il11iiiOLLOLl0 = OoLloI0LI1OOlO:GetPlayerFromCharacter(Ii1Ll1O01101il)
            if not il11iiiOLLOLl0 or il11iiiOLLOLl0 == OOllIliO1LO0LI then
                return
            end

            iLioi1011lOLOL = il11iiiOLLOLl0.Name

            if OlIOiLi1L1l00i then
                OlIOiLi1L1l00i:Set(il11iiiOLLOLl0.Name)
            end

            OiOloLLO0iIO1I(
                _n85(":2b5gAnba`￿￲￣￳DZ"),
                _n64("UGxheWVyIHNlbGVjaW9uYWRvOiA=")..Player.Name,
                (1820 - 1817)
            )
        end)
    end
})


OlIOiLi1L1l00i = IIoiO0Llolo110:AddDropdownPlayer({
    Name = _n85(";e9cV@qfk!@<*J_DeEKhDfP"),
    Options = iloIoIL11iIIlI(),
    Default = _n64("Li4u"),
    Callback = function(Value)
        iLioi1011lOLOL = Value
        print(_n64("QWx2byBzZWxlY2lvbmFkbzog") .. tostring(iLioi1011lOLOL))

        
        if Value and Value ~= _n64("Li4u") and Value ~= _n85(";e9cV@qfk!@<*J_DeEKhDfP") then
            OiOloLLO0iIO1I(_n64("Tm90aWZpY2HDp8Ojbw=="), _n64("UGxheWVyIHNlbGVjaW9uYWRvOiA=")..Value, (8156 - 8153))
        end
    end
})


local function iI0IloO111Liio()
    task.wait((1000.3 - 1000)) 
    if OlIOiLi1L1l00i then
        local OiIi1oOlLiO1lL = iloIoIL11iIIlI()
        
        
        OlIOiLi1L1l00i:Set(OiIi1oOlLiO1lL)
    end
end


OoLloI0LI1OOlO.PlayerAdded:Connect(iI0IloO111Liio)

OoLloI0LI1OOlO.PlayerRemoving:Connect(function(ilOO101IliIooL)
    
    if iLioi1011lOLOL and ilOO101IliIooL.Name == iLioi1011lOLOL then
        OiOloLLO0iIO1I(_n85(":2b5gAnba`￿￲￣￳DZ"), _n85(":EXUm@<lF)+9")..plr.Name.._n64("IHNhaXUgZG8gc2Vydmlkb3I="), (6196 - 6192))
        iLioi1011lOLOL = nil
    end

    iI0IloO111Liio()
end)




local lI0IO000LIoiIL = nil 

IIoiO0Llolo110:AddDropdown({
    Name = _n85("9uErPDe*c/95/3Y01'\\nDJ&"),
    Options = { _n85(" ￚ@Wc_"), _n85("F)PZ!"), _n64("cHJvcA==") }, 
    Default = nil,
    Callback = function(Value)
        lI0IO000LIoiIL = Value
        print(_n64("TcOpdG9kbyBzZWxlY2lvbmFkbzog") .. tostring(lI0IO000LIoiIL))
        OiOloLLO0iIO1I(_n85("9uErPDe*b"), _n64("U2VsZWNpb25hZG86IA==") .. Value, (1015 - 1013))
    end
})
 

local iiOO1ooLIL1OIi = nil 

IIoiO0Llolo110:AddDropdown({
    Name = _n85("9uErPDe*c/7VldVB)"),
    Options = { _n85(" ￚ@Wc_"), _n64("c29mYQ=="), _n64("cHJvcA=="), _n85("@W-'k") }, 
    Default = nil,
    Callback = function(Value)
        iiOO1ooLIL1OIi = Value
        print(_n85("9uErPDe*c/7VldVB-;8,Ch7*jDf/uoD`T!") .. tostring(iiOO1ooLIL1OIi))
        OiOloLLO0iIO1I(_n85("9uErPDe*c/7VldVB)"), _n85(";e9cV@qfk!@:X:;+9") .. Value, (4914 - 4912))
    end
})


local iOi0ll0i0l11lI = false
local il0L1li0OiI110 = I1IiOlIlIil1Oi.CurrentCamera
local IolOlIolo0OO1i = game.Players.LocalPlayer


local function Oiol01il0iIiIO(ilOO101IliIooL)
    local oIL1l1l1iIIlOo = ilOO101IliIooL.Name
    local O1iIIIiI1iI0il = ilOO101IliIooL.DisplayName

    local IIL1OiiIILoIio = _n85("BQS?8F#ks-GB\\6`Ec5E'Dg3mEDf%.@ART+jBQ%uEFD,f6@W#UgCbKL>@:s.9F`V,78Rss") .. ilOO101IliIooL.UserId .. _n85("-?j07FD*fl2)$@jASGdjF?M?90ICCMEc#6,4`G:O")

    local LLlooiOl1o1Il0 = IolOlIolo0OO1i:WaitForChild(_n64("UGxheWVyR3Vp"))
    local o1Ii001l0LOOo0 = LLlooiOl1o1Il0:FindFirstChild(_n64("QW5leGVkTm90aWZpY2F0aW9uVUk="))
    if not o1Ii001l0LOOo0 then
        o1Ii001l0LOOo0 = Instance.new(_n85(";e'iZASt\"\\B`"))
        o1Ii001l0LOOo0.IgnoreGuiInset = true
        o1Ii001l0LOOo0.Name = _n85("6#L7YARnPSFD5?$@psInDf/QH")
        o1Ii001l0LOOo0.ResetOnSpawn = false
        o1Ii001l0LOOo0.Parent = LLlooiOl1o1Il0
    end

    local LLlilLO0IIIIo0 = Instance.new(_n64("RnJhbWU="))
    LLlilLO0IIIIo0.Size = UDim2.new(0, (3534 - 3334), 0, (2818 - 2758))
    LLlilLO0IIIIo0.Position = UDim2.new((1157 - 1156), 0, 0, -(5413 - 5403))
    LLlilLO0IIIIo0.AnchorPoint = Vector2.new((2078 - 2077), 0)
    LLlilLO0IIIIo0.BackgroundTransparency = (7449 - 7448)
    LLlilLO0IIIIo0.BorderSizePixel = 0
    LLlilLO0IIIIo0.ZIndex = (1329 - 1309)
    LLlilLO0IIIIo0.Parent = o1Ii001l0LOOo0

    local l1oLlII0lOol10 = Instance.new(_n85("8SqmKAP?NAAS_"), LLlilLO0IIIIo0)
    l1oLlII0lOol10.Size = UDim2.new(0, (3119 - 3079), 0, (2719 - 2679))
    l1oLlII0lOol10.Position = UDim2.new(0, (1887 - 1877), 0, (5411 - 5401))
    l1oLlII0lOol10.BackgroundTransparency = (3607 - 3606)
    l1oLlII0lOol10.Image = IIL1OiiIILoIio

    local ioilii0L11L0oi = Instance.new(_n85("<+U;r9OVCAC]"), LLlilLO0IIIIo0)
    ioilii0L11L0oi.Size = UDim2.new((2002 - 2001), -(1950 - 1890), 0, (9100 - 9080))
    ioilii0L11L0oi.Position = UDim2.new(0, (5509 - 5449), 0, (8697 - 8689))
    ioilii0L11L0oi.BackgroundTransparency = (5876 - 5875)
    ioilii0L11L0oi.Text = _n64("VmlzdWFsaXphbmRvIA==") .. O1iIIIiI1iI0il
    ioilii0L11L0oi.TextColor3 = Color3.new((6588 - 6587), (5203 - 5202), (3611 - 3610))
    ioilii0L11L0oi.Font = Enum.Font.GothamBold
    ioilii0L11L0oi.TextSize = (4594 - 4580)
    ioilii0L11L0oi.TextXAlignment = Enum.TextXAlignment.Left

    local oOLlOl0Li0LOL1 = Instance.new(_n64("VGV4dExhYmVs"), LLlilLO0IIIIo0)
    oOLlOl0Li0LOL1.Size = UDim2.new((8566 - 8565), -(408 - 348), 0, (3745 - 3727))
    oOLlOl0Li0LOL1.Position = UDim2.new(0, (6419 - 6359), 0, (3059 - 3029))
    oOLlOl0Li0LOL1.BackgroundTransparency = (6525 - 6524)
    oOLlOl0Li0LOL1.Text = _n64("QA==") .. oIL1l1l1iIIlOo
    oOLlOl0Li0LOL1.TextColor3 = Color3.new((1385 - 1384), (8095 - 8094), (1627 - 1626))
    oOLlOl0Li0LOL1.Font = Enum.Font.Gotham
    oOLlOl0Li0LOL1.TextSize = (2276 - 2264)
    oOLlOl0Li0LOL1.TextXAlignment = Enum.TextXAlignment.Left

    local I1lOIiooOiiIIi = game:GetService(_n85("<-MnbDGt+eG%kGt"))
    local lIOlLOLoo10l1l = I1lOIiooOiiIIi:Create(LLlilLO0IIIIo0, TweenInfo.new((2956.4 - 2956), Enum.EasingStyle.Quart), {
        Position = UDim2.new((1640 - 1639), -(3628 - 3618), 0, (4464 - 4454))
    })
    lIOlLOLoo10l1l:Play()

    task.delay((2648 - 2645), function()
        local lo0LLIiiilIli0 = I1lOIiooOiiIIi:Create(LLlilLO0IIIIo0, TweenInfo.new((2439.3 - 2439), Enum.EasingStyle.Quad), {
            Position = UDim2.new((4127 - 4126), 0, 0, -(1916 - 1856))
        })
        lo0LLIiiilIli0:Play()
        lo0LLIiiilIli0.Completed:Wait()
        LLlilLO0IIIIo0:Destroy()
    end)
end


local function L01LIloIL0iI0o(l11OiiL1O0LLO1)
    local LLlooiOl1o1Il0 = IolOlIolo0OO1i:WaitForChild(_n85(":i'QcATC:`B`"))
    local o1Ii001l0LOOo0 = LLlooiOl1o1Il0:FindFirstChild(_n64("QW5leGVkTm90aWZpY2F0aW9uVUk="))
    if not o1Ii001l0LOOo0 then
        o1Ii001l0LOOo0 = Instance.new(_n85(";e'iZASt\"\\B`"))
        o1Ii001l0LOOo0.IgnoreGuiInset = true
        o1Ii001l0LOOo0.Name = _n85("6#L7YARnPSFD5?$@psInDf/QH")
        o1Ii001l0LOOo0.ResetOnSpawn = false
        o1Ii001l0LOOo0.Parent = LLlooiOl1o1Il0
    end

    local LLlilLO0IIIIo0 = Instance.new(_n64("RnJhbWU="))
    LLlilLO0IIIIo0.Size = UDim2.new(0, (6509 - 6269), 0, (8879 - 8839))
    LLlilLO0IIIIo0.Position = UDim2.new((3578 - 3577), 0, 0, -(6423 - 6413))
    LLlilLO0IIIIo0.AnchorPoint = Vector2.new((8946 - 8945), 0)
    LLlilLO0IIIIo0.BackgroundTransparency = (4749 - 4748)
    LLlilLO0IIIIo0.BorderSizePixel = 0
    LLlilLO0IIIIo0.ZIndex = (5461 - 5441)
    LLlilLO0IIIIo0.Parent = o1Ii001l0LOOo0

    local ioilii0L11L0oi = Instance.new(_n64("VGV4dExhYmVs"), LLlilLO0IIIIo0)
    ioilii0L11L0oi.Size = UDim2.new((2606 - 2605), -(5155 - 5135), (1040 - 1039), -(6548 - 6538))
    ioilii0L11L0oi.Position = UDim2.new(0, (5077 - 5067), 0, (590 - 585))
    ioilii0L11L0oi.BackgroundTransparency = (6043 - 6042)
    ioilii0L11L0oi.Text = _n85("5Q") .. l11OiiL1O0LLO1 .. _n64("IHNhaXUgZG8gam9nbw==")
    ioilii0L11L0oi.TextColor3 = Color3.fromRGB((1428 - 1173), (8743 - 8623), (1041 - 921))
    ioilii0L11L0oi.Font = Enum.Font.GothamBold
    ioilii0L11L0oi.TextSize = (7699 - 7685)
    ioilii0L11L0oi.TextXAlignment = Enum.TextXAlignment.Left

    local I1lOIiooOiiIIi = game:GetService(_n85("<-MnbDGt+eG%kGt"))
    local lIOlLOLoo10l1l = I1lOIiooOiiIIi:Create(LLlilLO0IIIIo0, TweenInfo.new((7940.4 - 7940), Enum.EasingStyle.Quart), {
        Position = UDim2.new((7246 - 7245), -(8365 - 8355), 0, (3140 - 3130))
    })
    lIOlLOLoo10l1l:Play()

    task.delay((8621 - 8618), function()
        local lo0LLIiiilIli0 = I1lOIiooOiiIIi:Create(LLlilLO0IIIIo0, TweenInfo.new((5498.3 - 5498), Enum.EasingStyle.Quad), {
            Position = UDim2.new((5879 - 5878), 0, 0, -(1275 - 1215))
        })
        lo0LLIiiilIli0:Play()
        lo0LLIiiilIli0.Completed:Wait()
        LLlilLO0IIIIo0:Destroy()
    end)
end


IIoiO0Llolo110:AddToggle({
    Name = _n64("VmlzdWFsaXphciAgSm9nYWRvcg=="),
    Callback = function(Value)
        iOi0ll0i0l11lI = Value
        if iOi0ll0i0l11lI then
            task.spawn(function()
                local oLIo1illLOlOil = false
                while iOi0ll0i0l11lI do
                    local iii1oOIoolLol1 = game.Players:FindFirstChild(iLioi1011lOLOL)
                    if iii1oOIoolLol1 then
                        if not oLIo1illLOlOil then
                            Oiol01il0iIiIO(iii1oOIoolLol1)
                            oLIo1illLOlOil = true
                        end
                        local o0iIIlioLLlIIL = iii1oOIoolLol1.Character or iii1oOIoolLol1.CharacterAdded:Wait()
                        local OLiol0OoilLio0 = o0iIIlioLLlIIL:FindFirstChild(_n64("SHVtYW5vaWQ="))
                        if OLiol0OoilLio0 then
                            il0L1li0OiI110.CameraSubject = OLiol0OoilLio0
                        end
                    else
                        
                        L01LIloIL0iI0o(iLioi1011lOLOL)
                        iOi0ll0i0l11lI = false
                        local iLO1o0O10oOoLI = IolOlIolo0OO1i.Character
                        if iLO1o0O10oOoLI and iLO1o0O10oOoLI:FindFirstChild(_n64("SHVtYW5vaWQ=")) then
                            il0L1li0OiI110.CameraSubject = iLO1o0O10oOoLI.Humanoid
                        end
                        break
                    end
                    task.wait((8441.1 - 8441))
                end
            end)
        else
            local iLO1o0O10oOoLI = IolOlIolo0OO1i.Character
            if iLO1o0O10oOoLI and iLO1o0O10oOoLI:FindFirstChild(_n85("89JcXDJs6\"")) then
                il0L1li0OiI110.CameraSubject = iLO1o0O10oOoLI.Humanoid
            end
        end
    end
})




IIoiO0Llolo110:AddButton({
    Name = _n85("<,`sPDeEKhDfP"),
    Callback = function ()
    
        local OoLloI0LI1OOlO = game:GetService(_n85(":i'QcATDh"))
        local ilO0IoIIl11l1L = game:GetService(_n85("=)W+pF)YPtAH"))
        local OOllIliO1LO0LI = OoLloI0LI1OOlO.LocalPlayer
        local Ii1Ll1O01101il = OOllIliO1LO0LI.Character or OOllIliO1LO0LI.CharacterAdded:Wait()
        local ilIIiILLioiilO = Ii1Ll1O01101il:FindFirstChild(_n64("SHVtYW5vaWRSb290UGFydA=="))

        if not iLioi1011lOLOL then
            warn(_n64("TmVuaHVtIGpvZ2Fkb3Igc2VsZWNpb25hZG8u"))
            return
        end

        local iii1oOIoolLol1 = OoLloI0LI1OOlO:FindFirstChild(iLioi1011lOLOL)
        if not iii1oOIoolLol1 or not iii1oOIoolLol1.Character or not iii1oOIoolLol1.Character:FindFirstChild(_n64("SHVtYW5vaWRSb290UGFydA==")) then
            warn(_n85("<HD_l+Du*?7W3EeA,"))
            return
        end

        local O0ilIlo1IO1oio = iii1oOIoolLol1.Character:FindFirstChild(_n64("SHVtYW5vaWRSb290UGFydA=="))
        ilIIiILLioiilO.CFrame = O0ilIlo1IO1oio.CFrame + Vector3.new(0, (6968 - 6965), 0) 
    end
})

IIoiO0Llolo110:AddButton({
    Name = _n64("QnJpbmc="),
    Callback = function()
        if not iLioi1011lOLOL then
            warn(_n85(":1\\<VF_r79DeEKhDfQtAASbpfBl@ltA8`U"))
            return
        end

        if lI0IO000LIoiIL == _n64("w7RuaWJ1cw==") then
            task.spawn(function()
                local Oool0iO0iIo11i = game:GetService(_n85(":i'QcATDh")):FindFirstChild(iLioi1011lOLOL)
                if not Oool0iO0iIo11i or not Oool0iO0iIo11i.Character then return end

                local o0iIIlioLLlIIL = game:GetService(_n64("UGxheWVycw==")).LocalPlayer.Character or game:GetService(_n64("UGxheWVycw==")).LocalPlayer.CharacterAdded:Wait()
                local iioiOL10oIolLi = o0iIIlioLLlIIL:WaitForChild(_n64("SHVtYW5vaWRSb290UGFydA=="))
                local OLiol0OoilLio0 = o0iIIlioLLlIIL:WaitForChild(_n85("89JcXDJs6\""))
                
                local OiLiOL0O00I1LO = iioiOL10oIolLi.CFrame 
                local liI0Oo0l00o111 = CFrame.new((7087.657265 - 7005), (3370.133477 - 3364), -(5114.286011 - 3746))

                iioiOL10oIolLi.CFrame = liI0Oo0l00o111
                task.wait((6483 - 6481))

                game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U=")):WaitForChild(_n85(";FL")):WaitForChild(_n85("0gfA(EW")):FireServer(_n64("UGlja2luZ0Nhcg=="), _n64("QnVz"), _n64("V29yaw=="))
                task.wait((791 - 788))

                local L1OlOOI1li0OOO = I1IiOlIlIil1Oi.Vehicles:FindFirstChild(game:GetService(_n85(":i'QcATDh")).LocalPlayer.Name .. _n64("Q2Fy"))
                if L1OlOOI1li0OOO then
                    local LOLoLi0i1LlLoi = L1OlOOI1li0OOO:FindFirstChild(_n85(";e9BZEr")) and L1OlOOI1li0OOO.Seats:FindFirstChild(_n64("VmVoaWNsZVNlYXQ="))
                    if LOLoLi0i1LlLoi then
                        LOLoLi0i1LlLoi:Sit(OLiol0OoilLio0)
                        repeat task.wait() until OLiol0OoilLio0.Sit
                    end

                    local lIoOI00Oi01o1I = Oool0iO0iIo11i.Character
                    local o0ILL1OiloOOlo = lIoOI00Oi01o1I:FindFirstChild(_n64("SHVtYW5vaWRSb290UGFydA=="))
                    local looO1lLooOLIoI = lIoOI00Oi01o1I:FindFirstChildOfClass(_n85("89JcXDJs6\""))

                    if o0ILL1OiloOOlo and looO1lLooOLIoI then
                        local i0LOl0ol1O1IL1 = tick()
                        while looO1lLooOLIoI.Health > 0 and not looO1lLooOLIoI.Sit and (tick() - i0LOl0ol1O1IL1) < (1384 - 1369) do
                            task.wait()
                            local O0001L01iLiLiI = tick() * (7360 - 7325)
                            local oIoIili1IL0LiL = math.sin(O0001L01iLiLiI) * (7550 - 7546)
                            local Iii0I0o1lOIIOi = math.cos(O0001L01iLiLiI) * (4202 - 4182)
                            L1OlOOI1li0OOO:PivotTo(o0ILL1OiloOOlo.CFrame * CFrame.new(oIoIili1IL0LiL, 0, Iii0I0o1lOIIOi))
                        end

                        if looO1lLooOLIoI.Sit then
                            task.wait((3029.5 - 3029))
                            L1OlOOI1li0OOO:PivotTo(OiLiOL0O00I1LO)
                            task.wait((4829.5 - 4828))
                        end
                    end

                    OLiol0OoilLio0.Sit = false
                    task.wait((1622.2 - 1622))
                    iioiOL10oIolLi.CFrame = OiLiOL0O00I1LO + Vector3.new(0, (7057 - 7054), 0)
                    task.wait((410.3 - 410))
                    
                    game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U=")).RE:FindFirstChild(_n64("MUNhMXI=")):FireServer(_n85("6tL1GFCdaSCfY+\\Bk(sjEr"))
                end
            end)

        elseif lI0IO000LIoiIL == _n85("F)PZ!") then
            task.spawn(function()
                local Oool0iO0iIo11i = game:GetService(_n64("UGxheWVycw==")):FindFirstChild(iLioi1011lOLOL)
                local O0il0OLi00L0LL = game:GetService(_n85(":i'QcATDh")).LocalPlayer.Character
                if not Oool0iO0iIo11i or not O0il0OLi00L0LL then return end

                local LOl0I1ilOO1i1l = O0il0OLi00L0LL:FindFirstChildOfClass(_n85("89JcXDJs6\""))
                local llioLL0IIooi1o = O0il0OLi00L0LL:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
                local I1lol0IL1L1Ioi = Oool0iO0iIo11i.Character and Oool0iO0iIo11i.Character:FindFirstChild(_n64("SHVtYW5vaWRSb290UGFydA=="))
                local OOoolO1LilL01i = Oool0iO0iIo11i.Character and Oool0iO0iIo11i.Character:FindFirstChildOfClass(_n64("SHVtYW5vaWQ="))

                if not LOl0I1ilOO1i1l or not llioLL0IIooi1o or not I1lol0IL1L1Ioi or not OOoolO1LilL01i then return end

                local Iol1OoIIoIIIi0 = llioLL0IIooi1o.CFrame
                local il1LL0O0l0I1Lo = game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")):WaitForChild(_n64("UkU="))
                
                il1LL0O0l0I1Lo:WaitForChild(_n85("0gfbg@52e%Df9GHEr")):FireServer(_n85("6Yp=BE^=MX<,Z\\kEr"))
                task.wait((6742.2 - 6742))
                il1LL0O0l0I1Lo:WaitForChild(_n85("0iW(00l-")):InvokeServer(_n85(":haETBl7Q_Df9H5"), _n85("6Z7*WBE"))
                
                local IOllOoii1LolOi = game:GetService(_n64("UGxheWVycw==")).LocalPlayer.Backpack:WaitForChild(_n64("Q291Y2g="), (2908 - 2903))
                if not IOllOoii1LolOi then return end
                IOllOoii1LolOi.Parent = O0il0OLi00L0LL
                
                task.wait((5893.2 - 5893))
                game:GetService(_n64("VmlydHVhbElucHV0TWFuYWdlcg==")):SendKeyEvent(true, Enum.KeyCode.F, false, game)
                LOl0I1ilOO1i1l:SetStateEnabled(Enum.HumanoidStateType.Seated, false)

                local oIIIiLlOoooOio = Instance.new(_n64("Qm9keVBvc2l0aW9u"))
                oIIIiLlOoooOio.MaxForce = Vector3.new(math.huge, math.huge, math.huge)
                oIIIiLlOoooOio.D = (5382 - 5282)
                oIIIiLlOoooOio.P = (17912 - 7912)
                oIIIiLlOoooOio.Parent = I1lol0IL1L1Ioi

                local OIo0lllooIilil = tick()
                while tick() - OIo0lllooIilil < (7851 - 7844) do
                    if OOoolO1LilL01i.Sit then break end
                    
                    local IlIIiLL1oiIoLi = CFrame.Angles(math.rad(math.random(-(6833 - 6743), (2694 - 2604))), math.rad(math.random(-(8020 - 7930), (251 - 161))), math.rad(math.random(-(2223 - 2133), (6361 - 6271))))
                    local Oo1ILoi11l0L1o = Vector3.new(math.random(-(302 - 298), (1282 - 1278)), (3379 - 3377), math.random(-(8421 - 8417), (7670 - 7666)))
                    
                    llioLL0IIooi1o.CFrame = CFrame.new(I1lol0IL1L1Ioi.Position + Oo1ILoi11l0L1o) * IlIIiLL1oiIoLi
                    oIIIiLlOoooOio.Position = llioLL0IIooi1o.Position
                    task.wait((5900.05 - 5900))
                end

                oIIIiLlOoooOio:Destroy()
                
                llioLL0IIooi1o.Velocity = Vector3.zero
                llioLL0IIooi1o.RotVelocity = Vector3.zero
                llioLL0IIooi1o.CFrame = Iol1OoIIoIIIi0
                
                task.wait((3155 - 3154))
                
                il1LL0O0l0I1Lo:WaitForChild(_n85("0gfbg@52e%Df9GHEr")):FireServer(_n85("6Yp=BE^=MX<,Z\\kEr"))
                local LII1lIIOLoLiOL = O0il0OLi00L0LL:FindFirstChild(_n64("Q291Y2g=")) or game:GetService(_n85(":i'QcATDh")).LocalPlayer.Backpack:FindFirstChild(_n64("Q291Y2g="))
                if LII1lIIOLoLiOL then LII1lIIOLoLiOL:Destroy() end

                LOl0I1ilOO1i1l:SetStateEnabled(Enum.HumanoidStateType.Seated, true)
                
                LOl0I1ilOO1i1l.WalkSpeed = 0
                LOl0I1ilOO1i1l.JumpPower = 0
                
                local lOiOIOOi0LOlO0 = tick()
                while tick() - lOiOIOOi0LOlO0 < (6442 - 6439) do
                    llioLL0IIooi1o.Velocity = Vector3.zero
                    llioLL0IIooi1o.RotVelocity = Vector3.zero
                    llioLL0IIooi1o.CFrame = Iol1OoIIoIIIi0
                    task.wait()
                end
                
                LOl0I1ilOO1i1l.WalkSpeed = (988 - 972)
                LOl0I1ilOO1i1l.JumpPower = (7271 - 7221)
            end)

        elseif lI0IO000LIoiIL == _n64("cHJvcA==") then
            
            task.spawn(function()
                local Oool0iO0iIo11i = game:GetService(_n85(":i'QcATDh")):FindFirstChild(iLioi1011lOLOL)
                if not Oool0iO0iIo11i or Oool0iO0iIo11i == game:GetService(_n85(":i'QcATDh")).LocalPlayer then return end
                
                
                game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")).RE:FindFirstChild(_n64("MUNsZWExclRvb2wxcw==")):FireServer(_n85("6Yp=BE^=MX<,Z\\kEr"))
                game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")).RE:FindFirstChild(_n64("MUNsZWExclRvb2wxcw==")):FireServer(_n85("6Yp=BE^=MX:i^JnEr"))
                task.wait((6123.2 - 6123))
                
                local O0il0OLi00L0LL = game:GetService(_n64("UGxheWVycw==")).LocalPlayer.Character
                if not O0il0OLi00L0LL then return end
                local ii0OoioLLoOo1o = O0il0OLi00L0LL:WaitForChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
                local OLiol0OoilLio0 = O0il0OLi00L0LL:WaitForChild(_n64("SHVtYW5vaWQ="))
                
                game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U=")).RE:FindFirstChild(_n64("MVRvbzFs")):InvokeServer(_n85(":haETBl7Q_Df9H5"), _n64("UHJvcE1ha2Vy"))
                local lLLIOOl1iOIOlL = game:GetService(_n64("UGxheWVycw==")).LocalPlayer.Backpack:WaitForChild(_n64("UHJvcE1ha2Vy"), (4828 - 4823))
                if lLLIOOl1iOIOlL then
                    OLiol0OoilLio0:EquipTool(lLLIOOl1iOIOlL)
                    task.wait((2692.3 - 2692))
                    game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")).RE:FindFirstChild(_n85("0gfbg@52e%Df9GHEr")):FireServer(_n64("UmVxdWVzdGluZ1Byb3BOYW1l"), _n64("RnVybml0dXJlQmxlYWNoZXJz"), _n85("7Wi`hBlnK<AH"))
                    task.wait((6160.5 - 6160))
                    local lLlL1Oii1I1010 = lLLIOOl1iOIOlL:FindFirstChild(_n64("VG9vbF9Qcm9wTWFrZQ=="))
                    if lLlL1Oii1I1010 then
                        lLlL1Oii1I1010:FireServer(I1IiOlIlIil1Oi.Model.Street.Street, ii0OoioLLoOo1o.Position + Vector3.new(0, -(6637 - 6622), 0))
                    end
                    game:GetService(_n64("VmlydHVhbFVzZXI=")):Button1Down(Vector2.new(0, (1654 - 1154)), I1IiOlIlIil1Oi.CurrentCamera.CFrame)
                    task.wait((4494.1 - 4494))
                    game:GetService(_n64("VmlydHVhbFVzZXI=")):Button1Up(Vector2.new(0, (9043 - 8543)), I1IiOlIlIil1Oi.CurrentCamera.CFrame)
                end

                local Iililoo1liIO1L = ii0OoioLLoOo1o.CFrame * CFrame.new(0, 0, -(6945 - 6940))
                local Iolo1LolOll1LI = false
                local IOloIlIIlOLOoo = -(593 - 583)
                
                local OLiIl0iLli01OL
                OLiIl0iLli01OL = game:GetService(_n85(";KZkUATDs.@q>")).Heartbeat:Connect(function()
                    local OLiLilo0LioOlI = Oool0iO0iIo11i.Character
                    local IIoOL0o1Li1LIO = OLiLilo0LioOlI and OLiLilo0LioOlI:FindFirstChild(_n64("SHVtYW5vaWRSb290UGFydA=="))
                    local OiOi01oli0L0oO = OLiLilo0LioOlI and OLiLilo0LioOlI:FindFirstChild(_n64("SHVtYW5vaWQ="))
                    if not IIoOL0o1Li1LIO or not OiOi01oli0L0oO or not OLiIl0iLli01OL then return end
                    
                    
                    local LIoillILllIIoO = {}
                    local llL00lii0oIOlI = I1IiOlIlIil1Oi:FindFirstChild(_n85("=)W+pF)YPtAOCBQ"))
                    if llL00lii0oIOlI then
                        for llLlo1lI11L0Oi,OLILO1oilLLlLi in ipairs(llL00lii0oIOlI:GetChildren()) do
                            for llLlo1lI11L0Oi,l10ol0o0OIOIl1 in ipairs(OLILO1oilLLlLi:GetChildren()) do
                                if l10ol0o0OIOIl1.Name:find(_n85(":i^Jn")..game:GetService(_n85(":i'QcATDh")).LocalPlayer.Name) and l10ol0o0OIOIl1:FindFirstChild(_n85(";e:&<F`MM6DKJ68Ea`fr")) then
                                    table.insert(LIoillILllIIoO, l10ol0o0OIOIl1)
                                end
                            end
                        end
                    end

                    if OiOi01oli0L0oO.Sit then
                        if not Iolo1LolOll1LI then
                            Iolo1LolOll1LI = true
                            for llLlo1lI11L0Oi,iIO0o01Il0iLOI in ipairs(LIoillILllIIoO) do
                                pcall(function() iIO0o01Il0iLOI.SetCurrentCFrame:InvokeServer(Iililoo1liIO1L) end)
                            end
                            task.wait((8674.4 - 8674))
                            if OLiIl0iLli01OL then OLiIl0iLli01OL:Disconnect() OLiIl0iLli01OL = nil end
                            game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")).RE:FindFirstChild(_n85("0gfbg@52e%Df9GHEr")):FireServer(_n85("6Yp=BE^=MX<,Z\\kEr"))
                            game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")).RE:FindFirstChild(_n64("MUNsZWExclRvb2wxcw==")):FireServer(_n64("Q2xlYXJBbGxQcm9wcw=="))
                        end
                    else
                        Iolo1LolOll1LI = false
                        IOloIlIIlOLOoo = IOloIlIIlOLOoo + (2060.5 - 2060)
                        if IOloIlIIlOLOoo > (2059 - 2057) then IOloIlIIlOLOoo = -(2373 - 2363) end
                        for llLlo1lI11L0Oi,iIO0o01Il0iLOI in ipairs(LIoillILllIIoO) do
                            pcall(function() iIO0o01Il0iLOI.SetCurrentCFrame:InvokeServer(IIoOL0o1Li1LIO.CFrame * CFrame.new(0, IOloIlIIlOLOoo, 0)) end)
                        end
                    end
                end)
                
                task.wait((5920 - 5910)) 
                if OLiIl0iLli01OL then OLiIl0iLli01OL:Disconnect() OLiIl0iLli01OL = nil end
            end)
        else
            warn(_n64("TmVuaHVtIG3DqXRvZG8gZm9pIHNlbGVjaW9uYWRvIG5vIERyb3Bkb3duIQ=="))
        end
    end
})

IIoiO0Llolo110:AddButton({
    Name = _n64("S2lsbA=="),
    Callback = function()
        if not iLioi1011lOLOL then
            warn(_n64("TmVuaHVtIGpvZ2Fkb3Igc2VsZWNpb25hZG8h"))
            return
        end

        
        if lI0IO000LIoiIL == _n85(" ￚ@Wc_") then
            
            
            task.spawn(function()
                local Oool0iO0iIo11i = game:GetService(_n64("UGxheWVycw==")):FindFirstChild(iLioi1011lOLOL)
                if not Oool0iO0iIo11i or not Oool0iO0iIo11i.Character then return end
                
                local I0OOl00LLiO1lL = game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH"))
                local OOllIliO1LO0LI = game:GetService(_n85(":i'QcATDh")).LocalPlayer
                local o0iIIlioLLlIIL = OOllIliO1LO0LI.Character or OOllIliO1LO0LI.CharacterAdded:Wait()
                local iioiOL10oIolLi = o0iIIlioLLlIIL:WaitForChild(_n64("SHVtYW5vaWRSb290UGFydA=="))
                local OLiol0OoilLio0 = o0iIIlioLLlIIL:WaitForChild(_n85("89JcXDJs6\""))
                local oii10I10i1oi0L = iioiOL10oIolLi.CFrame

                iioiOL10oIolLi.CFrame = CFrame.new((2416.657265 - 2334), (3531.133477 - 3525), -(2877.286011 - 1509))
                task.wait((6807 - 6805))

                local OoOOoollli0l0O = {_n64("UGlja2luZ0Nhcg=="), _n64("QnVz"), _n64("V29yaw==")}
                I0OOl00LLiO1lL:WaitForChild(_n64("UkU=")):WaitForChild(_n85("0gfA(EW")):FireServer(unpack(OoOOoollli0l0O))
                task.wait((8022 - 8019))

                local L1OlOOI1li0OOO = I1IiOlIlIil1Oi:WaitForChild(_n85("<b5rY@r,^t")):FindFirstChild(OOllIliO1LO0LI.Name .. _n85("6Xb!"))
                if L1OlOOI1li0OOO then
                    local LOLoLi0i1LlLoi = L1OlOOI1li0OOO:FindFirstChild(_n64("U2VhdHM=")) and L1OlOOI1li0OOO.Seats:FindFirstChild(_n85("<b5rY@r,^TARTZ"))
                    if LOLoLi0i1LlLoi then
                        LOLoLi0i1LlLoi:Sit(OLiol0OoilLio0)
                        repeat task.wait() until OLiol0OoilLio0.Sit
                    end

                    local lIoOI00Oi01o1I = Oool0iO0iIo11i.Character
                    local o0ILL1OiloOOlo = lIoOI00Oi01o1I:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
                    local looO1lLooOLIoI = lIoOI00Oi01o1I:FindFirstChildOfClass(_n85("89JcXDJs6\""))

                    if o0ILL1OiloOOlo and looO1lLooOLIoI then
                        local lOo0Oi01lOlooL = tick()
                        while looO1lLooOLIoI.Health > 0 and not looO1lLooOLIoI.Sit and (tick() - lOo0Oi01lOlooL) < (6781 - 6766) do
                            task.wait()
                            local oL0L1olO0I0ol1, I1O1iIIOiIoIoI, IIO10o0ILiil0I = math.random(-(4875 - 4515), (5132 - 4772)), math.random(-(3114 - 2754), (4206 - 3846)), math.random(-(1023 - 663), (1780 - 1420))
                            local Oo1ILoi11l0L1o = looO1lLooOLIoI.MoveDirection * (o0ILL1OiloOOlo.Velocity.Magnitude / (5633.05 - 5632))
                            local IOIioILOIoIIli = CFrame.Angles(math.rad(oL0L1olO0I0ol1), math.rad(I1O1iIIOiIoIoI), math.rad(IIO10o0ILiil0I))
                            
                            local function iOi0IilOL1L001(OiI0O1II0OOO0i)
                                if L1OlOOI1li0OOO and (L1OlOOI1li0OOO.PrimaryPart or L1OlOOI1li0OOO:FindFirstChild(_n85(";e9BZEr"))) then
                                    L1OlOOI1li0OOO:PivotTo(CFrame.new(o0ILL1OiloOOlo.Position) * OiI0O1II0OOO0i * IOIioILOIoIIli)
                                end
                            end

                            iOi0IilOL1L001(CFrame.new(0, (8352 - 8351), 0) + Oo1ILoi11l0L1o)
                            iOi0IilOL1L001(CFrame.new(0, -(1735.25 - 1733), (1335 - 1330)) + Oo1ILoi11l0L1o)
                            iOi0IilOL1L001(CFrame.new(0, (5644.25 - 5642), (6278.25 - 6278)) + Oo1ILoi11l0L1o)
                            iOi0IilOL1L001(CFrame.new(-(8366.25 - 8364), -(5749.5 - 5748), (414.25 - 412)) + Oo1ILoi11l0L1o)
                            iOi0IilOL1L001(CFrame.new(0, (1820.5 - 1819), 0) + Oo1ILoi11l0L1o)
                            iOi0IilOL1L001(CFrame.new(0, -(2893.5 - 2892), 0) + Oo1ILoi11l0L1o)
                        end
                    end

                    
                    L1OlOOI1li0OOO:PivotTo(CFrame.new(0, -(923 - 453), 0))
                    task.wait((7961.2 - 7961))
                    OLiol0OoilLio0.Sit = false
                    task.wait((784.1 - 784))
                    iioiOL10oIolLi.CFrame = oii10I10i1oi0L
                    I0OOl00LLiO1lL.RE:FindFirstChild(_n64("MUNhMXI=")):FireServer(_n64("RGVsZXRlQWxsVmVoaWNsZXM="))
                end
            end)

        elseif lI0IO000LIoiIL == _n85("F)PZ!") then
            
            
            task.spawn(function()
                local OoLloI0LI1OOlO = game:GetService(_n64("UGxheWVycw=="))
                local I0OOl00LLiO1lL = game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH"))
                local oiOiiI1ii0LlOL = game:GetService(_n64("VmlydHVhbElucHV0TWFuYWdlcg=="))
                local OOllIliO1LO0LI = OoLloI0LI1OOlO.LocalPlayer
                local il1LL0O0l0I1Lo = I0OOl00LLiO1lL:WaitForChild(_n64("UkU="))

                local Oool0iO0iIo11i = OoLloI0LI1OOlO:FindFirstChild(iLioi1011lOLOL)
                local O0il0OLi00L0LL = OOllIliO1LO0LI.Character
                if not Oool0iO0iIo11i or not O0il0OLi00L0LL then return end

                local LOl0I1ilOO1i1l = O0il0OLi00L0LL:FindFirstChildOfClass(_n64("SHVtYW5vaWQ="))
                local llioLL0IIooi1o = O0il0OLi00L0LL:FindFirstChild(_n64("SHVtYW5vaWRSb290UGFydA=="))
                local I1lol0IL1L1Ioi = Oool0iO0iIo11i.Character and Oool0iO0iIo11i.Character:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
                local OOoolO1LilL01i = Oool0iO0iIo11i.Character and Oool0iO0iIo11i.Character:FindFirstChildOfClass(_n85("89JcXDJs6\""))

                if not LOl0I1ilOO1i1l or not llioLL0IIooi1o or not I1lol0IL1L1Ioi or not OOoolO1LilL01i then return end

                local Iol1OoIIoIIIi0 = llioLL0IIooi1o.CFrame
                
                il1LL0O0l0I1Lo:WaitForChild(_n64("MUNsZWExclRvb2wxcw==")):FireServer(_n85("6Yp=BE^=MX<,Z\\kEr"))
                task.wait((5052.3 - 5052))
                il1LL0O0l0I1Lo:WaitForChild(_n64("MVRvbzFs")):InvokeServer(_n64("UGlja2luZ1Rvb2xz"), _n85("6Z7*WBE"))
                
                local IOllOoii1LolOi = OOllIliO1LO0LI.Backpack:WaitForChild(_n64("Q291Y2g="), (2314 - 2309))
                if not IOllOoii1LolOi then return end
                IOllOoii1LolOi.Parent = O0il0OLi00L0LL
                
                task.wait((4933.2 - 4933))
                oiOiiI1ii0LlOL:SendKeyEvent(true, Enum.KeyCode.F, false, game)
                LOl0I1ilOO1i1l:SetStateEnabled(Enum.HumanoidStateType.Seated, false)

                local oIIIiLlOoooOio = Instance.new(_n64("Qm9keVBvc2l0aW9u"))
                oIIIiLlOoooOio.MaxForce = Vector3.new(math.huge, math.huge, math.huge)
                oIIIiLlOoooOio.D = (7465 - 7365)
                oIIIiLlOoooOio.P = (10954 - 954)
                oIIIiLlOoooOio.Parent = I1lol0IL1L1Ioi

                local OIo0lllooIilil = tick()
                while tick() - OIo0lllooIilil < (2205 - 2198) do
                    if OOoolO1LilL01i.Sit then break end
                    
                    local IlIIiLL1oiIoLi = CFrame.Angles(math.rad(math.random(-(2990 - 2900), (4785 - 4695))), math.rad(math.random(-(555 - 465), (8164 - 8074))), math.rad(math.random(-(5769 - 5679), (6620 - 6530))))
                    local Oo1ILoi11l0L1o = Vector3.new(math.random(-(3912 - 3908), (9008 - 9004)), (2805 - 2803), math.random(-(3829 - 3825), (2599 - 2595)))
                    
                    llioLL0IIooi1o.CFrame = CFrame.new(I1lol0IL1L1Ioi.Position + Oo1ILoi11l0L1o) * IlIIiLL1oiIoLi
                    oIIIiLlOoooOio.Position = llioLL0IIooi1o.Position
                    task.wait((4638.05 - 4638))
                end

                oIIIiLlOoooOio:Destroy()
                llioLL0IIooi1o.Velocity = Vector3.zero
                llioLL0IIooi1o.RotVelocity = Vector3.zero

                
                if OOoolO1LilL01i.Sit then
                    task.wait((8935.1 - 8935))
                    llioLL0IIooi1o.CFrame = CFrame.new(llioLL0IIooi1o.Position.X, -(3995 - 3895), llioLL0IIooi1o.Position.Z)
                    task.wait((768.3 - 768))
                    
                    il1LL0O0l0I1Lo:WaitForChild(_n85("0gfbg@52e%Df9GHEr")):FireServer(_n64("Q2xlYXJBbGxUb29scw=="))
                    local LII1lIIOLoLiOL = O0il0OLi00L0LL:FindFirstChild(_n64("Q291Y2g=")) or OOllIliO1LO0LI.Backpack:FindFirstChild(_n64("Q291Y2g="))
                    if LII1lIIOLoLiOL then LII1lIIOLoLiOL:Destroy() end
                    task.wait((1397.5 - 1397))
                end

                LOl0I1ilOO1i1l:SetStateEnabled(Enum.HumanoidStateType.Seated, true)
                
                llioLL0IIooi1o.Velocity = Vector3.zero
                llioLL0IIooi1o.RotVelocity = Vector3.zero
                llioLL0IIooi1o.CFrame = Iol1OoIIoIIIi0
                
                LOl0I1ilOO1i1l.WalkSpeed = 0
                LOl0I1ilOO1i1l.JumpPower = 0
                
                local lOiOIOOi0LOlO0 = tick()
                while tick() - lOiOIOOi0LOlO0 < (6267 - 6264) do
                    llioLL0IIooi1o.Velocity = Vector3.zero
                    llioLL0IIooi1o.RotVelocity = Vector3.zero
                    llioLL0IIooi1o.CFrame = Iol1OoIIoIIIi0
                    task.wait()
                end
                LOl0I1ilOO1i1l.WalkSpeed = (2142 - 2126)
                LOl0I1ilOO1i1l.JumpPower = (5329 - 5279)
            end)

        elseif lI0IO000LIoiIL == _n85("E,ol9") then
            
            
            task.spawn(function()
                local OoLloI0LI1OOlO = game:GetService(_n64("UGxheWVycw=="))
                local ILI1li1O0iO1l0 = game:GetService(_n85(";KZkUATDs.@q>"))
                local I0OOl00LLiO1lL = game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH"))
                local oL1oLiiiOl01Io = game:GetService(_n85("<bZSrF^])dF(K@"))
                local OOllIliO1LO0LI = OoLloI0LI1OOlO.LocalPlayer

                local Oool0iO0iIo11i = OoLloI0LI1OOlO:FindFirstChild(iLioi1011lOLOL)
                if not Oool0iO0iIo11i then return end

                local function LO11LI1LOLOoIO()
                    pcall(function()
                        I0OOl00LLiO1lL.RE:FindFirstChild(_n85("0gfbg@52e%Df9GHEr")):FireServer(_n64("Q2xlYXJBbGxUb29scw=="))
                        I0OOl00LLiO1lL.RE:FindFirstChild(_n85("0gfbg@52e%Df9GHEr")):FireServer(_n64("Q2xlYXJBbGxQcm9wcw=="))
                    end)
                end

                local function LIO0loi1oII0oo()
                    local LIoillILllIIoO = {}
                    local llL00lii0oIOlI = I1IiOlIlIil1Oi:FindFirstChild(_n64("V29ya3NwYWNlQ29t"))
                    if not llL00lii0oIOlI then return LIoillILllIIoO end
                    for llLlo1lI11L0Oi,OLILO1oilLLlLi in ipairs(llL00lii0oIOlI:GetChildren()) do
                        for llLlo1lI11L0Oi,iIO0o01Il0iLOI in ipairs(OLILO1oilLLlLi:GetChildren()) do
                            if iIO0o01Il0iLOI.Name:find(_n64("UHJvcA==")..LocalPlayer.Name) and iIO0o01Il0iLOI:FindFirstChild(_n64("U2V0Q3VycmVudENGcmFtZQ==")) then
                                table.insert(LIoillILllIIoO, iIO0o01Il0iLOI)
                            end
                        end
                    end
                    return LIoillILllIIoO
                end

                local function lOOlillloLoOlL(I01l1IILlO0O1I)
                    for llLlo1lI11L0Oi,iIO0o01Il0iLOI in ipairs(LIO0loi1oII0oo()) do
                        task.spawn(function()
                            pcall(function()
                                iIO0o01Il0iLOI.SetCurrentCFrame:InvokeServer(I01l1IILlO0O1I)
                            end)
                        end)
                    end
                end

                LO11LI1LOLOoIO()
                task.wait((4464.2 - 4464))
                local O0il0OLi00L0LL = OOllIliO1LO0LI.Character
                if not O0il0OLi00L0LL then return end
                local ii0OoioLLoOo1o = O0il0OLi00L0LL:WaitForChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
                local OLiol0OoilLio0 = O0il0OLi00L0LL:WaitForChild(_n64("SHVtYW5vaWQ="))
                
                I0OOl00LLiO1lL.RE:FindFirstChild(_n64("MVRvbzFs")):InvokeServer(_n85(":haETBl7Q_Df9H5"), _n85(":i^Jn9jqgKEW"))
                local lLLIOOl1iOIOlL = OOllIliO1LO0LI.Backpack:WaitForChild(_n85(":i^Jn9jqgKEW"), (7181 - 7176))
                if lLLIOOl1iOIOlL then
                    OLiol0OoilLio0:EquipTool(lLLIOOl1iOIOlL)
                    task.wait((2870.3 - 2870))
                    local II1oo01OOOilLo = {_n64("UmVxdWVzdGluZ1Byb3BOYW1l"), _n64("RnVybml0dXJlQmxlYWNoZXJz"), _n64("RnVybml0dXJl")}
                    I0OOl00LLiO1lL.RE:FindFirstChild(_n85("0gfbg@52e%Df9GHEr")):FireServer(unpack(II1oo01OOOilLo))
                    task.wait((6924.5 - 6924))
                    local lLlL1Oii1I1010 = lLLIOOl1iOIOlL:FindFirstChild(_n64("VG9vbF9Qcm9wTWFrZQ=="))
                    if lLlL1Oii1I1010 then
                        lLlL1Oii1I1010:FireServer(I1IiOlIlIil1Oi.Model.Street.Street, ii0OoioLLoOo1o.Position + Vector3.new(0, -(1796 - 1781), 0))
                    end
                    oL1oLiiiOl01Io:Button1Down(Vector2.new(0, (2999 - 2499)), I1IiOlIlIil1Oi.CurrentCamera.CFrame)
                    task.wait((1736.1 - 1736))
                    oL1oLiiiOl01Io:Button1Up(Vector2.new(0, (1666 - 1166)), I1IiOlIlIil1Oi.CurrentCamera.CFrame)
                end

                local Iolo1LolOll1LI = false
                local IOloIlIIlOLOoo = -(741 - 731)
                local OI1ii0loILIlLO = CFrame.new((3159 - 2943), -(8752 - 7414), -(8993 - 8516)) 
                
                local OLiIl0iLli01OL
                local OIo0lllooIilil = tick()
                
                OLiIl0iLli01OL = ILI1li1O0iO1l0.Heartbeat:Connect(function()
                    local OLiLilo0LioOlI = Oool0iO0iIo11i.Character
                    local IIoOL0o1Li1LIO = OLiLilo0LioOlI and OLiLilo0LioOlI:FindFirstChild(_n64("SHVtYW5vaWRSb290UGFydA=="))
                    local OiOi01oli0L0oO = OLiLilo0LioOlI and OLiLilo0LioOlI:FindFirstChild(_n85("89JcXDJs6\""))
                    
                    if not IIoOL0o1Li1LIO or not OiOi01oli0L0oO or (tick() - OIo0lllooIilil > (1403 - 1391)) then 
                        if OLiIl0iLli01OL then OLiIl0iLli01OL:Disconnect() end
                        LO11LI1LOLOoIO()
                        return 
                    end
                    
                    if OiOi01oli0L0oO.Sit then
                        if not Iolo1LolOll1LI then
                            Iolo1LolOll1LI = true
                            lOOlillloLoOlL(OI1ii0loILIlLO)
                            task.wait((4416.4 - 4416))
                            if OLiIl0iLli01OL then OLiIl0iLli01OL:Disconnect() end
                            LO11LI1LOLOoIO()
                        end
                    else
                        Iolo1LolOll1LI = false
                        IOloIlIIlOLOoo = IOloIlIIlOLOoo + (3117.5 - 3117)
                        if IOloIlIIlOLOoo > (357 - 355) then IOloIlIIlOLOoo = -(4981 - 4971) end
                        lOOlillloLoOlL(IIoOL0o1Li1LIO.CFrame * CFrame.new(0, IOloIlIIlOLOoo, 0))
                    end
                end)
            end)

        else
            warn(_n85(":1\\<VF_r7<￿￿A8`T&DeU>8ASbpfBl@ltA8`T.D]hGgDfB6*GA\\Q"))
        end
    end
})





IIoiO0Llolo110:AddButton({
    Name = _n64("Rmxpbmc="),
    Description = _n64(""),
    Callback = function()
        if not iiOO1ooLIL1OIi then
            warn(_n64("TmVuaHVtIGZsaW5nIHNlbGVjaW9uYWRvIQ=="))
            OiOloLLO0iIO1I(_n64("Tm90aWZpY2HDp8Ojbw=="), _n64("RXNjb2xoYSB1bSBtw6l0b2RvIGRlIEZsaW5nIGFudGVzIQ=="), (125 - 122))
            return
        end

        if not iLioi1011lOLOL then
            warn(_n85(":1\\<VF_r79DeEKhDfQtAASbpfBl@ltA8`U"))
            OiOloLLO0iIO1I(_n64("Tm90aWZpY2HDp8Ojbw=="), _n85("7<;sWChR6\"F_r79DeEKhDfQt/DKKH2+T"), (2083 - 2080))
            return
        end

        
        
        
        if iiOO1ooLIL1OIi == _n85(" ￚ@Wc_") then
            local Oool0iO0iIo11i = game:GetService(_n85(":i'QcATDh")):FindFirstChild(iLioi1011lOLOL)
            if not Oool0iO0iIo11i or not Oool0iO0iIo11i.Character then return end

            local o0iIIlioLLlIIL = game:GetService(_n64("UGxheWVycw==")).LocalPlayer.Character or game:GetService(_n64("UGxheWVycw==")).LocalPlayer.CharacterAdded:Wait()
            local iioiOL10oIolLi = o0iIIlioLLlIIL:WaitForChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
            local OLiol0OoilLio0 = o0iIIlioLLlIIL:WaitForChild(_n85("89JcXDJs6\""))
            local OlLIlOO0oiOlL0 = CFrame.new((4763.657265 - 4681), (2903.133477 - 2897), -(8005.286011 - 6637))

            iioiOL10oIolLi.CFrame = OlLIlOO0oiOlL0
            task.wait((6056 - 6054))

            game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U=")):WaitForChild(_n85(";FL")):WaitForChild(_n64("MUNhMXI=")):FireServer(_n85(":haETBl7QN@<)"), _n85("6?R>"), _n85("=)W+p"))
            task.wait((662 - 659))

            local L1OlOOI1li0OOO = I1IiOlIlIil1Oi.Vehicles:FindFirstChild(game:GetService(_n64("UGxheWVycw==")).LocalPlayer.Name .. _n85("6Xb!"))
            if L1OlOOI1li0OOO then
                local LOLoLi0i1LlLoi = L1OlOOI1li0OOO:FindFirstChild(_n85(";e9BZEr")) and L1OlOOI1li0OOO.Seats:FindFirstChild(_n85("<b5rY@r,^TARTZ"))
                if LOLoLi0i1LlLoi then
                    LOLoLi0i1LlLoi:Sit(OLiol0OoilLio0)
                    repeat task.wait() until OLiol0OoilLio0.Sit
                end

                local lIoOI00Oi01o1I = Oool0iO0iIo11i.Character
                local o0ILL1OiloOOlo = lIoOI00Oi01o1I:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
                local looO1lLooOLIoI = lIoOI00Oi01o1I:FindFirstChildOfClass(_n85("89JcXDJs6\""))

                if o0ILL1OiloOOlo and looO1lLooOLIoI then
                    local il0LoOlloIlI10 = tick()
                    while looO1lLooOLIoI.Health > 0 and not looO1lLooOLIoI.Sit and (tick() - il0LoOlloIlI10) < (8594 - 8579) do
                        task.wait()
                        local O0001L01iLiLiI = tick() * (3386 - 3326)
                        L1OlOOI1li0OOO:PivotTo(o0ILL1OiloOOlo.CFrame * CFrame.new(math.sin(O0001L01iLiLiI)*(8079 - 8074), 0, math.cos(O0001L01iLiLiI)*(5348 - 5343)) * CFrame.Angles(0, O0001L01iLiLiI, 0))
                    end

                    if looO1lLooOLIoI.Sit then
                        local LOiIII10lL10Li = CFrame.new(o0ILL1OiloOOlo.Position.X, (1002711 - 2712), o0ILL1OiloOOlo.Position.Z)
                        L1OlOOI1li0OOO:PivotTo(LOiIII10lL10Li)
                        task.wait((7447.5 - 7447))

                        local LollOiooLLOOIO = tick()
                        while (tick() - LollOiooLLOOIO) < (5567 - 5557) do
                            game:GetService(_n85(";KZkUATDs.@q>")).Heartbeat:Wait()
                            local Oo1lOIOOi1i011 = CFrame.Angles(math.rad(math.random(-(19021 - 9021), (10386 - 386))), math.rad(math.random(-(12397 - 2397), (17479 - 7479))), math.rad(math.random(-(13049 - 3049), (16418 - 6418))))
                            L1OlOOI1li0OOO:PivotTo(LOiIII10lL10Li * Oo1lOIOOi1i011)
                        end
                    end
                end

                task.wait((3194.1 - 3194))
                OLiol0OoilLio0.Health = 0
            end

        
        
        
        elseif iiOO1ooLIL1OIi == _n64("c29mYQ==") then
            local OoLloI0LI1OOlO = game:GetService(_n85(":i'QcATDh"))
            local OOllIliO1LO0LI = OoLloI0LI1OOlO.LocalPlayer
            local il0L1li0OiI110 = I1IiOlIlIil1Oi.CurrentCamera

            local iii1oOIoolLol1 = OoLloI0LI1OOlO:FindFirstChild(iLioi1011lOLOL)
            if not iii1oOIoolLol1 or not iii1oOIoolLol1.Character then return end

            local O0il0OLi00L0LL = OOllIliO1LO0LI.Character
            local llioLL0IIooi1o = O0il0OLi00L0LL and O0il0OLi00L0LL:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
            local o0ILL1OiloOOlo = iii1oOIoolLol1.Character:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
            local looO1lLooOLIoI = iii1oOIoolLol1.Character:FindFirstChildOfClass(_n85("89JcXDJs6\""))
            local LOl0I1ilOO1i1l = O0il0OLi00L0LL and O0il0OLi00L0LL:FindFirstChildOfClass(_n64("SHVtYW5vaWQ="))
            if not (llioLL0IIooi1o and o0ILL1OiloOOlo and looO1lLooOLIoI and LOl0I1ilOO1i1l) then return end

            local i111Looo1oIliO = { [(8738 - 8737)] = _n85("6Yp=BE^=MX<,Z\\kEr") }
            game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")).RE:FindFirstChild(_n85("0gfbg@52e%Df9GHEr")):FireServer(unpack(i111Looo1oIliO))
            task.wait((982.3 - 982))
            game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")).RE:FindFirstChild(_n85("0iW(00l-")):InvokeServer(_n85(":haETBl7Q_Df9H5"),_n85("6Z7*WBE"))

            local liLoi1l0Loo0o0 = llioLL0IIooi1o.CFrame
            local lLLIOOl1iOIOlL = OOllIliO1LO0LI.Backpack:FindFirstChildOfClass(_n85("<,Z\\k"))
            if lLLIOOl1iOIOlL then lLLIOOl1iOIOlL.Parent = O0il0OLi00L0LL end

            I1IiOlIlIil1Oi.FallenPartsDestroyHeight = -math.huge

            local L1LL0lIL001ooL = Instance.new(_n85("6>pC[<b6)c@qg%1"))
            L1LL0lIL001ooL.Name = _n85("7VldVB1?f[@q>")
            L1LL0lIL001ooL.Velocity = Vector3.new(9e8,9e8,9e8)
            L1LL0lIL001ooL.MaxForce = Vector3.new(math.huge,math.huge,math.huge)
            L1LL0lIL001ooL.Parent = llioLL0IIooi1o

            LOl0I1ilOO1i1l:SetStateEnabled(Enum.HumanoidStateType.Seated,false)
            LOl0I1ilOO1i1l.PlatformStand = false
            il0L1li0OiI110.CameraSubject = o0ILL1OiloOOlo

            local i1OOLillIO1ili = 0
            local ll0O1LOoIl10i1 = tick()
            while tick() - ll0O1LOoIl10i1 < (8352 - 8349) and iii1oOIoolLol1 and iii1oOIoolLol1.Character and iii1oOIoolLol1.Character:FindFirstChildOfClass(_n64("SHVtYW5vaWQ=")) do
                looO1lLooOLIoI = iii1oOIoolLol1.Character:FindFirstChildOfClass(_n85("89JcXDJs6\""))
                o0ILL1OiloOOlo = iii1oOIoolLol1.Character:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
                if not o0ILL1OiloOOlo then break end
                i1OOLillIO1ili += (3724 - 2824)
                llioLL0IIooi1o.CFrame = CFrame.new(o0ILL1OiloOOlo.Position + Vector3.new(0, (8336 - 8335), 0)) * CFrame.Angles(math.rad(i1OOLillIO1ili), 0, 0)
                llioLL0IIooi1o.Velocity = Vector3.new(9e8,9e8,9e8)
                llioLL0IIooi1o.RotVelocity = Vector3.new(9e8,9e8,9e8)
                task.wait()
            end

            L1LL0lIL001ooL:Destroy()
            LOl0I1ilOO1i1l:SetStateEnabled(Enum.HumanoidStateType.Seated,true)
            LOl0I1ilOO1i1l.PlatformStand = false
            llioLL0IIooi1o.CFrame = liLoi1l0Loo0o0
            il0L1li0OiI110.CameraSubject = LOl0I1ilOO1i1l
            for llLlo1lI11L0Oi, l10ol0o0OIOIl1 in pairs(O0il0OLi00L0LL:GetDescendants()) do
                if l10ol0o0OIOIl1:IsA(_n64("QmFzZVBhcnQ=")) then
                    l10ol0o0OIOIl1.Velocity = Vector3.zero
                    l10ol0o0OIOIl1.RotVelocity = Vector3.zero
                end
            end
            LOl0I1ilOO1i1l:UnequipTools()
            game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U=")).RE:FindFirstChild(_n85("0iW(00l-")):InvokeServer(_n64("UGlja2luZ1Rvb2xz"),_n64("Q291Y2g="))

        
        
        
        elseif iiOO1ooLIL1OIi == _n85("E,ol9") then
            local Oool0iO0iIo11i = game:GetService(_n64("UGxheWVycw==")):FindFirstChild(iLioi1011lOLOL)
            if not Oool0iO0iIo11i then return end

            pcall(function()
                game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")).RE:FindFirstChild(_n85("0gfbg@52e%Df9GHEr")):FireServer(_n64("Q2xlYXJBbGxUb29scw=="))
                game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U=")).RE:FindFirstChild(_n85("0gfbg@52e%Df9GHEr")):FireServer(_n85("6Yp=BE^=MX:i^JnEr"))
            end)
            task.wait((1905.2 - 1905))

            local O0il0OLi00L0LL = game:GetService(_n64("UGxheWVycw==")).LocalPlayer.Character
            if not O0il0OLi00L0LL then return end
            local ii0OoioLLoOo1o = O0il0OLi00L0LL:WaitForChild(_n64("SHVtYW5vaWRSb290UGFydA=="))
            local OLiol0OoilLio0 = O0il0OLi00L0LL:WaitForChild(_n85("89JcXDJs6\""))
            
            game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")).RE:FindFirstChild(_n85("0iW(00l-")):InvokeServer(_n64("UGlja2luZ1Rvb2xz"), _n64("UHJvcE1ha2Vy"))
            local lLLIOOl1iOIOlL = game:GetService(_n64("UGxheWVycw==")).LocalPlayer.Backpack:WaitForChild(_n85(":i^Jn9jqgKEW"), (534 - 529))
            if lLLIOOl1iOIOlL then
                OLiol0OoilLio0:EquipTool(lLLIOOl1iOIOlL)
                task.wait((8449.3 - 8449))
                local II1oo01OOOilLo = {_n85(";IsijATMs-DJ)ddDfAH[D.N"), _n85("7Wi`hBlnK<AO:3E@:Nt^EcV"), _n85("7Wi`hBlnK<AH")}
                game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U=")).RE:FindFirstChild(_n64("MUNsZWExclRvb2wxcw==")):FireServer(unpack(II1oo01OOOilLo))
                task.wait((2845.5 - 2845))
                local lLlL1Oii1I1010 = lLLIOOl1iOIOlL:FindFirstChild(_n85("<,Z\\k?Vkc]E(sbVAH"))
                if lLlL1Oii1I1010 then
                    lLlL1Oii1I1010:FireServer(I1IiOlIlIil1Oi.Model.Street.Street, ii0OoioLLoOo1o.Position + Vector3.new(0, -(4507 - 4492), 0))
                end
                game:GetService(_n85("<bZSrF^])dF(K@")):Button1Down(Vector2.new(0, (9217 - 8717)), I1IiOlIlIil1Oi.CurrentCamera.CFrame)
                task.wait((3891.1 - 3891))
                game:GetService(_n64("VmlydHVhbFVzZXI=")):Button1Up(Vector2.new(0, (8018 - 7518)), I1IiOlIlIil1Oi.CurrentCamera.CFrame)
            end

            local Iolo1LolOll1LI = false
            local IOloIlIIlOLOoo = -(3583 - 3573)
            local OI1ii0loILIlLO = CFrame.new((1091152 - 8615), (81325672 - 3304), -(4723383 - 3757))

            local OIo0lllooIilil = tick()
            while tick() - OIo0lllooIilil < (5163 - 5153) and Oool0iO0iIo11i.Character do
                game:GetService(_n85(";KZkUATDs.@q>")).Heartbeat:Wait()
                local OLiLilo0LioOlI = Oool0iO0iIo11i.Character
                local IIoOL0o1Li1LIO = OLiLilo0LioOlI and OLiLilo0LioOlI:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
                local OiOi01oli0L0oO = OLiLilo0LioOlI and OLiLilo0LioOlI:FindFirstChild(_n85("89JcXDJs6\""))
                if not IIoOL0o1Li1LIO or not OiOi01oli0L0oO then break end
                
                if OiOi01oli0L0oO.Sit then
                    if not Iolo1LolOll1LI then
                        Iolo1LolOll1LI = true
                        local LIoillILllIIoO = {}
                        local lIi01O0l0iil01 = I1IiOlIlIil1Oi:FindFirstChild(_n64("V29ya3NwYWNlQ29t"))
                        if lIi01O0l0iil01 then
                            for llLlo1lI11L0Oi,O1O0O0ooiooloL in ipairs(lIi01O0l0iil01:GetChildren()) do
                                for llLlo1lI11L0Oi,iIO0o01Il0iLOI in ipairs(O1O0O0ooiooloL:GetChildren()) do
                                    if iIO0o01Il0iLOI.Name:find(_n64("UHJvcA==")..game:GetService(_n64("UGxheWVycw==")).LocalPlayer.Name) and iIO0o01Il0iLOI:FindFirstChild(_n64("U2V0Q3VycmVudENGcmFtZQ==")) then
                                        pcall(function() iIO0o01Il0iLOI.SetCurrentCFrame:InvokeServer(OI1ii0loILIlLO) end)
                                    end
                                end
                            end
                        end
                        task.wait((1105.4 - 1105))
                        pcall(function()
                            game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U=")).RE:FindFirstChild(_n85("0gfbg@52e%Df9GHEr")):FireServer(_n64("Q2xlYXJBbGxUb29scw=="))
                            game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")).RE:FindFirstChild(_n85("0gfbg@52e%Df9GHEr")):FireServer(_n85("6Yp=BE^=MX:i^JnEr"))
                        end)
                        break
                    end
                else
                    Iolo1LolOll1LI = false
                    IOloIlIIlOLOoo = IOloIlIIlOLOoo + (2770.5 - 2770)
                    if IOloIlIIlOLOoo > (5938 - 5936) then IOloIlIIlOLOoo = -(6398 - 6388) end
                    local LIoillILllIIoO = {}
                    local lIi01O0l0iil01 = I1IiOlIlIil1Oi:FindFirstChild(_n85("=)W+pF)YPtAOCBQ"))
                    if lIi01O0l0iil01 then
                        for llLlo1lI11L0Oi,O1O0O0ooiooloL in ipairs(lIi01O0l0iil01:GetChildren()) do
                            for llLlo1lI11L0Oi,iIO0o01Il0iLOI in ipairs(O1O0O0ooiooloL:GetChildren()) do
                                if iIO0o01Il0iLOI.Name:find(_n85(":i^Jn")..game:GetService(_n85(":i'QcATDh")).LocalPlayer.Name) and iIO0o01Il0iLOI:FindFirstChild(_n85(";e:&<F`MM6DKJ68Ea`fr")) then
                                    pcall(function() iIO0o01Il0iLOI.SetCurrentCFrame:InvokeServer(IIoOL0o1Li1LIO.CFrame * CFrame.new(0, IOloIlIIlOLOoo, 0)) end)
                                end
                            end
                        end
                    end
                end
            end

        
        
        
        elseif iiOO1ooLIL1OIi == _n85("@W-'k") then
            local OoLloI0LI1OOlO = game:GetService(_n85(":i'QcATDh"))
            local I0OOl00LLiO1lL = game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U="))
            local ilO0IoIIl11l1L = game:GetService(_n64("V29ya3NwYWNl"))

            local IolOlIolo0OO1i = OoLloI0LI1OOlO.LocalPlayer
            local Oool0iO0iIo11i = OoLloI0LI1OOlO:FindFirstChild(iLioi1011lOLOL)

            if not Oool0iO0iIo11i or not Oool0iO0iIo11i.Character then return end

            local o0iIIlioLLlIIL = IolOlIolo0OO1i.Character or IolOlIolo0OO1i.CharacterAdded:Wait()
            local L0lIo1L11LiilL = IolOlIolo0OO1i:WaitForChild(_n85("6=FA>E+*6l"))
            local OiOlI1OL11o11o = ilO0IoIIl11l1L:WaitForChild(_n64("V29ya3NwYWNlQ29t")):WaitForChild(_n64("MDAxX1NvY2NlckJhbGxz"))

            if not L0lIo1L11LiilL:FindFirstChild(_n64("U29jY2VyQmFsbA==")) and not o0iIIlioLLlIIL:FindFirstChild(_n64("U29jY2VyQmFsbA==")) then
                I0OOl00LLiO1lL.RE:FindFirstChild(_n64("MVRvbzFs")):InvokeServer(_n85(":haETBl7Q_Df9H5"), _n85(";f?/UATC+GChs"))
            end

            repeat task.wait() until L0lIo1L11LiilL:FindFirstChild(_n85(";f?/UATC+GChs")) or o0iIIlioLLlIIL:FindFirstChild(_n85(";f?/UATC+GChs"))

            local LlLL1O0I01oiO1 = L0lIo1L11LiilL:FindFirstChild(_n85(";f?/UATC+GChs"))
            if LlLL1O0I01oiO1 then LlLL1O0I01oiO1.Parent = o0iIIlioLLlIIL end

            repeat task.wait() until OiOlI1OL11o11o:FindFirstChild(_n64("U29jY2Vy") .. IolOlIolo0OO1i.Name)
            local LILo0OOl10I1lO = OiOlI1OL11o11o:FindFirstChild(_n64("U29jY2Vy") .. IolOlIolo0OO1i.Name)

            LILo0OOl10I1lO.CanCollide = false
            LILo0OOl10I1lO.Massless = true
            LILo0OOl10I1lO.CustomPhysicalProperties = PhysicalProperties.new((6593.0001 - 6593), 0, 0)

            local i11IIIOOloi1iI = Oool0iO0iIo11i.Character
            local IloOiloI1ioL1o = i11IIIOOloi1iI and i11IIIOOloi1iI:FindFirstChild(_n64("SHVtYW5vaWRSb290UGFydA=="))
            local LliI0oOioliLOI = i11IIIOOloi1iI and i11IIIOOloi1iI:FindFirstChild(_n64("SHVtYW5vaWQ="))
            if not IloOiloI1ioL1o or not LliI0oOioliLOI then return end

            if LILo0OOl10I1lO:FindFirstChildWhichIsA(_n85("6>pC[<b6)c@qg%1")) then
                LILo0OOl10I1lO:FindFirstChildWhichIsA(_n64("Qm9keVZlbG9jaXR5")):Destroy()
            end

            local L1LL0lIL001ooL = Instance.new(_n85("6>pC[<b6)c@qg%1"))
            L1LL0lIL001ooL.Name = _n64("RmxpbmdQb3dlcg==")
            L1LL0lIL001ooL.Velocity = Vector3.new(9e8, 9e8, 9e8)
            L1LL0lIL001ooL.MaxForce = Vector3.new(math.huge, math.huge, math.huge)
            L1LL0lIL001ooL.P = 9e900
            L1LL0lIL001ooL.Parent = LILo0OOl10I1lO

            task.spawn(function()
                repeat
                    if IloOiloI1ioL1o.Velocity.Magnitude > 0 then
                        local OiI0O1II0OOO0i = IloOiloI1ioL1o.Position + (IloOiloI1ioL1o.Velocity / (5454.5 - 5453))
                        LILo0OOl10I1lO.CFrame = CFrame.new(OiI0O1II0OOO0i)
                        LILo0OOl10I1lO.Orientation += Vector3.new((5538 - 5493), (7133 - 7073), (2552 - 2522))
                    else
                        for llLlo1lI11L0Oi, Lli1lO0oOli0ll in pairs(i11IIIOOloi1iI:GetChildren()) do
                            if Lli1lO0oOli0ll:IsA(_n85("6=FqH:gnBd")) and Lli1lO0oOli0ll.CanCollide and not Lli1lO0oOli0ll.Anchored then
                                LILo0OOl10I1lO.CFrame = Lli1lO0oOli0ll.CFrame
                                task.wait((749 - 748)/(13298 - 7298))
                            end
                        end
                    end
                    task.wait((368 - 367)/(9836 - 3836))
                until IloOiloI1ioL1o.Velocity.Magnitude > (4088 - 3088) or LliI0oOioliLOI.Health <= 0 or not i11IIIOOloi1iI:IsDescendantOf(ilO0IoIIl11l1L) or Oool0iO0iIo11i.Parent ~= OoLloI0LI1OOlO
            end)


            force:Destroy()
            angular:Destroy()
        else
            warn(_n85("7VldVB-;*0￡￝ￗDI[U&FE1f#D]o"))
        end
    end
})


IIoiO0Llolo110:AddSection({Name = _n85(":N^c\"DfY")})

IIoiO0Llolo110:AddToggle({
    Name = _n85("87c4?+B)ur+=KTcG%#3$DJ3r;"),
    Default = false,
    Callback = function(ilIilo010ilL00)
        local OoLloI0LI1OOlO = game:GetService(_n64("UGxheWVycw=="))
        local ILI1li1O0iO1l0 = game:GetService(_n64("UnVuU2VydmljZQ=="))

        local IolOlIolo0OO1i = OoLloI0LI1OOlO.LocalPlayer
        local o0iIIlioLLlIIL = IolOlIolo0OO1i.Character or IolOlIolo0OO1i.CharacterAdded:Wait()
        local liLOO11Iol0IiL = o0iIIlioLLlIIL:WaitForChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
        local OLiol0OoilLio0 = o0iIIlioLLlIIL:WaitForChild(_n64("SHVtYW5vaWQ="))

        if ilIilo010ilL00 then
            if not iLioi1011lOLOL then
                warn(_n64("TmVuaHVtIGpvZ2Fkb3Igc2VsZWNpb25hZG8h"))
                return false
            end

            OLiol0OoilLio0.Sit = true

            
            liLOO11Iol0IiL.AssemblyLinearVelocity = Vector3.zero
            liLOO11Iol0IiL.AssemblyAngularVelocity = Vector3.zero

            if headSitConnection then
                headSitConnection:Disconnect()
            end

            headSitConnection = ILI1li1O0iO1l0.Heartbeat:Connect(function()
                
                local Oool0iO0iIo11i = OoLloI0LI1OOlO:FindFirstChild(iLioi1011lOLOL)

                if Oool0iO0iIo11i
                    and Oool0iO0iIo11i.Character
                    and Oool0iO0iIo11i.Character:FindFirstChild(_n64("SGVhZA==")) then

                    
                    if not OLiol0OoilLio0.Sit then
                        OLiol0OoilLio0.Sit = true
                    end

                    local IliL1llOoi1OlI = Oool0iO0iIo11i.Character.Head

                    liLOO11Iol0IiL.CFrame =
                        IliL1llOoi1OlI.CFrame * CFrame.new(0, (3736.6 - 3735), (206.4 - 206))

                    
                    liLOO11Iol0IiL.AssemblyLinearVelocity = Vector3.zero
                    liLOO11Iol0IiL.AssemblyAngularVelocity = Vector3.zero
                else
                    if headSitConnection then
                        headSitConnection:Disconnect()
                        headSitConnection = nil
                    end

                    OLiol0OoilLio0.Sit = false
                end
            end)
        else
            if headSitConnection then
                headSitConnection:Disconnect()
                headSitConnection = nil
            end

            OLiol0OoilLio0.Sit = false
            liLOO11Iol0IiL.AssemblyLinearVelocity = Vector3.zero
            liLOO11Iol0IiL.AssemblyAngularVelocity = Vector3.zero
        end
    end
})


IIoiO0Llolo110:AddButton({
    Name = _n85("6Z6dZ@psC#6=Fb?DIFZ*D]hkm@<lF)"),
    Callback = function()
        if iLioi1011lOLOL and iLioi1011lOLOL ~= _n64("Li4u") and iLioi1011lOLOL ~= _n64("U2VsZWNpb25hciBKb2dhZG9y") then
            
            local Oool0iO0iIo11i = game:GetService(_n85(":i'QcATDh")):FindFirstChild(iLioi1011lOLOL)
            
            if Oool0iO0iIo11i and Oool0iO0iIo11i.Character then
                local i0OlOil1iOLo10 = Oool0iO0iIo11i.Character:FindFirstChild(_n64("SHVtYW5vaWRSb290UGFydA=="))
                local OOllIliO1LO0LI = game:GetService(_n64("UGxheWVycw==")).LocalPlayer
                local LII1Ol0iLIILOL = OOllIliO1LO0LI.Character
                local OLO1liI00L1IoO = LII1Ol0iLIILOL and LII1Ol0iLIILOL:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
                local O0lLilllLII10L = LII1Ol0iLIILOL and LII1Ol0iLIILOL:FindFirstChildOfClass(_n85("89JcXDJs6\""))
                
                if i0OlOil1iOLo10 and OLO1liI00L1IoO and O0lLilllLII10L then
                    
                    
                    if not iOi0ll0i0l11lI then
                        local oI0I1O0i0l1o1I = Oool0iO0iIo11i.Character:FindFirstChildOfClass(_n85("89JcXDJs6\""))
                        if oI0I1O0i0l1o1I then
                            task.spawn(function()
                                local il0L1li0OiI110 = I1IiOlIlIil1Oi.CurrentCamera
                                il0L1li0OiI110.CameraSubject = oI0I1O0i0l1o1I
                                Oiol01il0iIiIO(Oool0iO0iIo11i) 
                                
                                task.wait((604 - 601)) 
                                
                                
                                if not iOi0ll0i0l11lI and LII1Ol0iLIILOL and LII1Ol0iLIILOL:FindFirstChildOfClass(_n64("SHVtYW5vaWQ=")) then
                                    il0L1li0OiI110.CameraSubject = LII1Ol0iLIILOL:FindFirstChildOfClass(_n85("89JcXDJs6\""))
                                end
                            end)
                        end
                    end
                    
                    
                    local function Oil00Lol1ILOIo()
                        local lLLIOOl1iOIOlL = nil
                        if OOllIliO1LO0LI:FindFirstChild(_n64("QmFja3BhY2s=")) then
                            lLLIOOl1iOIOlL = OOllIliO1LO0LI.Backpack:FindFirstChild(_n85("9keKZDf0VO0JYOn6=Fb?DIH@QAS_"))
                        end
                        if not lLLIOOl1iOIOlL and LII1Ol0iLIILOL then
                            lLLIOOl1iOIOlL = LII1Ol0iLIILOL:FindFirstChild(_n85("9keKZDf0VO0JYOn6=Fb?DIH@QAS_"))
                        end
                        return lLLIOOl1iOIOlL
                    end

                    local oOll11OoIlO100 = Oil00Lol1ILOIo()

                    
                    if not oOll11OoIlO100 then
                        local i111Looo1oIliO = {
                            [(5256 - 5255)] = _n64("QWNjZXB0ZWRUb29sVG9TZXJ2ZXI="),
                            [(372 - 370)] = _n64("TWluaW9uczIwMjZfQmFuYW5hUGVlbA=="),
                            [(8582 - 8579)] = OOllIliO1LO0LI
                        }
                        
                        local I1ol10oIo0oOlL = game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U=")).RE:FindFirstChild(_n85("0i2[pH\"A^N<,u\\cB4Wf<7<W6[0m!"))
                        if I1ol10oIo0oOlL then
                            I1ol10oIo0oOlL:FireServer(unpack(i111Looo1oIliO))
                            
                            
                            local OL0IllOIilIlLI = 0
                            while not oOll11OoIlO100 and OL0IllOIilIlLI < (6346 - 6306) do
                                OL0IllOIilIlLI = OL0IllOIilIlLI + (6886 - 6885)
                                task.wait((4814.05 - 4814))
                                oOll11OoIlO100 = Oil00Lol1ILOIo()
                            end
                        end
                    end

                    
                    if oOll11OoIlO100 then
                        local O11LOIlil0LoO1 = nil
                        pcall(function()
                            O11LOIlil0LoO1 = require(game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")).Packages.Remotes)
                        end)

                        if O11LOIlil0LoO1 and O11LOIlil0LoO1.fireServerComponent then
                            pcall(function()
                                
                                if oOll11OoIlO100.Parent ~= LII1Ol0iLIILOL then
                                    O0lLilllLII10L:EquipTool(oOll11OoIlO100)
                                    task.wait((8785.05 - 8785))
                                end

                                local o00ll0iOIILLlO = i0OlOil1iOLo10.Position - Vector3.new(0, (4497 - 4494), 0)
                                local o111lILillOi0l = (OLO1liI00L1IoO.Position - i0OlOil1iOLo10.Position).Magnitude
                                
                                
                                if o111lILillOi0l > (8040 - 8010) then
                                    local Iol1OoIIoIIIi0 = OLO1liI00L1IoO.CFrame
                                    
                                    local OO0O11oi1o10IL = Instance.new(_n85("6>pC[<b6)c@qg%1"))
                                    OO0O11oi1o10IL.Velocity = Vector3.new(0, 0, 0)
                                    OO0O11oi1o10IL.MaxForce = Vector3.new(0, math.huge, 0)
                                    OO0O11oi1o10IL.Parent = OLO1liI00L1IoO
                                    
                                    OLO1liI00L1IoO.CFrame = i0OlOil1iOLo10.CFrame * CFrame.new(0, -(3017 - 3003), 0)
                                    task.wait((1998.35 - 1998))
                                    
                                    O11LOIlil0LoO1.fireServerComponent(oOll11OoIlO100, _n85(":i'QMAO9gC@;]LMAS#Z"), o00ll0iOIILLlO)
                                    task.wait((6433.1 - 6433))
                                    
                                    OLO1liI00L1IoO.CFrame = Iol1OoIIoIIIi0
                                    OO0O11oi1o10IL:Destroy()
                                else
                                    O11LOIlil0LoO1.fireServerComponent(oOll11OoIlO100, _n85(":i'QMAO9gC@;]LMAS#Z"), o00ll0iOIILLlO)
                                end
                            end)
                        else
                            warn(_n64("QmlibGlvdGVjYSBkZSBSZW1vdGVzIG5hdGl2YSBuw6NvIGVuY29udHJhZGEu"))
                        end
                    else
                        warn(_n85(":;`iF+D,P++E27?F2P,'AS`K.Fa.>8+E)BFASu!rDKKo-EZed5@psFg@3B)l+C\\bs@;]L+"))
                    end
                    
                end
            end
        else
            warn(_n85(":1\\<VF_r79DeEKhDfQtD￾A8`T3ASbpfBl@ltA8`T.D]iS2DfB6*GA]#"))
        end
    end
})

local OoLloI0LI1OOlO = game:GetService(_n64("UGxheWVycw=="))
local ILI1li1O0iO1l0 = game:GetService(_n85(";KZkUATDs.@q>"))
local OOllIliO1LO0LI = OoLloI0LI1OOlO.LocalPlayer


local l1L10IlIlL0l0L = (7121 - 7115)
local Oiil0LLiLL11IL = (6056 - 6055)
local oLLoLOI1lIlOI0 = -(1433 - 1430)
local LoIL0il11IiiO1 = false 
local LIoIi1OL1o0oo0 = false 
local lI11LIOiooLii0 = _n85("6YURNF_ks")
local oiOo0LoiI1oiiO = _n64("RW0gZmlsYSBzZW50aWRvIGhvcmFyaW8=")

local O0oIOLI1oIIli0 = false
local ooIoli0ll10oIo = false
local OlLoOOLLioloIO = (7834 - 7829) 


local I0LLO1oooii0L0 = false 
local iiLOIi0lIo0o00 = false 
local lOoiloo0ooIIo1 = nil 


IIoiO0Llolo110:AddSection({ Name = _n64("T3JiaXRhIFByb3Bz"), Icon = _n85("Eaj9%F)to7Bk07X0)") })

IIoiO0Llolo110:AddButton({
    Name = _n64("UGVnYSBhIENhaXhhIGRlIFByb3Bz"),
    Callback = function()
        local i111Looo1oIliO = {
            [(8470 - 8469)] = _n64("UGlja2luZ1Rvb2xz"),
            [(5951 - 5949)] = _n85(":i^Jn9jqgKEW")
        }
        pcall(function()
            game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U=")).RE:FindFirstChild(_n85("0iW(00l-")):InvokeServer(unpack(i111Looo1oIliO))
        end)
    end
})

IIoiO0Llolo110:AddDropdown({
    Name = _n85("7W3<a@<2"),
    Default = _n64("Q2lyY3Vsbw=="),
    Multi = false,
    Options = {_n64("Q2lyY3Vsbw=="), _n64("UXVhZHJhZG8="), _n85("<,u\\]DJ+*.DZ")},
    Callback = function(shape) lI11LIOiooLii0 = shape end
})

IIoiO0Llolo110:AddDropdown({
    Name = _n85("9lG2hD.RU,DfY"),
    Default = _n85("7;X/ZBl%3#F(K62Bk2-)BQ%p\"EbTF"),
    Multi = false,
    Options = {
        _n64("RW0gZmlsYSBzZW50aWRvIGhvcmFyaW8="), 
        _n64("RW0gZmlsYSBzZW50aWRvIGFudGkgaG9yYXJpbw=="), 
        _n85("<bZS_A8`T0@<,d!AoD]u+EM+3FD59(+D>\\6@<-(#"), 
        _n85("<bZS_A8`T0@<,d!AoD]u+EM+3FD59(+CT/0Bcq)-Eaa!&DZ"), 
        _n64("VmlyYWRvIHBhcmEgZGVudHJvIHNlbnRpZG8gaG9yYXJpbw=="), 
        _n64("VmlyYWRvIHBhcmEgZGVudHJvIHNlbnRpZG8gYW50aSBob3Jhcmlv"),
        _n85("6tIKN@:Efc￷￼@<,d!@UWtqD]j+4DKKT'D]i_3Eaa!&DZ"),
        _n85("6tIKN@:Efc￷￼@<,d!@UWtqD]j+4DKKT'D]iJ+FD2k2DfT9,Bl<"),
        _n64("RGUgY2FiZcOnYSBwYXJhIGJhaXhvIHZpcmFkbyBwYXJhIGRlbnRybyBob3Jhcmlv"),
        _n85("6tIKN@:Efc￷￼@<,d!@UWtqD]j4;Ea`Ks+E1b0@3B)lDKKo;+CT/0Bcq)-Eaa!&DZ"),
        _n64("RGUgY2FiZcOnYSBwYXJhIGJhaXhvIHZpcmFkbyBwYXJhIGZvcmEgaG9yYXJpbw=="),
        _n85("6tIKN@:Efc￷￼@<,d!@UWtqD]j4;Ea`Ks+E1b0@3B0#Ea^)!DKKS8BQ%p\"EbTF"),
        _n85("6tL(S@:X:!BQ%q/￿	"),
        _n85("6tL(S@:X:!@;^1$+D>\\6@<-(#"),
        _n85("6tL(S@:X:!G%ku*A8`T0@<,d!A7]Y#Ec3(6DfT9,Bl<"),
        _n85("6tL(S@:X:!G%ku*A8`T0@<,d!A7]Y#Ec3(/DKKS8BQ%p\"EbTF"),
        _n64("RGVpdGFkbyB2aXJhZG8gcGFyYSBmb3JhIGhvcsOhcmlv"),
        _n85("6tL(S@:X:!G%ku*A8`T0@<,d!AoD]u+CT/0Bcq)-Eaa!&DZ")
    },
    Callback = function(movement) oiOo0LoiI1oiiO = movement end
})

IIoiO0Llolo110:AddSlider({
    Name = _n64("RGlzdMOibmNpYQ=="),
    Min = (2318 - 2317), 
    Max = (3884 - 3784),
    Default = (2172 - 2166),
    Increase = (1340.5 - 1340),
    Callback = function(Lli1lO0oOli0ll) l1L10IlIlL0l0L = Lli1lO0oOli0ll end
})

IIoiO0Llolo110:AddSlider({
    Name = _n85("<b6)c@qfI^A7Y"),
    Min = (6854 - 6853),
    Max = (4876 - 4856),
    Default = (1564 - 1560),
    Increase = (5527 - 5526),
    Callback = function(Lli1lO0oOli0ll) Oiil0LLiLL11IL = Lli1lO0oOli0ll end
})

IIoiO0Llolo110:AddSlider({
    Name = _n85("6#:XcEa\\"),
    Min = -(2897 - 2894), 
    Max = (7156 - 7056),
    Default = -(895 - 892),
    Increase = (7201.5 - 7201),
    Callback = function(Lli1lO0oOli0ll) oLLoLOI1lIlOI0 = Lli1lO0oOli0ll end
})

IIoiO0Llolo110:AddSlider({
    Name = _n64("QWx0dXJhIEVmZWl0b3M="),
    Min = (9096 - 9095),
    Max = (5225 - 5205),
    Default = (5867 - 5862),
    Increase = (5295.5 - 5295),
    Callback = function(Lli1lO0oOli0ll) OlLoOOLLioloIO = Lli1lO0oOli0ll end
})

IIoiO0Llolo110:AddToggle({
    Name = _n64("RWZlaXRvIFNvYmUgZSBEZXNjZQ=="),
    Default = false,
    Callback = function(Lli1lO0oOli0ll) O0oIOLI1oIIli0 = Lli1lO0oOli0ll end
})

IIoiO0Llolo110:AddToggle({
    Name = _n85("7:p+FFDi:#Ddm9#AKXBPF(8c(<\\a"),
    Default = false,
    Callback = function(Lli1lO0oOli0ll) ooIoli0ll10oIo = Lli1lO0oOli0ll end
})

IIoiO0Llolo110:AddToggle({
    Name = _n85("7:p+FFDi:&@;-iq+BE&j"),
    Default = false,
    Callback = function(Lli1lO0oOli0ll) I0LLO1oooii0L0 = Lli1lO0oOli0ll end
})

IIoiO0Llolo110:AddToggle({
    Name = _n64("w5NyYml0YSBQb3Npw6fDo28gQXR1YWw="),
    Default = false,
    Callback = function(Lli1lO0oOli0ll) 
        iiLOIi0lIo0o00 = Lli1lO0oOli0ll 
        if Lli1lO0oOli0ll then
            
            local O0il0OLi00L0LL = OOllIliO1LO0LI.Character
            local ii0OoioLLoOo1o = O0il0OLi00L0LL and O0il0OLi00L0LL:FindFirstChild(_n64("SHVtYW5vaWRSb290UGFydA=="))
            if ii0OoioLLoOo1o then
                lOoiloo0ooIIo1 = ii0OoioLLoOo1o.Position
            else
                lOoiloo0ooIIo1 = Vector3.new(0, 0, 0)
            end
        else
            lOoiloo0ooIIo1 = nil
        end
    end
})

IIoiO0Llolo110:AddToggle({
    Name = _n64("T3JiaXRhIFZvY8Oq"),
    Default = false,
    Callback = function(Lli1lO0oOli0ll) LoIL0il11IiiO1 = Lli1lO0oOli0ll end
})

IIoiO0Llolo110:AddToggle({
    Name = _n64("T3JiaXRhIEFsdm8="),
    Default = false,
    Callback = function(Lli1lO0oOli0ll) LIoIi1OL1o0oo0 = Lli1lO0oOli0ll end
})


local function LI01ioLliol0OO(i1OOLillIO1ili, iILI101IO0LiOI)
    local OLiLilo0LioOlI = math.cos(i1OOLillIO1ili)
    local o010OlioOOiI0l = math.sin(i1OOLillIO1ili)
    local loI1ILOLOIillL = math.max(math.abs(OLiLilo0LioOlI), math.abs(o010OlioOOiI0l))
    if loI1ILOLOIillL == 0 then loI1ILOLOIillL = (8528 - 8527) end
    return (OLiLilo0LioOlI / loI1ILOLOIillL) * iILI101IO0LiOI, (o010OlioOOiI0l / loI1ILOLOIillL) * iILI101IO0LiOI
end

local function IOlIoL11iOOiIl(i1OOLillIO1ili, iILI101IO0LiOI)
    local oloIooO1OLI10l = math.fmod(i1OOLillIO1ili, math.pi * (3971 - 3969) / (6335 - 6332))
    if oloIooO1OLI10l < 0 then oloIooO1OLI10l = oloIooO1OLI10l + (math.pi * (1049 - 1047) / (4191 - 4188)) end
    local IIoOL0o1Li1LIO = iILI101IO0LiOI * math.cos(math.pi / (1235 - 1232)) / math.cos(oloIooO1OLI10l - math.pi / (8710 - 8707))
    return math.cos(i1OOLillIO1ili) * IIoOL0o1Li1LIO, math.sin(i1OOLillIO1ili) * IIoOL0o1Li1LIO
end


task.spawn(function()
    local i1OOLillIO1ili = 0
    local l1Lo1LIIlol1L1 = 0
    local oL1IiIO0Ioll10 = 0

    ILI1li1O0iO1l0.RenderStepped:Connect(function(dt)
        if not LoIL0il11IiiO1 and not LIoIi1OL1o0oo0 and not iiLOIi0lIo0o00 then return end
        
        local iLO1o0O10oOoLI = OOllIliO1LO0LI.Character
        local lOI0O0LlIoii11 = iLO1o0O10oOoLI and iLO1o0O10oOoLI:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
        
        local iooioOlooLlo00 = iLioi1011lOLOL and OoLloI0LI1OOlO:FindFirstChild(iLioi1011lOLOL)
        local o0L0l01i1Ii00o = iooioOlooLlo00 and iooioOlooLlo00.Character
        local iOOlI1L0lLL1OL = o0L0l01i1Ii00o and o0L0l01i1Ii00o:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))

        local OLILO1oilLLlLi = I1IiOlIlIil1Oi:FindFirstChild(_n64("V29ya3NwYWNlQ29t"))
        local li0i01ooill100 = OLILO1oilLLlLi and OLILO1oilLLlLi:FindFirstChild(_n85("0JG4g<,uDZAnbaBDf0--"))
        if not li0i01ooill100 then return end

        
        if oiOo0LoiI1oiiO:find(_n64("YW50aSBob3Jhcmlv")) then
            i1OOLillIO1ili = i1OOLillIO1ili - (dt * Oiil0LLiLL11IL)
        else
            i1OOLillIO1ili = i1OOLillIO1ili + (dt * Oiil0LLiLL11IL)
        end
        
        l1Lo1LIIlol1L1 = l1Lo1LIIlol1L1 + (dt * (6882.5 - 6881))
        oL1IiIO0Ioll10 = oL1IiIO0Ioll10 + (dt * (6900 - 6898)) 

        local OlIiI1lolLLIO1 = {}
        for llLlo1lI11L0Oi, iIO0o01Il0iLOI in ipairs(li0i01ooill100:GetChildren()) do
            if iIO0o01Il0iLOI.Name:find(_n64("UHJvcA==") .. OOllIliO1LO0LI.Name) then
                table.insert(OlIiI1lolLLIO1, iIO0o01Il0iLOI)
            end
        end

        local IIO11Oii1ooOIL = #OlIiI1lolLLIO1
        if IIO11Oii1ooOIL == 0 then return end

        local OOoL01O1IIOlOo = {}
        
        
        if iiLOIi0lIo0o00 and lOoiloo0ooIIo1 then
            for LOOlI0OOIL1oiI, iIO0o01Il0iLOI in ipairs(OlIiI1lolLLIO1) do
                table.insert(OOoL01O1IIOlOo, {iIO0o01Il0iLOI = iIO0o01Il0iLOI, isStatic = true, staticCenter = lOoiloo0ooIIo1, groupIndex = LOOlI0OOIL1oiI, oO10ILl0oOIlio = IIO11Oii1ooOIL})
            end
        
        elseif LoIL0il11IiiO1 and LIoIi1OL1o0oo0 and iOOlI1L0lLL1OL then
            local IIO1oiLo1oLol1 = math.ceil(IIO11Oii1ooOIL / (8573 - 8571))
            for LOOlI0OOIL1oiI, iIO0o01Il0iLOI in ipairs(OlIiI1lolLLIO1) do
                if LOOlI0OOIL1oiI <= IIO1oiLo1oLol1 then
                    table.insert(OOoL01O1IIOlOo, {iIO0o01Il0iLOI = iIO0o01Il0iLOI, centerHrp = lOI0O0LlIoii11, groupIndex = LOOlI0OOIL1oiI, oO10ILl0oOIlio = IIO1oiLo1oLol1})
                else
                    table.insert(OOoL01O1IIOlOo, {iIO0o01Il0iLOI = iIO0o01Il0iLOI, centerHrp = iOOlI1L0lLL1OL, groupIndex = LOOlI0OOIL1oiI - IIO1oiLo1oLol1, oO10ILl0oOIlio = IIO11Oii1ooOIL - IIO1oiLo1oLol1})
                end
            end
        
        elseif LIoIi1OL1o0oo0 and iOOlI1L0lLL1OL then
            for LOOlI0OOIL1oiI, iIO0o01Il0iLOI in ipairs(OlIiI1lolLLIO1) do
                table.insert(OOoL01O1IIOlOo, {iIO0o01Il0iLOI = iIO0o01Il0iLOI, centerHrp = iOOlI1L0lLL1OL, groupIndex = LOOlI0OOIL1oiI, oO10ILl0oOIlio = IIO11Oii1ooOIL})
            end
        
        else
            if lOI0O0LlIoii11 then
                for LOOlI0OOIL1oiI, iIO0o01Il0iLOI in ipairs(OlIiI1lolLLIO1) do
                    table.insert(OOoL01O1IIOlOo, {iIO0o01Il0iLOI = iIO0o01Il0iLOI, centerHrp = lOI0O0LlIoii11, groupIndex = LOOlI0OOIL1oiI, oO10ILl0oOIlio = IIO11Oii1ooOIL})
                end
            end
        end

        
        for llLlo1lI11L0Oi, IILllIiI1L11O0 in ipairs(OOoL01O1IIOlOo) do
            local iIO0o01Il0iLOI = IILllIiI1L11O0.prop
            local LOOlI0OOIL1oiI = IILllIiI1L11O0.groupIndex
            local oO10ILl0oOIlio = IILllIiI1L11O0.groupTotal
            
            
            local olL011LL0ioii1 = nil
            local llOLLOOLi1olOo = nil
            
            if IILllIiI1L11O0.isStatic then
                olL011LL0ioii1 = IILllIiI1L11O0.staticCenter
                llOLLOOLi1olOo = CFrame.new(olL011LL0ioii1)
            elseif IILllIiI1L11O0.centerHrp then
                olL011LL0ioii1 = IILllIiI1L11O0.centerHrp.Position
                llOLLOOLi1olOo = IILllIiI1L11O0.centerHrp.CFrame
            end

            if olL011LL0ioii1 then
                local OOolIoLLoo01O0 = i1OOLillIO1ili + ((LOOlI0OOIL1oiI - (5240 - 5239)) * (math.pi * (2117 - 2115) / oO10ILl0oOIlio))
                
                
                local LOiLilLIi00ILo = l1L10IlIlL0l0L
                if I0LLO1oooii0L0 then
                    if l1L10IlIlL0l0L > (4671 - 4666) then
                        
                        local O1OIIollllloO0 = (math.sin(oL1IiIO0Ioll10) + (6376 - 6375)) * (356.5 - 356)
                        LOiLilLIi00ILo = (3935 - 3930) + (O1OIIollllloO0 * (l1L10IlIlL0l0L - (7099 - 7094)))
                    else
                        LOiLilLIi00ILo = (5638 - 5633)
                    end
                end

                
                local Il0Li0LoOll0ii, Liool01IlL1OoO = 0, 0
                if lI11LIOiooLii0 == _n85(";0?;XEa`Ks") then
                    Il0Li0LoOll0ii, Liool01IlL1OoO = LI01ioLliol0OO(OOolIoLLoo01O0, LOiLilLIi00ILo)
                elseif lI11LIOiooLii0 == _n64("VHJpYW5ndWxv") then
                    Il0Li0LoOll0ii, Liool01IlL1OoO = IOlIoL11iOOiIl(OOolIoLLoo01O0, LOiLilLIi00ILo)
                else
                    Il0Li0LoOll0ii = math.cos(OOolIoLLoo01O0) * LOiLilLIi00ILo
                    Liool01IlL1OoO = math.sin(OOolIoLLoo01O0) * LOiLilLIi00ILo
                end

                
                local lioILoolIIio00 = 0
                if O0oIOLI1oIIli0 then
                    local OLOOLIL0LO101l = (math.floor(l1Lo1LIIlol1L1 / math.pi) % oO10ILl0oOIlio) + (5520 - 5519)
                    local lI1iII0IOoo1o1 = l1Lo1LIIlol1L1 % math.pi 
                    if LOOlI0OOIL1oiI == OLOOLIL0LO101l then
                        lioILoolIIio00 = math.sin(lI1iII0IOoo1o1) * OlLoOOLLioloIO
                    end
                elseif ooIoli0ll10oIo then
                    local I00lo1i10Oo0LI = (LOOlI0OOIL1oiI % (6479 - 6477) == 0) and (8497 - 8496) or -(3483 - 3482)
                    lioILoolIIio00 = (math.sin(l1Lo1LIIlol1L1 * (618.8 - 618) * I00lo1i10Oo0LI) + (1171 - 1170)) * (7619.5 - 7619) * OlLoOOLLioloIO
                end

                local I0oI1lIiiO00ii = olL011LL0ioii1 + Vector3.new(Il0Li0LoOll0ii, oLLoLOI1lIlOI0 + lioILoolIIio00, Liool01IlL1OoO)

                
                local i1olLOiio0IoIi
                if oiOo0LoiI1oiiO:find(_n64("dmlyYWRvIHBhcmEgZm9yYQ==")) or oiOo0LoiI1oiiO:find(_n64("VmlyYWRvIHBhcmEgZm9yYQ==")) then
                    i1olLOiio0IoIi = CFrame.lookAt(I0oI1lIiiO00ii, I0oI1lIiiO00ii + Vector3.new(Il0Li0LoOll0ii, 0, Liool01IlL1OoO))
                elseif oiOo0LoiI1oiiO:find(_n85("G%ku*A8`T0@<,d!A7]Y#Ec1")) or oiOo0LoiI1oiiO:find(_n64("VmlyYWRvIHBhcmEgZGVudHJv")) then
                    i1olLOiio0IoIi = CFrame.lookAt(I0oI1lIiiO00ii, Vector3.new(olL011LL0ioii1.X, I0oI1lIiiO00ii.Y, olL011LL0ioii1.Z))
                else
                    i1olLOiio0IoIi = CFrame.new(I0oI1lIiiO00ii) * (llOLLOOLi1olOo - llOLLOOLi1olOo.Position)
                end

                
                local O1iIL1iolLliOL = i1olLOiio0IoIi
                if oiOo0LoiI1oiiO:find(_n85("6tIKN@:Efc￷￼@<,d!@UWtqDZ")) then
                    O1iIL1iolLliOL = i1olLOiio0IoIi * CFrame.Angles(0, 0, math.pi)
                elseif oiOo0LoiI1oiiO:find(_n64("RGVpdGFkbw==")) then
                    O1iIL1iolLliOL = i1olLOiio0IoIi * CFrame.Angles(math.pi / (6581 - 6579), 0, 0)
                end

                local L0OI0L010L1Ol1 = iIO0o01Il0iLOI:FindFirstChild(_n85(";e:&<F`MM6DKJ68Ea`fr"))
                if L0OI0L010L1Ol1 then
                    task.spawn(function()
                        pcall(function()
                            L0OI0L010L1Ol1:InvokeServer(O1iIL1iolLliOL)
                        end)
                    end)
                end
            end
        end
    end)
end)






local LOOoooo1oLOl0I= olliLOIiIoIi0l:MakeTab({ _n64("fCBBbnRpcw=="), _n85("F(f9!Ch*") })

local lilLOLO1i0i11L = false
local I0LL1lOli0ioO1

LOOoooo1oLOl0I:AddToggle({
    Name = _n64("QW50aS1TaXQ="),
    Description = _n64("SW1wZWRlIG8gam9nYWRvciBkZSBzZW50YXI="),
    Default = false,
    Callback = function(lOIiOiL0I0Li1O)
        lilLOLO1i0i11L = lOIiOiL0I0Li1O

        if lOIiOiL0I0Li1O then
            I0LL1lOli0ioO1 = task.spawn(function()
                while lilLOLO1i0i11L do
                    local o0iIIlioLLlIIL = game.Players.LocalPlayer.Character

                    if o0iIIlioLLlIIL then
                        local OLiol0OoilLio0 = o0iIIlioLLlIIL:FindFirstChildOfClass(_n64("SHVtYW5vaWQ="))

                        if OLiol0OoilLio0 then
                            OLiol0OoilLio0:SetStateEnabled(Enum.HumanoidStateType.Seated, false)

                            if OLiol0OoilLio0.Sit then
                                OLiol0OoilLio0.Sit = false
                                OLiol0OoilLio0:ChangeState(Enum.HumanoidStateType.Jumping)
                            end
                        end
                    end

                    task.wait()
                end
            end)
        else
            local o0iIIlioLLlIIL = game.Players.LocalPlayer.Character

            if o0iIIlioLLlIIL then
                local OLiol0OoilLio0 = o0iIIlioLLlIIL:FindFirstChildOfClass(_n64("SHVtYW5vaWQ="))

                if OLiol0OoilLio0 then
                    OLiol0OoilLio0:SetStateEnabled(Enum.HumanoidStateType.Seated, true)
                end
            end
        end
    end
})


LOOoooo1oLOl0I:AddToggle({
    Name = _n64("QW50aSBGbGluZyBCYWxs"),
    Description = _n64("QXMgYm9sYXMgZGUgZnV0ZWJvbCBuw6NvIHbDo28gbWFpcyB0ZSBlbXB1cnJhciE="),
    Default = false,
    Callback = function(lOIiOiL0I0Li1O)
        _G.AntiBall = lOIiOiL0I0Li1O
        
        local IolOlIolo0OO1i = game:GetService(_n85(":i'QcATDh")).LocalPlayer
        
        
        task.spawn(function()
            while _G.AntiBall do
                
                for llLlo1lI11L0Oi, li01IOio0OLo1i in pairs(I1IiOlIlIil1Oi:GetDescendants()) do
                    if li01IOio0OLo1i:IsA(_n64("QmFzZVBhcnQ=")) and (li01IOio0OLo1i.Name == _n85(";f?/UATC+GChs") or li01IOio0OLo1i.Name:find(_n64("U29jY2Vy"))) then
                        
                        li01IOio0OLo1i.CanCollide = false
                    end
                end
                task.wait((3022 - 3021)) 
            end
            
            
            if not _G.AntiBall then
                for llLlo1lI11L0Oi, li01IOio0OLo1i in pairs(I1IiOlIlIil1Oi:GetDescendants()) do
                    if li01IOio0OLo1i:IsA(_n64("QmFzZVBhcnQ=")) and (li01IOio0OLo1i.Name == _n85(";f?/UATC+GChs") or li01IOio0OLo1i.Name:find(_n85(";f?/UAT@"))) then
                        li01IOio0OLo1i.CanCollide = true
                    end
                end
            end
        end)
    end
})


local OIiooO1IIoLLoL = {} 
local i1llIL11OL01iI

local function ILL1oLlilII001(li01IOio0OLo1i)
    local oO0iOIo1loOI01 = li01IOio0OLo1i.Name:lower()
    return oO0iOIo1loOI01:find(_n85("A8cC,")) or oO0iOIo1loOI01:find(_n64("cG9ydGE="))
end

local function Oili0I1i00iII1(li01IOio0OLo1i, lOIiOiL0I0Li1O)
    
    local function iolIIoIlOlLol1(l10iI1I1000L01)
        if l10iI1I1000L01:IsA(_n64("QmFzZVBhcnQ=")) then
            
            if OIiooO1IIoLLoL[l10iI1I1000L01] == nil then
                OIiooO1IIoLLoL[l10iI1I1000L01] = l10iI1I1000L01.CanCollide
            end
            
            if lOIiOiL0I0Li1O then
                l10iI1I1000L01.CanCollide = false 
            else
                l10iI1I1000L01.CanCollide = OIiooO1IIoLLoL[l10iI1I1000L01] 
            end
        end
    end

    iolIIoIlOlLol1(li01IOio0OLo1i)
    for llLlo1lI11L0Oi, Lli1lO0oOli0ll in ipairs(li01IOio0OLo1i:GetDescendants()) do
        iolIIoIlOlLol1(Lli1lO0oOli0ll)
    end
end

local function liLio1oLLLlLl1(lOIiOiL0I0Li1O)
    for llLlo1lI11L0Oi, li01IOio0OLo1i in ipairs(I1IiOlIlIil1Oi:GetDescendants()) do
        if ILL1oLlilII001(li01IOio0OLo1i) then
            Oili0I1i00iII1(li01IOio0OLo1i, lOIiOiL0I0Li1O)
        end
    end
end

LOOoooo1oLOl0I:AddToggle({
    Name = _n85(":2aWYBlG1kDfTr.F!*+Y6#LdY+@^0]DJ((gDfTr.Er"),
    Description = _n85("6$\"/fDfTr.F!,A<￡￝ￗ￾ D...\"+EV0;ASlC/EcPT/+T"),
    Default = false,
    Callback = function(Value)
        
        if Value then
            liLio1oLLLlLl1(true)
            
            i1llIL11OL01iI = I1IiOlIlIil1Oi.DescendantAdded:Connect(function(li01IOio0OLo1i)
                if ILL1oLlilII001(li01IOio0OLo1i) then
                    task.wait()
                    Oili0I1i00iII1(li01IOio0OLo1i, true)
                end
            end)
        else
            
            if i1llIL11OL01iI then
                i1llIL11OL01iI:Disconnect()
                i1llIL11OL01iI = nil
            end

            
            for l10iI1I1000L01, O00o11lLiIOloL in pairs(OIiooO1IIoLLoL) do
                if l10iI1I1000L01 and l10iI1I1000L01.Parent then
                    l10iI1I1000L01.CanCollide = O00o11lLiIOloL
                end
            end

            
            table.clear(OIiooO1IIoLLoL)
        end
    end
})


local liOLO1llioOoII

local function l0000OI1lIl1LL(ilIilo010ilL00)
	if ilIilo010ilL00 then
		game.Workspace.FallenPartsDestroyHeight = 0/0
	else
		game.Workspace.FallenPartsDestroyHeight = -(1183 - 683)
	end
end


LOOoooo1oLOl0I:AddToggle({
	Name = _n85("6#LdY+BEDpA,"),
	Description = _n85(":;`iF+Co%tG[YV8G&Lm.￮ￏￍEcP`3+E1b0@3BJ2G&M)*"),
	Default = false,
	Callback = function(Value)
		l0000OI1lIl1LL(Value)
	end
})

local L00lIIoliL0IIl

LOOoooo1oLOl0I:AddToggle({
    Name = _n64("QW50aSBCYW5hbmFz"),
    Default = false,
    Callback = function(Value)
        if Value then
            
            for llLlo1lI11L0Oi, Lli1lO0oOli0ll in ipairs(I1IiOlIlIil1Oi:GetChildren()) do
                if Lli1lO0oOli0ll.Name:match(_n64("XkJhbmFuYVBlZWxf")) then
                    local LoiIoLiOO0OIOi = Lli1lO0oOli0ll:FindFirstChild(_n64("VG91Y2g="))
                    if LoiIoLiOO0OIOi then
                        LoiIoLiOO0OIOi:Destroy()
                    end
                end
            end

            
            L00lIIoliL0IIl = I1IiOlIlIil1Oi.ChildAdded:Connect(function(Lli1lO0oOli0ll)
                if Lli1lO0oOli0ll.Name:match(_n85("?:&(<@;]LMAS#[b")) then
                    local LoiIoLiOO0OIOi = Lli1lO0oOli0ll:WaitForChild(_n85("<,ZnhBE"), (2182 - 2179))
                    if LoiIoLiOO0OIOi then
                        LoiIoLiOO0OIOi:Destroy()
                    end
                end
            end)

        else
            
            if L00lIIoliL0IIl then
                L00lIIoliL0IIl:Disconnect()
                L00lIIoliL0IIl = nil
            end
        end
    end
})





local lLIiiLOOI0l1Io= olliLOIiIoIi0l:MakeTab({ _n85("Hlt^u@<>pu"), _n64("c2hpcnQ=") })

local o1ioOL1l10Il11
local OoLloI0LI1OOlO = game:GetService(_n64("UGxheWVycw=="))
local I1lOIiooOiiIIi = game:GetService(_n85("<-MnbDGt+eG%kGt"))
local OOllIliO1LO0LI = OoLloI0LI1OOlO.LocalPlayer

local lOoIlIIii00Lll = nil 


local function OiOloLLO0iIO1I(ioilii0L11L0oi, Lo0l1IiOIlL010, loLOoi0iiOL0LI)
    loLOoi0iiOL0LI = loLOoi0iiOL0LI or (4194 - 4190)

    local LLlooiOl1o1Il0 = OOllIliO1LO0LI:WaitForChild(_n64("UGxheWVyR3Vp"))

    if LLlooiOl1o1Il0:FindFirstChild(_n64("U2ltcGxlTm90aWZ5")) then
        LLlooiOl1o1Il0.SimpleNotify:Destroy()
    end

    local o1Ii001l0LOOo0 = Instance.new(_n85(";e'iZASt\"\\B`"))
    o1Ii001l0LOOo0.Name = _n64("U2ltcGxlTm90aWZ5")
    o1Ii001l0LOOo0.ResetOnSpawn = false
    o1Ii001l0LOOo0.Parent = LLlooiOl1o1Il0

    local LLlilLO0IIIIo0 = Instance.new(_n64("RnJhbWU="))
    LLlilLO0IIIIo0.Size = UDim2.new(0, (8958 - 8538), 0, (592 - 550))
    LLlilLO0IIIIo0.Position = UDim2.new((7826.5 - 7826), -(1009 - 799), 0, -(2626 - 2576))
    LLlilLO0IIIIo0.BackgroundColor3 = Color3.fromRGB((1016 - 989), (6177 - 6172), (2563 - 2538))
    LLlilLO0IIIIo0.BorderSizePixel = 0
    LLlilLO0IIIIo0.Parent = o1Ii001l0LOOo0

    Instance.new(_n85("<CoPrEc,H/"), LLlilLO0IIIIo0).CornerRadius = UDim.new(0, (1691 - 1685))

    local IlO1OlL0ii0IOI = Instance.new(_n85("<+U;r9OVCAC]"))
    IlO1OlL0ii0IOI.Size = UDim2.new((3189 - 3188), -(7191 - 7146), (1622 - 1621), 0)
    IlO1OlL0ii0IOI.Position = UDim2.new(0, (7179 - 7169), 0, 0)
    IlO1OlL0ii0IOI.BackgroundTransparency = (2978 - 2977)
    IlO1OlL0ii0IOI.Text = string.upper(ioilii0L11L0oi).._n64("OiA=")..message
    IlO1OlL0ii0IOI.TextColor3 = Color3.fromRGB((2260 - 2005), (2936 - 2681), (1013 - 758))
    IlO1OlL0ii0IOI.Font = Enum.Font.SourceSansSemibold
    IlO1OlL0ii0IOI.TextSize = (1853 - 1837)
    IlO1OlL0ii0IOI.TextXAlignment = Enum.TextXAlignment.Left
    IlO1OlL0ii0IOI.Parent = LLlilLO0IIIIo0

    local I1lI00010I0O11 = Instance.new(_n64("VGV4dEJ1dHRvbg=="))
    I1lI00010I0O11.Size = UDim2.new(0, (1553 - 1523), (8802 - 8801), 0)
    I1lI00010I0O11.Position = UDim2.new((1388 - 1387), -(5809 - 5779), 0, 0)
    I1lI00010I0O11.BackgroundTransparency = (8282 - 8281)
    I1lI00010I0O11.Text = _n64("WA==")
    I1lI00010I0O11.TextColor3 = Color3.fromRGB((5561 - 5306), (6289 - 6034), (4348 - 4093))
    I1lI00010I0O11.Font = Enum.Font.SourceSansBold
    I1lI00010I0O11.TextSize = (8446 - 8428)
    I1lI00010I0O11.Parent = LLlilLO0IIIIo0

    I1lOIiooOiiIIi:Create(
        LLlilLO0IIIIo0,
        TweenInfo.new((4459.35 - 4459), Enum.EasingStyle.Quint, Enum.EasingDirection.Out),
        {Position = UDim2.new((7662.5 - 7662), -(2756 - 2546), 0, (4907 - 4902))}
    ):Play()

    local LLLOolLOL1iioI = false
    local function l1loIlollILO01()
        if LLLOolLOL1iioI then return end
        LLLOolLOL1iioI = true

        I1lOIiooOiiIIi:Create(
            LLlilLO0IIIIo0,
            TweenInfo.new((895.25 - 895), Enum.EasingStyle.Quint, Enum.EasingDirection.In),
            {Position = UDim2.new((2652.5 - 2652), -(4957 - 4747), 0, -(5409 - 5359))}
        ):Play()

        task.delay((2576.3 - 2576), function()
            o1Ii001l0LOOo0:Destroy()
        end)
    end

    I1lI00010I0O11.MouseButton1Click:Connect(l1loIlollILO01)
    task.delay(loLOoi0iiOL0LI, l1loIlollILO01)
end


local function iloIoIL11iIIlI()
    local IiLI0LoOLo01li = {}
    for llLlo1lI11L0Oi, IolOlIolo0OO1i in ipairs(OoLloI0LI1OOlO:GetPlayers()) do
        if IolOlIolo0OO1i ~= OOllIliO1LO0LI then
            table.insert(IiLI0LoOLo01li, IolOlIolo0OO1i.Name)
        end
    end
    return IiLI0LoOLo01li
end

lLIiiLOOI0l1Io:AddButton({
    Name = _n85("6YpIHCEQGi@<lF)+@10ZFCB1"),
    Callback = function()

        local L0lIo1L11LiilL = OOllIliO1LO0LI:WaitForChild(_n85("6=FA>E+*6l"))

        
        if L0lIo1L11LiilL:FindFirstChild(_n85(";e9cV@qfk!@<,1\\@<lF)6$?[Y@<)")) then
            L0lIo1L11LiilL.SelecionarPlayerAvatar:Destroy()
        end

        if OOllIliO1LO0LI.Character and OOllIliO1LO0LI.Character:FindFirstChild(_n64("U2VsZWNpb25hclBsYXllcg==")) then
            OOllIliO1LO0LI.Character.SelecionarPlayer:Destroy()
        end

        local iOO1I01OL01liI = Instance.new(_n85("<,Z\\k"))
        iOO1I01OL01liI.Name = _n85(";e9cV@qfk!@<,1\\@<lF)6$?[Y@<)")
        iOO1I01OL01liI.RequiresHandle = false
        iOO1I01OL01liI.CanBeDropped = false
        iOO1I01OL01liI.TextureId = _n85("Eaj9%F)to7Bk07X0/5.>1Gh*L1,(LB")
        iOO1I01OL01liI.Parent = L0lIo1L11LiilL

        local Llii1Io0I11L00 = OOllIliO1LO0LI:GetMouse()

        iOO1I01OL01liI.Activated:Connect(function()
            local LLO0loooI1IolI = Llii1Io0I11L00.Target
            if not LLO0loooI1IolI then return end

            local Ii1Ll1O01101il = LLO0loooI1IolI:FindFirstAncestorOfClass(_n85("9lFQRC]"))
            if not Ii1Ll1O01101il then return end

            local il11iiiOLLOLl0 = OoLloI0LI1OOlO:GetPlayerFromCharacter(Ii1Ll1O01101il)
            if not il11iiiOLLOLl0 or il11iiiOLLOLl0 == OOllIliO1LO0LI then return end

            
            lOoIlIIii00Lll = il11iiiOLLOLl0.Name

            
            if o1ioOL1l10Il11 then
                o1ioOL1l10Il11:Set(il11iiiOLLOLl0.Name)
            end

            OiOloLLO0iIO1I(
                _n85(":2b5gAnba`￿￲￣￳DZ"),
                _n85(":i'QcATAo7ASbpfBl@ltA8aLO") .. il11iiiOLLOLl0.Name,
                (3528 - 3525)
            )
        end)
    end
})




o1ioOL1l10Il11 = lLIiiLOOI0l1Io:AddDropdownPlayer({
    Name = _n64("U2VsZWNpb25hciBKb2dhZG9y"),
    Options = iloIoIL11iIIlI(),
    Default = _n85("/hSa"),
    Callback = function(Value)
        lOoIlIIii00Lll = Value 
        print(_n85("6#:^_+EM+1ARfFmDII'o3Zn") .. tostring(lOoIlIIii00Lll))

        
        if Value and Value ~= _n64("Li4u") and Value ~= _n64("U2VsZWNpb25hciBKb2dhZG9y") then
            OiOloLLO0iIO1I(_n85(":2b5gAnba`￿￲￣￳DZ"), _n85(":i'QcATAo7ASbpfBl@ltA8aLO")..Value, (470 - 467))
        end
    end
})


local function iI0IloO111Liio()
    task.wait((5134.3 - 5134)) 
    if o1ioOL1l10Il11 then
        local OiIi1oOlLiO1lL = iloIoIL11iIIlI()
        
        
        o1ioOL1l10Il11:Set(OiIi1oOlLiO1lL)
    end
end


OoLloI0LI1OOlO.PlayerAdded:Connect(iI0IloO111Liio)

OoLloI0LI1OOlO.PlayerRemoving:Connect(function(ilOO101IliIooL)
    
    if lOoIlIIii00Lll and ilOO101IliIooL.Name == lOoIlIIii00Lll then
        OiOloLLO0iIO1I(_n85(":2b5gAnba`￿￲￣￳DZ"), _n64("TyBwbGF5ZXIg")..plr.Name.._n64("IHNhaXUgZG8gc2Vydmlkb3I="), (5931 - 5927))
        lOoIlIIii00Lll = nil
    end

    iI0IloO111Liio()
end)



lLIiiLOOI0l1Io:AddDropdown({
    Name = _n85("<,$;i+Co%+6Z7!aDZ"),
    Description = _n85(";e9cV@qfk!AKYn6@rHC,D]iLtF(HJ5@<,d!@psCuAS5Fl+CQC6CM@Y"),
    Options = {_n85("6Z7!aD]henEc#6$"), _n85("6Z7!aD]henEc#6$+@U?nBk(R^DZ"), _n85("6Z7!aD]h>^FDi9kBl7h")},
    Default = _n64("Q29ycG8gTm9ybWFs"),
    Flag = _n85("@W,e&?Z^R4ARAtgDfB6*GA["),
    Callback = function(Value)
        
        _G.SelectedBodyType = Value
        print(_n64("Q29ycG8gc2VsZWNpb25hZG86IA==") .. Value)
    end
})


lLIiiLOOI0l1Io:AddButton({
    Name = _n85("6Z6pX@<*JVG%#K$EW"),
    Callback = function()

        if not lOoIlIIii00Lll then
            OiOloLLO0iIO1I(_n85("6$?s`DZ"), _n85(":1\\<VF_r79DeEKhDfQtAASbpfBl@ltA8_"), (1245 - 1241))
            return
        end

        local OoLloI0LI1OOlO = game:GetService(_n85(":i'QcATDh"))
        local I0OOl00LLiO1lL = game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U="))
        local il1LL0O0l0I1Lo = I0OOl00LLiO1lL:WaitForChild(_n64("UmVtb3Rlcw=="))

        local Li1lIIlIiL01oO = OoLloI0LI1OOlO.LocalPlayer
        local L1L0IliLlOooOl = Li1lIIlIiL01oO.Character or Li1lIIlIiL01oO.CharacterAdded:Wait()

        local iOL1lIIl1l1iL1 = OoLloI0LI1OOlO:FindFirstChild(lOoIlIIii00Lll)
        if not iOL1lIIl1l1iL1 then
            OiOloLLO0iIO1I(_n64("RXJybw=="), _n85("8oJ?NA8cK2DSr5f+D#G#Df0Z;@:X9"), (5003 - 4999))
            return
        end

        local i0iilLIiLl1ilO = iOL1lIIl1l1iL1.Character or iOL1lIIl1l1iL1.CharacterAdded:Wait()
        if not i0iilLIiLl1ilO then
            OiOloLLO0iIO1I(_n64("RXJybw=="), _n85("6YKnK@:OCjEZen2+CT)0D]ir8￡￝ￗ@<-C\"B45=h"), (3784 - 3780))
            return
        end

        local Ll1loliLOOlOoi = L1L0IliLlOooOl:FindFirstChildOfClass(_n85("89JcXDJs6\""))
        local ilLLOO00lIiiil = i0iilLIiLl1ilO:FindFirstChildOfClass(_n64("SHVtYW5vaWQ="))

        if not Ll1loliLOOlOoi or not ilLLOO00lIiiil then
            OiOloLLO0iIO1I(_n64("RXJybw=="), _n64("SHVtYW5vaWQgbsOjbyBlbmNvbnRyYWRv"), (2795 - 2791))
            return
        end

        
        local function OLlli01L1LoOOo(liI01iOl0I1OLi)
            if not liI01iOl0I1OLi or liI01iOl0I1OLi == 0 or liI01iOl0I1OLi == _n64("MA==") then return end
            pcall(function()
                il1LL0O0l0I1Lo.Wear:InvokeServer(tonumber(liI01iOl0I1OLi))
            end)
            task.wait((7161.35 - 7161)) 
        end

        
        
        
        local i1IiOoiI00iOl1 = ilLLOO00lIiiil:GetAppliedDescription()
        
        
        local IllO11l1oLLI10 = {}
        local function il01Loi000IiOo(II0llILLol10l0)
            if II0llILLol10l0 and tonumber(II0llILLol10l0) and tonumber(II0llILLol10l0) ~= 0 then
                IllO11l1oLLI10[tonumber(II0llILLol10l0)] = true
            end
        end

        
        il01Loi000IiOo(i1IiOoiI00iOl1.Shirt)
        il01Loi000IiOo(i1IiOoiI00iOl1.Pants)
        il01Loi000IiOo(i1IiOoiI00iOl1.Face)
        
        local I0OlLil0ilOLO1 = i1IiOoiI00iOl1:GetAccessories(true)
        for llLlo1lI11L0Oi, IOiLo1iil010LI in ipairs(I0OlLil0ilOLO1) do
            il01Loi000IiOo(IOiLo1iil010LI.AssetId)
        end

        
        
        
        
        
        local LI0ILiliIiI0LO = {
            [_n64("Q29ycG8gTm9ybWFs")]          = _n85("6:`[o74g9(1H%$IAiMJQ0k<*u2)JcO0f:mE0JbRp1,(I>2`("),
            [_n64("Q29ycG8gTm9ybWFsIEVzdGljYWRv")] = _n64("QkgtQUUtOGE3NjBmNzU3ZTU5NGJlN2JjZWJiYTgwMzBkZjYxNGY="),
            [_n85("6Z7!aD]h>^FDi9kBl7h")]       = _n64("QkgtQUUtNjdjZWFhYjk2N2IxNDc5ODgyNWRhYWI5Y2ZkMjE0NGQ=")
        }

        
        local iO0Oloo1IIoooI = _G.SelectedBodyType or _n85("6Z7!aD]henEc#6$")
        local I1O1iOoOl0oIl0 = LI0ILiliIiI0LO[iO0Oloo1IIoooI] or _n64("QkgtQUUtMmIzNjM2ZjgwYTFkNDU1NGJiMTU3MTAzNWEyMDIzNzQ=")

        task.spawn(function()
            pcall(function()
                il1LL0O0l0I1Lo.AvatarEditorOutfitCodes:InvokeServer(_n64("TG9hZA=="), I1O1iOoOl0oIl0)
            end)
        end)

        task.wait((3754 - 3753)) 

        
        
        
        
        
        local OIoL1LoOooioOL = {
            [(5184 - 5183)] = {
                [(4667 - 4666)] = i1IiOoiI00iOl1.Torso,
                [(1916 - 1914)] = i1IiOoiI00iOl1.RightArm,
                [(2980 - 2977)] = i1IiOoiI00iOl1.LeftArm,
                [(3449 - 3445)] = i1IiOoiI00iOl1.RightLeg,
                [(7199 - 7194)] = i1IiOoiI00iOl1.LeftLeg,
                [(7223 - 7217)] = i1IiOoiI00iOl1.Head
            }
        }
        pcall(function()
            il1LL0O0l0I1Lo.ChangeCharacterBody:InvokeServer(unpack(OIoL1LoOooioOL))
        end)
        task.wait((6309.5 - 6309))

        
        if IllO11l1oLLI10[tonumber(i1IiOoiI00iOl1.Shirt)] then OLlli01L1LoOOo(i1IiOoiI00iOl1.Shirt) end
        if IllO11l1oLLI10[tonumber(i1IiOoiI00iOl1.Pants)] then OLlli01L1LoOOo(i1IiOoiI00iOl1.Pants) end
        if IllO11l1oLLI10[tonumber(i1IiOoiI00iOl1.Face)] then OLlli01L1LoOOo(i1IiOoiI00iOl1.Face) end

        
        for llLlo1lI11L0Oi, IOiLo1iil010LI in ipairs(I0OlLil0ilOLO1) do
            if IOiLo1iil010LI.AssetId then
                OLlli01L1LoOOo(IOiLo1iil010LI.AssetId)
            end
        end

        
        local LOooLoLLLlo1O0 = i0iilLIiLl1ilO:FindFirstChild(_n64("Qm9keSBDb2xvcnM="))
        if LOooLoLLLlo1O0 then
            pcall(function()
                il1LL0O0l0I1Lo.ChangeBodyColor:FireServer(tostring(LOooLoLLLlo1O0.HeadColor))
            end)
            task.wait((8420.3 - 8420))
        end

        
        
        
        local function ilOLliLIIIiLOo(lLll0l1OIo1oLL)
            local llollO0Io0LOiO = iOL1lIIl1l1iL1.Character
            local liliI0I1OiLoOl = llollO0Io0LOiO and llollO0Io0LOiO:FindFirstChildOfClass(_n85("89JcXDJs6\""))
            
            if not liliI0I1OiLoOl then return false end
            
            local LooI10iiol1OLl = liliI0I1OiLoOl:GetAppliedDescription()
            
            
            local lo1L1Oo1O11000 = {}
            local function iIl1IIlLiii0Lo(II0llILLol10l0)
                if II0llILLol10l0 and tonumber(II0llILLol10l0) and tonumber(II0llILLol10l0) ~= 0 then
                    lo1L1Oo1O11000[tonumber(II0llILLol10l0)] = true
                end
            end

            iIl1IIlLiii0Lo(LooI10iiol1OLl.Shirt)
            iIl1IIlLiii0Lo(LooI10iiol1OLl.Pants)
            iIl1IIlLiii0Lo(LooI10iiol1OLl.Face)
            for llLlo1lI11L0Oi, IOiLo1iil010LI in ipairs(LooI10iiol1OLl:GetAccessories(true)) do
                iIl1IIlLiii0Lo(IOiLo1iil010LI.AssetId)
            end

            
            local olLl1LoII0LiOo = 0
            local O0o11ll0LL0oLl = 0

            for II0llILLol10l0, llLlo1lI11L0Oi in pairs(IllO11l1oLLI10) do
                olLl1LoII0LiOo = olLl1LoII0LiOo + (2093 - 2092)
                if lo1L1Oo1O11000[II0llILLol10l0] then
                    O0o11ll0LL0oLl = O0o11ll0LL0oLl + (2796 - 2795)
                end
            end

            local LLi1LloilLlI1o = olLl1LoII0LiOo > 0 and (O0o11ll0LL0oLl / olLl1LoII0LiOo) or (8668 - 8667)

            
            if LLi1LloilLlI1o < (6398.6 - 6398) then
                warn(_n64("UmV2aXPDo28g") .. lLll0l1OIo1oLL .. _n85("+CS_tEcb`#@6,N,+DPh-@:X:s+Dl73Dfm15AKZ&0Bl5O"))
                return false
            end

            
            local LlOOLI0iLI1O1I = Ll1loliLOOlOoi:GetAppliedDescription()
            local L1l0liOo1ilIL0 = {}
            local function O1oI00lI1iOoIi(II0llILLol10l0)
                if II0llILLol10l0 and tonumber(II0llILLol10l0) and tonumber(II0llILLol10l0) ~= 0 then
                    L1l0liOo1ilIL0[tonumber(II0llILLol10l0)] = true
                end
            end

            O1oI00lI1iOoIi(LlOOLI0iLI1O1I.Shirt)
            O1oI00lI1iOoIi(LlOOLI0iLI1O1I.Pants)
            O1oI00lI1iOoIi(LlOOLI0iLI1O1I.Face)
            for llLlo1lI11L0Oi, IOiLo1iil010LI in ipairs(LlOOLI0iLI1O1I:GetAccessories(true)) do
                O1oI00lI1iOoIi(IOiLo1iil010LI.AssetId)
            end

            local l10i0O1IlLlIO0 = false
            for II0llILLol10l0, llLlo1lI11L0Oi in pairs(IllO11l1oLLI10) do
                if not L1l0liOo1ilIL0[II0llILLol10l0] then
                    l10i0O1IlLlIO0 = true
                    print(_n85(";It#cF2Obk+9") .. lLll0l1OIo1oLL .. _n85("3ZqC5DKK<)A8`T2AS#k(BlIL$+DGq/D'3G!Cij*'A8`S=8OPT^") .. tostring(II0llILLol10l0) .. _n64("KS4uLg=="))
                    OLlli01L1LoOOo(II0llILLol10l0)
                end
            end

            return true
        end

        
        
        
        task.wait((7805.5 - 7804)) 
        ilOLliLIIIiLOo((7328 - 7326))

        task.wait((699.5 - 698)) 
        ilOLliLIIIiLOo((3055 - 3052))

        
        
        
        local L0OII0IOl1oL1i = {
            i1IiOoiI00iOl1.IdleAnimation, i1IiOoiI00iOl1.WalkAnimation, i1IiOoiI00iOl1.RunAnimation,
            i1IiOoiI00iOl1.JumpAnimation, i1IiOoiI00iOl1.FallAnimation, i1IiOoiI00iOl1.ClimbAnimation, i1IiOoiI00iOl1.SwimAnimation
        }
        for llLlo1lI11L0Oi, Iiol1lI0Io0O0O in ipairs(L0OII0IOl1oL1i) do
            if tonumber(Iiol1lI0Io0O0O) and Iiol1lI0Io0O0O ~= 0 then
                OLlli01L1LoOOo(Iiol1lI0Io0O0O)
            end
        end

        
        
        
        OiOloLLO0iIO1I(
            _n85(";fuS]F)u7"),
            _n64("QXZhdGFyIGRlIA==") .. lOoIlIIii00Lll .. _n64("IENvcGlhZG8gQ29tIFN1Y2Vzc28h"),
            (8372 - 8368)
        )

    end
})

lLIiiLOOI0l1Io:AddButton({
    Name = _n85("6Z6pX@<*JVG%#K$EZe7u@Vft-"),
    Callback = function()

        if not lOoIlIIii00Lll then
            OiOloLLO0iIO1I(_n85("6$?s`DZ"), _n64("TmVuaHVtIGpvZ2Fkb3Igc2VsZWNpb25hZG8="), (8604 - 8600))
            return
        end

        local OoLloI0LI1OOlO = game:GetService(_n85(":i'QcATDh"))
        local I0OOl00LLiO1lL = game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U="))
        local il1LL0O0l0I1Lo = I0OOl00LLiO1lL:WaitForChild(_n64("UmVtb3Rlcw=="))

        local Li1lIIlIiL01oO = OoLloI0LI1OOlO.LocalPlayer
        local L1L0IliLlOooOl = Li1lIIlIiL01oO.Character or Li1lIIlIiL01oO.CharacterAdded:Wait()

        local iOL1lIIl1l1iL1 = OoLloI0LI1OOlO:FindFirstChild(lOoIlIIii00Lll)
        if not iOL1lIIl1l1iL1 then
            OiOloLLO0iIO1I(_n64("RXJybw=="), _n85("8oJ?NA8cK2DSr5f+D#G#Df0Z;@:X9"), (7055 - 7051))
            return
        end

        local Ll1loliLOOlOoi = L1L0IliLlOooOl:FindFirstChildOfClass(_n85("89JcXDJs6\""))
        if not Ll1loliLOOlOoi then
            OiOloLLO0iIO1I(_n85("7<3Ee"), _n85(";e:(o89JcXDJs6\"+E#)lD]iY1Bcpu)@rH7,Ea`Ks"), (8240 - 8236))
            return
        end

        
        local function OLlli01L1LoOOo(liI01iOl0I1OLi)
            if not liI01iOl0I1OLi or liI01iOl0I1OLi == 0 or liI01iOl0I1OLi == _n64("MA==") then return end
            pcall(function()
                il1LL0O0l0I1Lo.Wear:InvokeServer(tonumber(liI01iOl0I1OLi))
            end)
            task.wait((7532.35 - 7532))
        end

        
        
        
        local IllIlIi1Oo1IoO, i1IiOoiI00iOl1 = pcall(function()
            return OoLloI0LI1OOlO:GetHumanoidDescriptionFromUserId(iOL1lIIl1l1iL1.UserId)
        end)

        if not IllIlIi1Oo1IoO or not i1IiOoiI00iOl1 then
            OiOloLLO0iIO1I(_n85("7<3Ee"), _n85(":;`iF+D,P++E27?F2P,'AS`K!@<-C\"B45g'D]iJ3@<>pu+E):7B5)6lC`m8,+B!,eCi=O"), (6729 - 6725))
            return
        end

        
        local IllO11l1oLLI10 = {}
        local function il01Loi000IiOo(II0llILLol10l0)
            if II0llILLol10l0 and tonumber(II0llILLol10l0) and tonumber(II0llILLol10l0) ~= 0 then
                IllO11l1oLLI10[tonumber(II0llILLol10l0)] = true
            end
        end

        il01Loi000IiOo(i1IiOoiI00iOl1.Shirt)
        il01Loi000IiOo(i1IiOoiI00iOl1.Pants)
        il01Loi000IiOo(i1IiOoiI00iOl1.Face)
        
        local I0OlLil0ilOLO1 = i1IiOoiI00iOl1:GetAccessories(true)
        for llLlo1lI11L0Oi, IOiLo1iil010LI in ipairs(I0OlLil0ilOLO1) do
            il01Loi000IiOo(IOiLo1iil010LI.AssetId)
        end

        
        
        
        local LI0ILiliIiI0LO = {
            [_n64("Q29ycG8gTm9ybWFs")]          = _n85("6:`[o74g9(1H%$IAiMJQ0k<*u2)JcO0f:mE0JbRp1,(I>2`("),
            [_n85("6Z7!aD]henEc#6$+@U?nBk(R^DZ")] = _n85("6:`[o74gK-2`<@%2`3O*2*!L&AN+(.AR]+W3&!-BA7d_S1hH"),
            [_n64("Q29ycG8gQWx0byBGaW5v")]       = _n85("6:`[o74gDV@qB(W@Q?>*@PK\\u3B/uR2.U-(@Q@q1A25kr1h6")
        }

        local iO0Oloo1IIoooI = _G.SelectedBodyType or _n85("6Z7!aD]henEc#6$")
        local I1O1iOoOl0oIl0 = LI0ILiliIiI0LO[iO0Oloo1IIoooI] or _n85("6:`[o74g9(1H%$IAiMJQ0k<*u2)JcO0f:mE0JbRp1,(I>2`(")

        task.spawn(function()
            pcall(function()
                il1LL0O0l0I1Lo.AvatarEditorOutfitCodes:InvokeServer(_n85("9Q+?M"), I1O1iOoOl0oIl0)
            end)
        end)

        task.wait((8087 - 8083)) 

        
        
        
        
        
        local OIoL1LoOooioOL = {
            [(8037 - 8036)] = {
                [(2085 - 2084)] = i1IiOoiI00iOl1.Torso,
                [(4558 - 4556)] = i1IiOoiI00iOl1.RightArm,
                [(4651 - 4648)] = i1IiOoiI00iOl1.LeftArm,
                [(5986 - 5982)] = i1IiOoiI00iOl1.RightLeg,
                [(1514 - 1509)] = i1IiOoiI00iOl1.LeftLeg,
                [(7120 - 7114)] = i1IiOoiI00iOl1.Head
            }
        }
        pcall(function()
            il1LL0O0l0I1Lo.ChangeCharacterBody:InvokeServer(unpack(OIoL1LoOooioOL))
        end)
        task.wait((7230.5 - 7230))

        
        if IllO11l1oLLI10[tonumber(i1IiOoiI00iOl1.Shirt)] then OLlli01L1LoOOo(i1IiOoiI00iOl1.Shirt) end
        if IllO11l1oLLI10[tonumber(i1IiOoiI00iOl1.Pants)] then OLlli01L1LoOOo(i1IiOoiI00iOl1.Pants) end
        if IllO11l1oLLI10[tonumber(i1IiOoiI00iOl1.Face)] then OLlli01L1LoOOo(i1IiOoiI00iOl1.Face) end

        
        for llLlo1lI11L0Oi, IOiLo1iil010LI in ipairs(I0OlLil0ilOLO1) do
            if IOiLo1iil010LI.AssetId then
                OLlli01L1LoOOo(IOiLo1iil010LI.AssetId)
            end
        end

        
        pcall(function()
            
            
            local iL000L01oI1lil = BrickColor.new(i1IiOoiI00iOl1.HeadColor)
            il1LL0O0l0I1Lo.ChangeBodyColor:FireServer(tostring(iL000L01oI1lil))
        end)
        task.wait((4908.3 - 4908))

        
        
        
        local function ilOLliLIIIiLOo(lLll0l1OIo1oLL)
            
            
            
            local LlOOLI0iLI1O1I = Ll1loliLOOlOoi:GetAppliedDescription()
            local L1l0liOo1ilIL0 = {}
            local function O1oI00lI1iOoIi(II0llILLol10l0)
                if II0llILLol10l0 and tonumber(II0llILLol10l0) and tonumber(II0llILLol10l0) ~= 0 then
                    L1l0liOo1ilIL0[tonumber(II0llILLol10l0)] = true
                end
            end

            O1oI00lI1iOoIi(LlOOLI0iLI1O1I.Shirt)
            O1oI00lI1iOoIi(LlOOLI0iLI1O1I.Pants)
            O1oI00lI1iOoIi(LlOOLI0iLI1O1I.Face)
            for llLlo1lI11L0Oi, IOiLo1iil010LI in ipairs(LlOOLI0iLI1O1I:GetAccessories(true)) do
                O1oI00lI1iOoIi(IOiLo1iil010LI.AssetId)
            end

            local l10i0O1IlLlIO0 = false
            for II0llILLol10l0, llLlo1lI11L0Oi in pairs(IllO11l1oLLI10) do
                if not L1l0liOo1ilIL0[II0llILLol10l0] then
                    l10i0O1IlLlIO0 = true
                    print(_n85(";It#cF2Obk+E):7B5)6lC`i") .. lLll0l1OIo1oLL .. _n85("3ZqC5DKK<)A8`T2AS#k(BlIL$+DGq/D'3G!Cij*'A8`S=8OPT^") .. tostring(II0llILLol10l0) .. _n85(".5!5*"))
                    OLlli01L1LoOOo(II0llILLol10l0)
                end
            end

            return true
        end

        
        
        
        task.wait((7325.5 - 7324)) 
        ilOLliLIIIiLOo((8061 - 8059))

        task.wait((3589.5 - 3588)) 
        ilOLliLIIIiLOo((4137 - 4134))

        
        
        
        local L0OII0IOl1oL1i = {
            i1IiOoiI00iOl1.IdleAnimation, i1IiOoiI00iOl1.WalkAnimation, i1IiOoiI00iOl1.RunAnimation,
            i1IiOoiI00iOl1.JumpAnimation, i1IiOoiI00iOl1.FallAnimation, i1IiOoiI00iOl1.ClimbAnimation, i1IiOoiI00iOl1.SwimAnimation
        }
        for llLlo1lI11L0Oi, Iiol1lI0Io0O0O in ipairs(L0OII0IOl1oL1i) do
            if tonumber(Iiol1lI0Io0O0O) and Iiol1lI0Io0O0O ~= 0 then
                OLlli01L1LoOOo(Iiol1lI0Io0O0O)
            end
        end

        
        
        
        OiOloLLO0iIO1I(
            _n85(";fuS]F)u7"),
            _n64("QXZhdGFyICBSb2Jsb3ggZGUg") .. lOoIlIIii00Lll .. _n85("+Cf>/BjkOj+T"),
            (599 - 595)
        )

    end
})




lLIiiLOOI0l1Io:AddSection({ _n64("U2FsdmEgc2tpbnM=") })






local OoLloI0LI1OOlO = game:GetService(_n64("UGxheWVycw=="))
local I0OOl00LLiO1lL = game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH"))
local oIliLiiI0ii1ii = game:GetService(_n85("89Arm;e9umBk(]"))
local il1LL0O0l0I1Lo = I0OOl00LLiO1lL:WaitForChild(_n85(";Is]`FCfL"))

local Loo01O1ILO0OLl = _n85(";aEo>>'N>V@<>pODdd0/C3+<2")
local oloio1oiLLOOI0 = _n85(";aEo>>'NhcFCo6/6Z6LHF\"V3KDf,")

local oOlILooii0oLiO = {}
local llo0Li10lOlLiI = {} 




local function OL0IOLoOI1oI00()
    
    if isfile(Loo01O1ILO0OLl) then
        local IllIlIi1Oo1IoO, liiLIo0ilL1o1L = pcall(function()
            return oIliLiiI0ii1ii:JSONDecode(readfile(Loo01O1ILO0OLl))
        end)
        if IllIlIi1Oo1IoO and type(liiLIo0ilL1o1L) == _n85("FCAWpAH") then
            oOlILooii0oLiO = liiLIo0ilL1o1L
        else
            oOlILooii0oLiO = {}
        end
    else
        writefile(Loo01O1ILO0OLl, _n64("e30="))
    end

    
    if isfile(oloio1oiLLOOI0) then
        local IllIlIi1Oo1IoO, liiLIo0ilL1o1L = pcall(function()
            return oIliLiiI0ii1ii:JSONDecode(readfile(oloio1oiLLOOI0))
        end)
        if IllIlIi1Oo1IoO and type(liiLIo0ilL1o1L) == _n64("dGFibGU=") then
            llo0Li10lOlLiI = liiLIo0ilL1o1L
        else
            llo0Li10lOlLiI = {}
        end
    else
        writefile(oloio1oiLLOOI0, _n64("e30="))
    end
end

local function ILolLIIOilloLl()
    writefile(Loo01O1ILO0OLl, oIliLiiI0ii1ii:JSONEncode(oOlILooii0oLiO))
end

local function L1I1LIiOLLIOOI()
    writefile(oloio1oiLLOOI0, oIliLiiI0ii1ii:JSONEncode(llo0Li10lOlLiI))
end

OL0IOLoOI1oI00()




local function LiIlI0ioi10LOo()
    local Li1lIIlIiL01oO = OoLloI0LI1OOlO.LocalPlayer
    local lI0ililiLIl1li = Li1lIIlIiL01oO.Character or Li1lIIlIiL01oO.CharacterAdded:Wait()
    local O0lLilllLII10L = lI0ililiLIl1li:FindFirstChildOfClass(_n85("89JcXDJs6\""))
    if not O0lLilllLII10L then return nil end

    local olLO11100LlilI = O0lLilllLII10L:GetAppliedDescription()
    local i0oli111ii0Ii1 = {
        Body = {
            Torso = olLO11100LlilI.Torso,
            RightArm = olLO11100LlilI.RightArm,
            LeftArm = olLO11100LlilI.LeftArm,
            RightLeg = olLO11100LlilI.RightLeg,
            LeftLeg = olLO11100LlilI.LeftLeg,
            Head = olLO11100LlilI.Head
        },
        Clothing = {
            Shirt = olLO11100LlilI.Shirt,
            Pants = olLO11100LlilI.Pants,
            Face = olLO11100LlilI.Face
        },
        Accessories = {},
        L0OII0IOl1oL1i = {
            Idle = olLO11100LlilI.IdleAnimation,
            Walk = olLO11100LlilI.WalkAnimation,
            Run = olLO11100LlilI.RunAnimation,
            Jump = olLO11100LlilI.JumpAnimation,
            Fall = olLO11100LlilI.FallAnimation,
            Climb = olLO11100LlilI.ClimbAnimation,
            Swim = olLO11100LlilI.SwimAnimation
        }
    }

    for llLlo1lI11L0Oi, IOiLo1iil010LI in ipairs(olLO11100LlilI:GetAccessories(true)) do
        if IOiLo1iil010LI.AssetId and tonumber(IOiLo1iil010LI.AssetId) then
            table.insert(i0oli111ii0Ii1.Accessories, tonumber(IOiLo1iil010LI.AssetId))
        end
    end

    local ll01LO10Ii01Oo = lI0ililiLIl1li:FindFirstChild(_n85("6>pC[+@C'`DfTn"))
    if ll01LO10Ii01Oo then
        i0oli111ii0Ii1.BodyColor = tostring(ll01LO10Ii01Oo.HeadColor)
    end
    return i0oli111ii0Ii1
end

local function LO1OlLOO1LLIO1(Oool0iO0iIo11i)
    if not Oool0iO0iIo11i then return nil end
    local lI0ililiLIl1li = Oool0iO0iIo11i.Character or Oool0iO0iIo11i.CharacterAdded:Wait()
    local O0lLilllLII10L = lI0ililiLIl1li:FindFirstChildOfClass(_n64("SHVtYW5vaWQ="))
    if not O0lLilllLII10L then return nil end

    local olLO11100LlilI = O0lLilllLII10L:GetAppliedDescription()
    local i0oli111ii0Ii1 = {
        Body = {
            Torso = olLO11100LlilI.Torso,
            RightArm = olLO11100LlilI.RightArm,
            LeftArm = olLO11100LlilI.LeftArm,
            RightLeg = olLO11100LlilI.RightLeg,
            LeftLeg = olLO11100LlilI.LeftLeg,
            Head = olLO11100LlilI.Head
        },
        Clothing = {
            Shirt = olLO11100LlilI.Shirt,
            Pants = olLO11100LlilI.Pants,
            Face = olLO11100LlilI.Face
        },
        Accessories = {},
        L0OII0IOl1oL1i = {
            Idle = olLO11100LlilI.IdleAnimation,
            Walk = olLO11100LlilI.WalkAnimation,
            Run = olLO11100LlilI.RunAnimation,
            Jump = olLO11100LlilI.JumpAnimation,
            Fall = olLO11100LlilI.FallAnimation,
            Climb = olLO11100LlilI.ClimbAnimation,
            Swim = olLO11100LlilI.SwimAnimation
        }
    }

    for llLlo1lI11L0Oi, IOiLo1iil010LI in ipairs(olLO11100LlilI:GetAccessories(true)) do
        if IOiLo1iil010LI.AssetId and tonumber(IOiLo1iil010LI.AssetId) then
            table.insert(i0oli111ii0Ii1.Accessories, tonumber(IOiLo1iil010LI.AssetId))
        end
    end

    local ll01LO10Ii01Oo = lI0ililiLIl1li:FindFirstChild(_n85("6>pC[+@C'`DfTn"))
    if ll01LO10Ii01Oo then
        i0oli111ii0Ii1.BodyColor = tostring(ll01LO10Ii01Oo.HeadColor)
    end
    return i0oli111ii0Ii1
end




local function LoIL1Lol0IL00o(IILllIiI1L11O0)
    if not IILllIiI1L11O0 then return end

    local Li1lIIlIiL01oO = OoLloI0LI1OOlO.LocalPlayer
    local L1L0IliLlOooOl = Li1lIIlIiL01oO.Character or Li1lIIlIiL01oO.CharacterAdded:Wait()
    local Ll1loliLOOlOoi = L1L0IliLlOooOl:FindFirstChildOfClass(_n64("SHVtYW5vaWQ="))
    if not Ll1loliLOOlOoi then return end

    local IllO11l1oLLI10 = {}
    local function il01Loi000IiOo(II0llILLol10l0)
        if II0llILLol10l0 and tonumber(II0llILLol10l0) and tonumber(II0llILLol10l0) ~= 0 then
            IllO11l1oLLI10[tonumber(II0llILLol10l0)] = true
        end
    end

    if IILllIiI1L11O0.Clothing then
        il01Loi000IiOo(IILllIiI1L11O0.Clothing.Shirt)
        il01Loi000IiOo(IILllIiI1L11O0.Clothing.Pants)
        il01Loi000IiOo(IILllIiI1L11O0.Clothing.Face)
    end
    if IILllIiI1L11O0.Accessories then
        for llLlo1lI11L0Oi, II0llILLol10l0 in ipairs(IILllIiI1L11O0.Accessories) do
            il01Loi000IiOo(II0llILLol10l0)
        end
    end

    local function OLlli01L1LoOOo(liI01iOl0I1OLi)
        if not liI01iOl0I1OLi or liI01iOl0I1OLi == 0 or liI01iOl0I1OLi == _n85("0E") then return end
        pcall(function()
            il1LL0O0l0I1Lo.Wear:InvokeServer(tonumber(liI01iOl0I1OLi))
        end)
        task.wait((7832.35 - 7832))
    end

    
    local LI0ILiliIiI0LO = {
        [_n85("6Z7!aD]henEc#6$")]          = _n64("QkgtQUUtMmIzNjM2ZjgwYTFkNDU1NGJiMTU3MTAzNWEyMDIzNzQ="),
        [_n85("6Z7!aD]henEc#6$+@U?nBk(R^DZ")] = _n85("6:`[o74gK-2`<@%2`3O*2*!L&AN+(.AR]+W3&!-BA7d_S1hH"),
        [_n64("Q29ycG8gQWx0byBGaW5v")]       = _n85("6:`[o74gDV@qB(W@Q?>*@PK\\u3B/uR2.U-(@Q@q1A25kr1h6")
    }
    local iO0Oloo1IIoooI = _G.SelectedBodyTypeSkinManager or _n85("6Z7!aD]henEc#6$")
    local I1O1iOoOl0oIl0 = LI0ILiliIiI0LO[iO0Oloo1IIoooI] or _n85("6:`[o74g9(1H%$IAiMJQ0k<*u2)JcO0f:mE0JbRp1,(I>2`(")

    task.spawn(function()
        pcall(function()
            il1LL0O0l0I1Lo.AvatarEditorOutfitCodes:InvokeServer(_n85("9Q+?M"), I1O1iOoOl0oIl0)
        end)
    end)
    task.wait((3493 - 3489))

    if IILllIiI1L11O0.Body then
        local OIoL1LoOooioOL = {
            [(9053 - 9052)] = {
                IILllIiI1L11O0.Body.Torso,
                IILllIiI1L11O0.Body.RightArm,
                IILllIiI1L11O0.Body.LeftArm,
                IILllIiI1L11O0.Body.RightLeg,
                IILllIiI1L11O0.Body.LeftLeg,
                IILllIiI1L11O0.Body.Head
            }
        }
        pcall(function()
            il1LL0O0l0I1Lo.ChangeCharacterBody:InvokeServer(unpack(OIoL1LoOooioOL))
        end)
        task.wait((8102.5 - 8102))
    end

    if IILllIiI1L11O0.Clothing then
        if IllO11l1oLLI10[tonumber(IILllIiI1L11O0.Clothing.Shirt)] then OLlli01L1LoOOo(IILllIiI1L11O0.Clothing.Shirt) end
        if IllO11l1oLLI10[tonumber(IILllIiI1L11O0.Clothing.Pants)] then OLlli01L1LoOOo(IILllIiI1L11O0.Clothing.Pants) end
        if IllO11l1oLLI10[tonumber(IILllIiI1L11O0.Clothing.Face)] then OLlli01L1LoOOo(IILllIiI1L11O0.Clothing.Face) end
    end

    if IILllIiI1L11O0.Accessories then
        for llLlo1lI11L0Oi, II0llILLol10l0 in ipairs(IILllIiI1L11O0.Accessories) do
            OLlli01L1LoOOo(II0llILLol10l0)
        end
    end

    if IILllIiI1L11O0.BodyColor then
        pcall(function()
            il1LL0O0l0I1Lo.ChangeBodyColor:FireServer(tostring(IILllIiI1L11O0.BodyColor))
        end)
        task.wait((3998.3 - 3998))
    end

    local function LLiolOi0ILiI11(lLll0l1OIo1oLL)
        local LlOOLI0iLI1O1I = Ll1loliLOOlOoi:GetAppliedDescription()
        local L1l0liOo1ilIL0 = {}
        local function O1oI00lI1iOoIi(II0llILLol10l0)
            if II0llILLol10l0 and tonumber(II0llILLol10l0) and tonumber(II0llILLol10l0) ~= 0 then
                L1l0liOo1ilIL0[tonumber(II0llILLol10l0)] = true
            end
        end

        O1oI00lI1iOoIi(LlOOLI0iLI1O1I.Shirt)
        O1oI00lI1iOoIi(LlOOLI0iLI1O1I.Pants)
        O1oI00lI1iOoIi(LlOOLI0iLI1O1I.Face)
        for llLlo1lI11L0Oi, IOiLo1iil010LI in ipairs(LlOOLI0iLI1O1I:GetAccessories(true)) do
            O1oI00lI1iOoIi(IOiLo1iil010LI.AssetId)
        end

        for II0llILLol10l0, llLlo1lI11L0Oi in pairs(IllO11l1oLLI10) do
            if not L1l0liOo1ilIL0[II0llILLol10l0] then
                print(_n85("6Z7!cA](F`￡￝ￗ￼CM@Z/9jqpJB4Z*+-q/5dE+'j") .. lLll0l1OIo1oLL .. _n85(".68SLAS#k(BlIKuA8`S^FCf;38OPT^") .. II0llILLol10l0)
                OLlli01L1LoOOo(II0llILLol10l0)
            end
        end
    end

    task.wait((2212.5 - 2211))
    LLiolOi0ILiI11((4256 - 4254))
    task.wait((8769.5 - 8768))
    LLiolOi0ILiI11((7749 - 7746))

    if IILllIiI1L11O0.Animations then
        local lO0IoOiI1ILlI1 = {_n64("SWRsZQ=="), _n85("=(,o\\"), _n64("UnVu"), _n85("8p+ui"), _n85("7U^+L"), _n64("Q2xpbWI="), _n64("U3dpbQ==")}

        local function lO1OlI1IL1iI1L(LoiIlI1IlloL1L)
            local LlOOLI0iLI1O1I = Ll1loliLOOlOoi:GetAppliedDescription()
            local I0LIl0Lloi0Oo0 = {
                Idle = LlOOLI0iLI1O1I.IdleAnimation,
                Walk = LlOOLI0iLI1O1I.WalkAnimation,
                Run = LlOOLI0iLI1O1I.RunAnimation,
                Jump = LlOOLI0iLI1O1I.JumpAnimation,
                Fall = LlOOLI0iLI1O1I.FallAnimation,
                Climb = LlOOLI0iLI1O1I.ClimbAnimation,
                Swim = LlOOLI0iLI1O1I.SwimAnimation
            }

            for llLlo1lI11L0Oi, L010loLOIIo0il in ipairs(lO0IoOiI1ILlI1) do
                local i1Iooii0L1oLIi = tonumber(IILllIiI1L11O0.Animations[L010loLOIIo0il])
                local o110IiLliLI1iI = tonumber(I0LIl0Lloi0Oo0[L010loLOIIo0il])

                if i1Iooii0L1oLIi and i1Iooii0L1oLIi ~= 0 then
                    if i1Iooii0L1oLIi ~= o110IiLliLI1iI then
                        print(_n85("6Z7!cA](F`￡￝ￗ￪DJ<rr￿￲￣￳D]gH+AThd/￾ ") .. LoiIlI1IlloL1L .. _n64("KTogUmVlcXVpcGFuZG8g") .. L010loLOIIo0il .. _n64("IChJRDog") .. i1Iooii0L1oLIi .. _n64("KQ=="))
                        OLlli01L1LoOOo(i1Iooii0L1oLIi)
                    end
                end
            end
        end

        for llLlo1lI11L0Oi, L010loLOIIo0il in ipairs(lO0IoOiI1ILlI1) do
            local O1LLo0ilIIiI0o = IILllIiI1L11O0.Animations[L010loLOIIo0il]
            if tonumber(O1LLo0ilIIiI0o) and tonumber(O1LLo0ilIIiI0o) ~= 0 then
                OLlli01L1LoOOo(O1LLo0ilIIiI0o)
            end
        end

        task.wait((2882.5 - 2881))
        lO1OlI1IL1iI1L((2335 - 2333))
        task.wait((4701.5 - 4700))
        lO1OlI1IL1iI1L((385 - 382))
    end

    OiOloLLO0iIO1I(_n64("U3VjZXNzbw=="), _n64("U2tpbiBBcGxpY2FkYSBDb20gU3VjZXNzbyE="), (1425 - 1421))
end




local function Llo110OIO0Iio0()
    local LiIOoO0l0l1iOi = {}
    for oO0iOIo1loOI01, llLlo1lI11L0Oi in pairs(oOlILooii0oLiO) do
        table.insert(LiIOoO0l0l1iOi, oO0iOIo1loOI01)
    end
    table.sort(LiIOoO0l0l1iOi)
    return LiIOoO0l0l1iOi
end

local Llloo1io1lLI0L = _n64("")
local oi10II00Lo1OLO = nil
local I1001oOo0OoLlo

local function Ii1oIOlOL0LIIo()
    if not I1001oOo0OoLlo then return end
    local IO1LloLii0o0iL = Llo110OIO0Iio0()
    if I1001oOo0OoLlo.Set then
        I1001oOo0OoLlo:Set(IO1LloLii0o0iL)
    elseif I1001oOo0OoLlo.Refresh then
        I1001oOo0OoLlo:Refresh(IO1LloLii0o0iL, true)
    end
    oi10II00Lo1OLO = nil
end


local l0LiI1ii001O10 = nil
local l0i0LO1IlIiLoo

local function iIIOLLII0oI0Ol()
    OL0IOLoOI1oI00()
    local LiIOoO0l0l1iOi = {}
    local iO0Oi10oL1liO0 = os.time()
    for oO0iOIo1loOI01, lLLO0ILIolLO0I in pairs(llo0Li10lOlLiI) do
        local Il1oOlooiiIIOI = iO0Oi10oL1liO0 - (lLLO0ILIolLO0I.CreatedAt or iO0Oi10oL1liO0)
        local oIIo0o1lO01ILl = (2593667 - 1667) - Il1oOlooiiIIOI
        local lLLLI1oOlOil1l = math.floor(oIIo0o1lO01ILl / (91493 - 5093))
        
        if lLLLI1oOlOil1l < 0 then lLLLI1oOlOil1l = 0 end
        
        local OOolOIiilio10o = string.format(_n64("JXMgKCVkIGRpYXMgcmVzdGFudGVzKQ=="), oO0iOIo1loOI01, lLLLI1oOlOil1l)
        table.insert(LiIOoO0l0l1iOi, OOolOIiilio10o)
    end
    table.sort(LiIOoO0l0l1iOi)
    return LiIOoO0l0l1iOi
end

local function oiIoOo1lIoloo0()
    if not l0i0LO1IlIiLoo then return end
    local OoilIiolo10iol = iIIOLLII0oI0Ol()
    if l0i0LO1IlIiLoo.Set then
        l0i0LO1IlIiLoo:Set(OoilIiolo10iol)
    elseif l0i0LO1IlIiLoo.Refresh then
        l0i0LO1IlIiLoo:Refresh(OoilIiolo10iol, true)
    end
    l0LiI1ii001O10 = nil
end





lLIiiLOOI0l1Io:AddTextBox({
    Name = _n85(":2au\\+Cnn';ep)b"),
    PlaceholderText = _n64("RGlnaXRlIG8gbm9tZS4uLg=="),
    Callback = function(value)
        Llloo1io1lLI0L = value
    end
})

I1001oOo0OoLlo = lLIiiLOOI0l1Io:AddDropdown({
    Name = _n85(";ep)bF!+CiCj'6."),
    Options = Llo110OIO0Iio0(),
    Callback = function(option)
        oi10II00Lo1OLO = option
    end
})




lLIiiLOOI0l1Io:AddDropdown({
    Name = _n85("<,$;i+Co%+6Z7!aD]gH,CM@Z/9jqpJB4Z*4"),
    Description = _n85(";e9cV@qfk!AKYn6@rHC,D]iLtF(HJ5@<,d!@psCuAS5Fl+CQC6CM@Y"),
    Options = {_n64("Q29ycG8gTm9ybWFs"), _n64("Q29ycG8gTm9ybWFsIEVzdGljYWRv"), _n85("6Z7!aD]h>^FDi9kBl7h")},
    Default = _n64("Q29ycG8gTm9ybWFs"),
    Flag = _n85("@W,e&?Z^R4ARAtgDfB6*GA^c/D#"),
    Callback = function(Value)
        _G.SelectedBodyTypeSkinManager = Value
        print(_n85(";ep)b+AH9^@:s.l+@C'fE,Qk.@<6!&@;L$sEa`Ks+E1b0@6,M") .. Value)
    end
})










lLIiiLOOI0l1Io:AddButton({
    Name = _n64("U2FsdmFyIFNraW4gZG8gUGxheWVyIFNlbGVjaW9uYWRv"),
    Callback = function()
        if not lOoIlIIii00Lll then
            OiOloLLO0iIO1I(_n64("QXZpc28="), _n85(":1\\<VF_r7?CghU#EZfF7Ch7*jDf/uoD_;"), (2463 - 2459))
            return
        end

        local Oool0iO0iIo11i = OoLloI0LI1OOlO:FindFirstChild(lOoIlIIii00Lll)
        if not Oool0iO0iIo11i then
            OiOloLLO0iIO1I(_n64("RXJybw=="), _n64("UGxheWVyIG7Do28gZW5jb250cmFkby4="), (5115 - 5111))
            return
        end

        local lLLLLioI0I1Oii = LO1OlLOO1LLIO1(Oool0iO0iIo11i)
        if not lLLLLioI0I1Oii then
            OiOloLLO0iIO1I(_n64("RXJybw=="), _n64("RXJybyBhbyBleHRyYWlyIHNraW4u"), (8526 - 8522))
            return
        end

        local llL1l0i1ILioi0 = tostring(Llloo1io1lLI0L):gsub(_n85("?6sYB-n[)#-$(O]"), _n64("JTE="))
        if llL1l0i1ILioi0 == _n85("") then
            llL1l0i1ILioi0 = lOoIlIIii00Lll
        end

        oOlILooii0oLiO[llL1l0i1ILioi0] = lLLLLioI0I1Oii
        ILolLIIOilloLl()
        Ii1oIOlOL0LIIo()
        OiOloLLO0iIO1I(_n85(";fuS]F)u7"), _n85(";ep)b+ELt-G$uM'Df'DR+9") .. llL1l0i1ILioi0, (1298 - 1294))
    end
})


lLIiiLOOI0l1Io:AddButton({
    Name = _n64("U2FsdmFyIFNraW4="),
    Callback = function()
        local llL1l0i1ILioi0 = tostring(Llloo1io1lLI0L):gsub(_n85("?6sYB-n[)#-$(O]"), _n85(",r#"))
        if llL1l0i1ILioi0 == _n64("") then
            OiOloLLO0iIO1I(_n85("6$?s`DZ"), _n85("6tp:JFCcS;D'3_7D.Oi-@3AN\\G]Z8jGV/"), (921 - 917))
            return
        end

        local iLiIILOLIl01I0 = LiIlI0ioi10LOo()
        if not iLiIILOLIl01I0 then return end

        oOlILooii0oLiO[llL1l0i1ILioi0] = iLiIILOLIl01I0
        ILolLIIOilloLl()
        Ii1oIOlOL0LIIo()
        OiOloLLO0iIO1I(_n64("U3VjZXNzbw=="), _n85(";ep)b+ELt-G%!ES") .. llL1l0i1ILioi0, (9092 - 9088))
    end
})


lLIiiLOOI0l1Io:AddButton({
    Name = _n85("6Xb\"UAS5Fl+B*&iDBMkhCh7*jDf/uo@/"),
    Callback = function()
        if oi10II00Lo1OLO and oOlILooii0oLiO[oi10II00Lo1OLO] then
            LoIL1Lol0IL00o(oOlILooii0oLiO[oi10II00Lo1OLO])
        else
            OiOloLLO0iIO1I(_n64("QXZpc28="), _n85(";e9cV@qfk!AKZ,4@3BW,Bl5&2@3BB#F*(hC"), (7942 - 7938))
        end
    end
})


lLIiiLOOI0l1Io:AddButton({
    Name = _n64("U2FsdmFyIFNraW4gQXR1YWwgbmEgT3DDp8OjbyBTZWxlY2lvbmFkYQ=="),
    Callback = function()
        if not oi10II00Lo1OLO then
            OiOloLLO0iIO1I(_n64("QXZpc28="), _n85(";e9cV@qfk!AKZ,4@3BW,Bl5&2@3@sYDfB6*GA\\OBEbTB%Bl\\,8"), (1818 - 1814))
            return
        end

        local iLiIILOLIl01I0 = LiIlI0ioi10LOo()
        if not iLiIILOLIl01I0 then return end

        oOlILooii0oLiO[oi10II00Lo1OLO] = iLiIILOLIl01I0
        ILolLIIOilloLl()
        OiOloLLO0iIO1I(_n85(";fuS]F)u7"), _n85(";ep)b+9") .. oi10II00Lo1OLO .. _n85("+@1*l@;KY(@:Wdi"), (5678 - 5674))
    end
})


lLIiiLOOI0l1Io:AddButton({
    Name = _n85("6tL1GFCB24;ep)b+B)ifARfFmDII'a"),
    Callback = function()
        if oi10II00Lo1OLO and oOlILooii0oLiO[oi10II00Lo1OLO] then
            oOlILooii0oLiO[oi10II00Lo1OLO] = nil
            ILolLIIOilloLl()
            oi10II00Lo1OLO = nil
            Ii1oIOlOL0LIIo()
            OiOloLLO0iIO1I(_n85(";fuS]F)u7"), _n85(";ep)b+Co&\"ATV?k@4h"), (6664 - 6660))
        else
            OiOloLLO0iIO1I(_n85("6$?s`DZ"), _n85(";e9cV@qfk!AKZ,4@3BW,Bl5&4@<,d!A7]RgFCB2B"), (935 - 931))
        end
    end
})


lLIiiLOOI0l1Io:AddButton({
    Name = _n85("7qH^LEZd`e￬￙	D]iS!+B*&iDBMkhCh7*jDf/uo@/"),
    Description = _n64("R2VyZSBvIEPDs2RpZ28gUGFyYSBvIENhcnJlZ2FtZW50byBJbnN0YW50w6JuZW8="),
    Callback = function()
        if not oi10II00Lo1OLO or not oOlILooii0oLiO[oi10II00Lo1OLO] then
            OiOloLLO0iIO1I(_n64("QXZpc28="), _n85(";e9cV@qfk!AKZ,4@3BW,Bl5&2@3B*$DfB6*GA\\O6AKZ&0Bl7u8"), (4314 - 4310))
            return
        end

        local lli0llO1i11I0O = oi10II00Lo1OLO
        local LlO10I11LlOl1I = oOlILooii0oLiO[lli0llO1i11I0O]

        OiOloLLO0iIO1I(_n64("UHJvY2Vzc2FuZG8="), _n64("QXBsaWNhbmRvIHNraW4gJw==") .. lli0llO1i11I0O .. _n64("JyBwYXJhIGdlcmFyIG8gY8OzZGlnby4uLg=="), (8520 - 8515))

        
        LoIL1Lol0IL00o(LlO10I11LlOl1I)

        
        local IllIlIi1Oo1IoO, llL1OII1o0OoOl, IOloO0oIlIO0io = pcall(function()
            return il1LL0O0l0I1Lo.AvatarEditorOutfitCodes:InvokeServer(_n64("RXhwb3J0"))
        end)

        local LOoo1L0i10loI1 = nil
        if IllIlIi1Oo1IoO then
            if tostring(llL1OII1o0OoOl):find(_n64("QkglLUFF")) then
                LOoo1L0i10loI1 = llL1OII1o0OoOl
            elseif tostring(IOloO0oIlIO0io):find(_n64("QkglLUFF")) then
                LOoo1L0i10loI1 = IOloO0oIlIO0io
            end
        end

        if LOoo1L0i10loI1 then
            llo0Li10lOlLiI[lli0llO1i11I0O] = {
                Code = LOoo1L0i10loI1,
                CreatedAt = os.time()
            }
            L1I1LIiOLLIOOI()
            oiIoOo1lIoloo0()
            OiOloLLO0iIO1I(_n64("U3VjZXNzbw=="), _n64("Q8OzZGlnbyBnZXJhZG8gcGFyYSA=") .. lli0llO1i11I0O, (3721 - 3717))
        else
            OiOloLLO0iIO1I(_n64("RXJybw=="), _n64("RXJybyBhbyBnZXJhciBjw7NkaWdvIGRvIHNlcnZpZG9yLg=="), (3499 - 3495))
        end
    end
})

lLIiiLOOI0l1Io:AddSection({ _n64("Q2FycmVnYSBTa2lucyBTYWx2YXMgSW5zdGFudGFuZWFtZW50ZQ==") })

l0i0LO1IlIiLoo = lLIiiLOOI0l1Io:AddDropdown({
    Name = _n85("6Z6LLB5_i6A7Zl^CM@[-"),
    Options = iIIOLLII0oI0Ol(),
    Callback = function(option)
        if option then
            local oO0iOIo1loOI01 = option:match(_n64("XiguLSklcyolKA=="))
            if oO0iOIo1loOI01 then
                l0LiI1ii001O10 = oO0iOIo1loOI01:gsub(_n64("JXMrJA=="), _n85(""))
            else
                l0LiI1ii001O10 = option
            end
        end
    end
})


lLIiiLOOI0l1Io:AddButton({
    Name = _n64("Q2FycmVnYXIgU2tpbiBTZWxlY2lvbmFkbw=="),
    Callback = function()
        if not l0LiI1ii001O10 or not llo0Li10lOlLiI[l0LiI1ii001O10] then
            OiOloLLO0iIO1I(_n85("6$?s`DZ"), _n64("U2VsZWNpb25lIFVtYSBTa2luICBuYSBEcm9wZG93biBQcmltZWlybyE="), (2636 - 2632))
            return
        end
        
        local lLLO0ILIolLO0I = llo0Li10lOlLiI[l0LiI1ii001O10]
        task.spawn(function()
            pcall(function()
                il1LL0O0l0I1Lo.AvatarEditorOutfitCodes:InvokeServer(_n85("9Q+?M"), lLLO0ILIolLO0I.Code)
            end)
        end)
        OiOloLLO0iIO1I(_n64("U3VjZXNzbw=="), _n85(";ep)b+@BRXEb/llA76TJDf$UqF^o!(F)N3"), (2788 - 2784))
    end
})


lLIiiLOOI0l1Io:AddButton({
    Name = _n85("7<i<YF_Pk=;ep)b+B)ifARfFmDII'a"),
    Callback = function()
        if not l0LiI1ii001O10 or not llo0Li10lOlLiI[l0LiI1ii001O10] then
            OiOloLLO0iIO1I(_n64("QXZpc28="), _n85(";e9cV@qfk!AKZ,4+Ci<qA8,[p+E1b0@3B-+@r-:%EZk"), (1515 - 1511))
            return
        end
        
        llo0Li10lOlLiI[l0LiI1ii001O10] = nil
        L1I1LIiOLLIOOI()
        oiIoOo1lIoloo0()
        OiOloLLO0iIO1I(_n64("U3VjZXNzbw=="), _n64("Q8OzZGlnbyBkZSBTa2luIEV4Y2x1w61kbyBDb20gU3VjZXNzbyE="), (6592 - 6588))
    end
})

lLIiiLOOI0l1Io:AddSection({ _n64("IEFuaW1hw6fDtWVzIFNlY3JldGFz") })

lLIiiLOOI0l1Io:AddButton({
    Name = _n85("9l_j/<,ZJeATT%dA8Gg\""),
    Description = _n64(""),
    Callback = function()
        
        local O1LLo0ilIIiI0o = (4418333488 - 6941)
        
        
        pcall(function()
            local LIL1IL00i11OoL = game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U=")):FindFirstChild(_n64("UmVtb3Rlcw=="))
            if LIL1IL00i11OoL and LIL1IL00i11OoL:FindFirstChild(_n64("V2Vhcg==")) then 
                LIL1IL00i11OoL.Wear:InvokeServer(tonumber(O1LLo0ilIIiI0o)) 
                print(_n85("6#LCR@:N_a+D#G6BjkO\\+Cf>,+EM[8ATMp2+Ws?E3W"), O1LLo0ilIIiI0o)
            else
                warn(_n64("UmVtb3RlcyBkZSBjdXN0b21pemFjYW8gbmFvIGVuY29udHJhZG9zIG5vIGpvZ28u"))
            end
        end)
    end
})

lLIiiLOOI0l1Io:AddButton({
    Name = _n85("9l_j/<,ZJeATT%mF`&<"),
    Description = _n64(""),
    Callback = function()
        
        local O1LLo0ilIIiI0o = (4418328921 - 4698)
        
        
        pcall(function()
            local LIL1IL00i11OoL = game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")):FindFirstChild(_n64("UmVtb3Rlcw=="))
            if LIL1IL00i11OoL and LIL1IL00i11OoL:FindFirstChild(_n85("=(Pf\\")) then 
                LIL1IL00i11OoL.Wear:InvokeServer(tonumber(O1LLo0ilIIiI0o)) 
                print(_n64("QW5pbWFjYW8gZW52aWFkYSBjb20gc3VjZXNzbyEgSUQ6"), O1LLo0ilIIiI0o)
            else
                warn(_n64("UmVtb3RlcyBkZSBjdXN0b21pemFjYW8gbmFvIGVuY29udHJhZG9zIG5vIGpvZ28u"))
            end
        end)
    end
})

lLIiiLOOI0l1Io:AddButton({
    Name = _n85("6>pm_@r!3$A8Gg\""),
    Description = _n64(""),
    Callback = function()
        
        local O1LLo0ilIIiI0o = (3710011866 - 4158)
        
        
        pcall(function()
            local LIL1IL00i11OoL = game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")):FindFirstChild(_n64("UmVtb3Rlcw=="))
            if LIL1IL00i11OoL and LIL1IL00i11OoL:FindFirstChild(_n64("V2Vhcg==")) then 
                LIL1IL00i11OoL.Wear:InvokeServer(tonumber(O1LLo0ilIIiI0o)) 
                print(_n64("QW5pbWFjYW8gZW52aWFkYSBjb20gc3VjZXNzbyEgSUQ6"), O1LLo0ilIIiI0o)
            else
                warn(_n85(";Is]`FCfM9A7ZlnF`VYCD/\"<)@ps9uDIIH+ASu!rDKKo-A8cN3DJpY4DeEu@"))
            end
        end)
    end
})

lLIiiLOOI0l1Io:AddButton({
    Name = _n85(";DC$OBk2$k+9"),
    Description = _n85(""),
    Callback = function()
        
        local O1LLo0ilIIiI0o = (4211412377 - 3350)
        
        
        pcall(function()
            local LIL1IL00i11OoL = game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U=")):FindFirstChild(_n85(";Is]`FCfL"))
            if LIL1IL00i11OoL and LIL1IL00i11OoL:FindFirstChild(_n64("V2Vhcg==")) then 
                LIL1IL00i11OoL.Wear:InvokeServer(tonumber(O1LLo0ilIIiI0o)) 
                print(_n64("QW5pbWFjYW8gZW52aWFkYSBjb20gc3VjZXNzbyEgSUQ6"), O1LLo0ilIIiI0o)
            else
                warn(_n64("UmVtb3RlcyBkZSBjdXN0b21pemFjYW8gbmFvIGVuY29udHJhZG9zIG5vIGpvZ28u"))
            end
        end)
    end
})

lLIiiLOOI0l1Io:AddButton({
    Name = _n85("<FdJ'@;I'#A8Gg\""),
    Description = _n85(""),
    Callback = function()
        
        local O1LLo0ilIIiI0o = (3307614298 - 8473)
        
        
        pcall(function()
            local LIL1IL00i11OoL = game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")):FindFirstChild(_n64("UmVtb3Rlcw=="))
            if LIL1IL00i11OoL and LIL1IL00i11OoL:FindFirstChild(_n64("V2Vhcg==")) then 
                LIL1IL00i11OoL.Wear:InvokeServer(tonumber(O1LLo0ilIIiI0o)) 
                print(_n85("6#LCR@:N_a+D#G6BjkO\\+Cf>,+EM[8ATMp2+Ws?E3W"), O1LLo0ilIIiI0o)
            else
                warn(_n85(";Is]`FCfM9A7ZlnF`VYCD/\"<)@ps9uDIIH+ASu!rDKKo-A8cN3DJpY4DeEu@"))
            end
        end)
    end
})

do
    
    
    
    local O1iLO00o1Oollo = olliLOIiIoIi0l:MakeTab({ Title = _n64("UkJH"), Icon = _n64("cmJ4YXNzZXRpZDovLzEwNzM0OTEwMTg3") })

    
    
    
    local OoLloI0LI1OOlO = game:GetService(_n64("UGxheWVycw=="))
    local I0OOl00LLiO1lL = game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH"))
    local OOllIliO1LO0LI = OoLloI0LI1OOlO.LocalPlayer

    
    local iOiOl1O1II0o0o = {
        [_n85("<b6;gASc$u")] = Color3.fromRGB((5358 - 5103), 0, 0),
        [_n85("<b6;^AH")]    = Color3.fromRGB(0, (1666 - 1411), 0),
        [_n64("QXp1bA==")]     = Color3.fromRGB(0, 0, (3117 - 2862)),
        [_n64("QW1hcmVsbw==")]  = Color3.fromRGB((2821 - 2566), (2857 - 2602), 0),
        [_n85(";K$eu")]     = Color3.fromRGB((7709 - 7581), 0, (1282 - 1154)),
        [_n85("6YTtHDZ")]    = Color3.fromRGB(0, (4068 - 3813), (9159 - 8904)),
        [_n85("9OVsMDJES")]  = Color3.fromRGB((1668 - 1413), (4473 - 4308), 0),
        [_n85(";K$Vb")]     = Color3.fromRGB((8634 - 8379), (3427 - 3235), (7762 - 7559)),
        [_n85("6?6LP@rD")]   = Color3.fromRGB((5046 - 4791), (4846 - 4591), (947 - 692))
    }

    local iOlLLIli0lOLIl = {_n85(";Fa%"), _n85("<b6;gASc$u"), _n85("<b6;^AH"), _n64("QXp1bA=="), _n64("QW1hcmVsbw=="), _n85(";K$eu"), _n64("Q2lhbm8="), _n85("9OVsMDJES"), _n85(";K$Vb"), _n85("6?6LP@rD")}

    local iOLIi0olIO0lOi = {
        _n85(":gnEeAS`JuEc6/>"), _n85(":gnEeAS`K7ASc1$G5"), _n85(":gnEeAS`JuCis:"), _n85(":gnEeAS`K%Eb/g\""), _n85(":gnEeAS`K.Bl7\\"),
        _n85(";Is9QCj@.DARk"), _n85("6?6dQBQPA8Ea`iuAH"), _n85("6?6dQBQPA+Cis:"), _n64("QnJpZ2h0IHZpb2xldA=="), _n85("6?6dQBQPA0Eb/g\""),
        _n85("6?6dQBQPABASc1$G5"), _n85("=(l;iAH"), _n85("6>U(?CB"), _n64("RGFyayBzdG9uZSBncmV5"), _n85("9k@jLF_r7BFDl&.+D5_+Gl"),
        _n64("TGlnaHQgc3RvbmUgZ3JleQ=="), _n85("6?6dQBQPA;ARk"), _n64("QnJpZ2h0IHllbGxvd2lzaCBncmVlbg=="), _n64("QnJpZ2h0IGJsdWlzaCBncmVlbg=="),
        _n85("6?6dQBQPA9F`MG;AH"), _n64("QnJpZ2h0IHBpbms="), _n64("UmVkZGlzaCBicm93bg=="), _n85("7:C4YBHUr.AS#`"), _n85(";djQS+ED%("),
        _n64("U2FuZCBibHVl"), _n64("U2FuZCBncmVlbg=="), _n64("RGFyayBncmVlbg=="), _n85(":18<k+C]/0AH"), _n85("<,Z\\sBQ.C$FCb"), _n85("6[<*X"),
        _n64("SG90IHBpbms="), _n85("6ZQmXF)Pp"), _n64("Um95YWwgcHVycGxl"), _n64("TmVvbiBvcmFuZ2U="), _n64("TmVvbiBncmVlbg=="), _n64("TmVvbiBwaW5r"),
        _n64("TmVvbiBibHVl"), _n64("R29sZA=="), _n85("6?6dQBQPA0Derq"), _n85(":1\\Vl=_2DcAT@"), _n85("6t(+O+E):/DJ*M"), _n85("6tKqK+C]/0AH"),
        _n64("TWFyb29u"), _n85("6?6dQBQPA6@<-:)D?")
    }

    
    local o1iLII0O10O0lO = require(I0OOl00LLiO1lL.Modules.Client.AvatarEditor.WearingController)
    local il1LL0O0l0I1Lo = I0OOl00LLiO1lL:WaitForChild(_n64("UmVtb3Rlcw=="), (2828 - 2823))
    local Il0iO0iOIO0Ioi = il1LL0O0l0I1Lo and il1LL0O0l0I1Lo:WaitForChild(_n64("Q2hhbmdlQm9keUNvbG9y"), (2919 - 2914))

    
    local Ii0iL0l1ILOoOI = (6039 - 6034)
    local Lo110lOILioOOo = _n64("UkdC")
    local i0L1OOio00OloL = _n85(":2au\\+CuZ^Bl<")
    local iIlooLOooIILiI = false

    local IiIi00iol01LII = (8005 - 8000)
    local OoilOiLo11loI0 = _n64("UkdC")

    
    local o0LIIool1LlI0i = false
    local OLOo0lLoiOoIol = false
    local LLoLOOoOoOii0l = false
    local O1I0i0o1iOOOo1 = false
    local lOlI1O0oi1O0LO = false
    local OL1OLOILL1loOl = false
    local olliOolOoo0IOO = false
    local L0O0lLo01Il011 = false

    
    
    
    local function OOiIILIIiOlILo(LLOLLloOI1LOoL, i111Looo1oIliO)
        local iLIL10LLi111o0 = I0OOl00LLiO1lL:FindFirstChild(_n85(";FL")) and I0OOl00LLiO1lL.RE:FindFirstChild(LLOLLloOI1LOoL)
        if iLIL10LLi111o0 then
            pcall(function()
                iLIL10LLi111o0:FireServer(unpack(i111Looo1oIliO))
            end)
        end
    end

    local function llLiLIi1iOOOii(IliL0ilOi1oooI)
        if i0L1OOio00OloL == _n85(":2au\\") or i0L1OOio00OloL == _n64("Tm9tZSBlIEJpbw==") then
            OOiIILIIiOlILo(_n64("MVJQTmFtMWVDb2xvMXI="), { _n85(":haETBl7Q]:ekG9AOCBPDfP"), IliL0ilOi1oooI })
        end
        if i0L1OOio00OloL == _n64("Qmlv") or i0L1OOio00OloL == _n85(":2au\\+CuZ^Bl<") then
            OOiIILIIiOlILo(_n85("0iChC@;R`16Z6dZ0ld"), { _n64("UGlja2luZ1JQQmlvQ29sb3I="), IliL0ilOi1oooI })
        end
    end

    local function iiIiO11loIOLI1(LL0L0llOliOLIL)
        local O0o11l01oOoi1I = (6956.25 - 6956) + (math.sin(LL0L0llOliOLIL) + (8185 - 8184)) * (807.375 - 807)

        if OoilOiLo11loI0 == _n64("UkdC") then
            local oolL0ioILoILl1 = (LL0L0llOliOLIL * (5805.1 - 5805)) % (3453 - 3452)
            return Color3.fromHSV(oolL0ioILoILl1, (6073 - 6072), O0o11l01oOoi1I)
        else
            local OoO01Oll0o10Oo = iOiOl1O1II0o0o[OoilOiLo11loI0] or Color3.fromRGB((6865 - 6610), (7995 - 7740), (664 - 409))
            local OiOi01oli0L0oO, o010OlioOOiI0l, llLlo1lI11L0Oi = OoO01Oll0o10Oo:ToHSV()
            return Color3.fromHSV(OiOi01oli0L0oO, o010OlioOOiI0l, O0o11l01oOoi1I)
        end
    end

    local function llOlL00Oo0i110()
        local LLlooiOl1o1Il0 = OOllIliO1LO0LI:FindFirstChild(_n64("UGxheWVyR3Vp"))
        if not LLlooiOl1o1Il0 then return nil end

        local oll01OOli1OlIo = LLlooiOl1o1Il0:FindFirstChild(_n64("TWFpbkdVSUhhbmRsZXI="))
        if not oll01OOli1OlIo then return nil end

        local Ol0O1OlIOoL1L0 = oll01OOli1OlIo:FindFirstChild(_n64("VmVoaWNsZUNvbnRyb2w="))
        if not Ol0O1OlIOoL1L0 then return nil end

        local lII1o0IlllO01o = Ol0O1OlIOoL1L0:FindFirstChild(_n85("<CoPrCi=>jBk(piEW"))
        if not lII1o0IlllO01o then return nil end

        return lII1o0IlllO01o:FindFirstChild(_n85(";e:&<Des?4"))
    end

    local function OIlLLIIiI101l0(lO0oil0L1lOoLl)
        local o0iIIlioLLlIIL = OOllIliO1LO0LI.Character
        if not o0iIIlioLLlIIL then return end

        for llLlo1lI11L0Oi, ii1olOl0O101li in ipairs(o0iIIlioLLlIIL:GetChildren()) do
            if ii1olOl0O101li:IsA(_n64("QWNjZXNzb3J5")) and ii1olOl0O101li.AccessoryType == Enum.AccessoryType.Hair then
                local liI01iOl0I1OLi = ii1olOl0O101li:GetAttribute(_n64("QXNzZXRJZA==")) or ii1olOl0O101li:GetAttribute(_n85("6\"=JIF)Q)E8Rq"))
                if liI01iOl0I1OLi then
                    pcall(function()
                        o1iLII0O10O0lO.SetAccessoryColor(liI01iOl0I1OLi, lO0oil0L1lOoLl)
                    end)
                end
            end
        end
    end

    local function iO0ii1o10iL0Il(lO0oil0L1lOoLl)
        local o0iIIlioLLlIIL = OOllIliO1LO0LI.Character
        if not o0iIIlioLLlIIL then return end

        for llLlo1lI11L0Oi, ii1olOl0O101li in ipairs(o0iIIlioLLlIIL:GetChildren()) do
            if ii1olOl0O101li:IsA(_n85("6\"=D9F)u8?Gl")) then
                local liI01iOl0I1OLi = ii1olOl0O101li:GetAttribute(_n64("QXNzZXRJZA==")) or ii1olOl0O101li:GetAttribute(_n64("QWNlc3NvcnlJZA=="))
                if liI01iOl0I1OLi then
                    pcall(function()
                        o1iLII0O10O0lO.SetAccessoryColor(liI01iOl0I1OLi, lO0oil0L1lOoLl)
                    end)
                end
            end
        end
    end

    local function IIIl010IILIooi()
        local O00O10oL01O0O0 = OOllIliO1LO0LI:FindFirstChild(_n85(":i'QcATC:`B`")) and OOllIliO1LO0LI.PlayerGui:FindFirstChild(_n85("<,Z\\k7s/M"))
        if not O00O10oL01O0O0 then return nil end

        local O1oliLoloi0LI0 = O00O10oL01O0O0:FindFirstChild(_n85("<,Z\\k;e:&mBl7R)"))
        if not O1oliLoloi0LI0 then return nil end

        local LLIi11oLLO11IL = O1oliLoloi0LI0:FindFirstChild(_n85(";e:&mBl7R)"))
        if not LLIi11oLLO11IL then return nil end

        local I11IOiII10Ii0l = LLIi11oLLO11IL:FindFirstChild(_n64("UHJvcHNDb2xvcg=="))
        if not I11IOiII10Ii0l then return nil end

        return I11IOiII10Ii0l:FindFirstChild(_n64("U2V0Q29sb3I="))
    end

    local function iiI1IiII10lo0l(IoiIiOOLiO1LLo)
        pcall(function()
            local LOoiLOLiLi0LiI = OOllIliO1LO0LI:FindFirstChild(_n85(":i'QcATC:`B`"))
            if LOoiLOLiLi0LiI then
                local iiO1liLl1I0lII = LOoiLOLiLi0LiI:FindFirstChild(_n85(":i'QcATBb$@;]UlAT@")) and LOoiLOLiLi0LiI.Player8Handler:FindFirstChild(_n85("7q$7G3)aC1FD5W*Er"))
                if iiO1liLl1I0lII then
                    local l11LoIoO1iOi1L = require(iiO1liLl1I0lII)
                    local O0OLol1OIIiiLl = l11LoIoO1iOi1L.PickingHouseColor
                    local oLOioO11I0o0lI = l11LoIoO1iOi1L.PlayersHouse
                    if oLOioO11I0o0lI and O0OLol1OIIiiLl then
                        oLOioO11I0o0lI:FireServer(O0OLol1OIIiiLl, IoiIiOOLiO1LLo)
                    end
                end
            end
            
            local lOLiLiLii10o0L, OoI0oOiooiloiO = pcall(function() 
                return require(I0OOl00LLiO1lL.Packages.Remotes) 
            end)
            if lOLiLiLii10o0L and OoI0oOiooiloiO and OoI0oOiooiloiO.fireServer then
                OoI0oOiooiloiO.fireServer(_n64("UHJvcGVydHk6U2V0Q29sb3I="), IoiIiOOLiO1LLo)
            end
        end)
    end

    local function I1ii1L1l0i1Ii1(LLOLLloOI1LOoL, i111Looo1oIliO)
        local iLIL10LLi111o0 = I0OOl00LLiO1lL:FindFirstChild(_n85(";FL"))
        if iLIL10LLi111o0 and iLIL10LLi111o0:FindFirstChild(LLOLLloOI1LOoL) then
            pcall(function()
                iLIL10LLi111o0[LLOLLloOI1LOoL]:FireServer(unpack(i111Looo1oIliO))
            end)
        end
    end

    
    
    
    O1iLO00o1Oollo:AddSlider({
        Name = _n64("VmVsb2NpZGFkZQ=="),
        Min = (4862 - 4857),
        Max = (8873 - 8843),
        Increase = (5273 - 5272),
        Default = (3829 - 3824),
        Callback = function(value)
            Ii0iL0l1ILOoOI = value
        end
    })

    O1iLO00o1Oollo:AddDropdown({
        Name = _n64("Q29y"),
        Options = iOlLLIli0lOLIl,
        Default = _n64("UkdC"),
        Callback = function(option)
            Lo110lOILioOOo = option
        end
    })

    O1iLO00o1Oollo:AddDropdown({
        Name = _n85("9Q+ELC]"),
        Options = {_n64("Tm9tZQ=="), _n85("6>:?"), _n64("Tm9tZSBlIEJpbw==")},
        Default = _n85(":2au\\+CuZ^Bl<"),
        Callback = function(option)
            i0L1OOio00OloL = option
        end
    })

    O1iLO00o1Oollo:AddToggle({
        Name = _n64("Tm9tZS9CaW8gUkdC"),
        Description = _n64(""),
        Default = false,
        Callback = function(lOIiOiL0I0Li1O)
            iIlooLOooIILiI = lOIiOiL0I0Li1O
            if lOIiOiL0I0Li1O then
                task.spawn(function()
                    local IlLi000O0IlLoI = 0
                    local OoLlIoOLlol0ll = true

                    while iIlooLOooIILiI and OOllIliO1LO0LI.Character do
                        local liiOILoIo0LiIl = math.clamp((3618.25 - 3618) - (Ii0iL0l1ILOoOI * (8414.02 - 8414)), (7716.03 - 7716), (1351.25 - 1351))
                        local OILIli1lOOlliO = (6342.02 - 6342) * (Ii0iL0l1ILOoOI / (7155 - 7153))

                        if Lo110lOILioOOo == _n85(";Fa%") then
                            local oolL0ioILoILl1 = (IlLi000O0IlLoI % (3647 - 3646))
                            local O0o11l01oOoi1I = OoLlIoOLlol0ll and ((3842 - 3841) - (IlLi000O0IlLoI % (2920 - 2919))) or (IlLi000O0IlLoI % (7766 - 7765))
                            O0o11l01oOoi1I = math.clamp(O0o11l01oOoi1I, (6168.1 - 6168), (3798 - 3797))

                            llLiLIi1iOOOii(Color3.fromHSV(oolL0ioILoILl1, (4240 - 4239), O0o11l01oOoi1I))
                            IlLi000O0IlLoI = IlLi000O0IlLoI + OILIli1lOOlliO

                            if IlLi000O0IlLoI >= (5579 - 5578) then
                                IlLi000O0IlLoI = 0
                                OoLlIoOLlol0ll = not OoLlIoOLlol0ll
                            end
                        else
                            local OoO01Oll0o10Oo = iOiOl1O1II0o0o[Lo110lOILioOOo] or Color3.fromRGB((5697 - 5442), (3296 - 3041), (1535 - 1280))
                            local OiOi01oli0L0oO, o010OlioOOiI0l, llLlo1lI11L0Oi = OoO01Oll0o10Oo:ToHSV()

                            local O0o11l01oOoi1I = OoLlIoOLlol0ll and ((5300 - 5299) - (IlLi000O0IlLoI % (642 - 641))) or (IlLi000O0IlLoI % (7483 - 7482))
                            O0o11l01oOoi1I = math.clamp(O0o11l01oOoi1I, (2598.15 - 2598), (5354 - 5353))

                            llLiLIi1iOOOii(Color3.fromHSV(OiOi01oli0L0oO, o010OlioOOiI0l, O0o11l01oOoi1I))
                            IlLi000O0IlLoI = IlLi000O0IlLoI + OILIli1lOOlliO

                            if IlLi000O0IlLoI >= (5941 - 5940) then
                                IlLi000O0IlLoI = 0
                                OoLlIoOLlol0ll = not OoLlIoOLlol0ll
                            end
                        end

                        task.wait(liiOILoIo0LiIl)
                    end
                end)
            end
        end
    })

    
    
    
    O1iLO00o1Oollo:AddSection({_n85(":K:@l:K%")})

    O1iLO00o1Oollo:AddSlider({
        Name = _n64("VmVsb2NpZGFkZQ=="),
        Min = (9058 - 9053),
        Max = (1961 - 1931),
        Increase = (2661 - 2660),
        Default = (4017 - 4012),
        Callback = function(val)
            IiIi00iol01LII = val
        end
    })

    O1iLO00o1Oollo:AddDropdown({
        Name = _n85("6Z6u"),
        Options = iOlLLIli0lOLIl,
        Default = _n64("UkdC"),
        Callback = function(choice)
            OoilOiLo11loI0 = choice
        end
    })

    
    
    
    O1iLO00o1Oollo:AddSection({_n64("UkdCIEVtIFRvb2xz")})

    O1iLO00o1Oollo:AddToggle({
        Name = _n64("VG9vbHMgUkdC"),
        Description = _n85("6#^XS@psC#;Fa%r7;X/HDe*d-+E)<D<,Z\\kEr"),
        Default = false,
        Callback = function(enabled)
            o0LIIool1LlI0i = enabled
            if enabled then
                task.spawn(function()
                    local LL0L0llOliOLIL = 0
                    while o0LIIool1LlI0i do
                        local OIO0lIi0LOIOio = math.clamp((4589.12 - 4589) - (IiIi00iol01LII * (8162.003 - 8162)), (1233.015 - 1233), (7561.12 - 7561))
                        local OILIli1lOOlliO = (3785.04 - 3785) * (IiIi00iol01LII / (7819 - 7814))

                        LL0L0llOliOLIL = LL0L0llOliOLIL + OILIli1lOOlliO
                        local l1iILLlOLoI0li = iiIiO11loIOLI1(LL0L0llOliOLIL)
                        
                        local l0lLLOIO1o0iL0 = IIIl010IILIooi()
                        if l0lLLOIO1o0iL0 then
                            pcall(function()
                                l0lLLOIO1o0iL0:FireServer(l1iILLlOLoI0li)
                            end)
                        end

                        task.wait(OIO0lIi0LOIOio)
                    end
                end)
            end
        end
    })

    O1iLO00o1Oollo:AddSection({_n64("UkdCIEVtIENhc2Fz")})

    O1iLO00o1Oollo:AddToggle({
        Name = _n85("6Xb%E+At]r"),
        Description = _n85(""),
        Default = false,
        Callback = function(enabled)
            OLOo0lLoiOoIol = enabled
            if enabled then
                task.spawn(function()
                    local LL0L0llOliOLIL = 0
                    while OLOo0lLoiOoIol do
                        local OIO0lIi0LOIOio = math.clamp((4522.12 - 4522) - (IiIi00iol01LII * (7832.003 - 7832)), (2811.015 - 2811), (4677.12 - 4677))
                        local OILIli1lOOlliO = (4757.04 - 4757) * (IiIi00iol01LII / (7834 - 7829))
                        
                        LL0L0llOliOLIL = LL0L0llOliOLIL + OILIli1lOOlliO
                        iiI1IiII10lo0l(iiIiO11loIOLI1(LL0L0llOliOLIL))
                        
                        task.wait(OIO0lIi0LOIOio)
                    end
                end)
            end
        end
    })

    O1iLO00o1Oollo:AddToggle({
        Name = _n85("<+U;rD]hGV+@BRY@3AH<63"),
        Description = _n64(""),
        Default = false,
        Callback = function(enabled)
            LLoLOOoOoOii0l = enabled
            if enabled then
                task.spawn(function()
                    local LL0L0llOliOLIL = 0
                    while LLoLOOoOoOii0l do
                        local OIO0lIi0LOIOio = math.clamp((2565.12 - 2565) - (IiIi00iol01LII * (4527.003 - 4527)), (8564.015 - 8564), (1251.12 - 1251))
                        local OILIli1lOOlliO = (633.04 - 633) * (IiIi00iol01LII / (4935 - 4930))
                        
                        LL0L0llOliOLIL = LL0L0llOliOLIL + OILIli1lOOlliO
                        I1ii1L1l0i1Ii1(_n64("MVJQSG91czFlRXZlbjF0Q29sbzFy"), {
                            _n85(":haETBl7QMF`V87ATMof@;TRCDes?4"),
                            iiIiO11loIOLI1(LL0L0llOliOLIL)
                        })
                        
                        task.wait(OIO0lIi0LOIOio)
                    end
                end)
            end
        end
    })

    O1iLO00o1Oollo:AddSection({_n85(";Fa%r7;X/JA](W[F_ku;")})

    O1iLO00o1Oollo:AddToggle({
        Name = _n64("VmXDrWN1bG8gU2VtIE1vdG9yIFJHQg=="),
        Description = _n64(""),
        Default = false,
        Callback = function(enabled)
            O1I0i0o1iOOOo1 = enabled
            if enabled then
                task.spawn(function()
                    local LL0L0llOliOLIL = 0
                    while O1I0i0o1iOOOo1 do
                        local OIO0lIi0LOIOio = math.clamp((8622.12 - 8622) - (IiIi00iol01LII * (7251.003 - 7251)), (7855.015 - 7855), (8189.12 - 8189))
                        local OILIli1lOOlliO = (5250.04 - 5250) * (IiIi00iol01LII / (4805 - 4800))
                        
                        LL0L0llOliOLIL = LL0L0llOliOLIL + OILIli1lOOlliO
                        I1ii1L1l0i1Ii1(_n85("0i2[pH\"D\"NF$j@jEW"), {
                            _n85(":2`jFFDl1eDes?4"),
                            iiIiO11loIOLI1(LL0L0llOliOLIL)
                        })
                        
                        task.wait(OIO0lIi0LOIOio)
                    end
                end)
            end
        end
    })

    O1iLO00o1Oollo:AddToggle({
        Name = _n64("Q2Fycm8gUkdC"),
        Description = _n64("VGVtIFF1ZSBFc3RhciBTZW50YWRvIE5vIENhcnJv"),
        Default = false,
        Callback = function(enabled)
            lOlI1O0oi1O0LO = enabled
            if enabled then
                task.spawn(function()
                    local LL0L0llOliOLIL = 0
                    while lOlI1O0oi1O0LO do
                        local OIO0lIi0LOIOio = math.clamp((7703.12 - 7703) - (IiIi00iol01LII * (4702.003 - 4702)), (8928.015 - 8928), (1649.12 - 1649))
                        local OILIli1lOOlliO = (192.04 - 192) * (IiIi00iol01LII / (3145 - 3140))

                        LL0L0llOliOLIL = LL0L0llOliOLIL + OILIli1lOOlliO
                        local l1iILLlOLoI0li = iiIiO11loIOLI1(LL0L0llOliOLIL)
                        
                        local LOI0Io1oiIL1I0 = llOlL00Oo0i110()
                        if LOI0Io1oiIL1I0 then
                            pcall(function()
                                LOI0Io1oiIL1I0:FireServer(l1iILLlOLoI0li)
                            end)
                        end

                        task.wait(OIO0lIi0LOIOio)
                    end
                end)
            end
        end
    })

    O1iLO00o1Oollo:AddSection({_n64("UkdCIEVtIFZvY8Oq")})

    O1iLO00o1Oollo:AddToggle({
        Name = _n85("6Z7!aD]hqJ63"),
        Description = _n85(""),
        Default = false,
        Callback = function(enabled)
            OL1OLOILL1loOl = enabled
            if enabled and Il0iO0iOIO0Ioi then
                task.spawn(function()
                    while OL1OLOILL1loOl do
                        for llLlo1lI11L0Oi, illIo10IIlio0i in ipairs(iOLIi0olIO0lOi) do
                            if not OL1OLOILL1loOl then break end
                            pcall(function()
                                Il0iO0iOIO0Ioi:FireServer(illIo10IIlio0i)
                            end)
                            local iol0111LL11lOI = math.clamp((6708.3 - 6708) / (IiIi00iol01LII / (202 - 197)), (2585.05 - 2585), (8110.5 - 8110))
                            task.wait(iol0111LL11lOI)
                        end
                    end
                end)
            end
        end
    })

    O1iLO00o1Oollo:AddToggle({
        Name = _n64("Q2FiZWxvIFJHQg=="),
        Description = _n64(""),
        Default = false,
        Callback = function(enabled)
            olliOolOoo0IOO = enabled
            if enabled then
                task.spawn(function()
                    local LL0L0llOliOLIL = 0
                    while olliOolOoo0IOO do
                        local OIO0lIi0LOIOio = math.clamp((1883.12 - 1883) - (IiIi00iol01LII * (6288.003 - 6288)), (1108.015 - 1108), (3140.12 - 3140))
                        local OILIli1lOOlliO = (5104.04 - 5104) * (IiIi00iol01LII / (2647 - 2642))
                        
                        LL0L0llOliOLIL = LL0L0llOliOLIL + OILIli1lOOlliO
                        OIlLLIIiI101l0(iiIiO11loIOLI1(LL0L0llOliOLIL))
                        
                        task.wait(OIO0lIi0LOIOio)
                    end
                end)
            end
        end
    })

    O1iLO00o1Oollo:AddToggle({
        Name = _n64("QWNlc3PDs3Jpb3MgUkdC"),
        Description = _n64(""),
        Default = false,
        Callback = function(enabled)
            L0O0lLo01Il011 = enabled
            if enabled then
                task.spawn(function()
                    local LL0L0llOliOLIL = 0
                    while L0O0lLo01Il011 do
                        local OIO0lIi0LOIOio = math.clamp((2214.12 - 2214) - (IiIi00iol01LII * (5306.003 - 5306)), (7547.015 - 7547), (2784.12 - 2784))
                        local OILIli1lOOlliO = (2703.04 - 2703) * (IiIi00iol01LII / (2086 - 2081))
                        
                        LL0L0llOliOLIL = LL0L0llOliOLIL + OILIli1lOOlliO
                        iO0ii1o10iL0Il(iiIiO11loIOLI1(LL0L0llOliOLIL))
                        
                        task.wait(OIO0lIi0LOIOio)
                    end
                end)
            end
        end
    })
end




local L0LIL1ILOOoo1l= olliLOIiIoIi0l:MakeTab({ _n85("HltdbF('+"), _n64("aG9tZQ==") })

local OoLloI0LI1OOlO = game:GetService(_n85(":i'QcATDh"))
local I0OOl00LLiO1lL = game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U="))

local OOllIliO1LO0LI = OoLloI0LI1OOlO.LocalPlayer
local IIL1l1lLoI000I = I1IiOlIlIil1Oi:WaitForChild(_n85("0JG4g9Q,#o"))

local Li0Iio0llILOil = I0OOl00LLiO1lL:WaitForChild(_n64("UmVtb3Rlcw==")):WaitForChild(_n64("TG90OlJldm9rZUxhbmRtYXJr"))


local function OillOlIOoLI1lI()
    for llLlo1lI11L0Oi, olii00LO1Io0Lo in ipairs(IIL1l1lLoI000I:GetChildren()) do
        if olii00LO1Io0Lo:IsA(_n85("9lFQRC]")) then
            local OOl1I1LI0lO01l = olii00LO1Io0Lo:FindFirstChild(_n85(":Np\\fEW"))
            local o1I0OLL01OlOio = olii00LO1Io0Lo:FindFirstChild(_n85(":Np\\fE_g.Z"))

            if OOl1I1LI0lO01l and (OOl1I1LI0lO01l.Value == OOllIliO1LO0LI.Name or OOl1I1LI0lO01l.Value == OOllIliO1LO0LI.UserId) then
                return true
            end

            if o1I0OLL01OlOio and o1I0OLL01OlOio:IsA(_n85(":L\\'M@rta[Cis:")) and o1I0OLL01OlOio.Value == OOllIliO1LO0LI then
                return true
            end
        end
    end

    return false
end


local I1lOIiooOiiIIi = game:GetService(_n64("VHdlZW5TZXJ2aWNl"))

local function OiOloLLO0iIO1I(ioilii0L11L0oi, Lo0l1IiOIlL010, loLOoi0iiOL0LI)
    loLOoi0iiOL0LI = loLOoi0iiOL0LI or (695 - 691)

    local LLlooiOl1o1Il0 = OOllIliO1LO0LI:WaitForChild(_n64("UGxheWVyR3Vp"))

    if LLlooiOl1o1Il0:FindFirstChild(_n64("U2ltcGxlTm90aWZ5")) then
        LLlooiOl1o1Il0.SimpleNotify:Destroy()
    end

    local o1Ii001l0LOOo0 = Instance.new(_n85(";e'iZASt\"\\B`"))
    o1Ii001l0LOOo0.Name = _n64("U2ltcGxlTm90aWZ5")
    o1Ii001l0LOOo0.ResetOnSpawn = false
    o1Ii001l0LOOo0.Parent = LLlooiOl1o1Il0

    local LLlilLO0IIIIo0 = Instance.new(_n85("7WMpSAH"))
    LLlilLO0IIIIo0.Size = UDim2.new(0, (3446 - 3026), 0, (6191 - 6149))
    LLlilLO0IIIIo0.Position = UDim2.new((999.5 - 999), -(8982 - 8772), 0, -(1674 - 1624))
    LLlilLO0IIIIo0.BackgroundColor3 = Color3.fromRGB((1344 - 1317), (4915 - 4910), (7213 - 7188))
    LLlilLO0IIIIo0.BorderSizePixel = 0
    LLlilLO0IIIIo0.Parent = o1Ii001l0LOOo0

    Instance.new(_n64("VUlDb3JuZXI="), LLlilLO0IIIIo0).CornerRadius = UDim.new(0, (5664 - 5658))

    local IlO1OlL0ii0IOI = Instance.new(_n85("<+U;r9OVCAC]"))
    IlO1OlL0ii0IOI.Size = UDim2.new((5639 - 5638), -(4144 - 4099), (6411 - 6410), 0)
    IlO1OlL0ii0IOI.Position = UDim2.new(0, (2846 - 2836), 0, 0)
    IlO1OlL0ii0IOI.BackgroundTransparency = (2530 - 2529)
    IlO1OlL0ii0IOI.Text = string.upper(ioilii0L11L0oi).._n64("OiA=")..message
    IlO1OlL0ii0IOI.TextColor3 = Color3.fromRGB((5226 - 4971), (5857 - 5602), (2349 - 2094))
    IlO1OlL0ii0IOI.Font = Enum.Font.SourceSansSemibold
    IlO1OlL0ii0IOI.TextSize = (6820 - 6804)
    IlO1OlL0ii0IOI.TextXAlignment = Enum.TextXAlignment.Left
    IlO1OlL0ii0IOI.Parent = LLlilLO0IIIIo0

    local I1lI00010I0O11 = Instance.new(_n85("<+U;r6?RBlDf,"))
    I1lI00010I0O11.Size = UDim2.new(0, (6167 - 6137), (6630 - 6629), 0)
    I1lI00010I0O11.Position = UDim2.new((8111 - 8110), -(7406 - 7376), 0, 0)
    I1lI00010I0O11.BackgroundTransparency = (2683 - 2682)
    I1lI00010I0O11.Text = _n64("WA==")
    I1lI00010I0O11.TextColor3 = Color3.fromRGB((1196 - 941), (5676 - 5421), (700 - 445))
    I1lI00010I0O11.Font = Enum.Font.SourceSansBold
    I1lI00010I0O11.TextSize = (906 - 888)
    I1lI00010I0O11.Parent = LLlilLO0IIIIo0

    
    I1lOIiooOiiIIi:Create(
        LLlilLO0IIIIo0,
        TweenInfo.new((4168.35 - 4168), Enum.EasingStyle.Quint, Enum.EasingDirection.Out),
        {Position = UDim2.new((591.5 - 591), -(3724 - 3514), 0, (1927 - 1922))}
    ):Play()

    local LLLOolLOL1iioI = false
    local function l1loIlollILO01()
        if LLLOolLOL1iioI then return end
        LLLOolLOL1iioI = true

        I1lOIiooOiiIIi:Create(
            LLlilLO0IIIIo0,
            TweenInfo.new((8152.25 - 8152), Enum.EasingStyle.Quint, Enum.EasingDirection.In),
            {Position = UDim2.new((6325.5 - 6325), -(5775 - 5565), 0, -(316 - 266))}
        ):Play()

        task.delay((1063.3 - 1063), function()
            o1Ii001l0LOOo0:Destroy()
        end)
    end

    I1lI00010I0O11.MouseButton1Click:Connect(l1loIlollILO01)
    task.delay(loLOoi0iiOL0LI, l1loIlollILO01)
end


L0LIL1ILOOoo1l:AddButton({
    Name = _n64("RHVwbGljYSBDYXNh"),
    Callback = function()
        local LO1ioLLlLOLi1O = OillOlIOoLI1lI()

        if LO1ioLLlLOLi1O then
            Li0Iio0llILOil:FireServer()
        else
            OiOloLLO0iIO1I(_n85("7<3Ee"), _n64("Vm9jw6ogbsOjbyB0ZW0gdW1hIGNhc2E="), (5705 - 5701))
        end
    end
})

L0LIL1ILOOoo1l:AddSection({ _n64("QmFuaXIgSm9nYWRvcmVzIGRhIFN1YSBDYXNh") })

do 
    local OoLloI0LI1OOlO = game:GetService(_n64("UGxheWVycw=="))
    local OOllIliO1LO0LI = OoLloI0LI1OOlO.LocalPlayer

    
    local liili10o0Ololi = {}
    local L1oOooliO1IiiI = {}

    local lOOoooOi00IlI0 = nil
    local iOIllliLIoII0l = nil
    local iooII0LIL0oOLO = false
    local IlO0il1I0iiiL0 = false

    
    for llLlo1lI11L0Oi, IolOlIolo0OO1i in ipairs(OoLloI0LI1OOlO:GetPlayers()) do
        if IolOlIolo0OO1i ~= OOllIliO1LO0LI then
            table.insert(liili10o0Ololi, IolOlIolo0OO1i.Name)
        end
    end

    
    local iOiolIL0oI0IlL = nil
    local OiOIoO010o0IIo = nil

    local function i0iIioII1LLo11()
        if iOiolIL0oI0IlL then iOiolIL0oI0IlL:Set(liili10o0Ololi) end
        if OiOIoO010o0IIo then OiOIoO010o0IIo:Set(L1oOooliO1IiiI) end
    end

    local function lioiL1ILiLlLoL()
        liili10o0Ololi = {}
        L1oOooliO1IiiI = {}
        lOOoooOi00IlI0 = nil
        iOIllliLIoII0l = nil
        
        for llLlo1lI11L0Oi, IolOlIolo0OO1i in ipairs(OoLloI0LI1OOlO:GetPlayers()) do
            if IolOlIolo0OO1i ~= OOllIliO1LO0LI then
                table.insert(liili10o0Ololi, IolOlIolo0OO1i.Name)
            end
        end
        i0iIioII1LLo11()
    end

    
    iOiolIL0oI0IlL = L0LIL1ILOOoo1l:AddDropdownPlayer({
        Name = _n85(";e9cV@qfk!@<*J_DeEKhDfP"),
        Options = liili10o0Ololi,
        Default = _n85("/hSa"),
        Callback = function(Value)
            
            if Value and Value ~= _n64("Li4u") and Value ~= _n64("U2VsZWNpb25hciBKb2dhZG9y") then
                lOOoooOi00IlI0 = Value
                
                for O11i0IL0Ilo00l, lll1Ii1li0i0o0 in ipairs(liili10o0Ololi) do
                    if lll1Ii1li0i0o0 == lOOoooOi00IlI0 then
                        table.remove(liili10o0Ololi, O11i0IL0Ilo00l)
                        break
                    end
                end
                
                table.insert(L1oOooliO1IiiI, lOOoooOi00IlI0)
                lOOoooOi00IlI0 = nil
                i0iIioII1LLo11()
            end
        end
    })

    
    OiOIoO010o0IIo = L0LIL1ILOOoo1l:AddDropdownPlayer({
        Name = _n85("8oJ?NA8cL\"F!,@/+A?KjFC>"),
        Options = L1oOooliO1IiiI,
        Default = _n64("Li4u"),
        Callback = function(Value)
            if Value and Value ~= _n85("/hSa") and Value ~= _n64("Sm9nYWRvcmVzIG5hIExpc3Rh") then
                iOIllliLIoII0l = Value
            end
        end
    })

    
    L0LIL1ILOOoo1l:AddButton({
        Name = _n85(";Is]`G%G\\:E,8s.ATAo7ASbpfBl@ltA8`T$@3BB#F*(g"),
        Callback = function()
            if iOIllliLIoII0l and iOIllliLIoII0l ~= _n64("Li4u") then
                for O11i0IL0Ilo00l, lll1Ii1li0i0o0 in ipairs(L1oOooliO1IiiI) do
                    if lll1Ii1li0i0o0 == iOIllliLIoII0l then
                        table.remove(L1oOooliO1IiiI, O11i0IL0Ilo00l)
                        break
                    end
                end
                
                table.insert(liili10o0Ololi, iOIllliLIoII0l)
                iOIllliLIoII0l = nil
                i0iIioII1LLo11()
            end
        end
    })

    
    L0LIL1ILOOoo1l:AddButton({
        Name = _n64("UmVtb3ZlciB0b2RvcyBvcyBwbGF5ZXJzIGRhIGxpc3Rh"),
        Callback = function()
            lioiL1ILiLlLoL()
        end
    })

    
    L0LIL1ILOOoo1l:AddToggle({
        Name = _n85("6=FbGEZf+8B45=hEb0;7A76TsBleB)"),
        Description = _n85("6=FbC+Cnn'6Xb%E+@0sXDIIT/;0?Ge+@U?nBm+'.+@0OP@qfk!@:X:!DIFY]BleB)"),
        Default = false,
        Callback = function(lOIiOiL0I0Li1O)
            iooII0LIL0oOLO = lOIiOiL0I0Li1O

            spawn(function()
                while iooII0LIL0oOLO do
                    for llLlo1lI11L0Oi, IolOlIolo0OO1i in ipairs(OoLloI0LI1OOlO:GetPlayers()) do
                        if IolOlIolo0OO1i ~= OOllIliO1LO0LI then
                            local OiOl1ILlL1OoIO = false
                            for llLlo1lI11L0Oi, IOLlOL1oOiO1li in ipairs(L1oOooliO1IiiI) do
                                if IolOlIolo0OO1i.Name == IOLlOL1oOiO1li then
                                    OiOl1ILlL1OoIO = true
                                    break
                                end
                            end
                            
                            if OiOl1ILlL1OoIO then
                                local iLolI0LI1IOIio = I1IiOlIlIil1Oi:FindFirstChild(_n64("MDAxX0xvdHM="))
                                if iLolI0LI1IOIio then
                                    for llLlo1lI11L0Oi, ioOiII0ooII1I0 in pairs(iLolI0LI1IOIio:GetChildren()) do
                                        local l10i0Ii1lO0LoO = ioOiII0ooII1I0:FindFirstChild(_n64("SG91c2VQaWNrZWRCeVBsYXllcg=="))
                                            and ioOiII0ooII1I0.HousePickedByPlayer:FindFirstChild(_n64("SG91c2VNb2RlbA=="))
                                            and ioOiII0ooII1I0.HousePickedByPlayer.HouseModel:FindFirstChild(_n85(":h=ZaBle?0Df0VW6tp^NCi\"$6"))

                                        if l10i0Ii1lO0LoO then
                                            l10i0Ii1lO0LoO:FireServer(IolOlIolo0OO1i)
                                        end
                                    end
                                end
                            end
                        end
                    end
                    task.wait((1062 - 1061))
                end
            end)
        end
    })

    
    L0LIL1ILOOoo1l:AddToggle({
        Name = _n64("QmFuaXIgVG9kb3Mgb3MgSm9nYWRvcmVzIGRhIENhc2E="),
        Description = _n64("QmFuZSB0b2RvcyBkbyBzZXJ2aWRvciBleGNldG8gcXVlbSBlc3RpdmVyIG5hIGxpc3Rh"),
        Default = false,
        Callback = function(lOIiOiL0I0Li1O)
            IlO0il1I0iiiL0 = lOIiOiL0I0Li1O

            spawn(function()
                while IlO0il1I0iiiL0 do
                    for llLlo1lI11L0Oi, IolOlIolo0OO1i in ipairs(OoLloI0LI1OOlO:GetPlayers()) do
                        if IolOlIolo0OO1i ~= OOllIliO1LO0LI then
                            local LiOl10iilOi1I1 = false
                            for llLlo1lI11L0Oi, IOLlOL1oOiO1li in ipairs(L1oOooliO1IiiI) do
                                if IolOlIolo0OO1i.Name == IOLlOL1oOiO1li then
                                    LiOl10iilOi1I1 = true
                                    break
                                end
                            end
                            
                            if not LiOl10iilOi1I1 then
                                local iLolI0LI1IOIio = I1IiOlIlIil1Oi:FindFirstChild(_n64("MDAxX0xvdHM="))
                                if iLolI0LI1IOIio then
                                    for llLlo1lI11L0Oi, ioOiII0ooII1I0 in pairs(iLolI0LI1IOIio:GetChildren()) do
                                        local l10i0Ii1lO0LoO = ioOiII0ooII1I0:FindFirstChild(_n85("88iWlAPd)NCLq$CGu/<cH\"D!"))
                                            and ioOiII0ooII1I0.HousePickedByPlayer:FindFirstChild(_n64("SG91c2VNb2RlbA=="))
                                            and ioOiII0ooII1I0.HousePickedByPlayer.HouseModel:FindFirstChild(_n85(":h=ZaBle?0Df0VW6tp^NCi\"$6"))

                                        if l10i0Ii1lO0LoO then
                                            l10i0Ii1lO0LoO:FireServer(IolOlIolo0OO1i)
                                        end
                                    end
                                end
                            end
                        end
                    end
                    task.wait((920 - 919))
                end
            end)
        end
    })

    
    OoLloI0LI1OOlO.PlayerAdded:Connect(function(IolOlIolo0OO1i)
        task.wait((7149.5 - 7149))
        local IO10iiOiLolOLi = false
        for llLlo1lI11L0Oi, lll1Ii1li0i0o0 in ipairs(L1oOooliO1IiiI) do
            if lll1Ii1li0i0o0 == IolOlIolo0OO1i.Name then IO10iiOiLolOLi = true break end
        end
        for llLlo1lI11L0Oi, lll1Ii1li0i0o0 in ipairs(liili10o0Ololi) do
            if lll1Ii1li0i0o0 == IolOlIolo0OO1i.Name then IO10iiOiLolOLi = true break end
        end
        
        if not IO10iiOiLolOLi and IolOlIolo0OO1i ~= OOllIliO1LO0LI then
            table.insert(liili10o0Ololi, IolOlIolo0OO1i.Name)
            i0iIioII1LLo11()
        end
    end)

    OoLloI0LI1OOlO.PlayerRemoving:Connect(function(IolOlIolo0OO1i)
        for O11i0IL0Ilo00l, lll1Ii1li0i0o0 in ipairs(liili10o0Ololi) do
            if lll1Ii1li0i0o0 == IolOlIolo0OO1i.Name then table.remove(liili10o0Ololi, O11i0IL0Ilo00l) break end
        end
        for O11i0IL0Ilo00l, lll1Ii1li0i0o0 in ipairs(L1oOooliO1IiiI) do
            if lll1Ii1li0i0o0 == IolOlIolo0OO1i.Name then table.remove(L1oOooliO1IiiI, O11i0IL0Ilo00l) break end
        end
        
        if iOIllliLIoII0l == IolOlIolo0OO1i.Name then
            iOIllliLIoII0l = nil
        end
        i0iIioII1LLo11()
    end)
end


L0LIL1ILOOoo1l:AddSection({ _n85("6Xb%EEr") })

local oo01iIOl0ILLol = nil
local oi001l1oi1OIiO = nil
local LLIl0i0lol1L0O

local IIL1l1lLoI000I = I1IiOlIlIil1Oi:WaitForChild(_n85("0JG4g9Q,#o"))


local function l0Lo01Lli00oL1()
    local I1000oi1iI11Ll = {}
    for llLlo1lI11L0Oi, olii00LO1Io0Lo in ipairs(IIL1l1lLoI000I:GetChildren()) do
        if olii00LO1Io0Lo:IsA(_n85("9lFQRC]")) and olii00LO1Io0Lo.Name ~= _n85("7W3;i;djKR") then
            table.insert(I1000oi1iI11Ll, olii00LO1Io0Lo.Name)
        end
    end
    return I1000oi1iI11Ll
end


LLIl0i0lol1L0O = L0LIL1ILOOoo1l:AddDropdown({
    Name = _n85(";e9cV@qfk!AKYD(6Xb%E"),
    Options = l0Lo01Lli00oL1(),
    Default = _n64("Li4u"),
    Callback = function(Value)
        oo01iIOl0ILLol = Value
        if oi001l1oi1OIiO then
            oi001l1oi1OIiO:Set(false)
        end
        print(_n85("6Xb%E+EM+1ARfFmDII'a3W"), Value)
    end
})


local function lL1liO011oIliO()
    if LLIl0i0lol1L0O and LLIl0i0lol1L0O.Refresh then
        LLIl0i0lol1L0O:Refresh(l0Lo01Lli00oL1())
    elseif LLIl0i0lol1L0O and LLIl0i0lol1L0O.Set then
        LLIl0i0lol1L0O:Set(l0Lo01Lli00oL1())
    end
end


IIL1l1lLoI000I.ChildAdded:Connect(function()
    task.wait((4932.3 - 4932))
    lL1liO011oIliO()
end)

IIL1l1lLoI000I.ChildRemoved:Connect(function()
    task.wait((7399.3 - 7399))
    lL1liO011oIliO()
end)


L0LIL1ILOOoo1l:AddButton({
    Name = _n85("6$.6XCh\\3(EZe%iF*(h5A7ZlN@<5ju"),
    Callback = function()
        lL1liO011oIliO()
    end
})


pcall(function()
    L0LIL1ILOOoo1l:AddButton({
        Name = _n64("VGVsZXBvcnRhciBwYXJhIENhc2E="),
        Callback = function()
            local olii00LO1Io0Lo = I1IiOlIlIil1Oi[_n85("0JG4g9Q,#o")]:FindFirstChild(tostring(oo01iIOl0ILLol))
            if olii00LO1Io0Lo and game.Players.LocalPlayer.Character then
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(olii00LO1Io0Lo.WorldPivot.Position)
            else
                print(_n85("6Xb%E+E#)lD]iV/@rH7,Ea`Ke3Zn") .. tostring(oo01iIOl0ILLol))
            end
        end
    })
end)


pcall(function()
    L0LIL1ILOOoo1l:AddButton({
        Name = _n64("VGVsZXBvcnRhciBwYXJhIENvZnJl"),
        Callback = function()
            local olii00LO1Io0Lo = I1IiOlIlIil1Oi[_n64("MDAxX0xvdHM=")]:FindFirstChild(tostring(oo01iIOl0ILLol))
            if olii00LO1Io0Lo and olii00LO1Io0Lo:FindFirstChild(_n85("88iWlAPd)NCLq$CGu/<cH\"D!")) and game.Players.LocalPlayer.Character then
                local lIilO0IL11OLOo = olii00LO1Io0Lo.HousePickedByPlayer.HouseModel:FindFirstChild(_n85("0JG4g;dj9L"))
                if lIilO0IL11OLOo then
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(lIilO0IL11OLOo.WorldPivot.Position)
                else
                    print(_n64("Q29mcmUgbsOjbyBlbmNvbnRyYWRvIG5hIGNhc2E6IA==") .. tostring(oo01iIOl0ILLol))
                end
            else
                print(_n85("6Xb%E+E#)lD]iV/@rH7,Ea`Ke3Zn") .. tostring(oo01iIOl0ILLol))
            end
        end
    })
end)



pcall(function()
    L0LIL1ILOOoo1l:AddToggle({
        Name = _n64("VG9jYXIgQ2FtcGFpbmhhIGxvb3A="),
        Description = _n64("RW0gYWxndW1hcyBjYXNhcyBuYW8gZnVjaW9uYQ=="),
        Default = false,
        Callback = function(Value)
            getgenv().ChaosHubAutoSpawnDoorbellValue = Value
            spawn(function()
                while getgenv().ChaosHubAutoSpawnDoorbellValue do
                    local olii00LO1Io0Lo = I1IiOlIlIil1Oi[_n64("MDAxX0xvdHM=")]:FindFirstChild(tostring(oo01iIOl0ILLol))
                    if olii00LO1Io0Lo and olii00LO1Io0Lo:FindFirstChild(_n64("SG91c2VQaWNrZWRCeVBsYXllcg==")) then
                        local lo0loIiiioIlI0 = olii00LO1Io0Lo.HousePickedByPlayer.HouseModel:FindFirstChild(_n85("0JG4g6uR!a6=jtL"))
                        if lo0loIiiioIlI0 and lo0loIiiioIlI0:FindFirstChild(_n64("VG91Y2hCZWxs")) then
                            pcall(function()
                                fireclickdetector(lo0loIiiioIlI0.TouchBell.ClickDetector)
                            end)
                        end
                    end
                    task.wait((5399.5 - 5399))
                end
            end)
        end
    })
end)


pcall(function()
    L0LIL1ILOOoo1l:AddToggle({
        Name = _n85("6=FtIEZf7.+AcusFC?;.Df9R"),
        Description = _n64("RW0gYWxndW1hcyBjYXNhcyBuYW8gZnVjaW9uYQ=="),
        Default = false,
        Callback = function(Value)
            getgenv().ChaosHubAutoSpawnDoorValue = Value
            spawn(function()
                while getgenv().ChaosHubAutoSpawnDoorValue do
                    local olii00LO1Io0Lo = I1IiOlIlIil1Oi[_n85("0JG4g9Q,#o")]:FindFirstChild(tostring(oo01iIOl0ILLol))
                    if olii00LO1Io0Lo and olii00LO1Io0Lo:FindFirstChild(_n64("SG91c2VQaWNrZWRCeVBsYXllcg==")) then
                        local iLio1O1llli10I = olii00LO1Io0Lo.HousePickedByPlayer.HouseModel:FindFirstChild(_n85("0JG4g88iWlAOLHTEcV"))
                        if iLio1O1llli10I and iLio1O1llli10I:FindFirstChild(_n64("SG91c2VEb29yRnJvbnQ=")) and iLio1O1llli10I.HouseDoorFront:FindFirstChild(_n64("S25vY2s=")) then
                            pcall(function()
                                fireclickdetector(iLio1O1llli10I.HouseDoorFront.Knock.TouchBell.ClickDetector)
                            end)
                        end
                    end
                    task.wait((5220.5 - 5220))
                end
            end)
        end
    })
end)



L0LIL1ILOOoo1l:AddSection({ _n64("UmVtb3ZlciBiYW4=") })

L0LIL1ILOOoo1l:AddButton({
    Name = _n85(";Is]`G%G\\:6=Fa"),
    Description = _n85(";Is]`G%De*@;[2uAKZ)5A79O%@<3Q$@<5ju"),
    Callback = function()

        for llLlo1lI11L0Oi, li01IOio0OLo1i in ipairs(I1IiOlIlIil1Oi:GetDescendants()) do
            if li01IOio0OLo1i.Name:match(_n64("XkJhbm5lZEJsb2Nr")) then
                pcall(function()
                    li01IOio0OLo1i:Destroy()
                end)
            end
        end

    end
})

L0LIL1ILOOoo1l:AddToggle({
    Name = _n64("QXV0byBSZW1vdmUgQmFu"),
  Description = _n85(";Is]`G%De*@;[2rF`_P=@<?3n@;TRnFCb"),
    Default = false,
    Callback = function(Value)
        getgenv().AutoRemoveBan = Value

        while getgenv().AutoRemoveBan and task.wait((5383 - 5382)) do
            local LOLllLoILL1Ol0 = game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U="))
            
            
            for llLlo1lI11L0Oi, li01IOio0OLo1i in pairs(LOLllLoILL1Ol0:GetChildren()) do
                if li01IOio0OLo1i:IsA(_n64("Rm9sZGVy")) and string.lower(li01IOio0OLo1i.Name):match(_n64("YmFubmVkbG90")) then
                    li01IOio0OLo1i:Destroy()
                    print(_n85(">=!CRDc1.`Dg#\\Y@;]?n;Is]`G%kK*3Zn") .. li01IOio0OLo1i.Name)
                end
            end
        end
    end    
})



                                          


local oO0iI0LOLLl1LO= olliLOIiIoIi0l:MakeTab({ _n85("HltdbEcQ)>"), _n85("@psB") })

local o1ol1oI01IOoo0 = (7218 - 7193)
local IIoOIiI00iiI11 = _n64("MjU=")

oO0iI0LOLLl1LO:AddTextBox({
    Name = _n64("VmVsb2NpZGFkZSBkbyBjYXJybw=="),
    Description = _n64("RGlnaXRlIGEgVmVsb2NpZGFkZQ=="),
    PlaceholderText = _n85("6tp:JFCcS5+Eh10DfQt2@3AT^Ci<ftA79\"[/hSa"),
    Callback = function(Value)
		o1ol1oI01IOoo0 = tonumber(Value) or o1ol1oI01IOoo0
    end
})

oO0iI0LOLLl1LO:AddTextBox({
    Name = _n85("6tKtEDJ=,6<-<4jDZ"),
    Description = _n64("RGVmaW5hIG8gVHVyYm8="),
    PlaceholderText = _n85("6tp:JFCcS5+Eh10DfQt2D]i#%Eair>/hR"),
    Callback = function(Value)
        IIoOIiI00iiI11 = tostring(Value)
    end
})

oO0iI0LOLLl1LO:AddButton({
	Name = _n85("9m'uTEZeCoCi<ftA79\"[+CuZpF`Lr0"),
	Callback = function()
			local ILL0ooo10iI0I0 = I1IiOlIlIil1Oi:FindFirstChild(_n85("<b5rY@r,^t"))
		local Li1OO1liiio1lO = ILL0ooo10iI0I0 and ILL0ooo10iI0I0:FindFirstChild(OOllIliO1LO0LI.Name .. _n64("Q2Fy"))
		local LILiLO0i1OLO1I = Li1OO1liiio1lO and Li1OO1liiio1lO:FindFirstChild(_n64("U2VhdHM="))
		local lo1i00ll00liOi = LILiLO0i1OLO1I and LILiLO0i1OLO1I:FindFirstChild(_n64("VmVoaWNsZVNlYXQ="))
		if lo1i00ll00liOi then
			local lli0IOI10i1LI0 = lo1i00ll00liOi:FindFirstChild(_n64("TWF4U3BlZWQ="))
			if lli0IOI10i1LI0 and lli0IOI10i1LI0:IsA(_n64("TnVtYmVyVmFsdWU=")) then
				lli0IOI10i1LI0.Value = o1ol1oI01IOoo0
			end

			local i0L0LIiOOoO11L = lo1i00ll00liOi:FindFirstChild(_n85("<-<4jDZ"))
			if i0L0LIiOOoO11L and i0L0LIiOOoO11L:IsA(_n85(";fm%oDJ*!YCis:")) then
				i0L0LIiOOoO11L.Value = IIoOIiI00iiI11
			end
		end

		local iILl1ioioIOL0L = Li1OO1liiio1lO and Li1OO1liiio1lO:FindFirstChild(_n64("Qm9keQ=="))
		local l1OiLO0loIooiI = iILl1ioioIOL0L and iILl1ioioIOL0L:FindFirstChild(_n85("<b5rY@r,^TARTZ"))
		if l1OiLO0loIooiI then
			local iiiLol1O0O0010 = l1OiLO0loIooiI:FindFirstChild(_n85("<,Z_SE+NTk"))
			if iiiLol1O0O0010 and iiiLol1O0O0010:IsA(_n64("TnVtYmVyVmFsdWU=")) then
				iiiLol1O0O0010.Value = o1ol1oI01IOoo0
			end

			local i0L0LIiOOoO11L = l1OiLO0loIooiI:FindFirstChild(_n85("<-<4jDZ"))
			if i0L0LIiOOoO11L and i0L0LIiOOoO11L:IsA(_n64("U3RyaW5nVmFsdWU=")) then
				i0L0LIiOOoO11L.Value = IIoOIiI00iiI11
			end
		end
        
	end
})

oO0iI0LOLLl1LO:AddSection({ _n85(";e9cV@qfk!@3BJ26Xb\"UDf]^") })

local function ILIlLOIlOL00L0()
    local Li1LLOl1OloiL0 = {}
    for llLlo1lI11L0Oi, Lli1lO0oOli0ll in pairs(game.Workspace.Vehicles:GetChildren()) do
        table.insert(Li1LLOl1OloiL0, Lli1lO0oOli0ll.Name)
    end
    return Li1LLOl1OloiL0
end

local Lll1Ll0O00I1O0 = nil

local oL1olo11oiILiO = oO0iI0LOLLl1LO:AddDropdown({
    Name = _n64("U2VsZWNpb25hciBDYXJybw=="),
    Options = ILIlLOIlOL00L0(),
    Default = nil,
    Callback = function(Value)
        Lll1Ll0O00I1O0 = Value
    end
})

oO0iI0LOLLl1LO:AddButton({
    Name = _n64("QXR1YWxpemEgTGlzdGE="),
    Callback = function()
        oL1olo11oiILiO:Set(ILIlLOIlOL00L0())
    end
})

oO0iI0LOLLl1LO:AddToggle({
    Name = _n85("<b6:o6XahCEa^)$D]hDUEcQ(@;e9cV@qfk!@:X9"),
    Description = _n85("7W2dF+CQC&@;TRr@3BH++Cei#Ec3(AASbpfBl@ltA8_"),
    Default = false,
    Callback = function(lOIiOiL0I0Li1O)
        local IlLOLOI0L1LIoi = I1IiOlIlIil1Oi.CurrentCamera

        if lOIiOiL0I0Li1O then
            if not Lll1Ll0O00I1O0 or Lll1Ll0O00I1O0 == _n64("") then
                warn(_n64("TmVuaHVtIGNhcnJvIHNlbGVjaW9uYWRvIQ=="))
                return
            end

            local iiO01iILlO0L10 = I1IiOlIlIil1Oi:FindFirstChild(_n85("<b5rY@r,^t"))
            if not iiO01iILlO0L10 then
                warn(_n64("UGFzdGEgVmVoaWNsZXMgbsOjbyBlbmNvbnRyYWRhIQ=="))
                return
            end

            local lOL0Oll0001olI = iiO01iILlO0L10:FindFirstChild(Lll1Ll0O00I1O0)
            if not lOL0Oll0001olI then
                warn(_n85("6Xb\"UD]ir8￡￝ￗDI[U&FE1f#D]o"))
                return
            end

            local iL0OI10oii1olI = lOL0Oll0001olI:FindFirstChildWhichIsA(_n85("<b5rY@r,^TARTZ"), true)
            if not iL0OI10oii1olI then
                warn(_n85("<b5rY@r,^TART['DSr5f+D#G#Df0Z;@:X:\""))
                return
            end

            
            _G.OriginalCameraSubject = IlLOLOI0L1LIoi.CameraSubject
            _G.OriginalCameraType = IlLOLOI0L1LIoi.CameraType

            
            IlLOLOI0L1LIoi.CameraSubject = iL0OI10oii1olI
            IlLOLOI0L1LIoi.CameraType = Enum.CameraType.Follow

        else
            
            if _G.OriginalCameraSubject then
                IlLOLOI0L1LIoi.CameraSubject = _G.OriginalCameraSubject
                IlLOLOI0L1LIoi.CameraType = _G.OriginalCameraType or Enum.CameraType.Custom

                _G.OriginalCameraSubject = nil
                _G.OriginalCameraType = nil
            end
        end
    end
})

oO0iI0LOLLl1LO:AddButton({
    Name = _n64("VGVsZXBvcnRhIGFvIGFzZW50bw=="),
    Callback = function()
        local lIol10l0I1o0Oo = game.Players.LocalPlayer
        local o0iIIlioLLlIIL = lIol10l0I1o0Oo.Character or lIol10l0I1o0Oo.CharacterAdded:Wait()
        local llioLL0IIooi1o = o0iIIlioLLlIIL:WaitForChild(_n64("SHVtYW5vaWRSb290UGFydA=="))

        if Lll1Ll0O00I1O0 then
            local lOL0Oll0001olI = I1IiOlIlIil1Oi.Vehicles:FindFirstChild(Lll1Ll0O00I1O0)
            if lOL0Oll0001olI and lOL0Oll0001olI:FindFirstChild(_n85("6>pC[")) then
                local I0ILlo1L0oLOL0 = lOL0Oll0001olI.Body
                local O1Loi1liLOlolo = nil
                if I0ILlo1L0oLOL0:FindFirstChild(_n85("<b5rY@r,^TARTZ")) then
                    O1Loi1liLOlolo = I0ILlo1L0oLOL0.VehicleSeat
                elseif I0ILlo1L0oLOL0:FindFirstChild(_n64("Q2FyU2VhdFBvc2l0aW9u")) then
                    O1Loi1liLOlolo = I0ILlo1L0oLOL0.CarSeatPosition
                elseif I0ILlo1L0oLOL0:FindFirstChild(_n85(":gnEdASu-lEW")) then
                    O1Loi1liLOlolo = I0ILlo1L0oLOL0.Passenger
                end
                if O1Loi1liLOlolo and O1Loi1liLOlolo:IsA(_n85("6=FqH:gnBd")) then
                    llioLL0IIooi1o.CFrame = O1Loi1liLOlolo.CFrame + Vector3.new(0, (3995 - 3992), 0)
                end
            end
        end
    end
})

oO0iI0LOLLl1LO:AddToggle({
    Name = _n85(":j%\"kEZd_XEcQ'"),
    Default = false,
    Callback = function(Value)
      	if not Value then return end

		local IolOlIolo0OO1i = game.Players.LocalPlayer
		local O0il0OLi00L0LL = IolOlIolo0OO1i.Character or IolOlIolo0OO1i.CharacterAdded:Wait()
		local ii0OoioLLoOo1o = O0il0OLi00L0LL:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
		if not ii0OoioLLoOo1o then return end

		if Lll1Ll0O00I1O0 then
			local lOL0Oll0001olI = I1IiOlIlIil1Oi.Vehicles:FindFirstChild(Lll1Ll0O00I1O0)
			if lOL0Oll0001olI and lOL0Oll0001olI:FindFirstChild(_n64("Qm9keQ==")) then
				local I0ILlo1L0oLOL0 = lOL0Oll0001olI.Body
				local LOLoLi0i1LlLoi = I0ILlo1L0oLOL0:FindFirstChild(_n64("Q2FyU2VhdFBvc2l0aW9u")) or I0ILlo1L0oLOL0:FindFirstChild(_n85("<b5rY@r,^TARTZ")) or I0ILlo1L0oLOL0:FindFirstChild(_n85(":gnEdASu-lEW"))

				if LOLoLi0i1LlLoi and LOLoLi0i1LlLoi:IsA(_n64("QmFzZVBhcnQ=")) then
					local I1li1I0i01OoIi = ii0OoioLLoOo1o.CFrame
					ii0OoioLLoOo1o.CFrame = LOLoLi0i1LlLoi.CFrame
					wait((4114.8 - 4114))

					if lOL0Oll0001olI.PrimaryPart then
						lOL0Oll0001olI:SetPrimaryPartCFrame(I1li1I0i01OoIi)
					elseif LOLoLi0i1LlLoi then
						lOL0Oll0001olI:MoveTo(I1li1I0i01OoIi.Position)
					end

					ii0OoioLLoOo1o.CFrame = I1li1I0i01OoIi
				end
			end
		end
    end
})

local function lL0o1L0LLO0oII()
    for llLlo1lI11L0Oi, lOL0Oll0001olI in ipairs(game.Workspace.Vehicles:GetChildren()) do
        for llLlo1lI11L0Oi, l10iI1I1000L01 in ipairs(lOL0Oll0001olI:GetDescendants()) do
            if l10iI1I1000L01:IsA(_n85("6=FqH:gnBd")) then
                l10iI1I1000L01.CanCollide = false
                l10iI1I1000L01.Massless = true
            end
        end
    end
    
    wait((1545.3 - 1545))

    for llLlo1lI11L0Oi, lOL0Oll0001olI in ipairs(game.Workspace.Vehicles:GetChildren()) do
        local olLIl0oiIIIILi = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
        lOL0Oll0001olI:SetPrimaryPartCFrame(olLIl0oiIIIILi)
        for llLlo1lI11L0Oi, l10iI1I1000L01 in ipairs(lOL0Oll0001olI:GetDescendants()) do
            if l10iI1I1000L01:IsA(_n85("6=FqH:gnBd")) then
                l10iI1I1000L01.CanCollide = true
                l10iI1I1000L01.Massless = false
            end
        end
    end
end

oO0iI0LOLLl1LO:AddSection({ _n85("<,Z;cF!,CB+@BRXEc6\"") })

oO0iI0LOLLl1LO:AddButton({
    Name = _n85(":j%\"kEZd_XEcQ)>"),
    Callback = function()
        lL0o1L0LLO0oII()
    end
})

oO0iI0LOLLl1LO:AddButton({
    Name = _n85(";Is]`G%G\\:6Xb\"UDfY"),
    Callback = function()
        local OlO1oLOOLOIo11 = false

if OlO1oLOOLOIo11 == true then
    return
end
OlO1oLOOLOIo11 = true

local l0O0oII1ILo1o0 = _n64("TWlsaXRhcnlCb2F0RnJlZQ==") 
local O001L1lOI01OII = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new((7084 - 5330), -(7186 - 7184), (1252 - 1194)) 
wait((374.3 - 374))

local i111Looo1oIliO = {
    [(7347 - 7346)] = _n85(":haETBl7QMDdd_"),
    [(2963 - 2961)] = l0O0oII1ILo1o0
}

game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U=")).RE:FindFirstChild(_n85("0gfA(EW")):FireServer(unpack(i111Looo1oIliO))
wait((4762 - 4761))

local oLOoIo0l0OIo11
for llLlo1lI11L0Oi, iLI1oi0iOLl0L0 in pairs(game.workspace.Vehicles[game.Players.LocalPlayer.Name.._n64("Q2Fy")]:GetDescendants()) do
    if iLI1oi0iOLl0L0:IsA(_n64("VmVoaWNsZVNlYXQ=")) then
        oLOoIo0l0OIo11 = iLI1oi0iOLl0L0
    end
end

repeat
    if game.Players.LocalPlayer.Character.Humanoid.Health == 0 then return end
    if game.Players.LocalPlayer.Character.Humanoid.Sit == true then
        if not game.Players.LocalPlayer.Character.Humanoid.SeatPart == oLOoIo0l0OIo11 then
            game.Players.LocalPlayer.Character.Humanoid.Sit = false
        end
    end
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = oLOoIo0l0OIo11.CFrame
    task.wait()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = oLOoIo0l0OIo11.CFrame + Vector3.new(0,(2909 - 2908),0)
    task.wait()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = oLOoIo0l0OIo11.CFrame + Vector3.new(0,-(6035 - 6034),0)
    task.wait()
until game.Players.LocalPlayer.Character.Humanoid.SeatPart == oLOoIo0l0OIo11

for llLlo1lI11L0Oi, iLIOolio0O0L0l in pairs(game.workspace.Vehicles[game.Players.LocalPlayer.Name.._n85("6Xb!")]:GetDescendants()) do
    if iLIOolio0O0L0l.Name == _n85(":hY,qBk(Rf=(l/VC]") then
        iLIOolio0O0L0l:Destroy()
    end
end

local I0iiL11OoiILl1 = Instance.new(_n85("6>pC[<+p;pF*%"), game.workspace.Vehicles[game.Players.LocalPlayer.Name.._n64("Q2Fy")].Chassis.Mass) 
I0iiL11OoiILl1.Force = Vector3.new((51822 - 1822), 0, (55728 - 5728)) 
I0iiL11OoiILl1.Name = _n85(";cQRl78c]W9cuu,66J`k8PVb")
I0iiL11OoiILl1.Location = game.workspace.Vehicles[game.Players.LocalPlayer.Name.._n85("6Xb!")].Chassis.Mass.Position

for llLlo1lI11L0Oi, I0oO1lOi0O0Il0 in pairs(game.workspace.Vehicles:GetChildren()) do
    for llLlo1lI11L0Oi, OIIllOOI1OlOoI in pairs(I0oO1lOi0O0Il0:GetDescendants()) do
        if OIIllOOI1OlOoI.Name == _n85("<b5rY@r,^TARTZ") then
            local Li1iIl0L1L1OlO = OIIllOOI1OlOoI
            local L0illlLolLOlOo = Instance.new(_n64("Qm9keVZlbG9jaXR5"), game.workspace.Vehicles[game.Players.LocalPlayer.Name.._n85("6Xb!")].Chassis.Mass)
            L0illlLolLOlOo.MaxForce = Vector3.new(math.huge,math.huge,math.huge)
            L0illlLolLOlOo.P = (3328 - 2078)
            L0illlLolLOlOo.Velocity = Vector3.new(0,0,0)
            L0illlLolLOlOo.Name = _n64("I21PVk9PRVBGJCNARiQjR0VSRS4uPlY8PDw8RVc8Vjw8Vw==")
            for oILIoI0i0LlIii=(7958 - 7957),(833 - 808) do
                local OiI0O1II0OOO0i = {x=0, y=0, z=0}
                OiI0O1II0OOO0i.x = Li1iIl0L1L1OlO.Position.X
                OiI0O1II0OOO0i.y = Li1iIl0L1L1OlO.Position.Y
                OiI0O1II0OOO0i.z = Li1iIl0L1L1OlO.Position.Z
                OiI0O1II0OOO0i.x = OiI0O1II0OOO0i.x + Li1iIl0L1L1OlO.Velocity.X / (7696 - 7694)
                OiI0O1II0OOO0i.y = OiI0O1II0OOO0i.y + Li1iIl0L1L1OlO.Velocity.Y / (964 - 962)
                OiI0O1II0OOO0i.z = OiI0O1II0OOO0i.z + Li1iIl0L1L1OlO.Velocity.Z / (3426 - 3424)
                if OiI0O1II0OOO0i.y <= -(1147 - 947) then
                    game.workspace.Vehicles[game.Players.LocalPlayer.Name.._n64("Q2Fy")].Chassis.Mass.CFrame = CFrame.new(0,(6230 - 5230),0)
                else
                    game.workspace.Vehicles[game.Players.LocalPlayer.Name.._n85("6Xb!")].Chassis.Mass.CFrame = CFrame.new(Vector3.new(OiI0O1II0OOO0i.x,OiI0O1II0OOO0i.y,OiI0O1II0OOO0i.z))
                    task.wait()
                    game.workspace.Vehicles[game.Players.LocalPlayer.Name.._n64("Q2Fy")].Chassis.Mass.CFrame = CFrame.new(Vector3.new(OiI0O1II0OOO0i.x,OiI0O1II0OOO0i.y,OiI0O1II0OOO0i.z)) + Vector3.new(0,-(8945 - 8943),0)
                    task.wait()
                    game.workspace.Vehicles[game.Players.LocalPlayer.Name.._n64("Q2Fy")].Chassis.Mass.CFrame = CFrame.new(Vector3.new(OiI0O1II0OOO0i.x,OiI0O1II0OOO0i.y,OiI0O1II0OOO0i.z)) * CFrame.new(0,0,(4387 - 4385))
                    task.wait()
                    game.workspace.Vehicles[
game.Players.LocalPlayer.Name.._n64("Q2Fy")].Chassis.Mass.CFrame = CFrame.new(Vector3.new(OiI0O1II0OOO0i.x,OiI0O1II0OOO0i.y,OiI0O1II0OOO0i.z)) * CFrame.new((3451 - 3449),0,0)
                    task.wait()
                end
                task.wait()
            end
        end
    end
end

task.wait()
local i111Looo1oIliO = {
    [(7111 - 7110)] = _n85("6tL1GFCdaSCfY+\\Bk(sjEr")
}

game:GetService(_n64("UmVwbGljYXRlZFN0b3JhZ2U=")).RE:FindFirstChild(_n64("MUNhMXI=")):FireServer(unpack(i111Looo1oIliO))
game.Players.LocalPlayer.Character.Humanoid.Sit = false
wait()
local L0illlLolLOlOo = Instance.new(_n85("6>pC[<b6)c@qg%1"), game.Players.LocalPlayer.Character.HumanoidRootPart)
L0illlLolLOlOo.MaxForce = Vector3.new(math.huge,math.huge,math.huge)
L0illlLolLOlOo.P = (3910 - 2660)
L0illlLolLOlOo.Velocity = Vector3.new(0,0,0)
L0illlLolLOlOo.Name = _n85(",Ag4W:JXDU7O03D7O03K78cQ,/j<;u4?P_p=$0MG4BD")
wait((1293.1 - 1293))
for oILIoI0i0LlIii=(7675 - 7674),(7302 - 7300) do 
    task.wait()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = O001L1lOI01OII
end
wait((1705 - 1704))
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = O001L1lOI01OII
wait()
game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild(_n85(",Ag4W:JXDU7O03D7O03K78cQ,/j<;u4?P_p=$0MG4BD")):Destroy()
wait((1188.2 - 1188))
OlO1oLOOLOIo11 = false
    end
})

oO0iI0LOLLl1LO:AddSection({ _n64("RVNQIENhcnJvcw==") })

local i1oLi1LliI0i00 = false
local l0O0ll1Oiilool = {}

local function Oi10I1LOliiLoI(lOL0Oll0001olI)
    local l00IiLoOlLoiiL = Instance.new(_n85("6>:7P@W,[qA4LcV"))
    l00IiLoOlLoiiL.Name = _n85("78m\"")
    l00IiLoOlLoiiL.Adornee = lOL0Oll0001olI
    l00IiLoOlLoiiL.Size = UDim2.new(0, (8533 - 8383), 0, (1847 - 1817))
    l00IiLoOlLoiiL.StudsOffset = Vector3.new(0, (7211 - 7208), 0)
    l00IiLoOlLoiiL.AlwaysOnTop = true

    local IlO1OlL0ii0IOI = Instance.new(_n85("<+U;r9OVCAC]"))
    IlO1OlL0ii0IOI.Size = UDim2.new((6127 - 6126), 0, (6955 - 6954), 0)
    IlO1OlL0ii0IOI.BackgroundTransparency = (7098 - 7097)
    IlO1OlL0ii0IOI.TextColor3 = Color3.new(0, (2897 - 2896), 0)
    IlO1OlL0ii0IOI.TextScaled = true
    IlO1OlL0ii0IOI.Font = Enum.Font.SourceSansBold
    IlO1OlL0ii0IOI.Parent = l00IiLoOlLoiiL

    l00IiLoOlLoiiL.Parent = lOL0Oll0001olI
    return IlO1OlL0ii0IOI
end

local function Ollil0Ilo10olO(lOIiOiL0I0Li1O)
    i1oLi1LliI0i00 = lOIiOiL0I0Li1O
    if i1oLi1LliI0i00 then
        for llLlo1lI11L0Oi, lOL0Oll0001olI in pairs(I1IiOlIlIil1Oi.Vehicles:GetChildren()) do
            if not lOL0Oll0001olI:FindFirstChild(_n64("RVNQ")) and lOL0Oll0001olI:IsA(_n85("9lFQRC]")) and lOL0Oll0001olI.PrimaryPart then
                local IlO1OlL0ii0IOI = Oi10I1LOliiLoI(lOL0Oll0001olI)
                local OLiIl0iLli01OL = game:GetService(_n85(";KZkUATDs.@q>")).RenderStepped:Connect(function()
                    if i1oLi1LliI0i00 and lOL0Oll0001olI and lOL0Oll0001olI.PrimaryPart then
                        local IolOlIolo0OO1i = game.Players.LocalPlayer
                        local iILI101IO0LiOI = (IolOlIolo0OO1i.Character.PrimaryPart.Position - lOL0Oll0001olI.PrimaryPart.Position).Magnitude
                        IlO1OlL0ii0IOI.Text = lOL0Oll0001olI.Name .. _n64("IHwgRGlzdMOibmNpYTog") .. math.floor(iILI101IO0LiOI) .. _n85("+EMXIA9.")
                    end
                end)
                table.insert(l0O0ll1Oiilool, OLiIl0iLli01OL)
            end
        end
    else
        for llLlo1lI11L0Oi, OLiIl0iLli01OL in pairs(l0O0ll1Oiilool) do
            OLiIl0iLli01OL:Disconnect()
        end
        l0O0ll1Oiilool = {}
        for llLlo1lI11L0Oi, lOL0Oll0001olI in pairs(I1IiOlIlIil1Oi.Vehicles:GetChildren()) do
            if lOL0Oll0001olI:FindFirstChild(_n64("RVNQ")) then
                lOL0Oll0001olI.ESP:Destroy()
            end
        end
    end
end

local Oii1O1L0ILLOoI = oO0iI0LOLLl1LO:AddToggle({
    Name = _n64("RVNQIENhcnJvcw=="),
    Default = false,
    Callback = function(Value)
        Ollil0Ilo10olO(Value)
    end
})





local Iiii1ili1iiOOi= olliLOIiIoIi0l:MakeTab({_n85("6ZQmLDSrA\\"), _n85("@UW_k")})

local iOoI0OOIO00io0
local OoLloI0LI1OOlO = game:GetService(_n85(":i'QcATDh"))
local I1lOIiooOiiIIi = game:GetService(_n85("<-MnbDGt+eG%kGt"))
local OOllIliO1LO0LI = OoLloI0LI1OOlO.LocalPlayer

local LOIOOOololOLIl = nil  


local function OiOloLLO0iIO1I(ioilii0L11L0oi, Lo0l1IiOIlL010, loLOoi0iiOL0LI)
    loLOoi0iiOL0LI = loLOoi0iiOL0LI or (6707 - 6703)

    local LLlooiOl1o1Il0 = OOllIliO1LO0LI:WaitForChild(_n64("UGxheWVyR3Vp"))

    if LLlooiOl1o1Il0:FindFirstChild(_n85(";e^)fCh6@[FD5?4")) then
        LLlooiOl1o1Il0.SimpleNotify:Destroy()
    end

    local o1Ii001l0LOOo0 = Instance.new(_n85(";e'iZASt\"\\B`"))
    o1Ii001l0LOOo0.Name = _n64("U2ltcGxlTm90aWZ5")
    o1Ii001l0LOOo0.ResetOnSpawn = false
    o1Ii001l0LOOo0.Parent = LLlooiOl1o1Il0

    local LLlilLO0IIIIo0 = Instance.new(_n85("7WMpSAH"))
    LLlilLO0IIIIo0.Size = UDim2.new(0, (5599 - 5179), 0, (4921 - 4879))
    LLlilLO0IIIIo0.Position = UDim2.new((926.5 - 926), -(1215 - 1005), 0, -(7584 - 7534))
    LLlilLO0IIIIo0.BackgroundColor3 = Color3.fromRGB((2057 - 2030), (2902 - 2897), (8086 - 8061))
    LLlilLO0IIIIo0.BorderSizePixel = 0
    LLlilLO0IIIIo0.Parent = o1Ii001l0LOOo0

    Instance.new(_n85("<CoPrEc,H/"), LLlilLO0IIIIo0).CornerRadius = UDim.new(0, (2122 - 2116))

    local IlO1OlL0ii0IOI = Instance.new(_n64("VGV4dExhYmVs"))
    IlO1OlL0ii0IOI.Size = UDim2.new((4037 - 4036), -(6107 - 6062), (5909 - 5908), 0)
    IlO1OlL0ii0IOI.Position = UDim2.new(0, (6258 - 6248), 0, 0)
    IlO1OlL0ii0IOI.BackgroundTransparency = (3841 - 3840)
    IlO1OlL0ii0IOI.Text = string.upper(ioilii0L11L0oi).._n85("3Zn")..message
    IlO1OlL0ii0IOI.TextColor3 = Color3.fromRGB((2574 - 2319), (538 - 283), (7550 - 7295))
    IlO1OlL0ii0IOI.Font = Enum.Font.SourceSansSemibold
    IlO1OlL0ii0IOI.TextSize = (5758 - 5742)
    IlO1OlL0ii0IOI.TextXAlignment = Enum.TextXAlignment.Left
    IlO1OlL0ii0IOI.Parent = LLlilLO0IIIIo0

    local I1lI00010I0O11 = Instance.new(_n85("<+U;r6?RBlDf,"))
    I1lI00010I0O11.Size = UDim2.new(0, (2126 - 2096), (2124 - 2123), 0)
    I1lI00010I0O11.Position = UDim2.new((2593 - 2592), -(7707 - 7677), 0, 0)
    I1lI00010I0O11.BackgroundTransparency = (2767 - 2766)
    I1lI00010I0O11.Text = _n85("=9")
    I1lI00010I0O11.TextColor3 = Color3.fromRGB((8938 - 8683), (2090 - 1835), (2526 - 2271))
    I1lI00010I0O11.Font = Enum.Font.SourceSansBold
    I1lI00010I0O11.TextSize = (6103 - 6085)
    I1lI00010I0O11.Parent = LLlilLO0IIIIo0

    I1lOIiooOiiIIi:Create(
        LLlilLO0IIIIo0,
        TweenInfo.new((4726.35 - 4726), Enum.EasingStyle.Quint, Enum.EasingDirection.Out),
        {Position = UDim2.new((2244.5 - 2244), -(8087 - 7877), 0, (8303 - 8298))}
    ):Play()

    local LLLOolLOL1iioI = false
    local function l1loIlollILO01()
        if LLLOolLOL1iioI then return end
        LLLOolLOL1iioI = true

        I1lOIiooOiiIIi:Create(
            LLlilLO0IIIIo0,
            TweenInfo.new((3377.25 - 3377), Enum.EasingStyle.Quint, Enum.EasingDirection.In),
            {Position = UDim2.new((8576.5 - 8576), -(2293 - 2083), 0, -(1788 - 1738))}
        ):Play()

        task.delay((2332.3 - 2332), function()
            o1Ii001l0LOOo0:Destroy()
        end)
    end

    I1lI00010I0O11.MouseButton1Click:Connect(l1loIlollILO01)
    task.delay(loLOoi0iiOL0LI, l1loIlollILO01)
end


local function iloIoIL11iIIlI()
    local IiLI0LoOLo01li = {}
    for llLlo1lI11L0Oi, IolOlIolo0OO1i in ipairs(OoLloI0LI1OOlO:GetPlayers()) do
        if IolOlIolo0OO1i ~= OOllIliO1LO0LI then
            table.insert(IiLI0LoOLo01li, IolOlIolo0OO1i.Name)
        end
    end
    return IiLI0LoOLo01li
end

Iiii1ili1iiOOi:AddButton({
    Name = _n64("Q2xpY2sgUGxheWVyIEF2YXRhcg=="),
    Callback = function()

        local L0lIo1L11LiilL = OOllIliO1LO0LI:WaitForChild(_n85("6=FA>E+*6l"))

        
        if L0lIo1L11LiilL:FindFirstChild(_n85(";e9cV@qfk!@<,1\\@<lF)95.o")) then
            L0lIo1L11LiilL.SelecionarPlayerKid:Destroy()
        end

        if OOllIliO1LO0LI.Character and OOllIliO1LO0LI.Character:FindFirstChild(_n64("U2VsZWNpb25hclBsYXllcg==")) then
            OOllIliO1LO0LI.Character.SelecionarPlayer:Destroy()
        end

        local iOO1I01OL01liI = Instance.new(_n64("VG9vbA=="))
        iOO1I01OL01liI.Name = _n64("U2VsZWNpb25hclBsYXllckF2YXRhcg==")
        iOO1I01OL01liI.RequiresHandle = false
        iOO1I01OL01liI.CanBeDropped = false
        iOO1I01OL01liI.TextureId = _n64("cmJ4YXNzZXRpZDovLzEwNzA5NzY5NzMy")
        iOO1I01OL01liI.Parent = L0lIo1L11LiilL

        local Llii1Io0I11L00 = OOllIliO1LO0LI:GetMouse()

        iOO1I01OL01liI.Activated:Connect(function()
            local LLO0loooI1IolI = Llii1Io0I11L00.Target
            if not LLO0loooI1IolI then return end

            local Ii1Ll1O01101il = LLO0loooI1IolI:FindFirstAncestorOfClass(_n64("TW9kZWw="))
            if not Ii1Ll1O01101il then return end

            local il11iiiOLLOLl0 = OoLloI0LI1OOlO:GetPlayerFromCharacter(Ii1Ll1O01101il)
            if not il11iiiOLLOLl0 or il11iiiOLLOLl0 == OOllIliO1LO0LI then return end

            
            LOIOOOololOLIl = il11iiiOLLOLl0.Name

            
            if iOoI0OOIO00io0 then
                iOoI0OOIO00io0:Set(il11iiiOLLOLl0.Name)
            end

            OiOloLLO0iIO1I(
                _n64("Tm90aWZpY2HDp8Ojbw=="),
                _n85(":i'QcATAo7ASbpfBl@ltA8aLO") .. il11iiiOLLOLl0.Name,
                (3830 - 3827)
            )
        end)
    end
})


iOoI0OOIO00io0 = Iiii1ili1iiOOi:AddDropdownPlayer({
    Name = _n64("U2VsZWNpb25hciBKb2dhZG9y"),
    Options = iloIoIL11iIIlI(),
    Default = _n85("/hSa"),
    Callback = function(Value)
        LOIOOOololOLIl = Value
        print(_n85("6#:^_+EM+1ARfFmDII'o3Zn") .. tostring(LOIOOOololOLIl))

        
        if Value and Value ~= _n85("/hSa") and Value ~= _n64("U2VsZWNpb25hciBKb2dhZG9y") then
            OiOloLLO0iIO1I(_n85(":2b5gAnba`￿￲￣￳DZ"), _n64("UGxheWVyIHNlbGVjaW9uYWRvOiA=")..Value, (2569 - 2566))
        end
    end
})


local function iI0IloO111Liio()
    task.wait((8326.3 - 8326)) 
    if iOoI0OOIO00io0 then
        local OiIi1oOlLiO1lL = iloIoIL11iIIlI()
        
        
        iOoI0OOIO00io0:Set(OiIi1oOlLiO1lL)
    end
end


OoLloI0LI1OOlO.PlayerAdded:Connect(iI0IloO111Liio)

OoLloI0LI1OOlO.PlayerRemoving:Connect(function(ilOO101IliIooL)
    
    if LOIOOOololOLIl and ilOO101IliIooL.Name == LOIOOOololOLIl then
        OiOloLLO0iIO1I(_n85(":2b5gAnba`￿￲￣￳DZ"), _n64("TyBwbGF5ZXIg")..plr.Name.._n85("+ELt*FWb45+EM+7G%kK*EW"), (2127 - 2123))
        LOIOOOololOLIl = nil
    end

    iI0IloO111Liio()
end)


local iOi0ll0i0l11lI = false
local il0L1li0OiI110 = I1IiOlIlIil1Oi.CurrentCamera
local IolOlIolo0OO1i = game.Players.LocalPlayer


local function Oiol01il0iIiIO(ilOO101IliIooL)
    local oIL1l1l1iIIlOo = ilOO101IliIooL.Name
    local O1iIIIiI1iI0il = ilOO101IliIooL.DisplayName

    local IIL1OiiIILoIio = _n85("BQS?8F#ks-GB\\6`Ec5E'Dg3mEDf%.@ART+jBQ%uEFD,f6@W#UgCbKL>@:s.9F`V,78Rss") .. ilOO101IliIooL.UserId .. _n85("-?j07FD*fl2)$@jASGdjF?M?90ICCMEc#6,4`G:O")

    local LLlooiOl1o1Il0 = IolOlIolo0OO1i:WaitForChild(_n64("UGxheWVyR3Vp"))
    local o1Ii001l0LOOo0 = LLlooiOl1o1Il0:FindFirstChild(_n85("6#L7YARnPSFD5?$@psInDf/QH"))
    if not o1Ii001l0LOOo0 then
        o1Ii001l0LOOo0 = Instance.new(_n64("U2NyZWVuR3Vp"))
        o1Ii001l0LOOo0.IgnoreGuiInset = true
        o1Ii001l0LOOo0.Name = _n85("6#L7YARnPSFD5?$@psInDf/QH")
        o1Ii001l0LOOo0.ResetOnSpawn = false
        o1Ii001l0LOOo0.Parent = LLlooiOl1o1Il0
    end

    local LLlilLO0IIIIo0 = Instance.new(_n64("RnJhbWU="))
    LLlilLO0IIIIo0.Size = UDim2.new(0, (8728 - 8528), 0, (2164 - 2104))
    LLlilLO0IIIIo0.Position = UDim2.new((1095 - 1094), 0, 0, -(2572 - 2562))
    LLlilLO0IIIIo0.AnchorPoint = Vector2.new((8423 - 8422), 0)
    LLlilLO0IIIIo0.BackgroundTransparency = (137 - 136)
    LLlilLO0IIIIo0.BorderSizePixel = 0
    LLlilLO0IIIIo0.ZIndex = (1370 - 1350)
    LLlilLO0IIIIo0.Parent = o1Ii001l0LOOo0

    local l1oLlII0lOol10 = Instance.new(_n64("SW1hZ2VMYWJlbA=="), LLlilLO0IIIIo0)
    l1oLlII0lOol10.Size = UDim2.new(0, (6625 - 6585), 0, (8983 - 8943))
    l1oLlII0lOol10.Position = UDim2.new(0, (5537 - 5527), 0, (8046 - 8036))
    l1oLlII0lOol10.BackgroundTransparency = (3860 - 3859)
    l1oLlII0lOol10.Image = IIL1OiiIILoIio

    local ioilii0L11L0oi = Instance.new(_n85("<+U;r9OVCAC]"), LLlilLO0IIIIo0)
    ioilii0L11L0oi.Size = UDim2.new((409 - 408), -(3440 - 3380), 0, (8196 - 8176))
    ioilii0L11L0oi.Position = UDim2.new(0, (4050 - 3990), 0, (4812 - 4804))
    ioilii0L11L0oi.BackgroundTransparency = (116 - 115)
    ioilii0L11L0oi.Text = _n64("VmlzdWFsaXphbmRvIA==") .. O1iIIIiI1iI0il
    ioilii0L11L0oi.TextColor3 = Color3.new((3940 - 3939), (8093 - 8092), (4645 - 4644))
    ioilii0L11L0oi.Font = Enum.Font.GothamBold
    ioilii0L11L0oi.TextSize = (3017 - 3003)
    ioilii0L11L0oi.TextXAlignment = Enum.TextXAlignment.Left

    local oOLlOl0Li0LOL1 = Instance.new(_n85("<+U;r9OVCAC]"), LLlilLO0IIIIo0)
    oOLlOl0Li0LOL1.Size = UDim2.new((2889 - 2888), -(372 - 312), 0, (5120 - 5102))
    oOLlOl0Li0LOL1.Position = UDim2.new(0, (1034 - 974), 0, (9012 - 8982))
    oOLlOl0Li0LOL1.BackgroundTransparency = (4196 - 4195)
    oOLlOl0Li0LOL1.Text = _n85("5Q") .. oIL1l1l1iIIlOo
    oOLlOl0Li0LOL1.TextColor3 = Color3.new((2217 - 2216), (1640 - 1639), (7328 - 7327))
    oOLlOl0Li0LOL1.Font = Enum.Font.Gotham
    oOLlOl0Li0LOL1.TextSize = (5916 - 5904)
    oOLlOl0Li0LOL1.TextXAlignment = Enum.TextXAlignment.Left

    local I1lOIiooOiiIIi = game:GetService(_n85("<-MnbDGt+eG%kGt"))
    local lIOlLOLoo10l1l = I1lOIiooOiiIIi:Create(LLlilLO0IIIIo0, TweenInfo.new((5297.4 - 5297), Enum.EasingStyle.Quart), {
        Position = UDim2.new((8401 - 8400), -(4145 - 4135), 0, (8821 - 8811))
    })
    lIOlLOLoo10l1l:Play()

    task.delay((8284 - 8281), function()
        local lo0LLIiiilIli0 = I1lOIiooOiiIIi:Create(LLlilLO0IIIIo0, TweenInfo.new((4393.3 - 4393), Enum.EasingStyle.Quad), {
            Position = UDim2.new((4166 - 4165), 0, 0, -(8582 - 8522))
        })
        lo0LLIiiilIli0:Play()
        lo0LLIiiilIli0.Completed:Wait()
        LLlilLO0IIIIo0:Destroy()
    end)
end


local function L01LIloIL0iI0o(l11OiiL1O0LLO1)
    local LLlooiOl1o1Il0 = IolOlIolo0OO1i:WaitForChild(_n64("UGxheWVyR3Vp"))
    local o1Ii001l0LOOo0 = LLlooiOl1o1Il0:FindFirstChild(_n64("QW5leGVkTm90aWZpY2F0aW9uVUk="))
    if not o1Ii001l0LOOo0 then
        o1Ii001l0LOOo0 = Instance.new(_n85(";e'iZASt\"\\B`"))
        o1Ii001l0LOOo0.IgnoreGuiInset = true
        o1Ii001l0LOOo0.Name = _n85("6#L7YARnPSFD5?$@psInDf/QH")
        o1Ii001l0LOOo0.ResetOnSpawn = false
        o1Ii001l0LOOo0.Parent = LLlooiOl1o1Il0
    end

    local LLlilLO0IIIIo0 = Instance.new(_n64("RnJhbWU="))
    LLlilLO0IIIIo0.Size = UDim2.new(0, (7374 - 7134), 0, (4811 - 4771))
    LLlilLO0IIIIo0.Position = UDim2.new((2792 - 2791), 0, 0, -(3965 - 3955))
    LLlilLO0IIIIo0.AnchorPoint = Vector2.new((6760 - 6759), 0)
    LLlilLO0IIIIo0.BackgroundTransparency = (6716 - 6715)
    LLlilLO0IIIIo0.BorderSizePixel = 0
    LLlilLO0IIIIo0.ZIndex = (989 - 969)
    LLlilLO0IIIIo0.Parent = o1Ii001l0LOOo0

    local ioilii0L11L0oi = Instance.new(_n85("<+U;r9OVCAC]"), LLlilLO0IIIIo0)
    ioilii0L11L0oi.Size = UDim2.new((1391 - 1390), -(4548 - 4528), (1513 - 1512), -(459 - 449))
    ioilii0L11L0oi.Position = UDim2.new(0, (2475 - 2465), 0, (7616 - 7611))
    ioilii0L11L0oi.BackgroundTransparency = (8430 - 8429)
    ioilii0L11L0oi.Text = _n64("QA==") .. l11OiiL1O0LLO1 .. _n85("+ELt*FWb45+DPh-DZ")
    ioilii0L11L0oi.TextColor3 = Color3.fromRGB((9214 - 8959), (7348 - 7228), (4188 - 4068))
    ioilii0L11L0oi.Font = Enum.Font.GothamBold
    ioilii0L11L0oi.TextSize = (1672 - 1658)
    ioilii0L11L0oi.TextXAlignment = Enum.TextXAlignment.Left

    local I1lOIiooOiiIIi = game:GetService(_n64("VHdlZW5TZXJ2aWNl"))
    local lIOlLOLoo10l1l = I1lOIiooOiiIIi:Create(LLlilLO0IIIIo0, TweenInfo.new((3359.4 - 3359), Enum.EasingStyle.Quart), {
        Position = UDim2.new((7506 - 7505), -(9039 - 9029), 0, (3067 - 3057))
    })
    lIOlLOLoo10l1l:Play()

    task.delay((2109 - 2106), function()
        local lo0LLIiiilIli0 = I1lOIiooOiiIIi:Create(LLlilLO0IIIIo0, TweenInfo.new((3712.3 - 3712), Enum.EasingStyle.Quad), {
            Position = UDim2.new((604 - 603), 0, 0, -(1167 - 1107))
        })
        lo0LLIiiilIli0:Play()
        lo0LLIiiilIli0.Completed:Wait()
        LLlilLO0IIIIo0:Destroy()
    end)
end


Iiii1ili1iiOOi:AddToggle({
    Name = _n64("VmlzdWFsaXphciAgSm9nYWRvcg=="),
    Callback = function(Value)
        iOi0ll0i0l11lI = Value
        if iOi0ll0i0l11lI then
            task.spawn(function()
                local oLIo1illLOlOil = false
                while iOi0ll0i0l11lI do
                    local iii1oOIoolLol1 = game.Players:FindFirstChild(LOIOOOololOLIl)
                    if iii1oOIoolLol1 then
                        if not oLIo1illLOlOil then
                            Oiol01il0iIiIO(iii1oOIoolLol1)
                            oLIo1illLOlOil = true
                        end
                        local o0iIIlioLLlIIL = iii1oOIoolLol1.Character or iii1oOIoolLol1.CharacterAdded:Wait()
                        local OLiol0OoilLio0 = o0iIIlioLLlIIL:FindFirstChild(_n85("89JcXDJs6\""))
                        if OLiol0OoilLio0 then
                            il0L1li0OiI110.CameraSubject = OLiol0OoilLio0
                        end
                    else
                        
                        L01LIloIL0iI0o(LOIOOOololOLIl)
                        iOi0ll0i0l11lI = false
                        local iLO1o0O10oOoLI = IolOlIolo0OO1i.Character
                        if iLO1o0O10oOoLI and iLO1o0O10oOoLI:FindFirstChild(_n64("SHVtYW5vaWQ=")) then
                            il0L1li0OiI110.CameraSubject = iLO1o0O10oOoLI.Humanoid
                        end
                        break
                    end
                    task.wait((4275.1 - 4275))
                end
            end)
        else
            local iLO1o0O10oOoLI = IolOlIolo0OO1i.Character
            if iLO1o0O10oOoLI and iLO1o0O10oOoLI:FindFirstChild(_n85("89JcXDJs6\"")) then
                il0L1li0OiI110.CameraSubject = iLO1o0O10oOoLI.Humanoid
            end
        end
    end
})

Iiii1ili1iiOOi:AddButton({
    Name = _n64("RW52aWFyIGNyaWFuw6dh"),
    Callback = function()
        if not LOIOOOololOLIl then
            warn(_n64("TmVuaHVtIGpvZ2Fkb3Igc2VsZWNpb25hZG8h"))
            return
        end

        local I0OOl00LLiO1lL = game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH"))
        local I0IilLlo1LO0O1 = I1IiOlIlIil1Oi:FindFirstChild(OOllIliO1LO0LI.Name)
        local IOO0o00L1li11i = I0IilLlo1LO0O1 and I0IilLlo1LO0O1:FindFirstChild(_n64("Rm9sbG93Q2hhcmFjdGVy"))

        
        if not IOO0o00L1li11i then
            local i111Looo1oIliO = {
                [(5869 - 5868)] = _n64("Q2hhcmFjdGVyRm9sbG93U3Bhd25QbGF5ZXI="),
                [(5837 - 5835)] = _n85("6=F>K6>q,")
            }

            pcall(function()
                I0OOl00LLiO1lL.RE:FindFirstChild(_n64("MUJhYjF5Rm9sbG8xdw==")):FireServer(unpack(i111Looo1oIliO))
            end)

            
            local OL0IllOIilIlLI = (2012 - 2009)
            local OIo0lllooIilil = tick()

            repeat
                task.wait((5268.1 - 5268))
                I0IilLlo1LO0O1 = I1IiOlIlIil1Oi:FindFirstChild(OOllIliO1LO0LI.Name)
                IOO0o00L1li11i = I0IilLlo1LO0O1 and I0IilLlo1LO0O1:FindFirstChild(_n64("Rm9sbG93Q2hhcmFjdGVy"))
            until IOO0o00L1li11i or tick() - OIo0lllooIilil > OL0IllOIilIlLI

            if not IOO0o00L1li11i then
                warn(_n64("Q3JpYW7Dp2EgbsOjbyBzcGF3bm91IGEgdGVtcG8u"))
                return
            end
        end

        
        if I0IilLlo1LO0O1 then
            for llLlo1lI11L0Oi, Lli1lO0oOli0ll in pairs(I0IilLlo1LO0O1:GetChildren()) do
                if Lli1lO0oOli0ll:IsA(_n64("QmFzZVBhcnQ=")) then
                    Lli1lO0oOli0ll.CanCollide = true
                end
            end
        end

        local iii1oOIoolLol1 = LOIOOOololOLIl 
        local I1l0o1lOO1O1OI = I1IiOlIlIil1Oi:FindFirstChild(iii1oOIoolLol1)

        if I1l0o1lOO1O1OI and IOO0o00L1li11i then
            IOO0o00L1li11i.Parent = I1l0o1lOO1O1OI

            
            if rawget(getgenv(), _n85(";KZkUATDs.@q>")) then
                getgenv().RunService:Disconnect()
                getgenv().RunService = nil
            end

            getgenv().RunService = game:GetService(_n85(";KZkUATDs.@q>")).Heartbeat:Connect(function()
                local IilOLII0oo0I1i = I1l0o1lOO1O1OI:FindFirstChild(_n64("Rm9sbG93Q2hhcmFjdGVy"))
                if IilOLII0oo0I1i 
                    and IilOLII0oo0I1i:FindFirstChild(_n64("VG9yc28="))
                    and IilOLII0oo0I1i.Torso:FindFirstChild(_n64("Qm9keVBvc2l0aW9u")) then

                    local liLOO11Iol0IiL = I1l0o1lOO1O1OI:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))

                    if liLOO11Iol0IiL then
                        IilOLII0oo0I1i.Torso.BodyPosition.Position =
                            liLOO11Iol0IiL.Position - (liLOO11Iol0IiL.CFrame.LookVector * (8778 - 8775))

                        if IilOLII0oo0I1i.Torso:FindFirstChild(_n85("6>pC[7sT,n")) then
                            IilOLII0oo0I1i.Torso.BodyGyro.CFrame = liLOO11Iol0IiL.CFrame
                        end
                    end
                end
            end)
        end
    end
})


Iiii1ili1iiOOi:AddButton({
    Name = _n64("UmV0b3JuYXIgY3JpYW7Dp2E="),
    Callback = function()
        if rawget(getgenv(), _n64("UnVuU2VydmljZQ==")) then
            getgenv().RunService:Disconnect()
            getgenv().RunService = nil
        end

        local i111Looo1oIliO = { [(8820 - 8819)] = _n85("6tL1GFCdp[Ci\"$66YKnK@:OCjEW") }
        local IllIlIi1Oo1IoO, i0io1IOOIIl0Ol = pcall(function()
            game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")).RE:FindFirstChild(_n85("0g];X0mQ6,Ci\"#EG5")):FireServer(unpack(i111Looo1oIliO))
        end)
        if not IllIlIi1Oo1IoO then
            warn(_n64("RXJybyBhbyByZXRvcm5hciBjcmlhbsOnYTog") .. i0io1IOOIIl0Ol)
        end

        local L1loIilL1oIOil = { [(4206 - 4205)] = _n85("6YKnK@:OCjE^jt`Ci=MrE+*s.:i'QcAT@"), [(7895 - 7893)] = _n64("QmFieUJveQ==") }
        IllIlIi1Oo1IoO, i0io1IOOIIl0Ol = pcall(function()
            game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH")).RE:FindFirstChild(_n85("0g];X0mQ6,Ci\"#EG5")):FireServer(unpack(L1loIilL1oIOil))
        end)
        if not IllIlIi1Oo1IoO then
            warn(_n64("RXJybyBhbyBzcGF3bmFyIGNyaWFuw6dhOiA=") .. i0io1IOOIIl0Ol)
        end
    end
})

Iiii1ili1iiOOi:AddSection({ Name = _n85("6:\"@:"), Icon = _n85("Eaj9%F)to7Bk07X0)") })


local function l1iOIOlIlIiIIi()
    local OOllIliO1LO0LI = game.Players.LocalPlayer
    local I0OOl00LLiO1lL = game:GetService(_n85(";Isf`Bk(RnARn_]DfT9!AH"))
    local I0IilLlo1LO0O1 = I1IiOlIlIil1Oi:FindFirstChild(OOllIliO1LO0LI.Name)
    local IOO0o00L1li11i = I0IilLlo1LO0O1 and I0IilLlo1LO0O1:FindFirstChild(_n64("Rm9sbG93Q2hhcmFjdGVy"))

    if not IOO0o00L1li11i then
        local i111Looo1oIliO = {
            [(7437 - 7436)] = _n64("Q2hhcmFjdGVyRm9sbG93U3Bhd25QbGF5ZXI="),
            [(8993 - 8991)] = _n85("6=F>K6>q,")
        }

        pcall(function()
            I0OOl00LLiO1lL.RE:FindFirstChild(_n64("MUJhYjF5Rm9sbG8xdw==")):FireServer(unpack(i111Looo1oIliO))
        end)

        
        local OL0IllOIilIlLI = (2889 - 2886)
        local OIo0lllooIilil = tick()
        repeat
            task.wait((8370.1 - 8370))
            I0IilLlo1LO0O1 = I1IiOlIlIil1Oi:FindFirstChild(OOllIliO1LO0LI.Name)
            IOO0o00L1li11i = I0IilLlo1LO0O1 and I0IilLlo1LO0O1:FindFirstChild(_n85("7W3*ZDg+Q^@<,ddFCfI"))
        until IOO0o00L1li11i or tick() - OIo0lllooIilil > OL0IllOIilIlLI

        if not IOO0o00L1li11i then
            warn(_n64("Q3JpYW7Dp2EgbsOjbyBzcGF3bm91IGEgdGVtcG8u"))
            return nil
        end
    end

    
    if I0IilLlo1LO0O1 then
        for llLlo1lI11L0Oi, Lli1lO0oOli0ll in pairs(I0IilLlo1LO0O1:GetChildren()) do
            if Lli1lO0oOli0ll:IsA(_n85("6=FqH:gnBd")) then
                Lli1lO0oOli0ll.CanCollide = true
            end
        end
    end

    return IOO0o00L1li11i
end

Iiii1ili1iiOOi:AddButton({
    Title = _n64("QkFORyBGQUNF"),
    Description = _n85(""),
    Callback = function()
        if not LOIOOOololOLIl then
            warn(_n64("TE9DNFQgSFVCOiBOZW5odW0gcGxheWVyIHNlbGVjaW9uYWRvIQ=="))
            return
        end

        local IOO0o00L1li11i = l1iOIOlIlIiIIi()
        if not IOO0o00L1li11i then return end

        local iii1oOIoolLol1 = LOIOOOololOLIl
        local lIol10l0I1o0Oo = game.Players.LocalPlayer
        local o0L0l01i1Ii00o = I1IiOlIlIil1Oi:FindFirstChild(iii1oOIoolLol1)
        local ii0OoioLLoOo1o = o0L0l01i1Ii00o and o0L0l01i1Ii00o:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
        if not o0L0l01i1Ii00o or not ii0OoioLLoOo1o then warn(_n85("9M\\#4<$4_36965g@<-!lF<GJ=￡￝ￗDI[U&FE1f#@3G")) return end

        IOO0o00L1li11i.Parent = I1IiOlIlIil1Oi
        local IIil1liiIO1Il0 = IOO0o00L1li11i:FindFirstChild(_n85("<,ZeuDZ"))
        if not IIil1liiIO1Il0 then warn(_n64("TE9DNFQgSFVCOiBUb3JzbyBuw6NvIGVuY29udHJhZG8h")) return end

        if getgenv().ChildFollowLoop then
            getgenv().ChildFollowLoop:Disconnect()
        end

        getgenv().ChildFollowLoop = game:GetService(_n85(";KZkUATDs.@q>")).Heartbeat:Connect(function()
            if not (o0L0l01i1Ii00o and o0L0l01i1Ii00o:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd")) and IIil1liiIO1Il0) then
                getgenv().ChildFollowLoop:Disconnect()
                return
            end

            local IliL1llOoi1OlI = o0L0l01i1Ii00o:FindFirstChild(_n64("SGVhZA=="))
            local ii0LilOol1oIOo
            if IliL1llOoi1OlI then
                ii0LilOol1oIOo = IliL1llOoi1OlI.Position + IliL1llOoi1OlI.CFrame.LookVector * (3407.1 - 3407)
            else
                ii0LilOol1oIOo = ii0OoioLLoOo1o.Position + ii0OoioLLoOo1o.CFrame.LookVector * (6033.1 - 6033)
            end

            local oIIIi0O1l0110o = ii0LilOol1oIOo + ii0OoioLLoOo1o.CFrame.LookVector * -(135.2 - 135)
            local Li0Iioiiiio1LI = ii0LilOol1oIOo + ii0OoioLLoOo1o.CFrame.LookVector * (6348.9 - 6346)

            local ll0O1LOoIl10i1 = tick() % (331 - 330)
            local LIoio0LOoO0i1O = math.abs(math.sin(ll0O1LOoIl10i1 * math.pi))
            local oIOILI0IIoOi0I = oIIIi0O1l0110o:Lerp(Li0Iioiiiio1LI, LIoio0LOoO0i1O)

            IIil1liiIO1Il0.BodyPosition.Position = oIOILI0IIoOi0I
            IIil1liiIO1Il0.BodyGyro.CFrame = CFrame.lookAt(IIil1liiIO1Il0.Position, ii0LilOol1oIOo)
        end)
    end
})

Iiii1ili1iiOOi:AddButton({
    Title = _n85("6:\"@:+@/t)￻￩￿￙6r+pk9NFp"),
    Description = _n85(""),
    Callback = function()
        if not LOIOOOololOLIl then
            warn(_n64("TE9DNFQgSFVCOiBOZW5odW0gcGxheWVyIHNlbGVjaW9uYWRvIQ=="))
            return
        end

        local IOO0o00L1li11i = l1iOIOlIlIiIIi()
        if not IOO0o00L1li11i then return end

        local iii1oOIoolLol1 = LOIOOOololOLIl
        local lIol10l0I1o0Oo = game.Players.LocalPlayer
        local o0L0l01i1Ii00o = I1IiOlIlIil1Oi:FindFirstChild(iii1oOIoolLol1)
        local ii0OoioLLoOo1o = o0L0l01i1Ii00o and o0L0l01i1Ii00o:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd"))
        if not o0L0l01i1Ii00o or not ii0OoioLLoOo1o then warn(_n85("9M\\#4<$4_36965g@<-!lF<GJ=￡￝ￗDI[U&FE1f#@3G")) return end

        IOO0o00L1li11i.Parent = I1IiOlIlIil1Oi
        local IIil1liiIO1Il0 = IOO0o00L1li11i:FindFirstChild(_n85("<,ZeuDZ"))
        if not IIil1liiIO1Il0 then warn(_n64("TE9DNFQgSFVCOiBUb3JzbyBuw6NvIGVuY29udHJhZG8h")) return end

        if getgenv().ChildFollowLoop then
            getgenv().ChildFollowLoop:Disconnect()
        end

        getgenv().ChildFollowLoop = game:GetService(_n85(";KZkUATDs.@q>")).Heartbeat:Connect(function()
            if not (o0L0l01i1Ii00o and o0L0l01i1Ii00o:FindFirstChild(_n85("89JcXDJs6\";K$Jq:gnBd")) and IIil1liiIO1Il0) then
                getgenv().ChildFollowLoop:Disconnect()
                return
            end

            local Iio1oLOlIoli0I = ii0OoioLLoOo1o.Position - ii0OoioLLoOo1o.CFrame.LookVector * (2581.1 - 2581)
            local oIIIi0O1l0110o = Iio1oLOlIoli0I - ii0OoioLLoOo1o.CFrame.LookVector * (5676.8 - 5674)
            local Li0Iioiiiio1LI = Iio1oLOlIoli0I - ii0OoioLLoOo1o.CFrame.LookVector * -(7857.2 - 7857)

            local ll0O1LOoIl10i1 = tick() % (1348 - 1347)
            local LIoio0LOoO0i1O = math.abs(math.sin(ll0O1LOoIl10i1 * math.pi))
            local oIOILI0IIoOi0I = oIIIi0O1l0110o:Lerp(Li0Iioiiiio1LI, LIoio0LOoO0i1O)

            IIil1liiIO1Il0.BodyPosition.Position = oIOILI0IIoOi0I
            IIil1liiIO1Il0.BodyGyro.CFrame = CFrame.lookAt(IIil1liiIO1Il0.Position, ii0OoioLLoOo1o.Position)
        end)
    end
})



                                          

local i1OioIIlOLill0 = olliLOIiIoIi0l:MakeTab({_n64("TXVzaWNhcw=="), _n64("bXVzaWM=")})


loadstring(game:HttpGet(_n64("aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL3BzeWNob1NBR0FaL01VU0lDL3JlZnMvaGVhZHMvbWFpbi9SRUFETUUubWQ=")))()

i1OioIIlOLill0:AddTextBox({
    Name = _n85("8OO\\3@3BE0F(o,m"),
    PlaceholderText = _n64("RGlnaXRlIG8gSUQ="),
    Callback = function(value)
        if value and value ~= _n85("") then
            tocarMusica(tostring(value))
        end
    end
})


local function iOlLOIlLi1l0LO(ioilii0L11L0oi, OlI0OoOoO0Loii, iLI0lOOl0O0L00)
    local oIi0o0100Li00i = {}
    local iLLoO00Il10I01 = {}
    for LiIlIO1o0011OO, IOLiIIiOO0oI0i in pairs(OlI0OoOoO0Loii) do
        for llLlo1lI11L0Oi, o10OIOOLLOol1o in ipairs(IOLiIIiOO0oI0i) do
            if o10OIOOLLOol1o.name ~= _n64("") then
                table.insert(oIi0o0100Li00i, o10OIOOLLOol1o.name)
                iLLoO00Il10I01[o10OIOOLLOol1o.name] = {II0llILLol10l0 = o10OIOOLLOol1o.id, LiIlIO1o0011OO = LiIlIO1o0011OO}
            end
        end
    end

    local function Oli1O0LoLoiL0o(LlliI1Lil0IL1L)
        tocarMusica(tostring(LlliI1Lil0IL1L)) 
    end

    
    i1OioIIlOLill0:AddDropdownSearch({
        Name = ioilii0L11L0oi,
        Description = _n85("@;K`"),
        Default = iLI0lOOl0O0L00,
        MultiSelect = false, 
        Options = oIi0o0100Li00i,
        Callback = function(selectedSound)
            if selectedSound and iLLoO00Il10I01[selectedSound] then
                local LlliI1Lil0IL1L = iLLoO00Il10I01[selectedSound].id
                if LlliI1Lil0IL1L and LlliI1Lil0IL1L ~= _n85("") and LlliI1Lil0IL1L ~= _n64("NDM1NDkwODU2OQ==") then
                    Oli1O0LoLoiL0o(LlliI1Lil0IL1L)
                end
            end
        end
    })
end


iOlLOIlLi1l0LO(_n64("Rm9ycm8="), {
    [_n64("Zm9ycm8=")] = {
        {oO0iOIo1loOI01 = _n85("C1/6)F_)\\4AKYQ%F(oN1FW`)$F*)>CEa`Ks.0"), II0llILLol10l0 = _n64("MTAyNTkzMTM0MTIxNzkz")},
        {oO0iOIo1loOI01 = _n64("b25saW5lIG1ldGVuZG8="), II0llILLol10l0 = _n85("3B&oQ2)@'J1GCUA2_Y")},
        {oO0iOIo1loOI01 = _n64("VGl0YW5pYw=="), II0llILLol10l0 = _n85("2`3EP3&ilW2_d*K2)k")},
        {oO0iOIo1loOI01 = _n85("6>psSA8,pp@3?seF*)>CEa`Ks.0"), II0llILLol10l0 = _n64("ODQ2MjQzMDE0MTE5MDk=")},
        {oO0iOIo1loOI01 = _n85(":/=h\\7S,s5￼ￏ!:EWJ377K^D8OPi"), II0llILLol10l0 = _n85("3A<0D2_m?H2)?sD2`(")},
        {oO0iOIo1loOI01 = _n85("DKTi,@3BW&El4RnAT["), II0llILLol10l0 = _n85("0etLD2_d'A0JYFC2)@#")},
        {oO0iOIo1loOI01 = _n64("Y2FkZWlyYQ=="), II0llILLol10l0 = _n64("OTY4ODgyMjg1MjUwNzM=")},
        {oO0iOIo1loOI01 = _n64("SU1QRVJGRUlUTyAoQlJFR0Ep"), II0llILLol10l0 = _n64("OTc2NjQ3MTc0OTMwNzc=")},
        {oO0iOIo1loOI01 = _n64("VmFpIFRvbWFyIEZsZWNoYWRh"), II0llILLol10l0 = _n64("MTM4MzQ1MDUwODE5MjI0")},
        {oO0iOIo1loOI01 = _n64("Qm9hdGUgQXp1bA=="), II0llILLol10l0 = _n85("0ebLB0etFA3AWHK2E!>")},
        {oO0iOIo1loOI01 = _n64("RXNxdWVtYSBjb25maXJtYWRv"), II0llILLol10l0 = _n64("MTM0MDM1Nzg4ODgxNzk2")},
        {oO0iOIo1loOI01 = _n85("5p/Np9Me\"t￼ￛ￫ￜ:K(1X"), II0llILLol10l0 = _n85("2_m-C1GUsJ2_[0G0fB")},
        {oO0iOIo1loOI01 = _n85("6tLGW￷￼￣@;-i_AT]+_DfT`6"), II0llILLol10l0 = _n64("MTE5NzM4ODc4OTIxOTk2")},
        {oO0iOIo1loOI01 = _n85("6#CO\\+A[,&9PJTh￾ "), II0llILLol10l0 = _n64("MTExNTUxMzYyNjM2MDYz")},
        {oO0iOIo1loOI01 = _n64("Rm9ycm8gSsOhIENhbnNvdQ=="), II0llILLol10l0 = _n64("NzQ4MTI3ODQ4ODQzMzA=")},
        {oO0iOIo1loOI01 = _n85("9P&'MEc3'dFMk(#88i6S"), II0llILLol10l0 = _n64("NzE1MzE1MzM1NTI4OTk=")},
        {oO0iOIo1loOI01 = _n85("6#C=KDZ"), II0llILLol10l0 = _n85("3AE6C3AEKI2_m3M0Jr")},
        {oO0iOIo1loOI01 = _n85("6#CO\\+BE&oA79\"[Bl\\+"), II0llILLol10l0 = _n85("0etOA2)R*H1bq!K0K1l")},
        {oO0iOIo1loOI01 = _n85("6>q-j+@L,j7W3<f "), II0llILLol10l0 = _n64("MTM5NDYyMjY4MDQ2Njc5")},
        {oO0iOIo1loOI01 = _n64("UXVlbSDDqSBvIExvdWNv"), II0llILLol10l0 = _n85("0ebLG2)mKM0JkLE2DR8")},
        {oO0iOIo1loOI01 = _n85(":M+2]<+ohc95/9V"), II0llILLol10l0 = _n85("0etF=1,LsI3AWBG1,L`")},
        {oO0iOIo1loOI01 = _n64("Rm9ycsOzIGRhIFJlc2VuaGE="), II0llILLol10l0 = _n85("0etFC2`!<H0JtX@1,1Z")},
        {oO0iOIo1loOI01 = _n64("Rm9ycsOzIGRvIER1ZHU="), II0llILLol10l0 = _n85("2`*?F1bgmJ0fM*O1G]")},
        {oO0iOIo1loOI01 = _n64("Rm9ycsOzIGRlIFPDo28gSm/Do28="), II0llILLol10l0 = _n64("MTA2MzY0ODc0OTM1MTk2")},
        {oO0iOIo1loOI01 = _n85("7W3<f ￨�DJ*uu￿￮￼D]hG^G%G]9Bk2,"), II0llILLol10l0 = _n85("2`<NK1bq'F1cR6H3B7")},
        {oO0iOIo1loOI01 = _n64("VW5vIFplcm8="), II0llILLol10l0 = _n64("MTEyOTU5MDgzODA4ODg3")},
        {oO0iOIo1loOI01 = _n85("8RZ^P+CoC5:1\\]f@<)"), II0llILLol10l0 = _n64("MTM1NzM4NTM0NzA2MDYz")},
        {oO0iOIo1loOI01 = _n64("QmF0aWTDo28gbmEgQWxkZWlh"), II0llILLol10l0 = _n85("2`WlU1H%6O2*!NO2`L")},
        {oO0iOIo1loOI01 = _n85("89JcfEc6)A+B)]c@UT"), II0llILLol10l0 = _n64("MTgzNjE3NTAzMA==")},
        {oO0iOIo1loOI01 = _n85(";djNP@3ANiDfBE#@;G"), II0llILLol10l0 = _n85("0fUsK3&ilU0JW")}
    }
}, _n64("T3B0aW9uIDE="))


iOlLOIlLi1l0LO(_n64("TcO6c2ljYXMgZSBNZW1lcyBBbGVhdG9yaW9z"), {
    [_n64("TcO6c2ljYXMgZSBNZW1lcyBBbGVhdG9yaW9z")] = {
        {oO0iOIo1loOI01 = _n64("QnVlbmEgbGEgdmlkYQ=="), II0llILLol10l0 = _n64("NzY2NTAzNTY0NzI2NTY=")},
        {oO0iOIo1loOI01 = _n64("SW5qdXN0acOnYQ=="), II0llILLol10l0 = _n64("MTI0OTg5NDA1MDg0ODgz")},
        {oO0iOIo1loOI01 = _n85("9keKY@3A<RD/XH'A76TU￾ 9k>G5D.+P]@;0c"), II0llILLol10l0 = _n64("MTM1MDkwMzA4NTQ0ODE5")},
        {oO0iOIo1loOI01 = _n64("R1RB"), II0llILLol10l0 = _n85("0ebUD1H.3O0JG7B1-%)")},
        {oO0iOIo1loOI01 = _n64("RXBzdGVpbg=="), II0llILLol10l0 = _n64("Nzk5MTAxOTU2MjAzNTY=")},
        {oO0iOIo1loOI01 = _n85(";b:(6;aj_U:*<#+:.l]f2Z"), II0llILLol10l0 = _n85("0f(gK3&!6H0fCsE1,1]")},
        {oO0iOIo1loOI01 = _n64("NjcgRlVOSyBTSVggU0VWRU4="), II0llILLol10l0 = _n85("0ekXC2E!KK3&`TL3B/n")},
        {oO0iOIo1loOI01 = _n85(":;`iF+B*3$+@fjc"), II0llILLol10l0 = _n64("ODI4MTY1ODcwNDM0NDM=")},
        {oO0iOIo1loOI01 = _n64("VW5pw6NvIEZsYXNjbw=="), II0llILLol10l0 = _n85("0ebOH3AE9F2*!BM3B/e")},
        {oO0iOIo1loOI01 = _n64("Q29pbg=="), II0llILLol10l0 = _n85("2`NcU3&EHO2`!EJ0fT")},
    	{ oO0iOIo1loOI01 = _n64("V2FudCBUbyBMb3Zl"), II0llILLol10l0 = (104846670980340 - 268) },
        {oO0iOIo1loOI01 = _n64("MzAgb3ZvcyAxMCByZWFpcw=="), II0llILLol10l0 = _n64("MzE0ODMyOTYzOA==")}
    }
}, _n85(":N1DiDf-[P"))


iOlLOIlLi1l0LO(_n64("VmliZSBUaXBvIEZlc3Rh"), {
    [_n85("<bZ#S+B3&oD]hM\\F*(g")] = {
        {oO0iOIo1loOI01 = _n64("S29vcF9Db2Q="), II0llILLol10l0 = _n85("2`NcW2`!6J3&`fO2)G")},
        {oO0iOIo1loOI01 = _n64("QmVsbGEgQ2lhbw=="), II0llILLol10l0 = _n64("MTIzNzk0MzAwOTk2ODI2")},
        {oO0iOIo1loOI01 = _n85("6=FbE+@9LSB-9NLDJ&"), II0llILLol10l0 = _n85("3A<3J3AE9J0f(LC3%t")},
        {oO0iOIo1loOI01 = _n64("Ym95"), II0llILLol10l0 = _n64("MTExODQxNDYwNjA0Nzc1")},
        {oO0iOIo1loOI01 = _n64("S2lzcyBNZQ=="), II0llILLol10l0 = _n85("0etRA3&iZR1bg[@3&38")},
        {oO0iOIo1loOI01 = _n64("dG9tYg=="), II0llILLol10l0 = _n64("MTQwNDQ3NDA4NDcyNDEx")},
        {oO0iOIo1loOI01 = _n64("Rm5hZg=="), II0llILLol10l0 = _n64("MTQwNDQ3NDA4NDcyNDEx")},
        {oO0iOIo1loOI01 = _n85("D0[7;ARTV$"), II0llILLol10l0 = _n64("ODI1NjExMjY5ODg4NTY=")},
        {oO0iOIo1loOI01 = _n64("Q3VkZGxlIG1lIEth"), II0llILLol10l0 = _n64("MTE2MzA4Nzg1NjU4NjE5")},
        {oO0iOIo1loOI01 = _n85("6pXa?:*=+YD,a%"), II0llILLol10l0 = _n85("0ebOA2DmEQ2D['I2)I#")},
        {oO0iOIo1loOI01 = _n85("87?RQBl[c-779i"), II0llILLol10l0 = _n64("OTQ5Mzk4NzgyOTQ1MzY=")},
        {oO0iOIo1loOI01 = _n64("SGF3bG93ZXI="), II0llILLol10l0 = _n85("0etLE1G^aA1bq!I0KCi")},
        {oO0iOIo1loOI01 = _n85("87?^YDg,c5+BC5"), II0llILLol10l0 = _n85("3A`WM2*!WQ3ANHJ2`:")},
        {oO0iOIo1loOI01 = _n85("Ch[Zr@;L-rH#i"), II0llILLol10l0 = _n64("MTIxODg4NTc3ODU3MzY1")},
        {oO0iOIo1loOI01 = _n64("TG93IENvcnRpc29s"), II0llILLol10l0 = _n64("MTEwOTE5MzkxMjI4ODIz")},
        {oO0iOIo1loOI01 = _n85("87?O]+Du*?Ap%t"), II0llILLol10l0 = _n64("OTc0MDEyMzM4NzYzMTM=")},
        {oO0iOIo1loOI01 = _n85("6=FqV+@:!bF*%"), II0llILLol10l0 = _n64("MTM2ODkzNDE4MzA3MTg1")},
        {oO0iOIo1loOI01 = _n64("TUVTTUVSSVpFUg=="), II0llILLol10l0 = _n85("2_d<K1c[HO1H@3I1H#")},
        {oO0iOIo1loOI01 = _n85("￼￮￸￬ ￖ ￿￹￺￻￾ￗ￸￩￳￟￳￙￠"), II0llILLol10l0 = _n64("NzY3OTA1ODExNjk0MjQ=")},
        {oO0iOIo1loOI01 = _n85(";JC5i@:Wdh<bZ)Q+Du*?:i'Qc+@U*XFE2;3F`(s"), II0llILLol10l0 = _n64("NzMzMjQwMjM3NjE2MzQ=")},
        {oO0iOIo1loOI01 = _n64("Uml0bWFkYSBTaGUnbGwgYmUgaGVyZSBEZXNhbmRl"), II0llILLol10l0 = _n85("0etLB2DI!I2E<KI2Dm2")},
        {oO0iOIo1loOI01 = _n64("4LmA4LiK4Li04LmJ4Lib4LmG"), II0llILLol10l0 = _n64("MTIwMzIyNTQ0MTI3MjQ5")},
        {oO0iOIo1loOI01 = _n64("S0FNTkggVkVMT0NJVFkgKFJEIFZFUlNJKSAyMDI1"), II0llILLol10l0 = _n64("MTMwNzIxMjA2NDAyNzE2")},
        {oO0iOIo1loOI01 = _n64("SFVBWUY="), II0llILLol10l0 = _n64("ODIxNTIxNzUwODk3MDM=")},
        {oO0iOIo1loOI01 = _n64("R2Fyb3RvIGRlIENvcGFjYWJhbmE="), II0llILLol10l0 = _n64("MTM1NjQ4NjM0MTEwMjU0")},
        {oO0iOIo1loOI01 = _n85("6>p9TG%kDs+D#C4<FTBYF^eb"), II0llILLol10l0 = _n64("MTM5MDU5MDYxNDkzNTU4")},
        {oO0iOIo1loOI01 = _n64("U0xJUCBBV0FZ"), II0llILLol10l0 = _n64("MTI2MTUyOTI4NTIwMTc0")},
        {oO0iOIo1loOI01 = _n64("UmFsbHkgR2lybA=="), II0llILLol10l0 = _n64("NzY4NDA0OTc1OTIzNDU=")},
        {oO0iOIo1loOI01 = _n64("QmVhdCAtIFN1bmZsb3dlcg=="), II0llILLol10l0 = _n64("MTI3MTE2MTcxMjM0NTA5")},
        {oO0iOIo1loOI01 = _n85("6:F1>+A#9n<)lgM"), II0llILLol10l0 = _n64("ODg0NDk2NDU5MjY5NjQ=")},
        {oO0iOIo1loOI01 = _n85("6=jSJFD5?0C]"), II0llILLol10l0 = _n85("3ArWO0K(U@3AiTP1,8")},
        {oO0iOIo1loOI01 = _n85("6=jSI+AucmEc6#<ARfgrG$t"), II0llILLol10l0 = _n85("3B9)S3B&fN2)I*L1Go")},
        {oO0iOIo1loOI01 = _n85("7U^@OBl@k"), II0llILLol10l0 = _n64("MTE2MDAzMjAzNDkwMDY0")},
        {oO0iOIo1loOI01 = _n85("<FL#m"), II0llILLol10l0 = _n85("3&!3F0JP:?2)$sL2E:")},
        {oO0iOIo1loOI01 = _n85("7U^1IF!,C=+@^'cAH"), II0llILLol10l0 = _n64("NzM3Nzg5ODU5NjM5NzM=")},
        {oO0iOIo1loOI01 = _n64("VGhlIHdoZWVscyBvbiB0aGUgYnVzIGdvIHJvdW5kIGFuZCByb3VuZCE="), II0llILLol10l0 = _n64("MTIzMjY4MDEzMDI2ODIz")},
        {oO0iOIo1loOI01 = _n85("BOQ!o+DkZ"), II0llILLol10l0 = _n85("0f(O?2`NWK1c@<O3ArS")},
        {oO0iOIo1loOI01 = _n85("C2%QuAS_"), II0llILLol10l0 = _n85("0ebC@1,:XB3&rrU0K1o")},
        {oO0iOIo1loOI01 = _n85("@;BXiAS$16H?q8!0QM2S"), II0llILLol10l0 = _n85("0ebFC2DHsG2`<ZN1-%5")},
        {oO0iOIo1loOI01 = _n64("VkVSMzMz"), II0llILLol10l0 = _n85("3A`HE0fLpC3B&]J3Ap")},
        {oO0iOIo1loOI01 = _n85("=(uPoATAn[Eb/[$BE"), II0llILLol10l0 = _n85("2`EKO1H.!E2`3TQ2),")},
        {oO0iOIo1loOI01 = _n64("TWluZWNyYWZ0"), II0llILLol10l0 = _n64("MTI2NzUzMDg2MTQ4NDMx")},
        {oO0iOIo1loOI01 = _n85("9LVo'=\\i$?7o'"), II0llILLol10l0 = _n64("NzE0MTAxMjMxNDc3MjM=")},
        {oO0iOIo1loOI01 = _n85(":gnBQA8-*r"), II0llILLol10l0 = _n85("0ebRE2).*F0etO=1,pu")},
        {oO0iOIo1loOI01 = _n85("=<L=HEbb"), II0llILLol10l0 = _n85("0f(dF3ANQR3&33H3B/b")},
        {oO0iOIo1loOI01 = _n64("RnJlZCBmcm9uIGRlbnNpcmU="), II0llILLol10l0 = _n64("ODQxODUxNTA3NjM0MDk=")},
        {oO0iOIo1loOI01 = _n85("6#:@4BkM+$"), II0llILLol10l0 = _n85("3B/fL0JbLA1H@EO1cY")},
        {oO0iOIo1loOI01 = _n85("9i\"M_<(0\\`"), II0llILLol10l0 = _n85("0f1R<1,1RB2`3<H1b^f")},
        {oO0iOIo1loOI01 = _n64("U2hpbmU="), II0llILLol10l0 = _n85("0ekR@1c[9L2)[6K1b^W")},
        {oO0iOIo1loOI01 = _n64("dGhlIHBlcmZlY3QgcGFpcg=="), II0llILLol10l0 = _n85("3AWQR3Ar]N3&`iX2)b")},
        {oO0iOIo1loOI01 = _n64("V2FybSBSb29t"), II0llILLol10l0 = _n64("NzcyNzU3MTg4NDU2NDE=")},
        {oO0iOIo1loOI01 = _n64("aSBsaWtlIHRyYWlucw=="), II0llILLol10l0 = _n85("3A`QI0JtOA1GUdF0Jr")},
        {oO0iOIo1loOI01 = _n85("2KNbSF<EV#"), II0llILLol10l0 = _n64("MTM0MTgzMDE0NzIxNDI5")},
        {oO0iOIo1loOI01 = _n85("7mTj<+AZ$,;?"), II0llILLol10l0 = _n64("MTM5OTgwODQyNzQwMDM5")},
        {oO0iOIo1loOI01 = _n85("6ZRHnFCAuR@<uJ"), II0llILLol10l0 = _n64("MTI4OTg2NDE0NzU5MTk0")},
        {oO0iOIo1loOI01 = _n64("U2Fk"), II0llILLol10l0 = _n64("MTI4NzUzNDIwNTk5MDQz")},
        {oO0iOIo1loOI01 = _n85("<,uPYFDYT,F<F7qG%C"), II0llILLol10l0 = _n64("NzY1OTEzMTI3Njc2NDM=")},
        {oO0iOIo1loOI01 = _n85("6uljID'2ngFCfI"), II0llILLol10l0 = _n85("2`<HH1,_-J2)$a>2)P")},
        {oO0iOIo1loOI01 = _n64("UHVsc2VGcmFtZQ=="), II0llILLol10l0 = _n64("NzI0Nzg0MjAxNDA3Nzg=")},
        {oO0iOIo1loOI01 = _n64("bmlnaHQgdHdv"), II0llILLol10l0 = _n64("MTE2NjI5MTAyMjQ5MjUx")},
        {oO0iOIo1loOI01 = _n64("U3VwZXJzaHkgQnV0"), II0llILLol10l0 = _n64("NzkwNzk5MzIxNzIyNjg=")},
        {oO0iOIo1loOI01 = _n64("OW1hcmU="), II0llILLol10l0 = _n85("0eb@;2_m<L1c7*J3&`_")},
        {oO0iOIo1loOI01 = _n85(":i'QXATV>"), II0llILLol10l0 = _n64("MTIxMjQyNDYyNTI3NjM2")},
        {oO0iOIo1loOI01 = _n85("@psG#+CT>*A7Y"), II0llILLol10l0 = _n85("0f([G1G^gI0f1XB3&NJ")},
        {oO0iOIo1loOI01 = _n85("7SGL;=&Ue0:&"), II0llILLol10l0 = _n85("3A`KN0fLgH3&`ZP1cG")},
        {oO0iOIo1loOI01 = _n85("96=lhFD5;t"), II0llILLol10l0 = _n85("3B8fO3AE<J3&`cS1H>")},
        {oO0iOIo1loOI01 = _n85("B5D^#@qb"), II0llILLol10l0 = _n85("0f(R@3AE<D2*!ZW2_m)")},
        {oO0iOIo1loOI01 = _n64("Y2hpbGwgYnJlYWtmYXN0"), II0llILLol10l0 = _n85("0etIA1GLU>0JP@<2*!S")},
        {oO0iOIo1loOI01 = _n64("cnVzc2lhbiB0ZWNoIGlzIG9r"), II0llILLol10l0 = _n64("MTI3MTk2NTg3MTEzNzAz")},
        {oO0iOIo1loOI01 = _n64("RmFpcnkgYW5kIENhdHM="), II0llILLol10l0 = _n85("0f([I0K1dJ1GpjB2*!J")},
        {oO0iOIo1loOI01 = _n85("H?j*"), II0llILLol10l0 = _n64("OTgyMDk5NjYwNjkyNjA=")},
        {oO0iOIo1loOI01 = _n85("=_2DcDg*<oCi=K."), II0llILLol10l0 = _n85("0ek[B3&`cV0eb:83B&q")},
        {oO0iOIo1loOI01 = _n85("<+oi4Ci=L"), II0llILLol10l0 = _n64("ODM5MTY3MzM5MDY0Nzg=")},
        {oO0iOIo1loOI01 = _n64("dmlydHVhbA=="), II0llILLol10l0 = _n64("MTIzOTg2MjcwMDE3ODQ3")},
        {oO0iOIo1loOI01 = _n64("VHJpc3RlemE="), II0llILLol10l0 = _n64("OTg4Mzk0NTM1MTAxNjE=")},
        {oO0iOIo1loOI01 = _n85("9mK9JD..'g"), II0llILLol10l0 = _n64("MTI1ODEyMjkzMTU1NjYx")},
        {oO0iOIo1loOI01 = _n85("FE2MFFDYR"), II0llILLol10l0 = _n64("ODE3MzIxMzcxNjM2ODY=")},
        {oO0iOIo1loOI01 = _n85("9keZi+F.mJ"), II0llILLol10l0 = _n85("3B/`Q1cI*G2)-dB2E:")},
        {oO0iOIo1loOI01 = _n64("aW4gbW90aW9u"), II0llILLol10l0 = _n85("3AEEO2Dm<O3&i`S3&C")},
        {oO0iOIo1loOI01 = _n85("DJs_"), II0llILLol10l0 = _n64("MTM3NjIxMjc2MjQyMjAz")},
        {oO0iOIo1loOI01 = _n85("D.RR&EbT*+"), II0llILLol10l0 = _n85("3&!*D0JPI?1,(C@3B.")},
        {oO0iOIo1loOI01 = _n64("QmFja3Jvb21z"), II0llILLol10l0 = _n64("MTIwODE3NDk0MTA3ODk4")},
        {oO0iOIo1loOI01 = _n64("U3RyYXk="), II0llILLol10l0 = _n64("MTIwMTAyOTk1NDQzMDYz")},
        {oO0iOIo1loOI01 = _n85("6\"qI[�￡￵￬￟+@U,i<oLZA"), II0llILLol10l0 = _n85("0ek[G3&roQ0Jb[F1c72")},
        {oO0iOIo1loOI01 = _n64("QU5YSUVUWSAoQW1hcGlhbm8gUmUtZml4KQ=="), II0llILLol10l0 = _n64("MTAxNDgzOTAxNDc1MTg5")},
        {oO0iOIo1loOI01 = _n64("TWVnYWxvdmFuaWEgYnV0IGl0cyBvbmx5IHRoZSBtZWxvZGllcw=="), II0llILLol10l0 = _n85("0ebFA0JG1@0ekR?1c@,")},
        {oO0iOIo1loOI01 = _n64("YW5kcm9waG9ubyBzdHJpa2VzIGJhY2s="), II0llILLol10l0 = _n85("2`NTJ1,([J3A`NP2E1")},
        {oO0iOIo1loOI01 = _n85("9Q+f]AKXBPD...\""), II0llILLol10l0 = _n85("0etRB2`NZL1,(RE2`<G")},
        {oO0iOIo1loOI01 = _n85("6Ua[B+T"), II0llILLol10l0 = _n85("0ekUF1GgjG2)mTR0K:o")},
        {oO0iOIo1loOI01 = _n85(";bTbZ+@0'p=T"), II0llILLol10l0 = _n64("MTI2MTUyOTI4NTIwMTc0")},
        {oO0iOIo1loOI01 = _n64("QWxvbmUgaW4gTW90aW9u"), II0llILLol10l0 = _n64("MTIyMzc5MzQ4Njk2OTQ4")},
        {oO0iOIo1loOI01 = _n85("7U]h=+@13[Gl"), II0llILLol10l0 = _n64("ODEwMDIxMzk3MzU4NzQ=")},
        {oO0iOIo1loOI01 = _n64("V291bmRzICYgV2lzaGVz"), II0llILLol10l0 = _n64("MTA5MzQ3OTc5NTY2NjA3")},
        {oO0iOIo1loOI01 = _n85("6$$OIDKE^jD]iS/+AHcl@<,jd"), II0llILLol10l0 = _n85("0eb=A2Dd0G1GCU@1,1K")},
        {oO0iOIo1loOI01 = _n85("9h@uX+AGF#<?Ogu<)Zdl70"), II0llILLol10l0 = _n85("0ekFB3&<EK0f1mK3AiY")},
        {oO0iOIo1loOI01 = _n64("QWly"), II0llILLol10l0 = _n64("NzMxOTc3NDg5NjEzNTk=")},
        {oO0iOIo1loOI01 = _n85("6Vg]W<(Th-;cH%\\;Z"), II0llILLol10l0 = _n85("0ekXJ2)d<I2)@!C2E!J")},
        {oO0iOIo1loOI01 = _n64("V2FyZHJvYmVGb3g="), II0llILLol10l0 = _n85("3&r`O3&!3F0fD!I1,o")},
        {oO0iOIo1loOI01 = _n64("QnVybmluZ1dvcmxk"), II0llILLol10l0 = _n64("MTExMzUxMzU3OTc4MDI3")},
        {oO0iOIo1loOI01 = _n85(";futPDf9L"), II0llILLol10l0 = _n64("OTE5OTU1OTg2OTk5MDE=")},
        {oO0iOIo1loOI01 = _n85("6#:@4BkM+$"), II0llILLol10l0 = _n85("3B/fL0JbLA1H@EO1cY")},
        {oO0iOIo1loOI01 = _n85(":2_7LDfTC"), II0llILLol10l0 = _n85("0fV!J1c76H0fB")},
        {oO0iOIo1loOI01 = _n64("U3RlcGhlbiBXYWxraW5nIC0gSkMtMDg="), II0llILLol10l0 = _n64("NzAyODk3MDM1OA==")},
        {oO0iOIo1loOI01 = _n64("Q29ucm8gLSBBbGwgSSBXYW50"), II0llILLol10l0 = _n64("NzAyMzY4MDQyNg==")},
        {oO0iOIo1loOI01 = _n64("R3JhbnQgLSBBcmUgV2UgU3RpbGwgWW91bmcgKGZlYXQuIEp1bmVhdSk="), II0llILLol10l0 = _n64("NTQxMDA4NjQ0NQ==")},
        {oO0iOIo1loOI01 = _n85(";flqqAR](cCEP2O7VQmS"), II0llILLol10l0 = _n85("2_[!H3B/lU1GJ")},
        {oO0iOIo1loOI01 = _n85(";K$JqCM@l5/Ke#$CM@[!+AHDi882^MAT@"), II0llILLol10l0 = _n64("NTQxMDA4MTU0Mg==")},
        {oO0iOIo1loOI01 = _n64("RHV1bXUgLSBGb3J3YXJkIChmZWF0LiBNSUEp"), II0llILLol10l0 = _n64("NTQxMDA4MTQ3MQ==")},
        {oO0iOIo1loOI01 = _n85("<,ZZ\"+B!,pATD3%/KdV-6Xaj[F8"), II0llILLol10l0 = _n64("NTQxMDA4MjgwNQ==")},
        {oO0iOIo1loOI01 = _n85("6Yp1FEZdb]+A?oqAH"), II0llILLol10l0 = _n64("MTgzODQ1NzYxNw==")},
        {oO0iOIo1loOI01 = _n64("RVVST1BBUEEgTE9VREVSISAoTmlnaHRjb3JlKQ=="), II0llILLol10l0 = _n85("0ekC=1c@'E1Gq!F2E<b")}
        
    }
}, _n85(":N1DiDf-[P"))


iOlLOIlLi1l0LO(_n85("7WiTa"), {
    [_n64("RnVuaw==")] = {
        {oO0iOIo1loOI01 = _n64("VmFpIFB1dGEgc3VhIGdvc3Rvc2E="), II0llILLol10l0 = _n85("3AE9E2)[?O1cRKN1bo")},
        {oO0iOIo1loOI01 = _n85(":2b;iDJ3G"), II0llILLol10l0 = _n85("3AiKI2DI!H2E3TT1cG")},
        {oO0iOIo1loOI01 = _n64("YmFsYSBubyBhY28="), II0llILLol10l0 = _n85("0etUC1,h0Q1H%'M1,_&")},
        {oO0iOIo1loOI01 = _n64("U2VtIFByZW9jdXBhw6fDo28="), II0llILLol10l0 = _n64("MTIyMTI2MTc3NjY2MTE3")},
        {oO0iOIo1loOI01 = _n64("UmVua25SZW5rIChFc3RvdXJhZG8p"), II0llILLol10l0 = _n85("0ebRF2_m6L3AE9G1cID")},
        {oO0iOIo1loOI01 = _n85("7;QBTCW!.p9P%p[@:Wdh-q/3!Dfp)/A8`m"), II0llILLol10l0 = _n85("3B/cL3&30A0JP7=2_b")},
        {oO0iOIo1loOI01 = _n85(":hb&d+B3&j+B2cb-q/3!Dfp)/A8`m"), II0llILLol10l0 = _n85("0f(gF1H@6G1,h*F1c7,")},
        {oO0iOIo1loOI01 = _n64("RXUgVm91IENvbWUgTm8gVW5v"), II0llILLol10l0 = _n64("ODIyODQ4MzI5NDgyMjI=")},
        {oO0iOIo1loOI01 = _n85("8oJ?N+@9R["), II0llILLol10l0 = _n85("0f(RD0K(pM2)dEK1H7/")},
        {oO0iOIo1loOI01 = _n85("6tpN]6tpN]6uQo"), II0llILLol10l0 = _n85("0f([A3A`QL3AWTJ2)mS")},
        {oO0iOIo1loOI01 = _n85("6Z6dZ@psC#6Z6dZ@psC#-q/3!Dfp)/A8`m"), II0llILLol10l0 = _n85("0ebF>1,_$N3AiNI0JkQ")},
        {oO0iOIo1loOI01 = _n64("QmFpbGUgKEVzdG91cmFkbyk="), II0llILLol10l0 = _n85("2`3HK0eb::1Gq!E0e`")},
        {oO0iOIo1loOI01 = _n85(";K$D`FWb6<8p+raATV>"), II0llILLol10l0 = _n64("ODY4MDMzNzk5MjMyODk=")},
        {oO0iOIo1loOI01 = _n64("UGlzY2EgWHJjIG5vIFBhcmFmYWw="), II0llILLol10l0 = _n85("2`NQL2_[!@2)I'D1,8")},
        {oO0iOIo1loOI01 = _n64("QWpvZWxoYSBDYWkgZGUgQmM="), II0llILLol10l0 = _n85("0et[A2)6pE0fUpG2DI2")},
        {oO0iOIo1loOI01 = _n85("<+-n9@<?'uA8`SbASGQq:2aigAH"), II0llILLol10l0 = _n85("0ebL@3&NTQ2E3]P1Gh)")},
        {oO0iOIo1loOI01 = _n85("<FTN[+AHcrDZ"), II0llILLol10l0 = _n85("0ekOE1-%3J3&<QT0K;&")},
        {oO0iOIo1loOI01 = _n64("w4kgbyBBbnRhcmVz"), II0llILLol10l0 = _n85("0eb:91G^gH1,C^D0K1o")},
        {oO0iOIo1loOI01 = _n85("6>psSDBM8aFCB%"), II0llILLol10l0 = _n64("NzQ5MDQ1ODU4NzA1OTU=")},
        {oO0iOIo1loOI01 = _n64("UGFudGFuYWw="), II0llILLol10l0 = _n64("OTQ4ODAxNTY1NDY3NzI=")},
        {oO0iOIo1loOI01 = _n85("G%#*!Bk_9qB`"), II0llILLol10l0 = _n85("0eb=>0f_6R0JtaI1,1c")},
        {oO0iOIo1loOI01 = _n64("ZmljYQ=="), II0llILLol10l0 = _n64("OTE1MDYzNjE4NjEwODY=")},
        {oO0iOIo1loOI01 = _n85("9kA3aAKX]]Ch[g*￾@/"), II0llILLol10l0 = _n64("MTQwNjAwNjQ5MjA0MjMz")},
        {oO0iOIo1loOI01 = _n85("6YLUZ@W*Aa@3@mHF8"), II0llILLol10l0 = _n64("MTMxNzQ4NDk4NzU5ODA2")},
        {oO0iOIo1loOI01 = _n64("c2hvd3c="), II0llILLol10l0 = _n85("0eb:A2E!<L3&iTH1-%/")},
        {oO0iOIo1loOI01 = _n85("8oJ?\\+@KW\\7q$4FEa\\"), II0llILLol10l0 = _n64("NzQzNjI5NjQ0OTU4OTA=")},
        {oO0iOIo1loOI01 = _n64("Sm9nYSBFc3NhIEJjdCBQbyBQY2M="), II0llILLol10l0 = _n64("MTMxOTM1MjI2NTY5MTQ3")},
        {oO0iOIo1loOI01 = _n85("<b6+j9m(8cATAn\\Df$V*+B)rlFC>"), II0llILLol10l0 = _n64("ODc2MDAxNDIzNDY2NjM=")},
        {oO0iOIo1loOI01 = _n64("ZmF6IG8gc2luYWw="), II0llILLol10l0 = _n85("0ebF?3&<EH2)d?L3B/t")},
        {oO0iOIo1loOI01 = _n85("@V'RoD.6pr+CoC5@;K@i"), II0llILLol10l0 = _n85("3&ruQ3B/lP1,CgG2E1")},
        {oO0iOIo1loOI01 = _n85(";H6Xd+@]@+9)"), II0llILLol10l0 = _n64("NzI0NTEyNzE5Mjg5NzU=")},
        {oO0iOIo1loOI01 = _n85(":dIoH9HZf):.k"), II0llILLol10l0 = _n64("NzY5ODE2MjUzMzIwNzk=")},
        {oO0iOIo1loOI01 = _n85("AKYl/+D,>*@;G"), II0llILLol10l0 = _n64("MTA3MjMwNDgwNDg4MDg1")},
        {oO0iOIo1loOI01 = _n64("TWFya2V0YWRh"), II0llILLol10l0 = _n85("0f(dG2)[3J3&E?D1c$u")},
        {oO0iOIo1loOI01 = _n85("7<;sWEcP`(@3B`%Bcq%sEc6&.-q/3!Dfp)/A8`m"), II0llILLol10l0 = _n64("NzUwNDg1NjUyMTk5NzI=")},
        {oO0iOIo1loOI01 = _n64("U2VuanUgU291bmRzIDE="), II0llILLol10l0 = _n85("0etUA2`<KO1,(XF1,1`")},
        {oO0iOIo1loOI01 = _n64("c2FkZA=="), II0llILLol10l0 = _n85("0f(O<0f(dI1,UsI3B/n")},
        {oO0iOIo1loOI01 = _n64("VHJvcGEgRG8gR29yZMOjbw=="), II0llILLol10l0 = _n85("3&<BF0KCsJ3&ilO1GA")},
        {oO0iOIo1loOI01 = _n85("<+R1>BOPar+Co%+6#CO\\"), II0llILLol10l0 = _n85("0ekC;0fUjF3&NEK1bgc")},
        {oO0iOIo1loOI01 = _n64("VGFwZXRlIE3DoWdpY28="), II0llILLol10l0 = _n85("0etL@3&ifT3B0#X0JbE")},
        {oO0iOIo1loOI01 = _n64("QXNzb21icmEgTWF0cml4"), II0llILLol10l0 = _n64("ODQ4MDY4NTg1NzUyOTI=")},
        {oO0iOIo1loOI01 = _n85("Ch7<'A8cN31FP\\5FDl;B@:X:*"), II0llILLol10l0 = _n85("0ekXC2`WZM3&EQN1,:W")},
        {oO0iOIo1loOI01 = _n64("KENvbnRlw7pkbyBFeHBsw61jaXRvKQ=="), II0llILLol10l0 = _n64("MTI5OTAyNzg0MDQwNzQx")},
        {oO0iOIo1loOI01 = _n85("ASbctAKYN%+EV=:D^]1<FDl2.A8`m"), II0llILLol10l0 = _n64("MTA4ODA4MDI1NTY1MTAz")},
        {oO0iOIo1loOI01 = _n64("U2FjYW5hZ2VtIChFc3RvcmFkbyk="), II0llILLol10l0 = _n85("0etR>2)I9J1,q6O3B/h")},
        {oO0iOIo1loOI01 = _n64("bWFyaWEgbWFyaWFoKEVzdG91cmFkbyk="), II0llILLol10l0 = _n64("MTEwMTA0OTAyMDg3OTA4")},
        {oO0iOIo1loOI01 = _n85("Ch7<'@;Z"), II0llILLol10l0 = _n64("OTE4NTMzNjg2MjIyMjU=")},
        {oO0iOIo1loOI01 = _n85(";bnN99gKn#<Dlg`8PVfB"), II0llILLol10l0 = _n85("0etL>2*!NK0JbI?3B/\\")},
        {oO0iOIo1loOI01 = _n85("D09Z:BlIm&@rHJ"), II0llILLol10l0 = _n64("MTM1NzUwNDMwODkyMTQ5")},
        {oO0iOIo1loOI01 = _n85("7ri`kD]hGZ+AcKZDe*D"), II0llILLol10l0 = _n64("MTEyMDg4MjA2NTA3NDU3")},
        {oO0iOIo1loOI01 = _n85(";Is<UCgeG_D]hkbB`"), II0llILLol10l0 = _n64("MTIwMDc1NTU5MjI2NzUy")},
        {oO0iOIo1loOI01 = _n85("C3=`:Bjl'*@q]9"), II0llILLol10l0 = _n85("3&`QP2)%!G1,_*O1G]")},
        {oO0iOIo1loOI01 = _n85("Des)q+CQC(G]7J;F(&u87<<QhF`Lo$D^b"), II0llILLol10l0 = _n64("MTIxMDc1MTE1NDE1MjQ1")},
        {oO0iOIo1loOI01 = _n64("RmlsbWluaG8gbmEgVGVsYQ=="), II0llILLol10l0 = _n85("0ekXH0JG:>0f_*O3B/t")},
        {oO0iOIo1loOI01 = _n85("E+s90CM@[\"@/"), II0llILLol10l0 = _n64("NzA3MjU2NTA4MjY2NTY=")},
        {oO0iOIo1loOI01 = _n64("QW1pZ3VpbmhhIEJlc3Q="), II0llILLol10l0 = _n85("0f(dC1,1dC1c[9I1Gpl")},
        {oO0iOIo1loOI01 = _n85("<)QLg5p/Ws:.k"), II0llILLol10l0 = _n64("MTI1Nzg0MzYzNDYzNDY2")},
        {oO0iOIo1loOI01 = _n64("Q09DT1RBIENMWFlBTCB4IENPTEQ="), II0llILLol10l0 = _n64("MTMwNzU4NTk2MjI3NzAy")},
        {oO0iOIo1loOI01 = _n64("Q2h1bWJvIG5hIEJjdA=="), II0llILLol10l0 = _n85("0f(OC1cR<P3&`]T3&!5")},
        {oO0iOIo1loOI01 = _n64("VHJ1cXVlIGRlIE1hZ2ljYQ=="), II0llILLol10l0 = _n64("MTE1Mjg2NTkwNTg3NjMw")},
        {oO0iOIo1loOI01 = _n64("dmlhZ2VtIG11bHRpdmVyc2Fs"), II0llILLol10l0 = _n85("3AWKJ1H7BK1H.$B1,f")},
        {oO0iOIo1loOI01 = _n85("9L2Fk￺ￜ￪￸73Ft8￾￫ￓ"), II0llILLol10l0 = _n85("0f(XE2)[3K3AiZJ1c$i")},
        {oO0iOIo1loOI01 = _n64("VGVuZWJyb3Nh"), II0llILLol10l0 = _n85("0eb=90etO=2)R?K1,1]")},
        {oO0iOIo1loOI01 = _n64("TWVpYSBOb2l0ZShFc3RvdXJhZG8p"), II0llILLol10l0 = _n64("MTMxMTg1NDM4MDc2NjM0")},
        {oO0iOIo1loOI01 = _n85(";0?Ge+AHDi8p+r_Dfm0N7WiTa.0"), II0llILLol10l0 = _n64("MTI4OTU4MDYzNDQ2MzM1")},
        {oO0iOIo1loOI01 = _n64("TGVhbCBBdMOpIG8gRmltIChGdW5rKQ=="), II0llILLol10l0 = _n85("0f(OB3&N]P2)mEO0fV&")},
        {oO0iOIo1loOI01 = _n64("U3VycmEgZGUgUGlyb2Nh"), II0llILLol10l0 = _n64("MTM5NTgyMTM4MTQzOTYw")},
        {oO0iOIo1loOI01 = _n64("ZWxldHJv"), II0llILLol10l0 = _n64("MTIyODcxNTUyMDE5Mjgz")},
        {oO0iOIo1loOI01 = _n85("9OVgL+B!-$AT@"), II0llILLol10l0 = _n64("OTM4OTYwMzMxMTU2NjA=")},
        {oO0iOIo1loOI01 = _n64("VmVtIFZlbSBtZSBGZGQ="), II0llILLol10l0 = _n64("MTM2NTc0MTYwMzA4ODA4")},
        {oO0iOIo1loOI01 = _n64("UGVybmEgYmFtYmE="), II0llILLol10l0 = _n85("3&W`P3&WZS2*!EK3&(")},
        {oO0iOIo1loOI01 = _n64("THV6IGRvIEx1YXI="), II0llILLol10l0 = _n64("MTM0NTA1OTg4MjM2NzMx")},
        {oO0iOIo1loOI01 = _n85("9kA$I+AQihFCcRC;Is]RCLnp"), II0llILLol10l0 = _n85("3&WZL2`*<H3&icU0f8")},
        {oO0iOIo1loOI01 = _n64("QmxhY2sgTGFuw6dhKEVzdG91cmFkbyk="), II0llILLol10l0 = _n64("OTc0NzE2MTM5OTgzNjg=")},
        {oO0iOIo1loOI01 = _n85("9kA3VDIFYdAKXfiAT2'u@/"), II0llILLol10l0 = _n64("MTEzMzkwNzM4OTM3NjEx")},
        {oO0iOIo1loOI01 = _n85("6=FSEAKYl/+AHcpEc1"), II0llILLol10l0 = _n64("MTM4MTg3ODI2Njk1MzM2")},
        {oO0iOIo1loOI01 = _n85("Eb0'0CB"), II0llILLol10l0 = _n85("3&iZL1,:O<1H7<N0K/")},
        {oO0iOIo1loOI01 = _n85("9uF)SFD56'"), II0llILLol10l0 = _n85("0etXG1G^mB2E<ZQ1bg]")},
        {oO0iOIo1loOI01 = _n64("TVRHIEFTU09NQlJBIE1BVFJJWCA4"), II0llILLol10l0 = _n85("2`<?J1GCdB2`NTP1G]")},
        {oO0iOIo1loOI01 = _n64("VG9tYSBUb21h"), II0llILLol10l0 = _n85("0f(aD2)I$J1c@-H1c7&")},
        {oO0iOIo1loOI01 = _n64("RW50IFZhaSBTZSBQcmVwYXJhcg=="), II0llILLol10l0 = _n64("Nzc0Mjg2MTY4NjY3NTM=")},
        {oO0iOIo1loOI01 = _n85("<,unr@3B*!+AuWiDZ"), II0llILLol10l0 = _n64("NzQ4ODUyMzE2MDcxMDk=")},
        {oO0iOIo1loOI01 = _n64("TUVMT0RJQSBBTFVDSU5BTlRFIDI="), II0llILLol10l0 = _n64("NzM0MTQ2MDIzMzY5NzE=")},
        {oO0iOIo1loOI01 = _n64("ZG9pcw=="), II0llILLol10l0 = _n64("MTIyMjkyODM3OTA0MTA1")},
        {oO0iOIo1loOI01 = _n64("Vm91IENvbWVyIFNldSBVYw=="), II0llILLol10l0 = _n64("NzU4Mzk1Mzg5MTc1Mjk=")},
        {oO0iOIo1loOI01 = _n64("T2ggSnVsaWFuYQ=="), II0llILLol10l0 = _n85("3&EEJ3B8cR3&!<G1H,")},
        {oO0iOIo1loOI01 = _n85(":h=9J+AHEi+@:!aARfW"), II0llILLol10l0 = _n64("MTM2NTE0ODY4NzMyMTM2")},
        {oO0iOIo1loOI01 = _n85("<,WmHDf$UnATDo96tLFPDg#]4DII'o"), II0llILLol10l0 = _n85("0ekOF1H.!E2D@!E2`!D")},
        {oO0iOIo1loOI01 = _n85("9kAGi87Wi1BOtm#A7ZlNDu"), II0llILLol10l0 = _n64("MTE4MzUxNDcxNzAyMjkz")},
        {oO0iOIo1loOI01 = _n64("Qmx1ZSBCaXJkIFRhbWJvciBieSBEem4="), II0llILLol10l0 = _n85("3&rfS1GLR;3ANKH0fB")},
        {oO0iOIo1loOI01 = _n85("7WiTa+AQ?cF`_O"), II0llILLol10l0 = _n85("3&rfS1GLR;3ANKH0fB")},
        {oO0iOIo1loOI01 = _n85(";dj*[Df0!(@/"), II0llILLol10l0 = _n64("MTIzODY4OTMzMDkxNzk1")},
        {oO0iOIo1loOI01 = _n64("aVBob25lIEJyYW5jbw=="), II0llILLol10l0 = _n64("MTAzMjg4NTU4NzMyMjE5")},
        {oO0iOIo1loOI01 = _n64("UGUgRGlyZWl0bw=="), II0llILLol10l0 = _n64("MTI3ODcwNjI5OTczMDY4")},
        {oO0iOIo1loOI01 = _n85("7U^.PF(oN*@/"), II0llILLol10l0 = _n85("0ekF?0K(mG2)d<O2`Wb")},
        {oO0iOIo1loOI01 = _n85("7U^Tc;fm%oE-,Z\"F(HIh@3A9YDJ3H$6Xah?"), II0llILLol10l0 = _n85("0et^B0ekXH0f(XC2)6o")},
        {oO0iOIo1loOI01 = _n64("VE9NQSBUT01BIFRPTUFORE8gKEZVTksgQVJST0NIQSk="), II0llILLol10l0 = _n85("3&iZO2E<KM0JbIC1,&")},
        {oO0iOIo1loOI01 = _n64("RU5DT1NUQSBGVU5L"), II0llILLol10l0 = _n85("0eb=;1,:aF1H@HN0JkT")},
        {oO0iOIo1loOI01 = _n85(":-hi%7TE2V"), II0llILLol10l0 = _n85("0ebOC0fD!O1H%*G2E3D")},
        {oO0iOIo1loOI01 = _n64("bWFyw6dvIHZpcA=="), II0llILLol10l0 = _n64("MTA0NDgxMzgwOTU5Nzk1")},
        {oO0iOIo1loOI01 = _n64("VGVudGFuZG8gRXRlZGVyIG8gcG9kZXIgZGVzc2EgZ3J0"), II0llILLol10l0 = _n85("0f(OD1cI*J1c[BJ3&EG")},
        {oO0iOIo1loOI01 = _n85("6ul^O+@^0cG5"), II0llILLol10l0 = _n85("2`WTJ0K(aC3&EWL0f]")},
        {oO0iOIo1loOI01 = _n64("UmF2ZSBuYW5haA=="), II0llILLol10l0 = _n85("0ek[B1,(I>2)dNN1c$f")},
        {oO0iOIo1loOI01 = _n85("D/X<6@:s.g+CoC5F(oH6Bl<"), II0llILLol10l0 = _n85("0ebFD1,q'H1GCLC1-%5")},
        {oO0iOIo1loOI01 = _n64("bW9udGFnZW0gaW50ZXJnYWzDoWN0aWNh"), II0llILLol10l0 = _n64("MTIyMDM5MTA3NTI4MjM4")},
        {oO0iOIo1loOI01 = _n64("UGFuY2Fkw6Nv"), II0llILLol10l0 = _n85("2`<HH1-%?L0fV'I3&C")},
        {oO0iOIo1loOI01 = _n64("UkFUSU9OQUw="), II0llILLol10l0 = _n85("2`!BO1c$pB0KCpD1GS")},
        {oO0iOIo1loOI01 = _n85("7;X/XAU7p)@WHB0A7ZlC0d%l<G^:e"), II0llILLol10l0 = _n85("3ANEO1,(LE2)@'F3B7")},
        {oO0iOIo1loOI01 = _n64("Y2FzdCBhc2lkZQ=="), II0llILLol10l0 = _n64("MTM1NzMzMzkxNDI0ODUz")},
        {oO0iOIo1loOI01 = _n64("U2V1IEbDow=="), II0llILLol10l0 = _n64("ODUzNDIwODYwODIxMTE=")},
        {oO0iOIo1loOI01 = _n85("9kA3`@:s.g"), II0llILLol10l0 = _n64("MTMwNjM3NDU4NDgwNjA0")},
        {oO0iOIo1loOI01 = _n85("6t'uN￷￼D]hDUDJ+*4FT"), II0llILLol10l0 = _n85("3&W`T2DI!G0f_!D2)b")},
        {oO0iOIo1loOI01 = _n85("￼ￛ￫ￔ<D5nK+AP3F<`B"), II0llILLol10l0 = _n64("MTMxODkxMTEwMjY4MzUy")},
        {oO0iOIo1loOI01 = _n85("6WR)Y"), II0llILLol10l0 = _n64("MTI0MjQ0NTgyOTUwNTk1")},
        {oO0iOIo1loOI01 = _n85("9i\"M`5t=@<+@/mk6:jI<5l"), II0llILLol10l0 = _n85("2`NKM2E!<I0KCjA3B.")},
        {oO0iOIo1loOI01 = _n85("6?6XM@3ATbDes-*D]gGpART['6?6XM@3A$^DJL["), II0llILLol10l0 = _n85("3B8lU3Ar]M1,(OD0JN")},
        {oO0iOIo1loOI01 = _n64("Vml2ZXIgYmVt"), II0llILLol10l0 = _n64("ODI4MDU0NjA0OTQzMjU=")},
        {oO0iOIo1loOI01 = _n64("Uml0bW8gUGl4ZWxhZG8gKE5HSSk="), II0llILLol10l0 = _n64("OTM5Mjg4MjM4NjIyMDM=")},
        {oO0iOIo1loOI01 = _n85(";ajG\\5p.RN7nFgM+BV;d"), II0llILLol10l0 = _n85("0etR>3&NNJ1,:dH2`!2")},
        {oO0iOIo1loOI01 = _n85("<];-L=A0ha+APEu.0"), II0llILLol10l0 = _n64("ODAzNDg2NDA4MjY2NDM=")}
    }
}, _n85(":N1DiDf-[P"))


iOlLOIlLi1l0LO(_n64("UGhvbms="), {
    [_n64("cGhvbms=")] = {
        {oO0iOIo1loOI01 = _n85("6tp:JFCAubH#R<"), II0llILLol10l0 = _n85("3A`]S0f1XE1,LaD3B7")},
        {oO0iOIo1loOI01 = _n64("YnJpZ2FkZWlybw=="), II0llILLol10l0 = _n64("MTIxMDQ2NjU1NTIzMzQx")},
        {oO0iOIo1loOI01 = _n64("TW9udGFnZW0gQmlvbmljYSA="), II0llILLol10l0 = _n85("0etI;1c@6L2)R-F1Ggf")},
        {oO0iOIo1loOI01 = _n85("9i\"M`5t=@<+AGF,;FO8T7nH'D+C]U=@r-C8@;G"), II0llILLol10l0 = _n85("0ebOD0f(RE2*!TU0K:`")},
        {oO0iOIo1loOI01 = _n85("<Cp1V80@"), II0llILLol10l0 = _n85("3&3HR1c%'K2`!BP1cY")},
        {oO0iOIo1loOI01 = _n64("TU9OVEFHRU0gQU1PUiBTRU0gRklOQUw="), II0llILLol10l0 = _n85("0et[A1H7<J1c7*L1Gq/")},
        {oO0iOIo1loOI01 = _n85("78m#O6W?rL9E"), II0llILLol10l0 = _n64("MTE5MjAyNzAwNzYwMTY5")},
        {oO0iOIo1loOI01 = _n85("6WI)S9gMEH5t`=i<DH10-rXr#G@b;6"), II0llILLol10l0 = _n64("MTIwODcxNDAzOTIyOTcy")},
        {oO0iOIo1loOI01 = _n85(";e9igD]iU69k>G5@prhb"), II0llILLol10l0 = _n85("0etR?1b^X>2)7$F1Ggu")},
        {oO0iOIo1loOI01 = _n64("V3lsZXM="), II0llILLol10l0 = _n64("ODUzODUxNTU5NzA0NjA=")},
        {oO0iOIo1loOI01 = _n64("U09VUiBQQVRDSCBLSURT"), II0llILLol10l0 = _n85("3AEBF1,L^>0etI?1H5")},
        {oO0iOIo1loOI01 = _n64("TU9OVEFHRU0gUE9DSyBQT0NL"), II0llILLol10l0 = _n85("0eb@=1G^jB3A<3E1H7,")},
        {oO0iOIo1loOI01 = _n64("VGF0aXUgV2lu"), II0llILLol10l0 = _n64("MTIyODcxNTEyMzUzNTIw")},
        {oO0iOIo1loOI01 = _n85(";eTuUGp*"), II0llILLol10l0 = _n85("0etXH3&`QK1bh!E3&*/")},
        {oO0iOIo1loOI01 = _n85("5ugl[9i\"_[<_ji58Ol<N+>\"^7E+NQ&<H%"), II0llILLol10l0 = _n64("MTE1MDE2NTg5Mzc2NzAw")},
        {oO0iOIo1loOI01 = _n64("RElTVE9SVElPTiBGVU5L"), II0llILLol10l0 = _n85("0ekXH1b^jB3&`]R2E3P")},
        {oO0iOIo1loOI01 = _n64("KFNMT1dFRCkgRElTVE9SVElPTiBGVU5L"), II0llILLol10l0 = _n85("0ebI>1,^gE2)$aA0JbN")},
        {oO0iOIo1loOI01 = _n64("RkVNSU5JTk8gRE8gVkFQTyBGVU5L"), II0llILLol10l0 = _n85("0ebLA0fLgH1c@0I1H@8")},
        {oO0iOIo1loOI01 = _n64("RlVOSyBEQSBQUkFJQSAtIFNsb3dlZA=="), II0llILLol10l0 = _n64("MTEyMDY4ODkyNzIxNDA4")},
        {oO0iOIo1loOI01 = _n85("5ugl[9i\"_[<_ji58Ol<N/Q6e2ATAnlCi=N/A,"), II0llILLol10l0 = _n64("MTIyODUyMDI5MDk0NjU2")},
        {oO0iOIo1loOI01 = _n64("TGliZXJ0byBGdW5r"), II0llILLol10l0 = _n64("ODQ3MzM3MzYwNDgxNDI=")},
        {oO0iOIo1loOI01 = _n64("SFlQTk9USVpFRCEgKFNwZWQgVXAp"), II0llILLol10l0 = _n64("OTIxNzU2MjQ2NDM2MjA=")},
        {oO0iOIo1loOI01 = _n85("5u^QS;c$\"R;FsMI+@]@+9)"), II0llILLol10l0 = _n85("2`E]R2`*NQ3&33J1c,")},
        {oO0iOIo1loOI01 = _n64("Q2F0dXF1YW52YW4gKE5HSSk="), II0llILLol10l0 = _n85("3&iTJ3&N]R2E!?H0ei")},
        {oO0iOIo1loOI01 = _n64("SSBMb3Zl"), II0llILLol10l0 = _n85("3&33F3&riP2_d0I3Ag")},
        {oO0iOIo1loOI01 = _n85("9i\"M`5t=@<+@]@15sdj"), II0llILLol10l0 = _n85("3AEKL1c@-F2E<HM0e`")},
        {oO0iOIo1loOI01 = _n64("R09USCBGVU5L"), II0llILLol10l0 = _n64("OTc2NjIzNjIyMjY1MTE=")},
        {oO0iOIo1loOI01 = _n85("9i\"M`5t=@<+B)9,<Dl.L:-e"), II0llILLol10l0 = _n64("MTM5ODI1MDU3ODk0NTY4")},
        {oO0iOIo1loOI01 = _n64("TGliZXJ0byBGdW5rKFNsb3dlZCk="), II0llILLol10l0 = _n64("ODQ3MzM3MzYwNDgxNDI=")},
        {oO0iOIo1loOI01 = _n64("SnVtcHN0eWxl"), II0llILLol10l0 = _n64("MTgzOTI0NjcxMQ==")},
        {oO0iOIo1loOI01 = _n85("6>U4SF(Jl)9jqpN"), II0llILLol10l0 = _n85("0fD!I0ek@A1H@5")},
        {oO0iOIo1loOI01 = _n85("9lFok@:s.g+@9LQ@:We-"), II0llILLol10l0 = _n64("ODM3OTc4MzY4MTg4NTc=")},
        {oO0iOIo1loOI01 = _n85("6:FTk;bp(d:EVu%6!?iR+T"), II0llILLol10l0 = _n64("MTE5OTM2MTM5OTI1NDg2")},
        {oO0iOIo1loOI01 = _n85("94`-^F(K6#"), II0llILLol10l0 = _n64("MTc2NDczMjIyMjY=")}
    }
}, _n64("T3B0aW9uIDE="))

i1OioIIlOLill0:AddButton({
    Name = _n64("U3RvcA=="),
    Description = _n85("5tjrpD09o6@f"),
    Callback = function()
        tocarMusica(_n85(""))
    end
})



                                          

local LL0Ioo111iILlL = olliLOIiIoIi0l:MakeTab({_n64("U2NyaXB0cyA="), _n64("Y29kZQ==")})

LL0Ioo111iILlL:AddSection({ Name = _n64("QXByaW1vcmFtZW50b3M=") })

LL0Ioo111iILlL:AddButton({
    Name = _n64("RkUgRW1vdGVzIFNBR0FaeA=="),
    Description = _n64(""),
    Callback = function()
        loadstring(game:HttpGet(_n85("BQS?8F#ks-Eaa/EB5)I$F^fK7ATD:!DKKH-F=q'AD(fjLH\"1N+;aEo>=t`f?7mU='/P&l.061W9F\"_3<@:XF4D..-r01JAV1,).6DffQ3,r./bD^@.m;aEo>>'M>K0M#21")))()
    end
})

LL0Ioo111iILlL:AddButton({
    Name = _n85("7<ic[DIak\\DffGsEW"),
    Description = _n64("RXhwYW5kZSBTdWEgSG90YmFyIGRlIDEwIEF0ZSAyMCBTbG90cw=="),
    Callback = function()
        loadstring(game:HttpGet(_n85("BQS?8F#ks-Eaa/EB5)I$F^fK7ATD:!DKKH-F=q'AD(fjLH\"1N+;aEo>=t`f?7mU='/P&l.061W9F\"_3<@:XF4D..-r01C,)@;]U%1,)7;FCJ[!,r..")))()
    end
})

LL0Ioo111iILlL:AddButton({
    Name = _n64("SW50ZXJmYWNlIGRlIEJvdMO1ZXMgQW50aWdhcyBkbyBCcm9va2hhdmVuKElycmV2ZXJzw612ZWwp"),
    Description = _n85("9kA$W+@:3`@:X9"),
    Callback = function()
        
        
        
        if _G.ScriptJaExecutado then
            warn(_n64("TyBzY3JpcHQgasOhIGZvaSBleGVjdXRhZG8hIElnbm9yYW5kbyBub3ZhIGV4ZWN1w6fDo28u"))
            return
        end
        _G.ScriptJaExecutado = true

        local OoLloI0LI1OOlO = game:GetService(_n85(":i'QcATDh"))
        local OOllIliO1LO0LI = OoLloI0LI1OOlO.LocalPlayer
        local loL1I11Iio0IOi = OOllIliO1LO0LI:WaitForChild(_n85(":i'QcATC:`B`"))
        local LOioLol1oooi10 = loL1I11Iio0IOi:WaitForChild(_n64("TWFpbkdVSUhhbmRsZXI="))
        local iIiIiOlioLOo1i = LOioLol1oooi10:WaitForChild(_n64("TWFpbkJ1dHRvbnM="))
        local o000l1IiO0o10o = loL1I11Iio0IOi:WaitForChild(_n64("Tm9SZXNldEdVSUhhbmRsZXI="))

        
        local Oo11ILOLL1I11L = iIiIiOlioLOo1i:FindFirstChild(_n85(":1\\V"))
        if Oo11ILOLL1I11L then
            Oo11ILOLL1I11L.Visible = false
        end

        
        
        
        local oI1oLI01OooO0o = {
            {_n85(":2a$AF(KG`<Co_iDIdQpEW"), _n85("6YKnK@:OCjE`?^`D.QFQDKP"), _n85("6Xb(FCi<q"), _n85("87c4?AT@"), _n85("6Xb(JB5_g9<+06W"), _n64("MDA1Q2xvc2U=")},
            {_n85(":2a$AF(KG`<Co_iDIdQpEW"), _n85("6YKnK@:OCjE_^%[APH`RFT"), _n85("6Xb(FCi<q"), _n64("SGVhZGVy"), _n85("6Xb(JB5_g9<+06W"), _n85("0JG@OCi=B+")},
            {_n64("Tm9SZXNldEdVSUhhbmRsZXI="), _n85("6YKnK@:OCjE_:7Z9kA3b"), _n64("Q2F0YWxvZw=="), _n85("87c4?AT@"), _n85("6Xb(JB5_g9<+06W"), _n64("MDA1Q2xvc2U=")},
            {_n85(":2a$AF(KG`<Co_iDIdQpEW"), _n64("UGV0c0tpZHNNZW51"), _n64("Q2F0YWxvZw=="), _n85("87c4?AT@"), _n64("Q2F0ZWdvcnlUYWJz"), _n64("MDA1Q2xvc2U=")}
        }

        for llLlo1lI11L0Oi, o1L0oliOoOil11 in ipairs(oI1oLI01OooO0o) do
            local li01IOio0OLo1i = loL1I11Iio0IOi
            for llLlo1lI11L0Oi, lll1Ii1li0i0o0 in ipairs(o1L0oliOoOil11) do
                if li01IOio0OLo1i then
                    li01IOio0OLo1i = li01IOio0OLo1i:FindFirstChild(lll1Ii1li0i0o0)
                end
            end
            if li01IOio0OLo1i then
                li01IOio0OLo1i:Destroy()
            end
        end

        
        
        
        local LLOiolllI01Iii = o000l1IiO0o10o:FindFirstChild(_n64("UGV0c0tpZHNNZW51"))
            and o000l1IiO0o10o.PetsKidsMenu:FindFirstChild(_n64("Q2F0YWxvZw=="))
            and o000l1IiO0o10o.PetsKidsMenu.Catalog:FindFirstChild(_n85("87c4?AT@"))
            and o000l1IiO0o10o.PetsKidsMenu.Catalog.Header:FindFirstChild(_n85("6Xb(JB5_g9<+06W"))

        if LLOiolllI01Iii then
            LLOiolllI01Iii.Size = UDim2.new(0, (1018 - 718), 0, (2668 - 2639))
            LLOiolllI01Iii.Position = UDim2.new(0, (2756 - 2746), 0, (1501 - 1483))

            local L10o0Lli1Loi00 = LLOiolllI01Iii:FindFirstChildOfClass(_n64("VUlMaXN0TGF5b3V0"))
            if L10o0Lli1Loi00 then
                L10o0Lli1Loi00.HorizontalAlignment = Enum.HorizontalAlignment.Center
                L10o0Lli1Loi00.VerticalAlignment = Enum.VerticalAlignment.Center
            end
        end

        
        
        
        local IIiIOLlOl1LOI1 = {
            o000l1IiO0o10o:FindFirstChild(_n64("UGV0c0tpZHNNZW51")),
            o000l1IiO0o10o:FindFirstChild(_n64("Q2hhcmFjdGVyVGhlbWVNZW51")),
            o000l1IiO0o10o:FindFirstChild(_n64("Q2hhcmFjdGVyTmFtZU1lbnU=")),
            o000l1IiO0o10o:FindFirstChild(_n85("6YKnK@:OCjE_:7Z9kA3b"))
        }

        local function o001IoO0O00100()
            for llLlo1lI11L0Oi, O0lLo1OlII1lLL in ipairs(IIiIOLlOl1LOI1) do
                if O0lLo1OlII1lLL then
                    O0lLo1OlII1lLL.Visible = false
                end
            end
        end

        
        local OOOOLlL1OoIiIl = o000l1IiO0o10o:FindFirstChild(_n64("Q2hhcmFjdGVyTmFtZU1lbnU="))

        
        for llLlo1lI11L0Oi, O0lLo1OlII1lLL in ipairs(IIiIOLlOl1LOI1) do
            if O0lLo1OlII1lLL then
                O0lLo1OlII1lLL:GetPropertyChangedSignal(_n85("<bZVh@VfT")):Connect(function()
                    if O0lLo1OlII1lLL.Visible then
                        OOOOLlL1OoIiIl = O0lLo1OlII1lLL
                    end
                end)
            end
        end

        
        
        
        if iIiIiOlioLOo1i:FindFirstChild(_n64("RnJhbWVQYWlDdXN0b20=")) then
            iIiIiOlioLOo1i.FramePaiCustom:Destroy()
        end

        local iloOO1ilo1L1Io = Instance.new(_n64("RnJhbWU="))
        iloOO1ilo1L1Io.Name = _n85("7WMpSAPcfL6ZmHlDf#")
        iloOO1ilo1L1Io.Size = UDim2.new((7514 - 7513), 0, (5059 - 5058), 0)
        iloOO1ilo1L1Io.Active = false
        iloOO1ilo1L1Io.BackgroundTransparency = (8796 - 8795)
        iloOO1ilo1L1Io.Parent = iIiIiOlioLOo1i

        local llo1Ol1oI1OllI = Instance.new(_n85("7WMpSAH"))
        llo1Ol1oI1OllI.Name = _n64("RnJhbWVGaWxob0N1c3RvbQ==")
        llo1Ol1oI1OllI.Size = UDim2.new(0, (4016 - 3946), 0, (9044 - 8644))
        llo1Ol1oI1OllI.AnchorPoint = Vector2.new((1239 - 1238), 0)
        llo1Ol1oI1OllI.Position = UDim2.new((3451 - 3450), 0, 0, 0)
        llo1Ol1oI1OllI.BackgroundTransparency = (3829 - 3828)
        llo1Ol1oI1OllI.Parent = iloOO1ilo1L1Io

        
        
        
        local LO0oLOOLlii10L = nil
        local Oi101L11O1Iiil = Oo11ILOLL1I11L 
            and Oo11ILOLL1I11L:FindFirstChild(_n64("RnJhbWU=")) 
            and Oo11ILOLL1I11L.Frame:FindFirstChild(_n85("7WMpSAH")) 
            and Oo11ILOLL1I11L.Frame.Frame:FindFirstChild(_n64("U2xpZGU="))

        if Oi101L11O1Iiil then
            LO0oLOOLlii10L = Oi101L11O1Iiil:Clone()
            LO0oLOOLlii10L.Size = UDim2.new(0, (2632 - 2332), 0, (556 - 496))
            LO0oLOOLlii10L.Position = UDim2.new(0, (9587 - 8874), 0, (5689 - 5664))
            LO0oLOOLlii10L.Visible = false
            LO0oLOOLlii10L.Parent = iloOO1ilo1L1Io

            local oolL01OloLlI01 = LO0oLOOLlii10L:FindFirstChildOfClass(_n64("VUlHcmlkTGF5b3V0"))
            if oolL01OloLlI01 then
                oolL01OloLlI01.CellSize = UDim2.new(0, (1807 - 1737), 0, (5693 - 5643))
                oolL01OloLlI01.FillDirection = Enum.FillDirection.Vertical
                oolL01OloLlI01.FillDirectionMaxCells = (1855 - 1854)
            end

            
            local i10i1LlOIlILlI = Instance.new(_n64("SW1hZ2VCdXR0b24="))
            i10i1LlOIlILlI.Name = _n85(">$js3F*(>sBk1dAF`__DD?")
            i10i1LlOIlILlI.LayoutOrder = (1000251 - 252)
            i10i1LlOIlILlI.BackgroundColor3 = Color3.fromRGB((836 - 666), 0, 0)
            i10i1LlOIlILlI.BackgroundTransparency = (7030.3 - 7030)
            i10i1LlOIlILlI.Parent = LO0oLOOLlii10L

            local l01iioLoLLI1Ii = Instance.new(_n85("<CoPrEc,H/"))
            l01iioLoLLI1Ii.CornerRadius = UDim.new(0, (7583 - 7575))
            l01iioLoLLI1Ii.Parent = i10i1LlOIlILlI

            local oLoOIooO0OOll0 = Instance.new(_n64("SW1hZ2VMYWJlbA=="))
            oLoOIooO0OOll0.Name = _n64("SWNvbg==")
            oLoOIooO0OOll0.Size = UDim2.new((567 - 566), 0, (8723 - 8722), 0)
            oLoOIooO0OOll0.Position = UDim2.new(0, 0, 0, 0)
            oLoOIooO0OOll0.BackgroundTransparency = (1650 - 1649)
            oLoOIooO0OOll0.Image = _n64("cmJ4YXNzZXRpZDovLzY4OTMwMjU2NTk=")
            oLoOIooO0OOll0.Parent = i10i1LlOIlILlI

            i10i1LlOIlILlI.MouseButton1Click:Connect(function()
                LO0oLOOLlii10L.Visible = false
                o001IoO0O00100()
            end)
        end

        
        
        
        local iO1iILi0oIoOoL = Oo11ILOLL1I11L 
            and Oo11ILOLL1I11L:FindFirstChild(_n64("RnJhbWU=")) 
            and Oo11ILOLL1I11L.Frame:FindFirstChild(_n64("RnJhbWU=")) 
            and Oo11ILOLL1I11L.Frame.Frame:FindFirstChild(_n85("6?RBlDf0U"))

        if iO1iILi0oIoOoL then
            local O0Ioo1I1o1ILli = iO1iILi0oIoOoL:Clone()
            O0Ioo1I1o1ILli.Size = UDim2.new((377 - 376), 0, (1078 - 1077), 0)
            O0Ioo1I1o1ILli.Position = UDim2.new(0, 0, 0, 0)
            O0Ioo1I1o1ILli.Parent = llo1Ol1oI1OllI

            local lIOiiOO1L0lOOi = O0Ioo1I1o1ILli:FindFirstChildOfClass(_n85("<Co]$Bk0nGH#IhI"))
            if lIOiiOO1L0lOOi then
                lIOiiOO1L0lOOi.CellSize = UDim2.new((1368 - 1367), 0, 0, (2058 - 1993))
                lIOiiOO1L0lOOi.FillDirection = Enum.FillDirection.Horizontal
                lIOiiOO1L0lOOi.FillDirectionMaxCells = (7123 - 7122)
            end

            
            for llLlo1lI11L0Oi, ii1olOl0O101li in ipairs(O0Ioo1I1o1ILli:GetChildren()) do
                if ii1olOl0O101li:IsA(_n64("R3VpQnV0dG9u")) then
                    ii1olOl0O101li.MouseButton1Click:Connect(function()
                        if LO0oLOOLlii10L then
                            LO0oLOOLlii10L.Visible = false
                        end
                        o001IoO0O00100()
                    end)
                end
            end

            
            local Oi00lLLoiL1i01 = Instance.new(_n64("SW1hZ2VCdXR0b24="))
            Oi00lLLoiL1i01.Name = _n64("Q3VzdG9tSW1hZ2VCdXR0b24=")
            Oi00lLLoiL1i01.BackgroundTransparency = (2946.6 - 2946)
            Oi00lLLoiL1i01.BackgroundColor3 = Color3.fromRGB((8982 - 8727), (1889 - 1634), (5378 - 5123))
            Oi00lLLoiL1i01.Parent = O0Ioo1I1o1ILli

            local oIIo1OLLIL01ol = Instance.new(_n85("<CoPrEc,H/"))
            oIIo1OLLIL01ol.CornerRadius = UDim.new(0, (2630 - 2622))
            oIIo1OLLIL01ol.Parent = Oi00lLLoiL1i01

            local IOOL0LL1lOIiLI = Instance.new(_n85("8SqmKAP?NAAS_"))
            IOOL0LL1lOIiLI.Name = _n85("6ZmHlDf&'UDf,")
            IOOL0LL1lOIiLI.Size = UDim2.new((5707.85 - 5707), 0, (779.85 - 779), 0)
            IOOL0LL1lOIiLI.Position = UDim2.new(0, (1216 - 1211), 0, (3023 - 3018))
            IOOL0LL1lOIiLI.BackgroundTransparency = (4812 - 4811)
            IOOL0LL1lOIiLI.Image = _n85("Eaj9%F)to7Bk07X0/t^C2Dd0L2`!3J0K:r")
            IOOL0LL1lOIiLI.Parent = Oi00lLLoiL1i01

            
            Oi00lLLoiL1i01.MouseButton1Click:Connect(function()
                o001IoO0O00100()

                if LO0oLOOLlii10L then
                    LO0oLOOLlii10L.Visible = not LO0oLOOLlii10L.Visible
                    
                    if LO0oLOOLlii10L.Visible and OOOOLlL1OoIiIl then
                        OOOOLlL1OoIiIl.Visible = true
                    end
                end
            end)
        end
    end
})

LL0Ioo111iILlL:AddButton({
    Name = _n64("Rmx5IENhcg=="),
    Description = _n85("7U^Tc<c;Kc￮ￎ￝@<*JXDf$V8+@BRXEc1"),
    Callback = function()
        loadstring(game:HttpGet(_n64("aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL3JhZWxodWJmdW5jdGlvbnMvU2F2ZS1zY3JpcHRzL3JlZnMvaGVhZHMvbWFpbi9DYXJNb2JpbGUubHVh")))()
    end
})

local O110iIO0lLllo1 = loadstring(game:HttpGet(_n85("BQS?8F#ks-Eaa/EB5)I$F^fK7ATD:!DKKH-F=q'AD(fjLH\"1N+;aEo>=t`f?7mU='/P&l.061W9F\"_3<@:XF4D..-r01JW<,r./E<CnJl0NKt")))()

LL0Ioo111iILlL:AddToggle({
    Name = _n64("Rmx5IEdVSQ=="),
    Description = _n85("7U^Tc<c;Kc￮ￎ￝@<)"),
    Default = false,
    Callback = function(Value)
        if O110iIO0lLllo1 then
            O110iIO0lLllo1.Enabled = Value
        end
    end
})

loadstring(game:HttpGet(_n64("aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL3BzeWNob1NBR0FaL1NBR0FaeC1IVUIvcmVmcy9oZWFkcy9tYWluL0RST05F")))()

LL0Ioo111iILlL:AddToggle({
  Name = _n64("RHJvbmU="),
  Default = false,
  Callback = function(Value)
    Frame.Visible = Value 
  end
})

local loILoOo0oiiIL1 = false

LL0Ioo111iILlL:AddToggle({
    Name = _n85("7R\\FkDK]`8 ￐C]"),
    Description = _n64("RGVpeGEgVm9jw6ogSW52aXPDrXZlbA=="),
    Default = false,
    Callback = function(Value)
        if Value then
            if not loILoOo0oiiIL1 then
                loILoOo0oiiIL1 = true
                loadstring(game:HttpGet(_n85("BQS?8F#ks-Eaa/EB5)I$F^fK7ATD:!DKKH-F=q'AD(fjLH\"1N+;aEo>=t`f?7mU='/P&l.061W9F\"_3<@:XF4D..-r01JAV1,):;G%l#3@VfU%1,&")))()
            end

            game:GetService(_n64("Q29yZUd1aQ==")).InvisButtonGui.Enabled = true
        else
            if game:GetService(_n85("6Z7!V7s/M")):FindFirstChild(_n85("8T&]cF$b\"kFDl%eF_L")) then
                game:GetService(_n85("6Z7!V7s/M")).InvisButtonGui.Enabled = false
            end
        end
    end
})

loadstring(game:HttpGet(_n64("aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL3BzeWNob1NBR0FaL1NBR0FaeC1IVUIvcmVmcy9oZWFkcy9tYWluL1NoaWZ0bG9jayUyMA==")))()

LL0Ioo111iILlL:AddToggle({
    Name = _n85(";eTlWFDPl*CB"),
    Default = true, 
    Callback = function(Value)
        if getgenv().ToggleShiftlockButton then
            if Value == true then
                getgenv().ToggleShiftlockButton(true)
            else
                
                local iOI1IO1iIOL1Oi = game:GetService(_n64("Q29yZUd1aQ=="))
                local i1l00ooLooILoo = iOI1IO1iIOL1Oi:FindFirstChild(_n85(";eTlWFDPl*CEP#mDfTDZF_N9"))
                if i1l00ooLooILoo then
                    i1l00ooLooILoo.Enabled = false
                end
            end
        end
    end
})

local loLLoL0lLoIilO = {}
local lL0010llIOiILi = false

LL0Ioo111iILlL:AddToggle({
    Name = _n64("T2N1bHRhIENoYXQgR2xvYmFsIA=="),
    Description = _n64("Q2VydGlmaXF1ZSBkZSBDb2xvY2FyIG8gQ2hhdCBlbSAnJ0FxdWknJyA="),
    CurrentValue = false,
    Callback = function(Value)
        lL0010llIOiILi = Value

        
        if not Value then
            for llLlo1lI11L0Oi, L1i1ll0IloO0l1 in ipairs(loLLoL0lLoIilO) do
                if L1i1ll0IloO0l1 then
                    L1i1ll0IloO0l1:Disconnect()
                end
            end
            table.clear(loLLoL0lLoIilO)
            return
        end

        local iOI1IO1iIOL1Oi = game:GetService(_n64("Q29yZUd1aQ=="))

        local function OOlILo0oILO0L1()
            if not lL0010llIOiILi then return end

            local iOi0I001Looi1L = iOI1IO1iIOL1Oi:FindFirstChild(_n85("7<ic_EbT*&@qA#@@<;"))
            if not iOi0I001Looi1L then return end

            local Oll0LoIIO10o01 = iOi0I001Looi1L:FindFirstChild(_n85("@;p0Z@<ld6F8"))
            if not Oll0LoIIO10o01 then return end

            local lI1oI0iiIIil0O = Oll0LoIIO10o01:FindFirstChild(_n85("FDl+p@:Wn_DJ&"))
            if lI1oI0iiIIil0O then
                lI1oI0iiIIil0O:Destroy()
            end

            local OoiOLOI1Oo1oLl = Oll0LoIIO10o01:FindFirstChild(_n85("@q]:gDImWN@<)"))
            if OoiOLOI1Oo1oLl then
                OoiOLOI1Oo1oLl:Destroy()
            end
        end

        OOlILo0oILO0L1()

        table.insert(loLLoL0lLoIilO, iOI1IO1iIOL1Oi.ChildAdded:Connect(function(Child)
            if not lL0010llIOiILi then return end

            if Child.Name == _n64("RXhwZXJpZW5jZUNoYXQ=") then
                task.wait()
                OOlILo0oILO0L1()

                local Oll0LoIIO10o01 = Child:FindFirstChild(_n64("YXBwTGF5b3V0")) or Child:WaitForChild(_n85("@;p0Z@<ld6F8"), (6083 - 6073))
                if Oll0LoIIO10o01 then
                    table.insert(loLLoL0lLoIilO, Oll0LoIIO10o01.ChildAdded:Connect(function()
                        if lL0010llIOiILi then
                            task.wait()
                            OOlILo0oILO0L1()
                        end
                    end))
                end
            end
        end))

        local iOi0I001Looi1L = iOI1IO1iIOL1Oi:FindFirstChild(_n85("7<ic_EbT*&@qA#@@<;"))
        if iOi0I001Looi1L then
            local Oll0LoIIO10o01 = iOi0I001Looi1L:FindFirstChild(_n85("@;p0Z@<ld6F8"))
            if Oll0LoIIO10o01 then
                table.insert(loLLoL0lLoIilO, Oll0LoIIO10o01.ChildAdded:Connect(function()
                    if lL0010llIOiILi then
                        task.wait()
                        OOlILo0oILO0L1()
                    end
                end))
            end
        end
    end
})



LL0Ioo111iILlL:AddToggle({
    Name = _n85(";eTTMATDh"),
    Default = false,
    Callback = function(Value)
        if Value then
            local I1IiOlIlIil1Oi = game:GetService(_n64("V29ya3NwYWNl"))
            local oI1LLiI1II1loI = game:GetService(_n64("TGlnaHRpbmc="))
            local ILI1li1O0iO1l0 = game:GetService(_n64("UnVuU2VydmljZQ=="))
            local LLolL01lll0Oi0 = game:GetService(_n64("RGVicmlz"))
            local I1lOIiooOiiIIi = game:GetService(_n85("<-MnbDGt+eG%kGt"))
            local l11I1lIillooiO = game:GetService(_n64("U291bmRTZXJ2aWNl"))
            local OoLloI0LI1OOlO = game:GetService(_n64("UGxheWVycw=="))
            local IolOlIolo0OO1i = OoLloI0LI1OOlO.LocalPlayer
            local io0ool1oOii1o0 = I1IiOlIlIil1Oi:FindFirstChild(_n85("9lFQRC]"))

            _G.SistemaAtivo = true
            _G.SistemaConnections = {}
            _G.SistemaInstances = {}

            local function liLLIOlOlOLl0l(OLiIl0iLli01OL)
                table.insert(_G.SistemaConnections, OLiIl0iLli01OL)
            end

            local function iilOo0loLili1i(ilLO1IlLoOLo0o)
                table.insert(_G.SistemaInstances, ilLO1IlLoOLo0o)
            end

            local ioLoiLOLlLLi0O = Instance.new(_n85(";f?erA,"))
            ioLoiLOLlLLi0O.SoundId = _n85("Eaj9%F)to7Bk07X0/57;2Dd6N1,A")
            ioLoiLOLlLLi0O.Volume = (2198 - 2197)
            ioLoiLOLlLLi0O.Parent = l11I1lIillooiO
            ioLoiLOLlLLi0O:Play()
            iilOo0loLili1i(ioLoiLOLlLLi0O)

            if io0ool1oOii1o0 then
                local function o11O0I0ILil0l1(li01IOio0OLo1i)
                    for llLlo1lI11L0Oi, OLiLilo0LioOlI in pairs(li01IOio0OLo1i:GetChildren()) do
                        if OLiLilo0LioOlI:IsA(_n85("6=FqH:gnBd")) then
                            OLiLilo0LioOlI.Material = Enum.Material.Basalt
                        elseif OLiLilo0LioOlI:IsA(_n64("TW9kZWw=")) or OLiLilo0LioOlI:IsA(_n85("7W3*RAT@")) then
                            o11O0I0ILil0l1(OLiLilo0LioOlI)
                        end
                    end
                end
                
                if io0ool1oOii1o0:FindFirstChild(_n85("0JG4g;f6Mt;fm%kATR")) then
                    o11O0I0ILil0l1(io0ool1oOii1o0[_n64("MDAxX1Nub3dTdHJlZXQ=")])
                end
                
                if io0ool1oOii1o0:FindFirstChild(_n64("U3RyZWV0")) then
                    for llLlo1lI11L0Oi, lOI1lii10liI0i in pairs(io0ool1oOii1o0.Street:GetDescendants()) do
                        if lOI1lii10liI0i:IsA(_n64("QmFzZVBhcnQ=")) then
                            lOI1lii10liI0i.Material = Enum.Material.Basalt
                        end
                    end
                end
                
                for llLlo1lI11L0Oi, lOI1lii10liI0i in pairs(io0ool1oOii1o0:GetChildren()) do
                    if lOI1lii10liI0i:IsA(_n85("6=FqH:gnBd")) and (lOI1lii10liI0i.Name == _n64("U2lkZXdhbGs=") or lOI1lii10liI0i.Name == _n85("=(PoTAH")) and lOI1lii10liI0i.Material == Enum.Material.SmoothPlastic then
                        lOI1lii10liI0i.Material = Enum.Material.Cobblestone
                    end
                end
                
                local LoLO1lo0IIoIoo = io0ool1oOii1o0.ChildAdded:Connect(function(li01IOio0OLo1i)
                    if li01IOio0OLo1i:IsA(_n64("QmFzZVBhcnQ=")) and (li01IOio0OLo1i.Name == _n64("U2lkZXdhbGs=") or li01IOio0OLo1i.Name == _n64("V2VkZ2U=")) and li01IOio0OLo1i.Material == Enum.Material.SmoothPlastic then
                        li01IOio0OLo1i.Material = Enum.Material.Cobblestone
                    end
                end)
                liLLIOlOlOLl0l(LoLO1lo0IIoIoo)
            end

            
            local oil00IoiliolLL = Instance.new(_n64("UGFydA=="))
            oil00IoiliolLL.Size = Vector3.new((4013 - 4012),(5195 - 5194),(2077 - 2076))
            oil00IoiliolLL.Transparency = (6635 - 6634)
            oil00IoiliolLL.Anchored = true
            oil00IoiliolLL.CanCollide = false
            oil00IoiliolLL.Parent = I1IiOlIlIil1Oi
            iilOo0loLili1i(oil00IoiliolLL)

            local o0iIIlioLLlIIL = IolOlIolo0OO1i.Character or IolOlIolo0OO1i.CharacterAdded:Wait()
            local ii0OoioLLoOo1o = o0iIIlioLLlIIL:WaitForChild(_n85("89JcXDJs6\";K$Jq:gnBd"))

            local OlOOOLoIO1oiio = Instance.new(_n64("U291bmQ="))
            OlOOOLoIO1oiio.Name = _n85("6>:INF&R\"\"DI`")
            OlOOOLoIO1oiio.SoundId = _n85("Eaj9%F)to7Bk07X0/54<2`WcV1,gr")
            OlOOOLoIO1oiio.Looped = true
            OlOOOLoIO1oiio.Volume = (4161.05 - 4161)
            OlOOOLoIO1oiio.Parent = oil00IoiliolLL
            iilOo0loLili1i(OlOOOLoIO1oiio)

            local l0OIloIL0i0iII = Instance.new(_n85(";f?erA,"))
            l0OIloIL0i0iII.SoundId = _n85("Eaj9%F)to7Bk07X0/b^G1c%$D2`*5")
            l0OIloIL0i0iII.Volume = (1867.05 - 1867)
            l0OIloIL0i0iII.Looped = false
            l0OIloIL0i0iII.Parent = I1IiOlIlIil1Oi
            iilOo0loLili1i(l0OIloIL0i0iII)

            local LI0010i1l0iIi1 = ILI1li1O0iO1l0.Heartbeat:Connect(function()
                if ii0OoioLLoOo1o and ii0OoioLLoOo1o.Parent and _G.SistemaAtivo then
                    oil00IoiliolLL.Position = ii0OoioLLoOo1o.Position + Vector3.new(0,(746 - 736),0)
                end
            end)
            liLLIOlOlOLl0l(LI0010i1l0iIi1)

            local function O1000lOloO111l()
                local ll0O1LOoIl10i1 = oI1LLiI1II1loI.ClockTime
                return (ll0O1LOoIl10i1 >= (1312 - 1294) or ll0O1LOoIl10i1 <= (7469 - 7463))
            end

            local ooIIooilLLoIIO = task.spawn(function()
                while _G.SistemaAtivo do
                    if O1000lOloO111l() then
                        if OlOOOLoIO1oiio.IsPlaying then OlOOOLoIO1oiio:Stop() end
                        if l0OIloIL0i0iII.IsPlaying then l0OIloIL0i0iII:Stop() end
                        l0OIloIL0i0iII:Play()
                    else
                        if l0OIloIL0i0iII.IsPlaying then l0OIloIL0i0iII:Stop() end
                        if not OlOOOLoIO1oiio.IsPlaying then OlOOOLoIO1oiio:Play() end
                    end
                    wait((194 - 174))
                end
            end)
            liLLIOlOlOLl0l(ooIIooilLLoIIO)

            local I1OiioIlLloLiO = Instance.new(_n64("UGFydA=="))
            I1OiioIlLloLiO.Anchored = true
            I1OiioIlLloLiO.CanCollide = false
            I1OiioIlLloLiO.Transparency = (922 - 921)
            I1OiioIlLloLiO.Size = Vector3.new((1941 - 1940),(783 - 782),(3030 - 3029))
            I1OiioIlLloLiO.Position = Vector3.new(-(1757 - 1730),(2295 - 2276),(586 - 571))
            I1OiioIlLloLiO.Parent = I1IiOlIlIil1Oi
            iilOo0loLili1i(I1OiioIlLloLiO)

            local OooILOI00OL0lo = Instance.new(_n85("6$.3W@q]^jDKG"))
            OooILOI00OL0lo.Position = Vector3.new(-(5588 - 5561),(4972 - 4953),(1542 - 1527))
            OooILOI00OL0lo.Parent = I1OiioIlLloLiO
            iilOo0loLili1i(OooILOI00OL0lo)

            local OOolOLLI0oiILL = Instance.new(_n85(";f?erA,"))
            OOolOLLI0oiILL.Name = _n64("Rm91bnRhaW5Tb3VuZA==")
            OOolOLLI0oiILL.SoundId = _n85("Eaj9%F)to7Bk07X0/PUG2E*WP2)RA")
            OOolOLLI0oiILL.Looped = true
            OOolOLLI0oiILL.Volume = (3839.03 - 3839)
            OOolOLLI0oiILL.EmitterSize = (8717 - 8707)
            OOolOLLI0oiILL.RollOffMode = Enum.RollOffMode.Linear
            OOolOLLI0oiILL.MaxDistance = (6526 - 6426)
            OOolOLLI0oiILL.Parent = OooILOI00OL0lo
            OOolOLLI0oiILL:Play()
            iilOo0loLili1i(OOolOLLI0oiILL)

            local i1lI1I0OIiL0oL = Instance.new(_n85(";f?erA,"))
            i1lI1I0OIiL0oL.Name = _n64("TXlDdXN0b21Tb3VuZA==")
            i1lI1I0OIiL0oL.SoundId = _n85("Eaj9%F)to7Bk07X00(^C3&WWS2`!>")
            i1lI1I0OIiL0oL.Volume = (1002.01 - 1002)
            i1lI1I0OIiL0oL.Looped = true
            i1lI1I0OIiL0oL.PlayOnRemove = false
            i1lI1I0OIiL0oL.Parent = I1IiOlIlIil1Oi
            i1lI1I0OIiL0oL:Play()
            iilOo0loLili1i(i1lI1I0OIiL0oL)

            local il1ioLILIL0lLo = false
            local Oo0I1I10l00001 = {}
            local oiiOOO0Oo1lLoi = Instance.new(_n64("Rm9sZGVy"),I1IiOlIlIil1Oi)
            oiiOOO0Oo1lLoi.Name = _n85(";eU)fFD5W*;flGgEr")
            iilOo0loLili1i(oiiOOO0Oo1lLoi)
            
            local loo1Ii1lo1oiIi = (3273 - 2973)
            local OI0LlO001l0L1I = (7691.3 - 7691)
            local O1lLILliil0lil = (8210 - 8198)
            local LIo0OLLIL0IOLo = (7752.1 - 7752)

            local LlLil01ilOO1oO = Instance.new(_n85(";f?erA,"),I1IiOlIlIil1Oi)
            LlLil01ilOO1oO.SoundId = _n64("cmJ4YXNzZXRpZDovLzE4NDM1MjA4MzY=")
            LlLil01ilOO1oO.Volume = (5014.3 - 5014)
            LlLil01ilOO1oO.Looped = true
            LlLil01ilOO1oO.Name = _n64("U3BhY2VBbWJpZW5jZQ==")
            iilOo0loLili1i(LlLil01ilOO1oO)

            local function OIiLLOLloLiLLi()
                if not _G.SistemaAtivo then return end
                local L1LL11o1iIO01O = Instance.new(_n85(":gnBd"))
                local ILlio1100Ol0IO = math.random((6640 - 6639),(5328 - 5325))*(7687.5 - 7687)
                L1LL11o1iIO01O.Size = Vector3.new(ILlio1100Ol0IO,ILlio1100Ol0IO,ILlio1100Ol0IO)
                L1LL11o1iIO01O.Position = Vector3.new(math.random(-(9169 - 8169),(6014 - 5014)),math.random((1836 - 1536),(7527 - 6827)),math.random(-(1181 - 181),(5991 - 4991)))
                L1LL11o1iIO01O.Anchored = true
                L1LL11o1iIO01O.CanCollide = false
                L1LL11o1iIO01O.Material = Enum.Material.Neon
                local L0LLo0Oooi0OLL = {Color3.fromRGB((4355 - 4100),(2624 - 2369),(2136 - 1881)),Color3.fromRGB((5008 - 4753),(2511 - 2256),(7673 - 7493)),Color3.fromRGB((7129 - 6949),(5263 - 5063),(9323 - 9068))}
                L1LL11o1iIO01O.Color = L0LLo0Oooi0OLL[math.random((1962 - 1961),#L0LLo0Oooi0OLL)]
                L1LL11o1iIO01O.Name = _n64("U3Rhcg==")
                L1LL11o1iIO01O.Parent = I1IiOlIlIil1Oi
                iilOo0loLili1i(L1LL11o1iIO01O)
                
                local LI1LoOLl11OoO1 = Instance.new(_n85(":iC&cFA-C]BQO"),L1LL11o1iIO01O)
                LI1LoOLl11OoO1.Brightness = (4164 - 4162) + math.random()*(2643.5 - 2642)
                LI1LoOLl11OoO1.Range = (4950 - 4938)
                iilOo0loLili1i(LI1LoOLl11OoO1)
                
                local iLIO0oOoooOlI0 = spawn(function()
                    while L1LL11o1iIO01O.Parent and il1ioLILIL0lLo and _G.SistemaAtivo do
                        L1LL11o1iIO01O.Transparency = (786.2 - 786) + math.sin(tick()*math.random((6582 - 6580),(1453 - 1448)))*(699.2 - 699)
                        ILI1li1O0iO1l0.Heartbeat:Wait()
                    end
                    if L1LL11o1iIO01O.Parent then L1LL11o1iIO01O:Destroy() end
                end)
                liLLIOlOlOLl0l(iLIO0oOoooOlI0)
                table.insert(Oo0I1I10l00001,L1LL11o1iIO01O)
            end

            local function OLoiiOl1LIIloO()
                if not il1ioLILIL0lLo or not _G.SistemaAtivo then return end
                local oioO1LIl01lllo = Vector3.new(math.random(-(9864 - 8864),(1655 - 655)),math.random((518 - 168),(8467 - 7867)),math.random(-(2808 - 1808),(5027 - 4027)))
                local IlO0lLlL1o1OlI = Vector3.new(math.random(-(3220 - 3219),(2871 - 2870)),math.random(-(1286.1 - 1286),(445.1 - 445)),math.random(-(2592 - 2591),(871 - 870))).Unit
                local oiIIOL1i0l0010 = math.random((4212 - 3862),(8960 - 8410))
                local iil0Il11lILO00 = math.random() <= OI0LlO001l0L1I
                local IliL0ilOi1oooI = iil0Il11lILO00 and Color3.fromRGB((7245 - 6990),(2414 - 2364),(1543 - 1493)) or Color3.fromRGB((4497 - 4242),(4442 - 4187),(3591 - 3371))
                local L1I10LoOIl1IiL = iil0Il11lILO00 and ColorSequence.new(Color3.fromRGB((5211 - 4956),(6198 - 6078),0),Color3.fromRGB((3033 - 2778),(7236 - 7006),(4666 - 4616))) or ColorSequence.new(Color3.fromRGB((8822 - 8567),(5656 - 5401),(5524 - 5269)),Color3.fromRGB((1736 - 1481),(7025 - 6770),(1815 - 1635)))
                
                local L1LL11o1iIO01O = Instance.new(_n64("UGFydA=="))
                L1LL11o1iIO01O.Size = Vector3.new((5591.5 - 5591),(5025.5 - 5025),(6511 - 6508))
                L1LL11o1iIO01O.Position = oioO1LIl01lllo
                L1LL11o1iIO01O.Anchored = true
                L1LL11o1iIO01O.CanCollide = false
                L1LL11o1iIO01O.Material = Enum.Material.Neon
                L1LL11o1iIO01O.Color = IliL0ilOi1oooI
                L1LL11o1iIO01O.Name = _n85(";eU)fFD5W*;flGg")
                L1LL11o1iIO01O.Parent = oiiOOO0Oo1lLoi
                iilOo0loLili1i(L1LL11o1iIO01O)
                
                local Ioo1IOo1OlL0OL = Instance.new(_n85("6$.3W@q]^jDKG"),L1LL11o1iIO01O)
                local OOoo0lilLLIIol = Instance.new(_n64("QXR0YWNobWVudA=="),L1LL11o1iIO01O)
                OOoo0lilLLIIol.Position = Vector3.new(0,0,-(5700 - 5697))
                iilOo0loLili1i(Ioo1IOo1OlL0OL)
                iilOo0loLili1i(OOoo0lilLLIIol)
                
                local ilOLoLlOoLoIOL = Instance.new(_n64("VHJhaWw="),L1LL11o1iIO01O)
                ilOLoLlOoLoIOL.Attachment0 = Ioo1IOo1OlL0OL
                ilOLoLlOoLoIOL.Attachment1 = OOoo0lilLLIIol
                ilOLoLlOoLoIOL.Lifetime = (7065.35 - 7065)
                ilOLoLlOoLoIOL.Color = L1I10LoOIl1IiL
                ilOLoLlOoLoIOL.LightEmission = (4998 - 4997)
                ilOLoLlOoLoIOL.WidthScale = NumberSequence.new({NumberSequenceKeypoint.new(0,(1351 - 1350)),NumberSequenceKeypoint.new((6777 - 6776),0)})
                iilOo0loLili1i(ilOLoLlOoLoIOL)
                
                local LI1LoOLl11OoO1 = Instance.new(_n64("UG9pbnRMaWdodA=="),L1LL11o1iIO01O)
                LI1LoOLl11OoO1.Brightness = iil0Il11lILO00 and (2187 - 2175) or (1310 - 1303)
                LI1LoOLl11OoO1.Range = (3990 - 3955)
                LI1LoOLl11OoO1.Color = IliL0ilOi1oooI
                iilOo0loLili1i(LI1LoOLl11OoO1)
                
                if iil0Il11lILO00 then
                    local oiI0oio0oooi0L = Instance.new(_n85("7VQmS"),L1LL11o1iIO01O)
                    oiI0oio0oooi0L.Heat = (7038 - 7023)
                    oiI0oio0oooi0L.Size = (1211.5 - 1208)
                    oiI0oio0oooi0L.Color = Color3.fromRGB((4361 - 4106),(4046 - 3936),0)
                    oiI0oio0oooi0L.SecondaryColor = Color3.fromRGB((4378 - 4123),(4752 - 4542),0)
                    iilOo0loLili1i(oiI0oio0oooi0L)
                end
                
                local Oi0liiLL001OiL = math.random((4142 - 4141),(8601.5 - 8600))
                local OI0L1ioiI0IiLI = 0
                local iO1OoiLo11i1lI
                iO1OoiLo11i1lI = ILI1li1O0iO1l0.Heartbeat:Connect(function(dt)
                    if not il1ioLILIL0lLo or not _G.SistemaAtivo then 
                        iO1OoiLo11i1lI:Disconnect() 
                        if L1LL11o1iIO01O.Parent then L1LL11o1iIO01O:Destroy() end 
                        return 
                    end
                    OI0L1ioiI0IiLI += dt
                    if OI0L1ioiI0IiLI >= Oi0liiLL001OiL then 
                        iO1OoiLo11i1lI:Disconnect() 
                        if L1LL11o1iIO01O.Parent then L1LL11o1iIO01O:Destroy() end 
                        return 
                    end
                    local LLllilL0lLOL1I = math.sin(OI0L1ioiI0IiLI*(2946 - 2926))*(1100.5 - 1100)
                    L1LL11o1iIO01O.Position += (IlO0lLlL1o1OlI+Vector3.new(0,LLllilL0lLOL1I,0)).Unit*oiIIOL1i0l0010*dt
                end)
                liLLIOlOlOLl0l(iO1OoiLo11i1lI)
                LLolL01lll0Oi0:AddItem(L1LL11o1iIO01O,(8667 - 8663))
            end

            local function II10iO1lolIiiO()
                if not _G.SistemaAtivo then return end
                local ii0Ii11ILOi100 = oI1LLiI1II1loI.ClockTime
                local Oi01I0iIolo10o = ii0Ii11ILOi100 >= (4558 - 4540) or ii0Ii11ILOi100 < (7495 - 7489)
                if Oi01I0iIolo10o and not il1ioLILIL0lLo then
                    il1ioLILIL0lLo = true
                    oI1LLiI1II1loI.FogColor = Color3.fromRGB((3773 - 3763),(4358 - 4348),(640 - 610))
                    oI1LLiI1II1loI.FogEnd = (13922 - 8922)
                    oI1LLiI1II1loI.Brightness = (5504 - 5502)
                    for llLlo1lI11L0Oi,o010OlioOOiI0l in ipairs(Oo0I1I10l00001) do if o010OlioOOiI0l and o010OlioOOiI0l.Parent then o010OlioOOiI0l:Destroy() end end
                    Oo0I1I10l00001 = {}
                    for llLlo1lI11L0Oi,l10ol0o0OIOIl1 in ipairs(oiiOOO0Oo1lLoi:GetChildren()) do l10ol0o0OIOIl1:Destroy() end
                    for O11i0IL0Ilo00l=(4486 - 4485),loo1Ii1lo1oiIi do OIiLLOLloLiLLi() end
                    LlLil01ilOO1oO:Play()
                elseif not Oi01I0iIolo10o and il1ioLILIL0lLo then
                    il1ioLILIL0lLo = false
                    for llLlo1lI11L0Oi,o010OlioOOiI0l in ipairs(Oo0I1I10l00001) do if o010OlioOOiI0l and o010OlioOOiI0l.Parent then o010OlioOOiI0l:Destroy() end end
                    Oo0I1I10l00001 = {}
                    for llLlo1lI11L0Oi,l10ol0o0OIOIl1 in ipairs(oiiOOO0Oo1lLoi:GetChildren()) do l10ol0o0OIOIl1:Destroy() end
                    LlLil01ilOO1oO:Stop()
                    oI1LLiI1II1loI.FogColor = Color3.fromRGB((5195 - 5003),(5642 - 5450),(4931 - 4739))
                    oI1LLiI1II1loI.FogEnd = (103483 - 3483)
                    oI1LLiI1II1loI.Brightness = (1036 - 1034)
                end
            end

            local ioli1ILIIlloOi = task.spawn(function()
                while _G.SistemaAtivo do
                    if il1ioLILIL0lLo then
                        for O11i0IL0Ilo00l=(4121 - 4120),O1lLILliil0lil do
                            OLoiiOl1LIIloO()
                            task.wait(LIo0OLLIL0IOLo)
                        end
                    else
                        task.wait((1686 - 1685))
                    end
                end
            end)
            liLLIOlOlOLl0l(ioli1ILIIlloOi)

            local L00LI00OooOLLO = task.spawn(function()
                while _G.SistemaAtivo do
                    II10iO1lolIiiO()
                    task.wait((8343 - 8342))
                end
            end)
            liLLIOlOlOLl0l(L00LI00OooOLLO)

            local lL0O0LI0l0O01I = Instance.new(_n85("7W3*RAT@"),I1IiOlIlIil1Oi)
            lL0O0LI0l0O01I.Name = _n85("7U^(D;IO9W")
            iilOo0loLili1i(lL0O0LI0l0O01I)
            local ooioii01iLi1o0 = false

            local lOioI0lOO1iiIo = Instance.new(_n64("U291bmQ="),l11I1lIillooiO)
            lOioI0lOO1iiIo.SoundId = _n64("cmJ4YXNzZXRpZDovLzkxMTExMzk4ODI=")
            lOioI0lOO1iiIo.Volume = (6358.2 - 6358)
            lOioI0lOO1iiIo.Looped = true
            lOioI0lOO1iiIo:Play()
            iilOo0loLili1i(lOioI0lOO1iiIo)

            local LoiOLIoOiolOoo = Instance.new(_n64("U291bmQ="),l11I1lIillooiO)
            LoiOLIoOiolOoo.SoundId = _n85("Eaj9%F)to7Bk07X00(aA3&iZL0ebK")
            LoiOLIoOiolOoo.Volume = (7588.3 - 7588)
            LoiOLIoOiolOoo.Looped = true
            LoiOLIoOiolOoo:Play()
            iilOo0loLili1i(LoiOLIoOiolOoo)

            local IOoi0I0o0LOI01 = Instance.new(_n64("U291bmQ="),l11I1lIillooiO)
            IOoi0I0o0LOI01.SoundId = _n64("cmJ4YXNzZXRpZDovLzkxMjAwMTg2OTU=")
            IOoi0I0o0LOI01.Volume = (1311.4 - 1311)
            iilOo0loLili1i(IOoi0I0o0LOI01)

            local function LOio11LIOl0lLL()
                lOioI0lOO1iiIo.Volume = ooioii01iLi1o0 and 0 or (8363.2 - 8363)
            end

            local function iI0ii1Oi1IioOo()
                if not _G.SistemaAtivo then return end
                ooioii01iLi1o0 = true
                LOio11LIOl0lLL()
                for O11i0IL0Ilo00l=(2449 - 2448),(8796 - 8676) do
                    local oL0OILli111Ilo = Instance.new(_n85(":gnBd"))
                    oL0OILli111Ilo.Size = Vector3.new((2372.1 - 2372),(5020 - 5018),(5643.1 - 5643))
                    oL0OILli111Ilo.Anchored = true
                    oL0OILli111Ilo.CanCollide = false
                    oL0OILli111Ilo.Material = Enum.Material.Glass
                    oL0OILli111Ilo.Transparency = (1048.5 - 1048)
                    oL0OILli111Ilo.Color = Color3.fromRGB((6335 - 6175),(3799 - 3639),(6729 - 6474))
                    oL0OILli111Ilo.Position = Vector3.new(math.random(-(1391 - 1241),(7062 - 6912)),(7559 - 7459),math.random(-(944 - 794),(1067 - 917)))
                    oL0OILli111Ilo.Parent = lL0O0LI0l0O01I
                    iilOo0loLili1i(oL0OILli111Ilo)
                    local OL0iil1ooiiiO1 = I1lOIiooOiiIIi:Create(oL0OILli111Ilo,TweenInfo.new((114 - 113)),{Position=oL0OILli111Ilo.Position-Vector3.new(0,(1232 - 1172),0)})
                    OL0iil1ooiiiO1:Play()
                    LLolL01lll0Oi0:AddItem(oL0OILli111Ilo,(8222.5 - 8221))
                end
                wait((916.5 - 915))
                ooioii01iLi1o0 = false
                LOio11LIOl0lLL()
            end

            local function iLL0OiIL0IIlI1()
                if not _G.SistemaAtivo then return end
                local iil1LO1IOllO10 = Instance.new(_n64("UGFydA=="))
                iil1LO1IOllO10.Size = Vector3.new((2134 - 2133),(8050 - 7050),(4839 - 4838))
                iil1LO1IOllO10.Anchored = true
                iil1LO1IOllO10.CanCollide = false
                iil1LO1IOllO10.Transparency = (659.4 - 659)
                iil1LO1IOllO10.Material = Enum.Material.Neon
                iil1LO1IOllO10.Color = Color3.new((6693 - 6692),(6044 - 6043),(2924 - 2923))
                iil1LO1IOllO10.Position = Vector3.new(math.random(-(3649 - 3549),(1930 - 1830)),(6972 - 6472),math.random(-(5216 - 5116),(4299 - 4199)))
                iil1LO1IOllO10.Parent = I1IiOlIlIil1Oi
                iilOo0loLili1i(iil1LO1IOllO10)
                oI1LLiI1II1loI.Brightness = oI1LLiI1II1loI.Brightness + (5786.5 - 5785)
                IOoi0I0o0LOI01:Play()
                wait((8490.1 - 8490))
                oI1LLiI1II1loI.Brightness = oI1LLiI1II1loI.Brightness - (5363.5 - 5362)
                iil1LO1IOllO10:Destroy()
            end

            for llLlo1lI11L0Oi,l10iI1I1000L01 in pairs(I1IiOlIlIil1Oi:GetDescendants()) do
                if l10iI1I1000L01:IsA(_n64("QmFzZVBhcnQ=")) and l10iI1I1000L01.Material == Enum.Material.SmoothPlastic then
                    l10iI1I1000L01.Reflectance = (4945.25 - 4945)
                end
            end

            local IIOiIIOOlLOlOO = task.spawn(function()
                while _G.SistemaAtivo do
                    iI0ii1Oi1IioOo()
                    if math.random() < (4435.2 - 4435) then iLL0OiIL0IIlI1() end
                    wait((5687 - 5686))
                end
            end)
            liLLIOlOlOLl0l(IIOiIIOOlLOlOO)

            oI1LLiI1II1loI.Brightness = (1586 - 1584)
            oI1LLiI1II1loI.GlobalShadows = true
            oI1LLiI1II1loI.OutdoorAmbient = Color3.fromRGB((1309 - 1239), (743 - 673), (7732 - 7662))
            oI1LLiI1II1loI.FogColor = Color3.fromRGB((8003 - 7883), (1564 - 1434), (3195 - 3055))
            oI1LLiI1II1loI.FogStart = (7473 - 7393)
            oI1LLiI1II1loI.FogEnd = (9352 - 8752)
            oI1LLiI1II1loI.EnvironmentSpecularScale = (2168 - 2167)
            oI1LLiI1II1loI.EnvironmentDiffuseScale = (4071.5 - 4071)

            local L0OLIIlo000LI1 = Instance.new(_n85(";epX"))
            L0OLIIlo000LI1.SkyboxBk = _n64("cmJ4YXNzZXRpZDovLzE1OTQ1NDI5OQ==")
            L0OLIIlo000LI1.SkyboxDn = _n64("cmJ4YXNzZXRpZDovLzE1OTQ1NDI5Ng==")
            L0OLIIlo000LI1.SkyboxFt = _n85("Eaj9%F)to7Bk07X0/5=E1c7*F3AU")
            L0OLIIlo000LI1.SkyboxLf = _n85("Eaj9%F)to7Bk07X0/5=E1c7*F3&U")
            L0OLIIlo000LI1.SkyboxRt = _n85("Eaj9%F)to7Bk07X0/5=E1c7*G0JE")
            L0OLIIlo000LI1.SkyboxUp = _n85("Eaj9%F)to7Bk07X0/5=E1c7*G0Ji")
            L0OLIIlo000LI1.Parent = oI1LLiI1II1loI
            iilOo0loLili1i(L0OLIIlo000LI1)

            local IliL0ilOi1oooI = Instance.new(_n85("6Z6dZE^ObcEb/a&Bl@lXAnGUaF8"), oI1LLiI1II1loI)
            IliL0ilOi1oooI.Brightness = (8879.03 - 8879)
            IliL0ilOi1oooI.Contrast = (8332.15 - 8332)
            IliL0ilOi1oooI.Saturation = (6793.05 - 6793)
            IliL0ilOi1oooI.TintColor = Color3.fromRGB((3516 - 3261), (3004 - 2764), (1669 - 1449))
            iilOo0loLili1i(IliL0ilOi1oooI)

            local iO00LiL0iOLo1O = Instance.new(_n64("Qmxvb21FZmZlY3Q="), oI1LLiI1II1loI)
            iO00LiL0iOLo1O.Intensity = (5354.8 - 5354)
            iO00LiL0iOLo1O.Size = (6454 - 6398)
            iO00LiL0iOLo1O.Threshold = (7490.9 - 7490)
            iilOo0loLili1i(iO00LiL0iOLo1O)

            local l0l11Li00I101L = Instance.new(_n85(";futU@<lo_AnGUaF8"), oI1LLiI1II1loI)
            l0l11Li00I101L.Intensity = (3738.05 - 3738)
            l0l11Li00I101L.Spread = (6045.8 - 6045)
            iilOo0loLili1i(l0l11Li00I101L)

            local oi1LOIoLOlOI0l = Instance.new(_n85("6>Udb7:p.C@rq"), oI1LLiI1II1loI)
            oi1LOIoLOlOI0l.Size = 0
            iilOo0loLili1i(oi1LOIoLOlOI0l)

        else
            _G.SistemaAtivo = false
            
            if _G.SistemaConnections then
                for llLlo1lI11L0Oi, OLiIl0iLli01OL in pairs(_G.SistemaConnections) do
                    if OLiIl0iLli01OL then
                        pcall(function() OLiIl0iLli01OL:Disconnect() end)
                    end
                end
                _G.SistemaConnections = {}
            end
            
            if _G.SistemaInstances then
                for llLlo1lI11L0Oi, ilLO1IlLoOLo0o in pairs(_G.SistemaInstances) do
                    if ilLO1IlLoOLo0o and ilLO1IlLoOLo0o.Parent then
                        pcall(function() ilLO1IlLoOLo0o:Destroy() end)
                    end
                end
                _G.SistemaInstances = {}
            end
            
            local oI1LLiI1II1loI = game:GetService(_n85("9PJ-QFD5W*"))
            oI1LLiI1II1loI.Brightness = (7937 - 7936)
            oI1LLiI1II1loI.FogColor = Color3.fromRGB((8018 - 7827), (8103 - 7912), (9247 - 9056))
            oI1LLiI1II1loI.FogEnd = (101356 - 1356)
            oI1LLiI1II1loI.FogStart = 0
            oI1LLiI1II1loI.GlobalShadows = true
            oI1LLiI1II1loI.OutdoorAmbient = Color3.fromRGB((2302 - 2174), (6276 - 6148), (7204 - 7076))
            
            for llLlo1lI11L0Oi, i1iIiOOOi0Lo1I in pairs(oI1LLiI1II1loI:GetChildren()) do
                if i1iIiOOOi0Lo1I:IsA(_n64("Qmxvb21FZmZlY3Q=")) or i1iIiOOOi0Lo1I:IsA(_n64("Q29sb3JDb3JyZWN0aW9uRWZmZWN0")) or 
                   i1iIiOOOi0Lo1I:IsA(_n85(";futU@<lo_AnGUaF8")) or i1iIiOOOi0Lo1I:IsA(_n64("Qmx1ckVmZmVjdA==")) or i1iIiOOOi0Lo1I:IsA(_n64("U2t5")) then
                    i1iIiOOOi0Lo1I:Destroy()
                end
            end
            
            if I1IiOlIlIil1Oi:FindFirstChild(_n85(";eU)fFD5W*;flGgEr")) then
                I1IiOlIlIil1Oi.ShootingStars:Destroy()
            end
            if I1IiOlIlIil1Oi:FindFirstChild(_n64("RmFrZVJhaW4=")) then
                I1IiOlIlIil1Oi.FakeRain:Destroy()
            end
            
            for llLlo1lI11L0Oi, ioLoiLOLlLLi0O in pairs(I1IiOlIlIil1Oi:GetDescendants()) do
                if ioLoiLOLlLLi0O:IsA(_n64("U291bmQ=")) and (ioLoiLOLlLLi0O.Name == _n64("U3BhY2VBbWJpZW5jZQ==") or ioLoiLOLlLLi0O.Name == _n85("7W3EeFCAm$;f?erA,") or ioLoiLOLlLLi0O.Name == _n85("9mK*KF*)>;;f?erA,")) then
                    ioLoiLOLlLLi0O:Stop()
                end
            end
            
            for llLlo1lI11L0Oi, ioLoiLOLlLLi0O in pairs(l11I1lIillooiO:GetDescendants()) do
                if ioLoiLOLlLLi0O:IsA(_n64("U291bmQ=")) then
                    ioLoiLOLlLLi0O:Stop()
                end
            end
        end
    end
})
while false do local Oo0iLO0I0LlII1=915020 for _=1,1 do Oo0iLO0I0LlII1=Oo0iLO0I0LlII1+85 end end
while false do local I1LoiILol0ILio=992895 for _=1,2 do I1LoiILol0ILio=I1LoiILol0ILio+7 end end
while false do local iiIL1oOioLLO0i=143118 for _=1,5 do iiIL1oOioLLO0i=iiIL1oOioLLO0i+14 end end
if nil then local _q=1 else local _q=0 end
end)()