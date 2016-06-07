**How to setup**
------------

>Server
  
 1. Create a script in ServerScriptService
 2. Add 'require(428158721)()' at the top of the script

>Client

1. Create a localscript in either StarterPlayerScripts, StarterCharacterScripts, StarterGui or StarterPack
2. Add 'require(Game.ReplicatedStorage:WaitForChild('Environment'))()' to the top of the localscript

>How to use

  Server
    Network -- By Kurieita
      Network:Add('Function Name', function(Arguments) end)
      Network:Send(Name, Player, Arguements)
    Color
      Color.Palette(PaletteName, Colour, Shade)
        Palettes
          Material
            Red - Base, 50 - 900, A100 - A700
            Pink - Base, 50 - 900, A100 - A700
            Purple - Base, 50 - 900, A100 - A700
            Deep Purple - Base, 50 - 900, A100 - A700
            Indigo - Base, 50 - 900, A100 - A700
            Blue - Base, 50 - 900, A100 - A700
            Light Blue - Base, 50 - 900, A100 - A700
            Cyan - Base, 50 - 900, A100 - A700
            Teal - Base, 50 - 900, A100 - A700
            Green - Base, 50 - 900, A100 - A700
            Light Green - Base, 50 - 900, A100 - A700
            Lime - Base, 50 - 900, A100 - A700
            Yellow - Base, 50 - 900, A100 - A700
            Amber - Base, 50 - 900, A100 - A700
            Orange - Base, 50 - 900, A100 - A700
            Deep Orange - Base, 50 - 900, A100 - A700
            Brown - Base, 50 - 900
            Grey - Base, 50 - 900
            Blue Grey - Base, 50 - 900
    Color3
    	Color3.New(r, g, b)
    	Color3.FromRGB(R, G, B)
    	Color3.FromHSV(HSV)
    	Color3.FromHEX(#HEX)
		String
			String.Replicate(String, Number)
			(Rest are normal string functions capitalized)
