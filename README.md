# python-project---snake

Documentatie proiect Python: 
--Ce am facut in echipa? 
  Am conceput un joc snake care are un backround in carouri si buton de restart la fiecare game over; la fiecare mancare, sarpele creste in lungime, isi schimba culoarea si isi creste viteza, iar la sfarsitul jocului se retine scorul, urmand ca la mai multe incercari sa se tina minte scorul cel mai mare 

--Ce research, referinte am folosit?
pentru buton in pygame :
 https://www.geeksforgeeks.org/how-to-draw-rectangle-in-pygame/
 https://www.pygame.org/docs/ref/draw.html
 https://www.geeksforgeeks.org/how-to-create-buttons-in-a-game-using-pygame/
 https://chat.openai.com/share/8a7a05e3-3fc0-4323-8fba-1792ca50341d

pt schimbare de backround:
 https://www.pygame.org/docs/ref/color_list.html
 https://chat.openai.com/share/149b9923-a637-4dc5-a250-b70bbb820a44

tutorial de baza
 https://youtu.be/QFvqStqPCRU?si=11Z2RfuluexovKJb

idee de "highest_score.txt" luata din acest tutorial (trebuie deschis "highest_score.txt", scris '0' si salvat ca sa functioneze programul)
 https://www.techwithtim.net/tutorials/game-development-with-python/tetris-pygame/tutorial-4

pt scoreboard 
 https://www.geeksforgeeks.org/file-handling-python/?ref=lbp
 https://www.geeksforgeeks.org/open-a-file-in-python/?ref=lbp
 https://www.geeksforgeeks.org/how-to-read-from-a-file-in-python/?ref=lbp
 https://www.geeksforgeeks.org/writing-to-file-in-python/?ref=lbp

tutorial cod baza 
 https://www.geeksforgeeks.org/snake-game-in-python-using-pygame-module/
 https://github.com/memoiry/Snaky


--Ce trebuie sa faca cineva ca sa ruleze solutia?
  - python instalat, extensia de python pe vscode plus pygame prin pip install din command prompt
  - un fisier notepad atasat codului cu numele "highest_score" si in care se scrie 0 si se salveaza

--Descriere joc: 
 - jocul incepe odata ce dam run codului : daca apasam pe x, iesim (primul if din while TRUE), daca apasam pe o tasta, avem mai multe variante care vor descrie miscarea sarpelui corelata cu apasatul tastelor respective( elif-ul).
 - backround ul se deseneaza inaintea sarpelui pentru a nu se suprapune invers 
 - sarpele se mareste odata cu atingerea blocului food care se spawneaza random pe suprafata de joc
 - sarpele isi schimba si culoarea prin random.randint
 - atunci cand sarpele atinge marginea sau propriul corp, intervine functia game over si draw_button (butonul de restart), sarpele nemaintrunand conditiile de miscare de la validation of direction si nemaiputand fi miscat de jucator, iar scorul se opreste si afiseaza
 - putem incepe un alt joc prin apasarea butonului de restart de jos 
 - la finalul jocului se pastreaza mereu cel mai mare scor in istoric printr un fisier txt cu ajutorul functiilor de score

-- sectiune referinte: codul este pus pe contul de github al ambilor studenti
  
