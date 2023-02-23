# **Chemical Warfare**

For the sake of realism Chemical Warfare should be added into the game for various groups to research, develop and use within wartime.  
To make the gasses harder to obtain and more valued various criteria would have to be met.  

This includes: 
* Research and Development wings for certain militarized groups
* Research into PREVENTING such attacks, and lessening their effects. (PPE R&D)
* Scientists and Chemist

Some gasses to add should be:
* Tear Gas
* Chlorine Gas
* Phosgene Gas
* Mustard Gas

# In-depth Information

For any game engineers/developers willing to look into the system here is a semi-in-depth write up about the pros, cons and specifics of adding such gasses to the game. This includes effects, formulas for calculating damage and certain features that will pair well.

## Tear Gas

### Information

Tear gas is known as a lachrymator agent. 

Known Effects
* Severe eye pain
* Severe respiratory pain
* Skin irritation
* Bleeding
* Blindness

Tear Gas is known to be a non-lethal or less-lethal weapon, for this sake some form of damage should still be taken. The following formula is a good rule of thumb.

```lua
Exposure / 60 --> Per every 60 exposure, take one damage basically. Or whatever comes out of it.
```

### Manufacturing

[2-Chlorobenzalmalononitrile](https://webbook.nist.gov/cgi/inchi?ID=C2698411&Mask=200) is the primary active ingredient in CS Gas.  
CS is synthesized by the reaction of [2-Chlorobenzaldehyde](https://pubchem.ncbi.nlm.nih.gov/compound/2-Chlorobenzaldehyde) and [Malononitrile](https://pubchem.ncbi.nlm.nih.gov/compound/MALONONITRILE) via the [Knoevenagel condensation](https://www.organic-chemistry.org/namedreactions/knoevenagel-condensation.shtm):  

```
ClC6H4CHO + H2C(CN)2 → ClC6H4CHC(CN)2 + H2O
```

The rest will be left to players to figure out how to convert it to an aerosol/gas.
