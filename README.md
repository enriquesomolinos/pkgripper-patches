# PKG Ripper patches

These patches contains the information to remove contents from your own PS4 backups.

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