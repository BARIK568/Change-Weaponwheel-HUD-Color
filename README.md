To be able to change the color of the weapon wheel, you actually just need to use a simple FiveM Native. This consists of replacing the old color (ID: 166) with the new color you want.



Citizen.CreateThread(function()
  ReplaceHudColour(116, 64)
end)


Citizen.CreateThread(function()
  ReplaceHudColourWithRgba(
    116, -- old Color
    240, -- R
    153, -- G
    153, -- B
    255 -- A
  )
end)
