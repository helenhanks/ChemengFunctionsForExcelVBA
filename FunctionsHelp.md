#Chemistry Functions

####MolecularWeight("formula")
  Returns molecular wight (kg/kmol) of given molecule (formula as string)
  
####MolWeightMix("component names", mole fractions)
Returns average molecular weight (kg/kmol) of a mixture for given cell ranges containing component names as strings and mole fractions as double.

#Energy Functions

####LHV(HHV, H mass fraction)
Returns lower heating value for given higher heating value (kJ/kg) and mass fraction of H in fuel sample (kg H/kg fuel).

####HHV(LHV, H mass fraction)
Returns higher heating value for given lower heating value (kJ/kg) and mass fraction of H in fuel sample (kg H/kg fuel).
  
#Geometry Functions

####CircleArea(diameter)
Returns circle area for a given diameter
