# Energy provider: GreenChoice

Greenchoice offers the option to export the below data from the website. This data can be transformed and used to import into Home Assistant.

**Data provided**
- Electricity consumption - Tariff 1 - High resolution (day interval)
- Electricity consumption - Tariff 2 - High resolution (day interval)
- Electricity production - Tariff 1 - High resolution (day interval)
- Electricity production - Tariff 2 - High resolution (day interval)

**Tooling needed**
- Python 3
- Pandas python library ```pip install pandas```

**How-to**
- Export the data from GreenChoice
- Download the ```GreenChoiceDataPrepare.py``` file and put it in the same directory as the downloaded GreenChoice data
- Execute the python script with as parameter the name of the file that contains the exported data ```python GreenChoiceDataPrepare.py meterstanden_stroom_2023.csv```. The python script creates the needed files for the generic import script. 
- Follow the steps in the overall how-to