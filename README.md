-- ID du jeu autorisé
local jeuAutorisé = 1234567890  -- Remplace par l'ID de ton jeu

-- Vérifie si le jeu actuel est le bon
if game.PlaceId == jeuAutorisé then
    print("Jeu correct détecté. Activation du script...")
    


else
    warn("Ce n'est pas le bon jeu. Script désactivé.")
end
