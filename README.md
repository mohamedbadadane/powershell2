# historique.txt

PS C:\powershell2> Get-Content .\historique.txt

  Id CommandLine                                                                                          
  -- -----------                                                                                          
    1 Set-Location -Path C:\...                                                                            
    2 remove-item -path C:\FolderTest1                                                                     
    3 remove-item -path C:\FolderTest2 -recurse                                                            
    4 remove-item -path C:\EvenFolder -recurse                                                             
    5 remove-item -path C:\oddFolder -recurse                                                              
    6 Set-Location -Path C:\...                                                                            
    7 Set-Location foldertest2                                                                             
    8 Set-Location ..                                                                                      
    9 new-item -path EvenFolder -ItemType directory                                                        
    10 new-item -path OddFolder -ItemType directory                                                         
    11 Set-Location foldertest2                                                                             
    12 move-item -path file6 -Destination C:\EvenFolder                                                     
    13 move-item -path file8 -Destination C:\EvenFolder                                                     
    14 move-item -path file10 -Destination C:\EvenFolder                                                    
    15 move-item -path file7 -Destination C:\oddFolder                                                      
    16 move-item -path file9 -Destination C:\oddFolder                                                      
    17 set-location ..                                                                                      
    18 set-location foldertest1                                                                             
    19 move-item -path file2 -Destination C:\EvenFolder                                                     
    20 move-item -path file4 -Destination C:\EvenFolder                                                     
    21 move-item -path file1 -Destination C:\oddFolder                                                      
    22 move-item -path file3 -Destination C:\oddFolder                                                      
    23 move-item -path file5 -Destination C:\oddFolder                                                      
    24 set-location ..                                                                                      
    25 remove-item -path historique.txt                                                                     
    26 remove-item -path listing.txt                                                                        
    27 get-history > historique.txt                                                                         
    28 sudo get-history > historique.txt                                                                    
    29 new-item -path powershell2 -itemtype directory                                                       
    30 Set-Location powershell2                                                                             
    31 new-item -path historique.txt -itemtype file                                                         
    32 new-item -path listing.txt -itemtype file  
---
# listing.txt

PS C:\powershell2> Get-Content .\listing.txt


    Répertoire : C:\EvenFolder


Mode                 LastWriteTime         Length Name                                                    
----                 -------------         ------ ----                                                    
-a----        18/03/2026     06:17              0 file10                                                  
-a----        18/03/2026     06:17              0 file2                                                   
-a----        18/03/2026     06:17              0 file4                                                   
-a----        18/03/2026     06:17              0 file6                                                   
-a----        18/03/2026     06:17              0 file8                                                   


    Répertoire : C:\OddFolder


Mode                 LastWriteTime         Length Name                                                    
----                 -------------         ------ ----                                                    
-a----        18/03/2026     06:17              0 file1                                                   
-a----        18/03/2026     06:17              0 file3                                                   
-a----        18/03/2026     06:17              0 file5                                                   
-a----        18/03/2026     06:17              0 file7                                                   
-a----        18/03/2026     06:17              0 file9                                                   
