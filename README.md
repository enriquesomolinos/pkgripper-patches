# PKG Ripper patches

These patches contains the information to remove contents from your own PS4 backups.


## Current patches
| Game                                 	| Base pkg orig. size 	| Base pkg with pkgripper 	| Update pkg orig. size 	| Update pkg with pkgripper 	|
|--------------------------------------	|---------------------	|-------------------------	|-----------------------	|---------------------------	|
| EP1003-CUSA02092_00-DOOMEUROPEROWSKU 	| 45.9 GB             	| 28.5 GB                 	| 29 GB                 	| 24.8 GB                   	|
| EP3678-CUSA17580_00-TRANSFOBASEGAME0 	| 3.2 GB              	| 2.1 GB                  	| 0.7 GB                	| 0.7 GB                    	|
| EP4001-CUSA16283_00-F12020EMASTER000 	| 34.85 GB            	| 17.8 GB                 	| 18.5 GB               	| 15.5 GB                   	|
| EP9000-CUSA12982_00-MEDIEVILHD000001 	| 20 GB               	| 8.0 GB                  	| 16 GB                 	| 16 GB                     	|
| UP0777-CUSA27897_00-MSGNASCAR21XXXXX 	| 10.7 GB             	| 0.5                     	| 11.5 GB               	| 11.1                      	|
|                                      	|                     	|                         	|                       	|                           	|

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
