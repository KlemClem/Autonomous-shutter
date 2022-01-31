# Autonomous shutter

A motherboard with a stm32 automatically controls the closing of the shutter, depending on the brightness and temperature.  
 - Case study 1: The sun goes down, the temperature drops, the shutters close automatically to keep the privacy and isolate the windows from the cold of the night.
 - Case study 2 : The outside temperature is very high because of the sun orientation, the shutters close to keep the shade in the house and keep the coolness
## Introduction 

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.
## Operation 
```bash
variables
    nombre, somme: nombres
    continuer: texte
début algorithme
    continuer prend la valeur "oui" // initialisation
    afficher 'entrez un nombre :'
    lire nombre
    somme prend la valeur nombre
    tant que continuer="oui"
        afficher "entrez le nombre suivant"
        lire nombre
        somme prend la valeur somme+nombre
        afficher "voulez-vous continuer (oui/non)"
        lire continuer
    fin tant que
    afficher "la somme des nombres entrés est" somme
fin algorithme
```

## Usage

```python
import foobar

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Software used 
[MIT](https://choosealicense.com/licenses/mit/)
