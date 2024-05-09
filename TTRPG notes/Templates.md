```template
{{ define("lookupAbility", ["$items"]) }}
{{ 
  const abilities = $items['# Abilities'];
  const abilityMapping = {
    "STR": abilities['STR'],
    "DEX": abilities['DEX'],
    "CON": abilities['CON'],
    "INT": abilities['INT'],
    "WIS": abilities['WIS'],
    "CHA": abilities['CHA']
  };
  return abilityMapping[this];
}}