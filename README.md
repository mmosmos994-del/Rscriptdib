--RScrpit Backdoor Scanner v1.4 Por rudhaFSI
--Ele roda requires e códigos seversidescrpit.

--Tutorial:
--1:Aperte em "Executar", Se todos os jogadores pularem, o jogo tem backdoor.
--2:Após isso, aperte em "Adiquirir" Espere o RScrpit analizar todos os remotes.
--3:Se aparecer "Remotes Adiquridos :D!" Caso contrário aparecer "Sem Backdoor :(..." Não há backdoor.

for i,v in pairs(game:GetService('Players'):GetPlayers()) do 
  if v.Character ~= nil and v.Character:IsA("Model") and v.Character:FindFirstChildWhichIsA("Humanoid") then 
    v.Character:FindFirstChildWhichIsA("Humanoid").Jump = true 
  end
end