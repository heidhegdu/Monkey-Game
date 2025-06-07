if game.PlaceId == 5987989452 then
    

    --Main
    local Window = OrionLib:MakeWindow({Name = "MonkeyHub", HidePremium = false, SaveConfig = true, ConfigFolder = "MonkeyCfg", IntroEnabled = true})
     

    --Pontos
    local plr = game.Players.LocalPlayer
    local char = plr.Character





    --Funçao
    function TeleportBasePrimaria()
        char.HumanoidRootPart.CFrame = CFrame.new(-29.183500289916992, 3.999999761581421, 178.66189575195312)


    end

    function TeleportBaseSegundaria()
        char.HumanoidRootPart.CFrame = CFrame.new(148.55992126464844, 4.00001435114746, 380.06536865234375)


    end

    function TeleportKatana()
        char.HumanoidRootPart.CFrame = CFrame.new(-34.56835174560547, -7.999992370605469, 426.9297790527344)


    end

    function TeleportMachadoDeFogo()
        char.HumanoidRootPart.CFrame = CFrame.new(-95.28823852539062, 3.999999761581421, 94.93623352050781)


    end

    function TeleportMarteloeTorreta()
        char.HumanoidRootPart.CFrame = CFrame.new(104.62137603759766, -13.000000953674316, 111.2880859375)


    end

    function TeleportMotoSerra()
        char.HumanoidRootPart.CFrame = CFrame.new(-71.66642761230469, -7.999992370605469, 516.6576538085938)


    end

    function TeleportLancasChamas()
        char.HumanoidRootPart.CFrame = CFrame.new(15.951681137084961, -18.000001907348633, 162.24142456054688)


    end

    function TeleportGuitarra()
        char.HumanoidRootPart.CFrame = CFrame.new(50.97103500366211, 4.000013351440043, 377.3851623535156)


    end

    function TeleportFacao()
        char.HumanoidRootPart.CFrame = CFrame.new(-9.887192726135254, -13, 97.63130950927734)


    end

    function TeleportBastaoDeGuarda()
        char.HumanoidRootPart.CFrame = CFrame.new(-2.8003036975860596, -2.999990701675415, 477.6972351074219)


    end

    function TeleportPeDeCabra()
        char.HumanoidRootPart.CFrame = CFrame.new(-60.906044006247656, 3.999999761581421, 195.25047302246094)


    end

    function TeleportBastao()
        char.HumanoidRootPart.CFrame = CFrame.new(124.80109405517578, -13.000016212463379, 184.79013061523438)


    end

    function TeleportPanela()
        char.HumanoidRootPart.CFrame = CFrame.new(17.465431213378906, 3.999999761581421, 225.6336669921875)


    end

    function TeleportMarrom()
        char.HumanoidRootPart.CFrame = CFrame.new(30.84091567993164, -13, 106.2332534790039)


    end

    function TeleportAzul()
        char.HumanoidRootPart.CFrame = CFrame.new(6.47295142200928, -13.000000953674316, 319.853759765625)


    end

    function TeleportVerde()
        char.HumanoidRootPart.CFrame = CFrame.new(34.97066879272461, 3.999999523162842, 65.14508056640625)


    end

    function TeleportRoxo()
        char.HumanoidRootPart.CFrame = CFrame.new(120.46566009521484, -13.000016212463379, 163.48329162597656)


    end

    function TeleportRosa()
        char.HumanoidRootPart.CFrame = CFrame.new(96.41764068603516, 3.999999761581421, 139.97239685058564)


    end

    function TeleportLaranja()
        char.HumanoidRootPart.CFrame = CFrame.new(-20.572792053222656, -18.000001907348633, 150.0460052490344)


    end

    function TeleportAmostraAlpha()
        char.HumanoidRootPart.CFrame = CFrame.new(-94.57206726074219, 3.999999761581421, 82.6716079711914)


    end

    function TeleportGeradorBasePrimaria()
        char.HumanoidRootPart.CFrame = CFrame.new(25.17339324951172, 3.999999761581421, 235.4532012939453)


    end

    function TeleportGeradorBaseSegundaria()
        char.HumanoidRootPart.CFrame = CFrame.new(112.27301788330078, 4.000014305114746, 416.1598815917969)


    end

    function TeleportGeradorCameras()
        char.HumanoidRootPart.CFrame = CFrame.new(-61.361480712890625, 14.000008583068848, 415.8369140625)


    end

    function TeleportGeradorIluminacao()
        char.HumanoidRootPart.CFrame = CFrame.new(8.037822723388672, 4.000000476837158, 350.59625244140625)


    end

    function TeleportGeradorBombasDeAguas()
        char.HumanoidRootPart.CFrame = CFrame.new(42.48645782470703, -13.000000953674316, 92.63813018798828)


    end

    function TeleportGeradorSistemaQuimico()
        char.HumanoidRootPart.CFrame = CFrame.new(102.02413940429688, -9.000000953674316, 219.54672241210938)


    end



    --Jogador

    local JogadorTab = Window:MakeTab({
        Name = "Humano",
        Icon = "rbxassetid://4483345998",
        PremiumOnly = false
    })
    local Section = JogadorTab:AddSection({
        Name = "Bases"
    })

    JogadorTab:AddButton({
        Name = "Base Primaria",
        Callback = function()
            TeleportBasePrimaria()
        
        end
       
    })
    
    JogadorTab:AddButton({
        Name = "Base Segundaria",
        Callback = function()
            TeleportBaseSegundaria()
        end
    
    })

    local Section = JogadorTab:AddSection({
        Name = "Equipamentos"
    })

    JogadorTab:AddButton({
        Name = "Katana",
        Callback = function()
            TeleportKatana()
        
        end
    })

    JogadorTab:AddButton({
        Name = "Machado De Fogo",
        Callback = function()
            TeleportMachadoDeFogo()
        
        end
    })

    JogadorTab:AddButton({
        Name = "Martelo e Torreta",
        Callback = function()
            TeleportMarteloeTorreta()
        
        end
    })

    JogadorTab:AddButton({
        Name = "Moto Serra",
        Callback = function()
            TeleportMotoSerra()
        
        end
    })

    JogadorTab:AddButton({
        Name = "Lança Chamas",
        Callback = function()
            TeleportLancasChamas()
        
        end
    })

    JogadorTab:AddButton({
        Name = "Guitarra",
        Callback = function()
            TeleportGuitarra()
        
        end
    })

    JogadorTab:AddButton({
        Name = "Facão",
        Callback = function()
            TeleportFacao()
        
        end
    })

    JogadorTab:AddButton({
        Name = "Bastão De Guarda",
        Callback = function()
            TeleportBastaoDeGuarda()
        
        end
    })

    JogadorTab:AddButton({
        Name = "Pé De Cabra",
        Callback = function()
            TeleportPeDeCabra()
        
        end
    })

    JogadorTab:AddButton({
        Name = "Bastão",
        Callback = function()
            TeleportBastao()
        
        end

    })

    JogadorTab:AddButton({
        Name = "Panela",
        Callback = function()
            TeleportPanela()
        
        end

    })


    local Jogador2Tab = Window:MakeTab({
        Name = "Macaco",
        Icon = "rbxassetid://4483345998",
        PremiumOnly = false
    })
    local Section = Jogador2Tab:AddSection({
        Name = "Cores"
    })

    Jogador2Tab:AddButton({
        Name = "Marrom",
        Callback = function()
            TeleportMarrom()
        
        end
    })

    Jogador2Tab:AddButton({
        Name = "Azul",
        Callback = function()
            TeleportAzul()
        
        end
    })

    Jogador2Tab:AddButton({
        Name = "Verde",
        Callback = function()
            TeleportVerde()
        
        end
    })

    Jogador2Tab:AddButton({
        Name = "Roxo",
        Callback = function()
            TeleportRoxo()
        
        end
    })

    Jogador2Tab:AddButton({
        Name = "Rosa",
        Callback = function()
            TeleportRosa()
        
        end
    })

    Jogador2Tab:AddButton({
        Name = "Laranja",
        Callback = function()
            TeleportLaranja()
        
        end
    })

    Jogador2Tab:AddButton({
        Name = "Amostra Alpha",
        Callback = function()
            TeleportAmostraAlpha()
        
        end
    })


    local Jogador3Tab = Window:MakeTab({
        Name = "Geradores",
        Icon = "rbxassetid://4483345998",
        PremiumOnly = false
    })
    local Section = Jogador3Tab:AddSection({
        Name = "Geradores"
    })

    Jogador3Tab:AddButton({
        Name = "Gerador Base Primaria",
        Callback = function()
            TeleportGeradorBasePrimaria()
        
        end
    })

    Jogador3Tab:AddButton({
        Name = "Gerador Base Segundaria",
        Callback = function()
            TeleportGeradorBaseSegundaria()
        
        end
    })

    Jogador3Tab:AddButton({
        Name = "Gerador Das Cameras",
        Callback = function()
            TeleportGeradorCameras()
        
        end
    })

    Jogador3Tab:AddButton({
        Name = "Gerador Da Iluminação",
        Callback = function()
            TeleportGeradorIluminacao()
        
        end
    })

    Jogador3Tab:AddButton({
        Name = "Gerador Das Bombas De Àguas",
        Callback = function()
            TeleportGeradorBombasDeAguas()
        
        end
    })

    Jogador3Tab:AddButton({
        Name = "Gerador Do Sistema Quimico",
        Callback = function()
            TeleportGeradorSistemaQuimico()
        
        end
    })
    
    
end
