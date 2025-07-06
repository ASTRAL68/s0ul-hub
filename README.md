-- ID du jeu autorisé
local jeuAutorisé = 5712833750  -- Remplace par l'ID de ton jeu

-- Vérifie si le jeu actuel est le bon
if game.PlaceId == jeuAutorisé then
    print("Jeu correct détecté. Activation du script...")
    
loadstring(game:HttpGet("https://raw.githubusercontent.com/ASTRAL68/animal-simulator/refs/heads/main/README.md"))()

else
    warn("Ce n'est pas le bon jeu. Script désactivé.")
end
