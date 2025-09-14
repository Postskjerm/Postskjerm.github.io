# Postskjerm.github.io
Webpage

<img width="23" height="23" alt="Prayer_icon" src="https://github.com/user-attachments/assets/b4631664-ecf1-49e9-b1f7-64b0d83c502e" />


<img width="31" height="24" alt="Dragon_bones" src="https://github.com/user-attachments/assets/b6f75f70-1588-4086-a245-e9c78c360ddd" />

<img width="23" height="20" alt="Big_bones" src="https://github.com/user-attachments/assets/32ef2615-526c-4ff0-93ba-c96a2a907752" />
big_bones <- function(big_bones){
  
  xp = 15
    
  "gp/xp" = big_bones/xp 
  
  tekst = paste0("Big bones er ", 
                 `gp/xp` ," gp/xp")
  
  return(tekst)
  
}
big_bones(550)


dragon_bones <- function(dragon_bones){
  
  xp = 72
  
  "gp/xp" = dragon_bones/xp 
  
  tekst = paste0("Dragon bones er ", 
                 `gp/xp` ," gp/xp")
  
  return(tekst)
  
}
dragon_bones(3500)
  