# PKG Ripper patches

These patches contains the information to remove contents from your own PS4 backups.


## Current patches
| Game                                 	| Base orig. size 	| Base ripped 	| Update orig. size 	| Update ripped 	| Space saved
|--------------------------------------	|---------------------	|-------------------------	|-----------------------	|---------------------------	| ------------
| EP1003-CUSA02092_00-DOOMEUROPEROWSKU 	| 45.9 GB             	| 28.5 GB                 	| 29 GB                 	| 24.8 GB                   	| 22 GB
| EP3678-CUSA17580_00-TRANSFOBASEGAME0 	| 3.2 GB              	| 2.1 GB                  	| 0.7 GB                	| 0.7 GB                    	|  1 GB
| EP4001-CUSA16283_00-F12020EMASTER000 	| 34.85 GB            	| 17.8 GB                 	| 18.5 GB               	| 15.5 GB                   	| 20 GB
| EP9000-CUSA12982_00-MEDIEVILHD000001 	| 20 GB               	| 8.0 GB                  	| 16 GB                 	| 16 GB                     	| 12 GB
| UP0777-CUSA27897_00-MSGNASCAR21XXXXX 	| 10.7 GB             	| 0.5                     	| 11.5 GB               	| 11.1                      	| 10 GB
| EP2037-CUSA25234_00-DKALLIANCE01EURO 	| 19.7 GB               | 1.2 GB                   	| 23.0 GB                  	| 23.0 GB                      	| 18 GB
| EP6665-CUSA27790_00-WRC10SIEE0000000 	| 25.3 GB               | 17.0 GB                   | 12.5 GB                  	| 11.4 GB                      	|  9 GB
| EP1003-CUSA05486_00-SKYRIMHDFULLGAME 	| 31.1 GB               | 12.4 GB                   |  2.8 GB                  	|  2.8 GB                      	| 19 GB
| EP4291-CUSA18673_00-CRYSIS3REMASTERE 	| 10.0 GB               | 1.8 GB                    |  6.4 GB                  	|  6.4 GB                      	|  8 GB
| EP0001-CUSA15778_00-FARCRY6GAME00000 	| 34.8 GB               | 0.2 GB                    |  59.3 GB                  | 46.6 GB                      	| 48 GB
| EP9000-CUSA01715_00-0000GODOFWAR3PS4 	| 40.0 GB               | 37.0 GB                   | 0.1 GB                  	|  0.1 GB                      	|  3 GB
| UP3376-CUSA20594_00-SSVISAGEGAMEPACK 	| 8.45 GB               | 0.13 GB                   | 8.32 GB                  	| 8.32 GB                      	|  8 GB
| EP1464-CUSA24653_00-AWREMASTERED0000 	| 27.8 GB               | 2.53 GB                   | 26.9 GB                  	| 26.9 GB                      	| 25 GB
| EP4497-CUSA16579_00-0000000000000001 	| 59.4 GB               | 26.4 GB                   | 40.8 GB                  	| 39.6 GB                      	| 33 GB
| EP4389-CUSA04462_00-ELEXRPGPBNGEU001 	| 22.8 GB               | 18.6 GB                   | 4.9 GB                  	| 4.9 GB                      	|  4 GB
| EP2165-CUSA15639_00-LOF2GAMEEUXXXXXX 	| 11.7 GB               | 0.5 GB                    | 11.4 GB                  	| 11.4 GB                      	| 10 GB
| EP2028-CUSA03144_00-WASTELAND2GTYPS4 	| 4.8 GB                | 0.6 GB                    | 2.0 GB                  	| 2.0 GB                      	|  4 GB
| UP1001-CUSA15666_00-WWE2K20MAINSKU01 	| 45.9 GB               | 37.5 GB                   | 13.2 GB                  	| 13.2 GB                      	|  8 GB
| EP0001-CUSA11560_00-AC3GAMEPS4000001 	| 39.0 GB               | 17.0 GB                   | 19.0 GB                  	| 18.6 GB                      	| 21 GB
| EP1001-CUSA28235_00-NBA2K22000000000 	| 45.21 GB              | 37.0 GB                   | 46.89 GB                 	| 46.89 GB                     	|  8 GB
| EP0001-CUSA13034_00-ORWFULLGAME00000 	| 28.7 GB               | 22.1 GB                   | 19.4 GB                 	| 16.1 GB                     	|  9 GB
| UP4040-CUSA01830_00-ASSETTOCORSAXXXX 	| 12.9 GB               |  5.7 GB                   | 16.0 GB                 	| 16.1 GB                     	|  7 GB
| EP4295-CUSA23755_00-ASTERIXBTA0000EU 	|  1.3 GB               |  0.2 GB                   |  1.2 GB                 	| 1.2 GB                     	|  1 GB


## File structure

TBD
´´´
<?xml version="1.0"?>
<pkgpatch>
    <patchInfo description="Removes unnecesary content and all languages except spanish" title_id="CUSA17580" content_id="EP3678-CUSA17580_00-TRANSFOBASEGAME0">
    </patchInfo>
    <patches>
        <patch description="Removes all duplicate content from update 01.01 and all languages except spanish" pkg_required_version="01.00" update_version_required="01.01">
            <file path="Media/SymbolMap"/>
            
        </patch>
        <patch description="fake patch to link the update with your base.pkg file" pkg_required_version="01.01" update_version_required="01.01"/>        
    </patches>

</pkgpatch>
´´´´
 
## Colaboration

Any can add more patches simply doing a merge request or open an issue and I'll add it. 
