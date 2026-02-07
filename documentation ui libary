## NovaLib Documentation

## Ui Lib 
```lua 
local NovaLib = loadstring(game:HttpGet("https://novaliboficial.page.gd"))() 
``` 
  
## Window 
```lua 
local Window = NovaLib:MakeWindow({ 
  Title = "Nova Hub : Blox Fruits", 
  SubTitle = "by yourname", 
  SaveFolder = "NovaHub_Config.json" 
}) 
``` 
  
## Icon  
```lua 
Window:AddMinimizeButton({ 
    Button = { Image = "rbxassetid://71014873973869", BackgroundTransparency = 0 }, 
    Corner = { CornerRadius = UDim.new(35, 1) }, 
}) 
``` 
  
## Tab 
```lua 
local Tab1 = Window:MakeTab({"Nome da Aba", "nome_do_icone"}) 
-- Icones disponíveis: home, sword, settings, list, user, etc.
``` 

## Set theme 
Dark 
```lua 
  NovaLib:SetTheme("Dark") 
``` 
Darkers 
```lua 
  NovaLib:SetTheme("Darker") 
``` 
Purple 
```lua 
  NovaLib:SetTheme("Purple") 
``` 

## Start tab 
```lua 
Window:SelectTab(Tab1) 
``` 

## Section 
```lua 
local Section = Tab1:AddSection({"Título da Section"}) 
``` 
  
## Paragraph 
```lua 
local Paragraph = Tab1:AddParagraph({"Título", "Conteúdo do parágrafo aqui.\nSegunda linha."}) 
``` 

## Discord invite 
```lua 
Tab1:AddDiscordInvite({ 
    Name = "Nome do Servidor", 
    Description = "Descrição do convite", 
    Logo = "rbxassetid://18751483361", 
    Invite = "link_do_discord", 
}) 
``` 

## Dialog 
```lua 
  local Dialog = Window:Dialog({ 
    Title = "Título do Dialog", 
    Text = "Mensagem que aparecerá no Dialog", 
    Options = { 
      {"Confirmar", function() 
         print("Clicou em Confirmar")
      end}, 
      {"Cancelar", function() 
         print("Clicou em Cancelar")
      end} 
    } 
  }) 
``` 

## Button 
```lua 
Tab1:AddButton({"Texto do Botão", function() 
    print("Botão clicado!") 
end}) 
``` 

## Toggle 
```lua 
Tab1:AddToggle({ 
  Name = "Título do Toggle", 
  Description = "Descrição opcional", 
  Default = false,
  Callback = function(Value) 
    print("Toggle:", Value)
  end 
}) 
``` 
  
## Sliders 
```lua 
Tab1:AddSlider({ 
  Name = "Velocidade", 
  Min = 1, 
  Max = 100, 
  Default = 16, 
  Callback = function(Value) 
    print("Valor do Slider:", Value)
  end 
}) 
``` 
  
## Dropdown 
```lua 
Tab1:AddDropdown({ 
  Name = "Selecionar Opção", 
  Options = {"Opção 1", "Opção 2", "Opção 3"}, 
  Default = "Opção 1", 
  Callback = function(Value) 
    print("Selecionado:", Value)
  end 
}) 
``` 
  
## Textbox 
```lua 
Tab1:AddTextBox({ 
  Name = "Título da Caixa", 
  PlaceholderText = "Digite algo aqui...", 
  Callback = function(Value) 
    print("Texto digitado:", Value)
  end 
}) 
``` 
