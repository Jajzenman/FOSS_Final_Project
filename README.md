# FOSS_Final_Project

Map NYC Health & Hospitals Corporation (entities) in maplibre
Each hospital center is color coded according to its "Center Type"
 "Acute Care Hospital"           color "Crimson"
 "Child Health Center"           color "CornflowerBlue"
 "Diagnostic & Treatment Center" color "green"
 "Nursing Home"                  color "orange"

Menus to go to 
  (1) first Hospital Unit created (Bellevue)
  (2) Hospital Units categorized by "type of Center"
      when selecting a Center Type, filter is set to only those Hospital centers
  (3) Default is "All Centers
  (4) After filter is set, only those centers that meeet the criteria as shown as dots on the map
  (5) Map zooms out so that all "centers can be seen on the map
  (6) when you hover over a "dot", the name and type of the center appear in the popup; as well as a link
      to https://new.mta.info" so that user can enter from and to address to display appropriate bus route
  (7) ScaleControl added to lower left of map to show scale of the map shown

Things to do:
  (1) set up legend on map to explain colors of each Hopital Center type
  (2) rewrite maptiler (leaflet function) so that it works in maplibre (and allows user to switch between
      'transit' map and 'open streets' map
      
